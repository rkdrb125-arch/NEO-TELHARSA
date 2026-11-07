# NEO-TELHARSA v0.54

Base: v0.53. Scene IDs, canonical story, flags, save keys, investigation and choices preserved.

## Background art replacement
Put optional WEBP images under `assets/backgrounds/` with these exact names:
- city-night.webp — Prologue / city skyline
- xero-square.webp — EP1 / commercial hologram district
- dawn-crime-scene.webp — EP2 / pre-dawn investigation street
- slum-alley.webp — EP3 / slum entrance
- covered-alley.webp — EP3 / covered back alley
- abandoned-house.webp — EP3 / interrogation inside abandoned house
- house-door.webp — EP3 / entrance and armed intrusion
- rainy-house-exterior.webp — EP3 / aftermath

Images are optional. If not present, the original CSS scene art remains. Backgrounds are behind the actor layer; dialogue remains in front. Suggested source resolution: 1920x1080 for desktop and 1080x1920 for mobile (same file uses cover cropping; center important subjects). Keep artwork free of characters and text.

## Reading and touch
Retains v0.53 per-scene reading pages, text reveal, choice first-tap arm/second-tap commit, existing scene IDs and save data. Mobile layout adds minimum hit areas and word wrapping.

## Validation
See V054_TEST_REPORT.json. Automated browser testing may be limited by Chromium runtime availability.
