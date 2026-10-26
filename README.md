# Unit Hub Mobile

Private. iPhone companion to Delta Unit Hub (desktop v36 or later).

- **What it does:** loads a Unit Hub backup (.json from History > Download backup), shows the bed board and assignments for one shift, takes quick edits (bed status, initials, acuity, isolation, flags, DC today, nurse, CNA), toggles doubled rooms (A/B beds for 256, 258, 261, 262, 267, 268, 269, 270), and saves a backup the desktop can load.
- **Data:** this file holds no patient data, only a fictional example. Backups are read on the phone and never uploaded.
- **How Nathan opens it:** the private claude.ai link (only he can open it). This repository is the code backup and version history. There is no GitHub Pages site on purpose: Pages would make it public.
- **Single file:** `index.html`. Edit, then republish to the claude.ai link and copy to iCloud `80 Work - Delta Health/10 Unit Hub and Apps`.

## Versions
- v2 (2026-10-26): Settings tab with A/B bed toggles (same rules as desktop), home-screen icon, save fallback (share sheet / download).
- v1 (2026-10-26): bed board, assignments, load and save backups.
