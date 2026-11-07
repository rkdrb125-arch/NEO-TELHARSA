# Optional opening images (v0.64)

For each of the 20 music segments, add any of these filenames:
- `shot-01-background.webp` … `shot-20-background.webp` — full-bleed scene, recommended 1920×1080
- `shot-01-character.png` … `shot-20-character.png` — transparent foreground character, recommended 1080×1920 or 1600×900
- `shot-01-overlay.png` … `shot-20-overlay.png` — optional transparent effects layer

All three are optional. Missing assets fall back to existing CSS scenes automatically. Preserve names, case, and directory structure.

The `assets/opening/op-shot-manifest.json` is a mapping/reference; runtime mapping is embedded in index.html for local file compatibility. For custom names or focus positions, update both.

Keep illustrations spoiler-safe (no original Miguel revelation, NANO's nature, or late-game secrets).

Full per-shot storyboard: `../../../V065_OP_ASSET_SHOT_GUIDE.md`.
