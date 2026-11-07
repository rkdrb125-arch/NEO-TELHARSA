# NEO-TELHARSA v0.67 — Mobile Cinematic Layer Pass

Based on the supplied v0.66 archive. This is a presentation-only update.

- Main story: added scene-specific desktop/mobile focal positions for bundled backgrounds, subtle zoom framing, preserved foreground actor stacking and dialogue priority.
- Opening: 20 existing segments now animate real background/character/overlay layers at different speeds based on their existing camera direction and audio clock. No changes to segment timing, MP3, subtitles, or storyline.
- Fallback: missing shot assets continue to use the existing CSS scene. Asynchronous image-generation guard and preload logic unchanged.
- Accessibility: reduced-motion disables the new transforms; mobile caption safe areas retained.
- No new canon, characters, or spoiler images introduced.
- Browser rendering and actual-device playback require further validation.
