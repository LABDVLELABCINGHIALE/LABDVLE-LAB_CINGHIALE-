# Character Asset Review R004D

Data: 2026-09-29. Fonte: `ASSET_AUDIT_R004C.md` e ispezione visiva degli originali in `reel-factory/assets/`. Gli asset sono stati soltanto letti. Tutti i percorsi sotto sono relativi alla radice del repository; gli ID sono proposte logiche, senza rinomina.

## 1. Inventario sintetico e criterio strutturale

| CHARACTER | Totale | SINGLE | MULTIVIEW_SHEET | CONTACT_SHEET | OTHER |
| --- | ---: | ---: | ---: | ---: | ---: |
| RACHEL | 30 | 23 | 7 | 0 | 0 |
| BOOMERX | 6 | 6 | 0 | 0 | 0 |
| **Totale** | **36** | **29** | **7** | **0** | **0** |

`MULTIVIEW_SHEET` indica una tavola intenzionale con angoli, figura intera e ritratto dello stesso personaggio. `CONTACT_SHEET` sarebbe una raccolta generica di miniature/varianti senza sequenza di angoli; non ne sono state trovate. Nessuna tavola è un DUO. Per i SINGLE, `VIEW` indica direzione o CLOSEUP; `FULL_BODY` è riportato in `FRAMING` per non perdere la direzione.

## 2. Single assets — 29

| Path relativo | CHARACTER | ASSET_TYPE | VIEW | OUTFIT | FRAMING | Asset ID proposto | Ruolo |
| --- | --- | --- | --- | --- | --- | --- | --- |
| `reel-factory/assets/characters/boomerx/BoomerX 3-4.png` | BOOMERX | SINGLE | THREE_QUARTER | CANONICAL_WORK | FULL_BODY | `boomerx.3q` | PRIMARY_CANDIDATE |
| `reel-factory/assets/characters/boomerx/BoomerX di fianco.png` | BOOMERX | SINGLE | SIDE | CANONICAL_WORK | FULL_BODY | `boomerx.side` | SECONDARY |
| `reel-factory/assets/characters/boomerx/BoomerX di fronte.png` | BOOMERX | SINGLE | FRONT | CANONICAL_WORK | FULL_BODY | `boomerx.front` | PRIMARY_CANDIDATE |
| `reel-factory/assets/characters/boomerx/BoomerX di spalle.png` | BOOMERX | SINGLE | REAR | CANONICAL_WORK | FULL_BODY | `boomerx.rear` | SECONDARY |
| `reel-factory/assets/characters/boomerx/BoomerX primo piano.png` | BOOMERX | SINGLE | CLOSEUP | CANONICAL_WORK | PORTRAIT | `boomerx.closeup` | PRIMARY_CANDIDATE |
| `reel-factory/assets/characters/boomerx/Immagine ChatGPT 29 set 2026, 15_58_34.png` | BOOMERX | SINGLE | FRONT | CANONICAL_WORK | PARTIAL_BODY | `boomerx.front.medium` | SECONDARY |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_05-1.png` | RACHEL | SINGLE | FRONT | EXEC | FULL_BODY | `rachel.exec.front` | EXACT_ALIAS |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_06-2.png` | RACHEL | SINGLE | FRONT | EXEC | FULL_BODY | `rachel.exec.walk.front` | EXACT_ALIAS |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_10-6.png` | RACHEL | SINGLE | THREE_QUARTER | EXEC | FULL_BODY | `rachel.exec.3q` | PRIMARY_CANDIDATE |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_05-6.png` | RACHEL | SINGLE | THREE_QUARTER | WORK | FULL_BODY | `rachel.work.3q.alt` | SECONDARY |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_33-4.png` | RACHEL | SINGLE | THREE_QUARTER | GALA | FULL_BODY | `rachel.gala.3q.alt01` | SECONDARY |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_34-5.png` | RACHEL | SINGLE | THREE_QUARTER | GALA | FULL_BODY | `rachel.gala.3q.alt02` | SECONDARY |
| `reel-factory/assets/characters/rachel/LDC_RACHEL_EXEC-01_TRE_QUARTI_ANTEPRIMA.png` | RACHEL | SINGLE | THREE_QUARTER | EXEC | FULL_BODY_PREVIEW | `rachel.exec.3q.preview` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel execu camminata .png` | RACHEL | SINGLE | FRONT | EXEC | FULL_BODY | `rachel.exec.walk.front` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel execu di spalle.png` | RACHEL | SINGLE | REAR | EXEC | FULL_BODY | `rachel.exec.rear` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel execu fianco.png` | RACHEL | SINGLE | SIDE | EXEC | FULL_BODY | `rachel.exec.side` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel execu fronte.png` | RACHEL | SINGLE | FRONT | EXEC | FULL_BODY | `rachel.exec.front` | PRIMARY_CANDIDATE |
| `reel-factory/assets/characters/rachel/Rachel execu primo piano.png` | RACHEL | SINGLE | CLOSEUP | EXEC | HALF_BODY | `rachel.exec.closeup` | PRIMARY_CANDIDATE |
| `reel-factory/assets/characters/rachel/Rachel gala 3-4.png` | RACHEL | SINGLE | THREE_QUARTER | GALA | FULL_BODY | `rachel.gala.3q` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel gala di fianco.png` | RACHEL | SINGLE | SIDE | GALA | FULL_BODY | `rachel.gala.side` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel gala di fianco1.png` | RACHEL | SINGLE | SIDE | GALA | FULL_BODY | `rachel.gala.side.alt` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel gala di fronte.png` | RACHEL | SINGLE | FRONT | GALA | FULL_BODY | `rachel.gala.front` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel gala di spalle.png` | RACHEL | SINGLE | REAR | GALA | FULL_BODY | `rachel.gala.rear` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel gala primo piano.png` | RACHEL | SINGLE | CLOSEUP | GALA | HALF_BODY | `rachel.gala.closeup` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel work  di spalle.png` | RACHEL | SINGLE | REAR | WORK | FULL_BODY | `rachel.work.rear` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel work 3-4.png` | RACHEL | SINGLE | THREE_QUARTER | WORK | FULL_BODY | `rachel.work.3q` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel work di fianco.png` | RACHEL | SINGLE | SIDE | WORK | FULL_BODY | `rachel.work.side` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel work di fronte.png` | RACHEL | SINGLE | FRONT | WORK | FULL_BODY | `rachel.work.front` | SECONDARY |
| `reel-factory/assets/characters/rachel/Rachel work primo pianoi.png` | RACHEL | SINGLE | CLOSEUP | WORK | HALF_BODY | `rachel.work.closeup` | SECONDARY |

`rachel.exec.3q` è un candidato tre quarti moderato, con busto quasi frontale e posa presso la scrivania; l’anteprima `rachel.exec.3q.preview` mostra un angolo più netto ma misura solo 368 × 634 px. `rachel.work.side` mostra il corpo di lato mentre il volto è girato verso la camera. Le due righe `EXACT_ALIAS` sono file distinti con byte identici ai rispettivi file nominati; non aggiungono una nuova vista.

## 3. Multiview e contact sheet — 7

Le sette tavole contengono circa sei pannelli ciascuna: frontale, tre quarti, profilo, retro, mezzo busto/primo piano e posa con prop o ambientazione. Sono tutte RACHEL, `ASSET_TYPE=MULTIVIEW_SHEET`; `CONTACT_SHEET=0`. Le proporzioni e i dettagli facciali tra pannelli vanno comunque confermati prima di usarle come vincolo generativo.

| Path relativo | CHARACTER | ASSET_TYPE | OUTFIT | Viste circa | Viste presenti | Utilità potenziale | Classificazione | Asset ID proposto |
| --- | --- | --- | --- | ---: | --- | --- | --- | --- |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_34-1.png` | RACHEL | MULTIVIEW_SHEET | EXEC | ~6 | FRONT, THREE_QUARTER, SIDE, REAR, CLOSEUP/mezzo busto, ambientata | identity reference; body proportion reference; angle consistency; ComfyUI future reference | MULTIVIEW_PRIMARY_CANDIDATE | `rachel.exec.multiview.01` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_35-2.png` | RACHEL | MULTIVIEW_SHEET | EXEC | ~6 | FRONT, THREE_QUARTER, SIDE, REAR, CLOSEUP/mezzo busto, ambientata | body proportion reference; angle consistency; ComfyUI future reference | MULTIVIEW_SECONDARY | `rachel.exec.multiview.02` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_36-3.png` | RACHEL | MULTIVIEW_SHEET | EXEC | ~6 | FRONT, THREE_QUARTER, SIDE, REAR, CLOSEUP/mezzo busto, ambientata | identity reference; angle consistency; ComfyUI future reference | MULTIVIEW_SECONDARY | `rachel.exec.multiview.03` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_53-1.png` | RACHEL | MULTIVIEW_SHEET | GALA | ~6 | FRONT, THREE_QUARTER, SIDE, REAR, CLOSEUP/mezzo busto, ambientata | body proportion reference; angle consistency; ComfyUI future reference | MULTIVIEW_SECONDARY | `rachel.gala.multiview.01` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_54-2.png` | RACHEL | MULTIVIEW_SHEET | GALA | ~6 | FRONT, THREE_QUARTER, SIDE, REAR, CLOSEUP/mezzo busto, ambientata | body proportion reference; angle consistency; ComfyUI future reference | MULTIVIEW_SECONDARY | `rachel.gala.multiview.02` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_56-3.png` | RACHEL | MULTIVIEW_SHEET | GALA | ~6 | FRONT, THREE_QUARTER, SIDE, REAR, CLOSEUP/mezzo busto, ambientata | angle consistency; ComfyUI future reference | MULTIVIEW_SECONDARY | `rachel.gala.multiview.03` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_56_08-4.png` | RACHEL | MULTIVIEW_SHEET | GALA | ~6 | FRONT, THREE_QUARTER, SIDE, REAR, CLOSEUP/mezzo busto, ambientata | angle consistency; lighting/style reference; ComfyUI future reference | MULTIVIEW_SECONDARY | `rachel.gala.multiview.04` |

`rachel.exec.multiview.01` è la candidata primaria: presenta le quattro direzioni a figura intera più ritratto e posa ambientata nello stesso look. Le altre due tavole executive e le quattro gala restano secondarie; le gala documentano un outfit diverso. Nessuna tavola BoomerX esiste, quindi `BOOMERX_MULTIVIEW_PRIMARY=NONE`. Le tavole non sostituiscono automaticamente i SINGLE come reference dell’identità.

## 4. Exact duplicates — 2 coppie

SHA-256 calcolato sui file originali. Le coppie sono byte-identiche; nessuna cancellazione automatica è proposta.

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_06-2.png`
PATH_B=`reel-factory/assets/characters/rachel/Rachel execu camminata .png`
SHA256=`73c71fc6cc60c98dcf20eeeaac650c897acd038a1f2060b3aed1532f11a04b16`
RECOMMENDATION=EXACT_DUPLICATE_CANDIDATE per scelta futura del path canonico; conservare entrambi per ora.
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_05-1.png`
PATH_B=`reel-factory/assets/characters/rachel/Rachel execu fronte.png`
SHA256=`d99f10ec608d734b344583fbaefcafac00135a63c90ee160ac4cb594216a0e27`
RECOMMENDATION=EXACT_DUPLICATE_CANDIDATE per scelta futura del path canonico; conservare entrambi per ora.
```

## 5. Near duplicates — 12 coppie candidate, 3 controlli distinti

Confronto senza installazioni: pHash 64 bit con DCT su 32 × 32 in scala di grigi, dHash 64 bit su 9 × 8 e differenza media assoluta RGB dopo ridimensionamento a 96 × 96. Le distanze più piccole indicano struttura visiva più simile; la media RGB è su scala 0–255. I valori dipendono da inquadratura, sfondo e layout, quindi la RELATION deriva anche dalla verifica visiva degli originali. `SAME_IMAGE_REENCODED`: nessun caso confermato. Le tavole sono varianti di composizione, non lo stesso file ricodificato.

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_34-1.png`
PATH_B=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_35-2.png`
RELATION=VERY_SIMILAR
SIMILARITY_EVIDENCE=pHash 24/64; dHash 31/64; RGB MAE 52.9/255; verifica visiva: stesse sei viste executive, pannelli e pose generati diversamente.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_34-1.png`
PATH_B=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_36-3.png`
RELATION=VERY_SIMILAR
SIMILARITY_EVIDENCE=pHash 18/64; dHash 20/64; RGB MAE 45.0/255; verifica visiva: stesse sei viste executive; layout e ritratto cambiano.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_35-2.png`
PATH_B=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_36-3.png`
RELATION=VERY_SIMILAR
SIMILARITY_EVIDENCE=pHash 28/64; dHash 33/64; RGB MAE 52.2/255; verifica visiva: stesse sei viste executive; proporzioni dei pannelli e pose cambiano.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_53-1.png`
PATH_B=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_54-2.png`
RELATION=VERY_SIMILAR
SIMILARITY_EVIDENCE=pHash 18/64; dHash 17/64; RGB MAE 36.2/255; verifica visiva: stesse sei viste gala, layout e accessori diversi.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_53-1.png`
PATH_B=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_56-3.png`
RELATION=VERY_SIMILAR
SIMILARITY_EVIDENCE=pHash 18/64; dHash 20/64; RGB MAE 38.7/255; verifica visiva: stesse sei viste gala, fondali e pose diversi.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_53-1.png`
PATH_B=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_56_08-4.png`
RELATION=VERY_SIMILAR
SIMILARITY_EVIDENCE=pHash 24/64; dHash 13/64; RGB MAE 38.2/255; verifica visiva: stesse sei viste gala; diverso stile dei pannelli.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_54-2.png`
PATH_B=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_56-3.png`
RELATION=VERY_SIMILAR
SIMILARITY_EVIDENCE=pHash 22/64; dHash 21/64; RGB MAE 39.6/255; verifica visiva: stesse sei viste gala; diversa composizione e posa con prop.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_54-2.png`
PATH_B=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_56_08-4.png`
RELATION=VERY_SIMILAR
SIMILARITY_EVIDENCE=pHash 28/64; dHash 20/64; RGB MAE 40.4/255; verifica visiva: stesse sei viste gala; diversa composizione e luce.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_56-3.png`
PATH_B=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_56_08-4.png`
RELATION=VERY_SIMILAR
SIMILARITY_EVIDENCE=pHash 24/64; dHash 15/64; RGB MAE 43.0/255; verifica visiva: stesse sei viste gala; diversa posa e crop.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_33-4.png`
PATH_B=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_34-5.png`
RELATION=VERY_SIMILAR
SIMILARITY_EVIDENCE=pHash 14/64; dHash 13/64; RGB MAE 28.5/255; verifica visiva: stesso look gala e fondale; camminata rispetto a posa appoggiata con tablet.
RECOMMENDATION=KEEP_BOTH
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_34-5.png`
PATH_B=`reel-factory/assets/characters/rachel/Rachel gala di fronte.png`
RELATION=SAME_POSE_VARIANT
SIMILARITY_EVIDENCE=pHash 6/64; dHash 7/64; RGB MAE 20.2/255; verifica visiva: inquadratura gala quasi frontale e fondale molto simili; tablet rispetto a mano sulla giacca.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Rachel gala di fianco.png`
PATH_B=`reel-factory/assets/characters/rachel/Rachel gala di fianco1.png`
RELATION=SAME_POSE_VARIANT
SIMILARITY_EVIDENCE=pHash 20/64; dHash 23/64; RGB MAE 31.6/255; verifica visiva: stesso profilo gala nella stessa ambientazione; diverso crop, mantello e posizione.
RECOMMENDATION=CHOOSE_ONE_LATER
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Rachel gala 3-4.png`
PATH_B=`reel-factory/assets/characters/rachel/Rachel gala di fianco1.png`
RELATION=DISTINCT
SIMILARITY_EVIDENCE=pHash 12/64; dHash 12/64; RGB MAE 27.5/255; verifica visiva: pHash vicino per palette e fondale gala, ma tre quarti con calice rispetto a profilo.
RECOMMENDATION=KEEP_BOTH
```

```text
PATH_A=`reel-factory/assets/characters/boomerx/BoomerX di fronte.png`
PATH_B=`reel-factory/assets/characters/boomerx/BoomerX di spalle.png`
RELATION=DISTINCT
SIMILARITY_EVIDENCE=pHash 0/64; dHash 8/64; RGB MAE 9.4/255; verifica visiva: pHash identico per fondale e sagoma centrale, ma fronte rispetto a retro.
RECOMMENDATION=KEEP_BOTH
```

```text
PATH_A=`reel-factory/assets/characters/rachel/Rachel work di fianco.png`
PATH_B=`reel-factory/assets/characters/rachel/Rachel work di fronte.png`
RELATION=DISTINCT
SIMILARITY_EVIDENCE=pHash 18/64; dHash 12/64; RGB MAE 13.8/255; verifica visiva: sfondo work quasi identico, ma corpo di lato rispetto a frontale.
RECOMMENDATION=KEEP_BOTH
```

I tre casi `DISTINCT` sono controlli espliciti: una distanza hash bassa non basta per dichiarare due viste duplicate. Nessuna coppia diversa per SHA-256 è stata confermata come stessa immagine semplicemente ricodificata.

## 6. Primary reference candidates

| Personaggio | Vista | Path relativo | Asset ID | Motivazione e limite |
| --- | --- | --- | --- | --- |
| RACHEL | front | `reel-factory/assets/characters/rachel/Rachel execu fronte.png` | `rachel.exec.front` | EXEC, figura intera; alias byte-identico al file ChatGPT 15_54_05-1. |
| RACHEL | three_quarter | `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_10-6.png` | `rachel.exec.3q` | EXEC, risoluzione piena; angolo moderato, da confermare con Owner. |
| RACHEL | closeup | `reel-factory/assets/characters/rachel/Rachel execu primo piano.png` | `rachel.exec.closeup` | EXEC, viso leggibile; inquadratura fino alla vita. |
| BOOMERX | front | `reel-factory/assets/characters/boomerx/BoomerX di fronte.png` | `boomerx.front` | CANONICAL_WORK, figura intera. |
| BOOMERX | three_quarter | `reel-factory/assets/characters/boomerx/BoomerX 3-4.png` | `boomerx.3q` | CANONICAL_WORK, figura intera. |
| BOOMERX | closeup | `reel-factory/assets/characters/boomerx/BoomerX primo piano.png` | `boomerx.closeup` | CANONICAL_WORK, volto e dettagli leggibili. |

RACHEL_MULTIVIEW_PRIMARY=`reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_34-1.png` (`rachel.exec.multiview.01`, candidatura provvisoria).

BOOMERX_MULTIVIEW_PRIMARY=NONE (nessuna tavola rilevata).

## 7. Secondary references

Le tabelle sezioni 2 e 3 assegnano il ruolo a ogni file. `RACHEL_SECONDARY` comprende 18 SINGLE distinti non primari e sei tavole MULTIVIEW_SECONDARY: profilo/retro EXEC, camminata, preview a bassa risoluzione, tutte le viste WORK e GALA, pose alternative e reference di scena. I due `EXACT_ALIAS` restano tracciati separatamente. `BOOMERX_SECONDARY` comprende il profilo, il retro e la vista frontale parziale. Le pose con sfondo simile restano utili per camera e ambientazione anche quando una sola sarà scelta come reference canonica.

## 8. Asset ID proposti

La mappa completa, un file per riga, è nelle colonne `Asset ID proposto` delle sezioni 2 e 3. Convenzione: `rachel.<outfit>.<vista>[.<variante>]`, `rachel.<outfit>.multiview.NN`, `boomerx.<vista>[.<variante>]`. FRONT→`front`, THREE_QUARTER→`3q`, CLOSEUP→`closeup`, SIDE→`side`, REAR→`rear`. I due alias esatti condividono l’ID del contenuto identico. Gli ID delle tavole e alcuni termini di vista affinano le etichette provvisorie di R004C; nessun file viene rinominato.

## 9. Decisioni Owner richieste

1. Confermare o sostituire il candidato RACHEL three_quarter EXEC: il SINGLE ad alta risoluzione è quasi frontale; la preview ha angolo più netto ma bassa risoluzione.
2. Confermare la tavola EXEC `rachel.exec.multiview.01` oppure scegliere `.02`/`.03` dopo controllo di coerenza di volto, capelli, outfit e proporzioni tra pannelli.
3. Decidere se promuovere una tavola GALA a reference primaria per quel look; nessuna è proposta come primaria dell’identità generale.
4. Scegliere in futuro la reference canonica per le pose GALA quasi sovrapposte (frontale e profilo), mantenendo le altre come varianti se utili.
5. Scegliere il path canonico per ciascuna coppia esatta e la politica di alias del catalogo; nessuna eliminazione è implicita.
