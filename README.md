# ContactGen3D Website

This is a lightweight static site scaffold adapted from the Vysics website structure (HTML/CSS/JS, no build tools).

## Structure
- `index.html`: Main page (replace titles, abstract, links).
- `style.css`: Typography and layout (hero, link tiles, tables, two-column sections, citation box, carousels support).
- `script.js`: Optional gallery utilities (dormant by default).
- `static/images/`: Put figures, videos, and preview images here.
- `static/logos/`: Icon assets for dataset and video tiles.

## Replace Placeholders
- Update `<title>`, meta description, and social `og:`/`twitter:` tags.
- Fill authors, affiliations, and venue.
- Set the Paper/Code/Dataset/Video links.
- Add figures/videos to `static/images/` and reference them from `index.html`.

## Preview Locally
Use any static file server, e.g. Python:

```bash
python3 -m http.server -d . 8080
# Then open http://localhost:8080
```

## Publish on GitHub Pages
- Push to `main` (or `gh-pages`).
- In repository Settings → Pages, set Source to `Deploy from a branch` and select the branch and root (`/`).

## Notes
- Heavy media from the template was intentionally not copied. Add your own assets to `static/images/`.
- The stylesheet already supports carousels and figure grids if you decide to add them later.
