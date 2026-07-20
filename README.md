# QITS Website

A static website for QITS (Quality &amp; Technical Solution Service) — no build step, no dependencies. Just HTML, CSS and JS.

## Files
- `index.html` — the page
- `style.css` — all styling
- `script.js` — mobile menu + footer year
- `assets/favicon.svg` — browser tab icon

## How to host it for free on GitHub Pages

1. Go to https://github.com and log in (create a free account if you don't have one).
2. Click the **+** icon top-right → **New repository**.
3. Name it anything, e.g. `qits-website`. Set it to **Public**. Don't add a README (you already have one). Click **Create repository**.
4. On the new repo page, click **uploading an existing file** (or drag files into the browser window).
5. Upload **all the files in this folder** — `index.html`, `style.css`, `script.js`, `README.md`, and the `assets` folder with `favicon.svg` inside it. Keep the same folder structure (`assets/favicon.svg`, not just `favicon.svg` at the root).
6. Click **Commit changes**.
7. Go to the repo's **Settings** tab → **Pages** (left sidebar).
8. Under "Build and deployment" → Source, choose **Deploy from a branch**. Branch: **main**, folder: **/ (root)**. Click **Save**.
9. Wait 1–2 minutes, then refresh the Pages settings page. You'll see a link like:
   `https://YOUR-USERNAME.github.io/qits-website/`
   That's your live site — share it with anyone.

## Making changes later
Edit any file directly on GitHub (click the pencil icon on the file page) and commit — the live site updates automatically within a minute or two.

## Customizing
- Colors and fonts are defined as CSS variables at the top of `style.css` under `:root`.
- All copy lives in `index.html` — search for the text you want to change.
- To add real photos, drop image files into `assets/` and reference them with `<img src="assets/yourfile.jpg">` wherever you'd like in `index.html`.
