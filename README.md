# Zora — a visual novel

Scene 1 of Zora's story, by Brandon Farley (GLITCHMADE). A single static page:
click to advance, one choice, two branches. No accounts, no tracking, no backend.

This is the GitHub Pages port of the Perchance proof of concept at
https://perchance.org/zora-visual-novel — same script, same art, real files.

## Publish it on GitHub Pages

1. Create a new **public** repository on GitHub (e.g. `zora`).
2. Upload everything in this folder (`index.html`, `assets/`, this README, `.nojekyll`).
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   branch `main`, folder `/ (root)`. Save.
4. Your page address becomes:
   `https://<your-github-username>.github.io/zora/`

## Files

- `index.html` — the whole scene: script, styling, and choices.
- `assets/background.webp` — the moonlit shop window, empty street.
- `assets/zora-faint.webp` — Zora at new moon: nearly gone, grin and eyes carrying it.
- `assets/zora-full.webp` — Zora at full moon: fully solid.

## Notes

The sprites were rendered on plain black backgrounds, so they sit as a dark panel
over the scene rather than blending in. A transparent cutout (e.g. rembg) and
re-upload would fix that; it was accepted as-is for the proof of concept.
