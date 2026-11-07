# v0.67 visual layer order

Main: background image / ambience -> vignette -> actor silhouettes -> HUD / narration / choices. Scene-specific focus is configured in v054ApplyBackground. Adjust `v067Focus` and `v067MobileFocus` if crop hides important composition.

Opening: CSS fallback shot -> background WebP -> character PNG -> overlay PNG -> title and subtitles / controls. Motion uses `--v067-bg-*`, `--v067-char-*`, `--v067-fx-*` CSS variables. All twenty shot timings and file names are inherited from v0.66.

Image-less scenes intentionally retain CSS visuals. Character PNGs should have transparent backgrounds. Recommended test widths: 360, 390, 430, 768, 1280 CSS pixels.
