# NEO-TELHARSA v0.64 — Optional Opening Illustration Asset System

- Built from the original v0.63 ZIP, without modifying game story, save schema, existing MP3, or subtitle cue timings.
- 20 storyboard segments each have three independent illustration slots: background WebP, transparent character PNG, and transparent overlay PNG.
- The browser attempts to load optional assets on entering each segment. A missing image hides itself and leaves the v0.63 CSS animation visible.
- Image layers follow existing audio-clock-driven cut and camera animation. Supports cover/contain responsive rendering and reduced motion.
- Asset path mapping is embedded in `index.html` for `file://` support; the human-editable reference is `assets/opening/op-shot-manifest.json`.
- To customize positions/paths, change both the JSON reference and corresponding `op64Assets` embedded configuration in `index.html`. JSON alone is reference, not live runtime config.
- No images are included: this release supplies the integration slots only.
- Verification: JavaScript syntax via Node, ZIP integrity, and SHA-256 comparison for original MP3 and other files except index.html and new files. Browser visual validation not performed.
