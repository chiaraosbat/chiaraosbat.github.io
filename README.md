# Chiara Osbat Website

This repository contains the static source for `https://chiaraosbat.github.io`.

## Stack

- Plain HTML and CSS
- Local Geist Sans and Geist Mono font files
- Static deployment to GitHub Pages via GitHub Actions

## Local preview

```bash
open docs/index.html in your browser
```

If you prefer a local web server, any simple static server can point at `docs/`.

## Main files

- `docs/index.html` for the homepage bio
- `docs/research/index.html` for the full research list
- `docs/styles/site.css` for the site styling
- `docs/CV.pdf` for the CV link
- `docs/images/chiara-portrait.jpg` for the homepage portrait

## Notices

See `THIRD_PARTY_NOTICES.md` for licenses and acknowledgements for design inspiration and fonts.

## Deployment

GitHub Pages deployment is defined in `.github/workflows/deploy.yml`. The workflow publishes the `docs/` directory directly, with no build step required.
