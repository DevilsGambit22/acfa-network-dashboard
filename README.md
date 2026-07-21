# ACFA Network Dashboard v1.10 — Expanded Radio Playlist

Project Sentinel and the animated SVG Lady Justice remain removed.

## ACFA Radio playlist

The radio keeps the three original tracks and adds five new tracks:

1. The Last Kingdom
2. The Forgotten Kingdom
3. Queen's Shadow
4. Sentinel Awakens
5. Golden Horizon
6. Command Center
7. Eternal Justice
8. Midnight Tribunal

Add the five new files to `assets/music/` using these exact filenames:

- `sentinel-awakens.mp3`
- `golden-horizon.mp3`
- `command-center.mp3`
- `eternal-justice.mp3`
- `midnight-tribunal.mp3`

## Victory fanfare

Victory Fanfare is not part of the radio playlist. Place it at:

`assets/music/victory-fanfare.mp3`

It is reserved for an ACFA Official match victory. When triggered, the dashboard pauses the radio, plays the fanfare, and resumes the prior radio track afterward.

## Celebration controls

The dashboard retains:

- Victory Mode overlay
- Championship Mode overlay
- Gold celebration particles
- Shared JSON state polling through `celebration-state.json`

Use a new unique `eventKey` for every victory so the fanfare plays once per browser session for each event.
