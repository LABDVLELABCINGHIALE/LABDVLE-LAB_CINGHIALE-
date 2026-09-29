# Reel Media Factory

Pipeline automatizzata per la produzione dei Reel del Laboratorio del Cinghiale.

## Obiettivo

Topic / script
→ dialogo Rachel + BoomerX
→ clip video modulari
→ ComfyUI
→ finishing/QC
→ assemblaggio FFmpeg
→ Reel finale

## Architettura

- AO-NODE-01: repository, sviluppo e governance
- SER6: runtime n8n, PostgreSQL, FFmpeg e servizi locali
- ComfyUI: renderer video tramite API
- Video Finisher: componente intercambiabile locale/cloud

## Stato

Base runtime Reel Factory operativa: preflight e verifica R003 superati, APPLY eseguito, nessun blocker infrastrutturale corrente. ComfyUI non è ancora collegato e la pipeline n8n R005 non è ancora implementata.

## Documentazione

- [Architettura R001](architecture/ARCHITECTURE_R001.md)
- [Stato R004A](docs/STATUS_R004A.md)
- [Decisioni architetturali](docs/DECISIONS.md)
