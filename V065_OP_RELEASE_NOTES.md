# NEO-TELHARSA v0.65 — Opening Asset Stability

- Based on v0.64 ZIP; no changes to story, save keys, choices, MP3, or subtitle timing data.
- Added a 20-shot production guide with filenames, composition, camera direction, mobile safe area, and spoiler precautions.
- Asset loading: asynchronous preloading for next segment; bounded cache of completed loads; generation token prevents stale images from a previous shot appearing after seeking; failed assets remain hidden with CSS fallback.
- Mobile: cover/contain layout, safe-area controls, caption width limits, reduced-motion support.
- Verification: Node JavaScript syntax check, ZIP testzip, and SHA-256 comparison for all original ZIP entries except modified `index.html` and `assets/opening/shots/README.md`.
- Browser visual playback and vocal-level forced alignment were not performed.
