# Character Asset Audit R004C

Data: 2026-09-29. Perimetro: tutti i file presenti sotto `reel-factory/assets/` al momento dell’audit. Inventario in sola lettura: 36 immagini PNG, 30 Rachel e 6 BoomerX. Nessuna immagine di Rachel e BoomerX insieme e nessun file nella categoria ALTRO.

Metodo: formato e dimensioni letti dai file con Pillow; dimensione in byte dal filesystem; SHA-256 calcolato sull’intero file; classificazione della posa e dell’ambientazione tramite ispezione visiva. I percorsi sono relativi alla radice del repository. Gli asset ID sono proposte logiche e non cambiano i nomi dei file.

## RACHEL — 30 asset

| Path relativo | Nome file | Formato | Pixel | Byte | SHA-256 | Classificazione visiva | Asset ID proposto |
| --- | --- | --- | ---: | ---: | --- | --- | --- |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_05-1.png` | `Immagine ChatGPT 29 set 2026, 15_54_05-1.png` | PNG | 1122 × 1402 | 2128751 | `d99f10ec608d734b344583fbaefcafac00135a63c90ee160ac4cb594216a0e27` | executive; frontale; figura intera | `rachel.exec.front` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_06-2.png` | `Immagine ChatGPT 29 set 2026, 15_54_06-2.png` | PNG | 1122 × 1402 | 2199617 | `73c71fc6cc60c98dcf20eeeaac650c897acd038a1f2060b3aed1532f11a04b16` | executive; camminata frontale; figura intera | `rachel.exec.walk.front` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_10-6.png` | `Immagine ChatGPT 29 set 2026, 15_54_10-6.png` | PNG | 1122 × 1402 | 2177591 | `09fb0dae304b3ef747b521dedf0d0e7fe68b4225f8dd6f22d6dae3f68130af38` | executive; 3/4; figura intera; scrivania | `rachel.exec.desk.3q` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_34-1.png` | `Immagine ChatGPT 29 set 2026, 15_54_34-1.png` | PNG | 1145 × 1374 | 2221968 | `816d81bf152931d21750aa4cd7effc29fb0bc194e0741d6c99a83c3d3ee3d049` | executive; tavola multi-pose | `rachel.exec.board.01` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_35-2.png` | `Immagine ChatGPT 29 set 2026, 15_54_35-2.png` | PNG | 1145 × 1374 | 2210855 | `f039e5c4dc5671a5dff9f648a6d5aea6aa43fdb7b2a04e4c5a96c0874f7ebb24` | executive; tavola multi-pose | `rachel.exec.board.02` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_36-3.png` | `Immagine ChatGPT 29 set 2026, 15_54_36-3.png` | PNG | 1024 × 1536 | 2388918 | `d5285d942722c0298be19204e995ef622304414d152dab0c8031a63635fa75db` | executive; tavola multi-pose | `rachel.exec.board.03` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_05-6.png` | `Immagine ChatGPT 29 set 2026, 15_55_05-6.png` | PNG | 1024 × 1536 | 2469509 | `1a8a52eae45d923ac9105ca4f6d911dc4d5b693f6afcbf619c044722b093484d` | shopfloor/work; 3/4; figura intera | `rachel.work.3q.alt` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_33-4.png` | `Immagine ChatGPT 29 set 2026, 15_55_33-4.png` | PNG | 1024 × 1536 | 2236239 | `63d37e8b582c4837f1baed20f866512b1b38d841e524568b859db0e6e0c7c9dd` | gala; 3/4; figura intera | `rachel.gala.3q.alt01` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_34-5.png` | `Immagine ChatGPT 29 set 2026, 15_55_34-5.png` | PNG | 1024 × 1536 | 2293825 | `401446cba76eb7f6a5ef8812e85d949420d651df619e7f56252edc4afe6385ef` | gala; 3/4; figura intera | `rachel.gala.3q.alt02` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_53-1.png` | `Immagine ChatGPT 29 set 2026, 15_55_53-1.png` | PNG | 1145 × 1374 | 2353194 | `b97cdb36b8091473ad7353bf9654f259b2f9c2bca0c071bf61cdd6c52c119823` | gala; tavola multi-pose | `rachel.gala.board.01` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_54-2.png` | `Immagine ChatGPT 29 set 2026, 15_55_54-2.png` | PNG | 1024 × 1536 | 2300141 | `d04ffc580bda2bbc45df84dc7a65700524967cdd1eef3c62e61732803879e0ce` | gala; tavola multi-pose | `rachel.gala.board.02` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_55_56-3.png` | `Immagine ChatGPT 29 set 2026, 15_55_56-3.png` | PNG | 1145 × 1374 | 2234159 | `ba7e3700777347d6bdf7e684ae72775ba4c43207061b2e4abfd624af0bc7d257` | gala; tavola multi-pose | `rachel.gala.board.03` |
| `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_56_08-4.png` | `Immagine ChatGPT 29 set 2026, 15_56_08-4.png` | PNG | 1214 × 1295 | 2327227 | `a8d884acda0c6e77cc97a0e9728df44c9df542ed2dfe7d29cc69863cda22fc23` | gala; tavola multi-pose | `rachel.gala.board.04` |
| `reel-factory/assets/characters/rachel/LDC_RACHEL_EXEC-01_TRE_QUARTI_ANTEPRIMA.png` | `LDC_RACHEL_EXEC-01_TRE_QUARTI_ANTEPRIMA.png` | PNG | 368 × 634 | 319171 | `70cfb95e7efcf83f84cefd9fe4a45b79bc7363e88307302f30345ff122402a61` | executive; 3/4; anteprima | `rachel.exec.3q.preview` |
| `reel-factory/assets/characters/rachel/Rachel execu camminata .png` | `Rachel execu camminata .png` | PNG | 1122 × 1402 | 2199617 | `73c71fc6cc60c98dcf20eeeaac650c897acd038a1f2060b3aed1532f11a04b16` | executive; camminata frontale; figura intera | `rachel.exec.walk.front` |
| `reel-factory/assets/characters/rachel/Rachel execu di spalle.png` | `Rachel execu di spalle.png` | PNG | 1122 × 1402 | 2117728 | `76684e774d834021d2313e3638a0c7300b721e6f391a40f4f7f7c45de9dcf946` | executive; retro; figura intera | `rachel.exec.back` |
| `reel-factory/assets/characters/rachel/Rachel execu fianco.png` | `Rachel execu fianco.png` | PNG | 1122 × 1402 | 2111007 | `17fac123fb967fa39ab0074b48e68a95c3d940a0d03df9e8f36506a80e305f5b` | executive; profilo; figura intera | `rachel.exec.profile` |
| `reel-factory/assets/characters/rachel/Rachel execu fronte.png` | `Rachel execu fronte.png` | PNG | 1122 × 1402 | 2128751 | `d99f10ec608d734b344583fbaefcafac00135a63c90ee160ac4cb594216a0e27` | executive; frontale; figura intera | `rachel.exec.front` |
| `reel-factory/assets/characters/rachel/Rachel execu primo piano.png` | `Rachel execu primo piano.png` | PNG | 1122 × 1402 | 1879570 | `ae867ced013274a3f370054336c9126fd6e32719aca536a5716b49d71ad42d24` | executive; primo piano | `rachel.exec.closeup` |
| `reel-factory/assets/characters/rachel/Rachel gala 3-4.png` | `Rachel gala 3-4.png` | PNG | 1122 × 1402 | 2187603 | `dac03cc930c0f4f1c15547b48bcaa9eac4524ae42cd3fe25c737f679e3130cee` | gala; 3/4; figura intera | `rachel.gala.3q` |
| `reel-factory/assets/characters/rachel/Rachel gala di fianco.png` | `Rachel gala di fianco.png` | PNG | 1024 × 1536 | 2208997 | `5180d39c1b31e99eb45f283d9eb804915e6f40ead9c26c4804d0514d50689933` | gala; profilo; figura intera | `rachel.gala.profile` |
| `reel-factory/assets/characters/rachel/Rachel gala di fianco1.png` | `Rachel gala di fianco1.png` | PNG | 1122 × 1402 | 2212580 | `0c4f6b12cfaeb9361bc9e695fbd36440f325a311536e6721d2c7dafc57ad0575` | gala; profilo; figura intera | `rachel.gala.profile.alt` |
| `reel-factory/assets/characters/rachel/Rachel gala di fronte.png` | `Rachel gala di fronte.png` | PNG | 1024 × 1536 | 2214818 | `8811c9d07459901983e788b38a478c1573725a050ba4cdc221577a563a46ab76` | gala; frontale; figura intera | `rachel.gala.front` |
| `reel-factory/assets/characters/rachel/Rachel gala di spalle.png` | `Rachel gala di spalle.png` | PNG | 1122 × 1402 | 2090088 | `9e0226ebc2e38a18614070d99cb4c6e5785939900fdd170576e111ba9dd9ce36` | gala; retro; figura intera | `rachel.gala.back` |
| `reel-factory/assets/characters/rachel/Rachel gala primo piano.png` | `Rachel gala primo piano.png` | PNG | 1024 × 1536 | 2121063 | `135d22c5455b1fddcfe8b81e5a831778206af471d846a3a1d995165e0727982f` | gala; primo piano | `rachel.gala.closeup` |
| `reel-factory/assets/characters/rachel/Rachel work  di spalle.png` | `Rachel work  di spalle.png` | PNG | 1024 × 1536 | 2332005 | `064806594bf4b042b85d3033da3e8a9a156b3c702e81885b914a2c86a1dacb1f` | shopfloor/work; retro; figura intera | `rachel.work.back` |
| `reel-factory/assets/characters/rachel/Rachel work 3-4.png` | `Rachel work 3-4.png` | PNG | 1024 × 1536 | 2375344 | `246480ddf64b612c61b0aa7ac7976cbadd9f0ea0f2c21f9c7e1d878b8cbc3bcc` | shopfloor/work; 3/4; figura intera | `rachel.work.3q` |
| `reel-factory/assets/characters/rachel/Rachel work di fianco.png` | `Rachel work di fianco.png` | PNG | 1024 × 1536 | 2230259 | `61fe3b21bb3bd6fd211d1477e90cb92f9a302578e9f3e41115c0562bf6a945c3` | shopfloor/work; profilo; figura intera | `rachel.work.profile` |
| `reel-factory/assets/characters/rachel/Rachel work di fronte.png` | `Rachel work di fronte.png` | PNG | 1024 × 1536 | 2289610 | `265bf28926950b7ba6aeed714c3c0f8acab398ed5c8d2c44c69d2501121b8a97` | shopfloor/work; frontale; figura intera | `rachel.work.front` |
| `reel-factory/assets/characters/rachel/Rachel work primo pianoi.png` | `Rachel work primo pianoi.png` | PNG | 1024 × 1536 | 2245830 | `1dd67215558bdd949cc98331390a0e76be30d1d3dfaa0c76faba4037340a3564` | shopfloor/work; primo piano | `rachel.work.closeup` |

Le sette tavole multi-pose (tre executive, quattro gala) raccolgono più viste di Rachel nella stessa immagine: sono reference secondarie per pose, abbigliamento e stile, non immagini di un duo. L’anteprima `rachel.exec.3q.preview` ha risoluzione ridotta rispetto agli altri asset Rachel.

## BOOMERX — 6 asset

| Path relativo | Nome file | Formato | Pixel | Byte | SHA-256 | Classificazione visiva | Asset ID proposto |
| --- | --- | --- | ---: | ---: | --- | --- | --- |
| `reel-factory/assets/characters/boomerx/BoomerX 3-4.png` | `BoomerX 3-4.png` | PNG | 1122 × 1402 | 2397833 | `91827e45c0d5be3d480f02844f51cc49d714863a219de34f16d96ebc46dad46e` | 3/4; figura intera | `boomerx.3q` |
| `reel-factory/assets/characters/boomerx/BoomerX di fianco.png` | `BoomerX di fianco.png` | PNG | 1122 × 1402 | 2212178 | `02e5702eceb3911324dbcb06a9e9202211d9f779ac6840de86cee4ed4c38c183` | profilo; figura intera | `boomerx.profile` |
| `reel-factory/assets/characters/boomerx/BoomerX di fronte.png` | `BoomerX di fronte.png` | PNG | 1122 × 1402 | 2382643 | `dd77a8286120b5c6065ba845fc5aef1106709da0baa24d70afa9401eb2701e93` | frontale; figura intera | `boomerx.front` |
| `reel-factory/assets/characters/boomerx/BoomerX di spalle.png` | `BoomerX di spalle.png` | PNG | 1122 × 1402 | 2300765 | `51ed58a0f591da58e2a499a36f309840d98b6c243ff9141f3130e088f056a1c9` | retro; figura intera | `boomerx.back` |
| `reel-factory/assets/characters/boomerx/BoomerX primo piano.png` | `BoomerX primo piano.png` | PNG | 1122 × 1402 | 2386839 | `02f846eaa29f082f8c242529b2c2f981a6cbfdcdace26d2f027eeb2ab2ff2a59` | primo piano | `boomerx.closeup` |
| `reel-factory/assets/characters/boomerx/Immagine ChatGPT 29 set 2026, 15_58_34.png` | `Immagine ChatGPT 29 set 2026, 15_58_34.png` | PNG | 1122 × 1402 | 2363126 | `7c81ee0be522f30a26e447d72c89765f1a0bc933748e062b84b824d3e327338f` | frontale; figura parziale | `boomerx.front.medium` |

## GRUPPO / DUO — 0 asset

Nessuna immagine mostra Rachel e BoomerX insieme. Le tavole con più pose dello stesso personaggio restano nella categoria RACHEL. Per futuri asset di gruppo/duo, gli ID potranno seguire `duo.lab.01`, `duo.shopfloor.01` e simili. Queste immagini saranno candidate per composizione Rachel + BoomerX, scala relativa, posizione reciproca, lighting/style, scena/ambientazione, B-roll statico e shot futuri a due personaggi. Non saranno reference primaria dell’identità dei singoli personaggi.

## ALTRO — 0 asset

Nessun file fuori dalle categorie sopra. Nessun asset resta senza classificazione di personaggio o tipo.

## Duplicati byte-identici

Due coppie SHA-256 identiche (34 contenuti distinti su 36 file). Sono alias di contenuto; nessuna proposta di eliminazione:

- `73c71fc6cc60c98dcf20eeeaac650c897acd038a1f2060b3aed1532f11a04b16` — `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_06-2.png` = `reel-factory/assets/characters/rachel/Rachel execu camminata .png` → `rachel.exec.walk.front`.
- `d99f10ec608d734b344583fbaefcafac00135a63c90ee160ac4cb594216a0e27` — `reel-factory/assets/characters/rachel/Immagine ChatGPT 29 set 2026, 15_54_05-1.png` = `reel-factory/assets/characters/rachel/Rachel execu fronte.png` → `rachel.exec.front`.

La corrispondenza riguarda i byte del file; non è una valutazione delle somiglianze visive tra immagini diverse.

## Convenzione logica futura

Forma proposta: `<personaggio>.<look>.<vista>[.<variante>]`, con `rachel.exec`, `rachel.work`, `rachel.gala`, `boomerx` e `duo.<ambientazione>`. `front`, `3q`, `profile`, `back`, `closeup`, `walk` e `board` descrivono la vista o il tipo di asset. Gli ID condivisi dalle due coppie di file identici rappresentano un solo contenuto logico. La nomenclatura è soltanto una mappa per il futuro catalogo.
