# Reel Media Factory — Architettura R001

## Nodi e responsabilità

| Componente | Ruolo previsto |
| --- | --- |
| AO-NODE-01 | Nodo Git: sorgenti, governance e sviluppo. |
| SER6 | Nodo runtime Ubuntu nativo. Ospiterà lo stack Reel separato dal repository e dallo stack FANTA esistente. |
| n8n | Orchestratore dei workflow: coordina gli step e scambia richieste e risultati con i moduli di produzione. |
| PostgreSQL | Database di stato dedicato allo stack Reel. |
| FFmpeg | Assemblaggio media deterministico, tramite worker separato da n8n. |
| ComfyUI | Renderer video raggiunto tramite API e adapter; endpoint e disponibilità runtime ancora da verificare. |
| Video Finisher | Modulo intercambiabile locale o cloud per la finalizzazione dei clip. |
| AI/QC locale | Modulo futuro e separato per analisi e controllo qualità; non è un prerequisito dello stack iniziale. |

## Flusso di produzione previsto

1. Il workflow definisce topic, script e shot. Rachel e BoomerX sono personaggi e asset standardizzati.
2. Si costruisce prima la timeline audio, con dialogo e tempi degli shot; la generazione video segue questa timeline.
3. Ogni Reel è composto da più clip indipendenti di circa 5–8 secondi. La baseline iniziale prevede un solo personaggio parlante per shot.
4. n8n invia le richieste video all'adapter API di ComfyUI. Il renderer produce i clip senza incorporare la logica di orchestrazione.
5. Un Video Finisher separato elabora i clip con un'implementazione locale o cloud sostituibile.
6. Un worker media usa FFmpeg per assemblare i clip e l'audio secondo la timeline definita. Il controllo AI/QC locale potrà essere aggiunto come modulo distinto.

Renderer e finisher comunicano con l'orchestrazione tramite interfacce dedicate: sostituirli non deve richiedere di incorporare rendering o finishing in n8n. Lo stack FANTA su `127.0.0.1:5678` resta separato; per n8n Reel è previsto `127.0.0.1:5679`. Queste sono scelte architetturali, non attestazioni di installazione o di disponibilità dei servizi.

## Perimetro attuale

R001, R001B e R002 hanno documentato audit, inventario Docker e piano di installazione. Il pacchetto R003 è stato preparato e revisionato staticamente fino a R003C. L'apply non è autorizzato e nessuna installazione Reel è stata eseguita. Per lo stato puntuale, vedere [STATUS_R004A.md](../docs/STATUS_R004A.md).
