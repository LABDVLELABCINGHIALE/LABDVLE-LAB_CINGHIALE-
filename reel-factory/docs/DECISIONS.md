# Reel Media Factory — Decisioni architetturali

| Ambito | Decisione |
| --- | --- |
| Repository canonico | `LABDVLELABCINGHIALE/LABDVLE-LAB_CINGHIALE-`. |
| Branch di lavoro | `feature/reel-media-factory`. |
| Separazione degli ambienti | Il repository custodisce sorgenti, governance e documentazione; il runtime SER6 resta separato dal repository. |
| Stack esistente | FANTA non deve essere modificato. La nuova istanza Reel usa risorse e porta dedicate. |
| Dati versionati | Nessun secret, media RAW o modello AI in Git. |
| Immagini Docker | Nessun tag `latest`. Fissare versione e digest quando possibile, dopo verifica dell'immagine effettivamente usata. |
| Renderer | n8n comunica con ComfyUI tramite un API adapter separato. |
| Composizione | Pipeline modulare, con renderer, Video Finisher e worker FFmpeg separati e sostituibili. |

Queste decisioni descrivono l'architettura prevista; non costituiscono autorizzazione all'installazione. Il blocco sul digest n8n locale è riportato in [STATUS_R004A.md](STATUS_R004A.md).
