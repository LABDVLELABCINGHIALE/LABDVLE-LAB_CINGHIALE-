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

Fase iniziale di infrastruttura e validazione.
