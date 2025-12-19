# DaScient Sites

Static, no-build GitHub Pages sites for DaScient.

This repository publishes to GitHub Pages and serves a single-page, Three.js-powered experience (the “Cosmic Dashboard”) from `index.html`.

## Live

- https://dascient.github.io/sites/

## What’s in here

- `index.html` — main site entry (Cosmic Dashboard)
- `.nojekyll` — disables Jekyll/Liquid processing on GitHub Pages (recommended for pure static sites)
- `assets/` — optional images/icons referenced by `index.html` (favicon + social preview)

## Quick start (local)

You can open `index.html` directly, but for best behavior use a tiny local server:

### Python
```bash
python3 -m http.server 8080

Then open:
	•	http://localhost:8080

Node

npx serve .

Deploy (GitHub Pages)
	1.	Repo → Settings → Pages
	2.	Source: Deploy from a branch
	3.	Branch: main
	4.	Folder: / (root)

Your site will publish at:
	•	https://dascient.github.io/sites/

Notes
	•	This repo is intentionally static (no Jekyll build, no bundlers).
	•	If you add third-party packages or large folders in the future, keep them out of the published root or ensure .nojekyll stays present.

License

MIT — see LICENSE.

