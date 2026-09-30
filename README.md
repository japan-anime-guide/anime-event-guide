# Japan Anime Event Guide

Static site published at https://japan-anime-events.pages.dev (Cloudflare Pages, deployed from the `main` branch; no build step, output directory is the repository root).

- `index.html` — the page (loads `events.json` at runtime)
- `events.json` — event data and series list; updated every two days by the System Dept scheduled task
- `img/` — event images and series logos
- `privacy.html` — privacy policy, ad/affiliate disclosure, image credits
- `_headers` — security headers for Cloudflare Pages

**Never commit credentials** (OAuth client secrets, tokens, API keys, `.env`). This repository must contain only files that are meant to be public on the website.
