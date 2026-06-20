# Settle

A gut-friendly weekly dinner planner (PWA). One low-FODMAP, low-fat dinner per day, built to clear the stomach before bed.

## Deploy on GitHub Pages
1. Create a new repo and push these files to the **root** (keep the folder structure).
2. Repo **Settings → Pages → Build from `main` / root**.
3. Open the published URL on your phone and "Add to Home Screen" to install it.

## Files
- `index.html` — the app. Edit the `MEALS` and `SHOPPING` arrays near the top of the `<script>` to change meals or the shopping list.
- `manifest.json` — install metadata (name, icons, colours).
- `sw.js` — offline cache. **Bump `CACHE = 'settle-v1'` to `-v2`, `-v3`… whenever you edit anything**, then commit, so phones pick up the new version.
- `icons/` — app icons.

Shopping-list ticks are saved on the device via localStorage.
