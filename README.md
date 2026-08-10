# Portfolio — Phillip

Personal portfolio site.

- `index.html` — Home page
- `portfolio.html` — Selected work (six Intuit case studies + pre-Intuit track)
- Image assets referenced by `portfolio.html` live alongside it in this folder.

## Local preview
Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)
Push this folder to a repo and enable Pages on the default branch (root).
`index.html` is served at the site root; "View selected work" links to `portfolio.html`.

Built as static HTML with Tailwind (CDN) and Google Fonts (Geist, Instrument Serif, JetBrains Mono).
