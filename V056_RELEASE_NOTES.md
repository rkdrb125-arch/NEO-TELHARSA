# v0.56 — Inner thought presentation

- Added three **separate** Daniela inner-thought scene nodes, after atmospheric scene transitions, not appended to narrative or dialogue text.
- Inner thoughts use a standalone dimmed screen, centered italic text at **70% opacity**, no speaker strip, with background and actor darkened.
- Each thought is its own scene: tap to continue; existing choices and their two-tap confirmation logic unchanged.
- Added IDs: `v056_thought_broadcast`, `v056_thought_missing`, `v056_thought_scream`. The previous scene IDs and localStorage save key are preserved.
- All new text is **game adaptation**, not canonical dialogue.
- Source v0.55. Test: JavaScript syntax and ZIP integrity. Mobile browser execution not claimed.
