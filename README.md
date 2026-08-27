# patelraj2406.github.io

Personal site — Raj Patel, Cloud Data Engineer.

## Deploy to GitHub Pages

1. Push these three items to the root of your `patelraj2406.github.io` repo:
   - `index.html`
   - `support.js`
   - `assets/raj-photo.jpg`
2. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Live at `https://patelraj2406.github.io` within a minute or two.

No build step, no dependencies to install. Fonts load from Google Fonts.

## Editing

All markup and content live in `index.html`:
- Layout is inside `<x-dc>` (inline styles only).
- Content data (jobs, education, certifications, projects, skill tiles) is in the `<script data-dc-script>` block at the bottom, inside `renderVals()`.
- `support.js` is the runtime; do not edit it.
