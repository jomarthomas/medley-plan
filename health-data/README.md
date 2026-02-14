# health-data README

Purpose
- Store raw exported files and screenshots from monitoring devices in a simple, chronological archive. Do not include derived analyses or processed datasets in this folder.

Accepted file types
- .pdf
- .csv
- .json
- .fit
- .gpx
- .png
- .jpg

Naming convention (date-based filenames)

Use the date-based filename format for clear chronological sorting and easy reference in reviews:

Format
- `YYYY-MM-DD_device_metric.ext`

Examples
- `2025-09-12_awultra_workout.fit`
- `2025-09-12_polarh10_vo2.csv`
- `2025-09-12_kardiomobile_ekg.pdf`
- `2025-09-12_omron_bp.png`
- `2025-09-12_scale_bodycomp.csv`

Structure (no deep nesting)
- Place files directly in the appropriate subfolder under `/health-data/`:
  - `/health-data/ekg/`
  - `/health-data/blood-pressure/`
  - `/health-data/body-composition/`
  - `/health-data/workouts/`
  - `/health-data/heart-rate/`
  - `/health-data/sleep/`

Guidelines
- Keep original raw files; if you annotate, save the annotation as a separate file.
- Preserve device timestamps in file metadata or add a short note file if the export lacks explicit timestamps.
- Avoid embedding personal identifiers inside file names beyond date and device.

Devices (examples of device tag)
- `awultra` — Apple Watch Ultra exports
- `polarh10` — Polar H10 chest-strap exports (CSV)
- `kardiomobile` — KardiaMobile 6L
- `omron` — OMRON Evolv
- `scale` — Smart Fitness Scale exports

Privacy
- This repository must remain private. Health exports are sensitive. Do not share public links or publish files from this folder.
