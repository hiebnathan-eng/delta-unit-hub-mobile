# Unit Hub Mobile

App link: https://hiebnathan-eng.github.io/delta-unit-hub-mobile/

iPhone companion to Delta Unit Hub (desktop v36 or later).

- **What it does:** loads a Unit Hub backup (.json from History > Download backup), shows the bed board and assignments for one shift, takes quick edits (bed status, initials, acuity, isolation, flags, DC today, nurse, CNA), toggles doubled rooms (A/B beds for 256, 258, 261, 262, 267, 268, 269, 270), and saves a backup the desktop can load.
- **Data:** this file holds no patient data, only a fictional example. Backups are read on the phone and never uploaded.
- **How to open it:** the GitHub Pages link above, in Safari, then Share > Add to Home Screen. The page is public, but it holds no data: each phone loads its own backup, which stays on that phone.
- **Single file:** `index.html`. Edit and push (Pages updates in about a minute), then copy to iCloud `80 Work - Delta Health/10 Unit Hub and Apps`.

## Versions
- v2 (2026-10-26): Settings tab with A/B bed toggles (same rules as desktop), home-screen icon, save fallback (share sheet / download).
- v1 (2026-10-26): bed board, assignments, load and save backups.
