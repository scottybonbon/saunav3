# SULA — saunav3

Static site. No build step. Deploy to GitHub Pages:

1. Upload everything in this folder to the repo root (keep the folder structure — `index.html`, `support.js`, `image-slot.js`, `uploads/` all at the top level).
2. Repo → Settings → Pages → Source: "Deploy from a branch" → branch `main`, folder `/ (root)` → Save.
3. Live in ~1 min at https://scottybonbon.github.io/saunav3/

`.nojekyll` is included so GitHub serves every file as-is. Fonts load from Google Fonts. Uses 4K video loops; transcode to 1080p before launch for faster loads.
