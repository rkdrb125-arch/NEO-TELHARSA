# NEO-TELHARSA v0.68 — SILENT PARADISE OP startup fix and cinematic cuts

## Fixes
- Moved the existing opening initializer to a dedicated script after the `#neoOp` DOM markup. Previously it ran before `#neoOp`/`#opAudio` existed and could throw on `.querySelectorAll`, preventing the opening button from being wired.
- Preserved the v0.67.1 reading stability hotfix: ordinary dialogue and narration paging must not fade or reinitialize the entire scene.
- Added cut-index-specific art direction for the 20 existing OP segments: XERO hologram flicker, Daniela rim light, investigation glow, title glow, memory fragment light, outro signal.
- Kept original bundled MP3, cue times, scene schedule, image assets and save logic unchanged.
- Retained mobile layouts, missing-image CSS fallback, reduced-motion behavior and spoiler-safe symbolic imagery.

## Testing and limits
- JavaScript syntax checked using Node.js `node --check` on both inline scripts.
- ZIP tested using Python zipfile.testzip().
- Browser smoke test attempted with Chromium/Playwright but local navigation was blocked by administrator (`ERR_BLOCKED_BY_ADMINISTRATOR`); real PC/mobile browser playback remains unverified.
- Original subtitle cue times were preserved, not re-aligned to vocals.

## Deploy
Extract this archive into the repository root (including assets directories), commit all changes and hard-refresh the deployed page. The start screen has the `♫ SILENT PARADISE · 오프닝 감상` button.
