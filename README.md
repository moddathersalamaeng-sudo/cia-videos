# CIA Academy — course videos

Video files for the Continual Improvement Academy (أكاديمية التحسين المستمر), served by GitHub Pages at
`https://moddathersalamaeng-sudo.github.io/cia-videos/` — the same origin as the Academy, so the Academy's
Content-Security-Policy (`'self'`) allows them.

| Folder | Content |
|---|---|
| `v/<id>.mp4` | the video (H.264 / AAC, fast start) |
| `p/<id>.jpg` | poster image |
| `s/<id>.html` | worksheet (where the episode has one) |
| `t/<id>.txt` | transcript (where the episode has subtitles) |
| `catalog.json` | ids, series, titles, durations |

Where each video appears in the Academy is decided in the Academy repository (`academy/tools/phase18/placements.py`,
built into `academy/data/seed/videos.json`). To add a video: put the files here with a new id, add the id to
`catalog.json` and `placements.py`, run `python3 tools/build_phase18.py` in the Academy, then push both repositories.

© 2026 مدثر سلامه — Continual Improvement Academy. All rights reserved.
