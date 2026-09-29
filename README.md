# Portfolio — Phillip

Personal portfolio site. A single static page, no build step.

- `index.html` — the whole site: hero, the AI-native Intuit Expert Platform (with the Dependency Planner prototype), the pre-Intuit track (DiversyFund, Omni, Fitify, HodlFeed), personal projects, and contact.
- `styles.css` — all styles. Colors are CSS variables at the top of the file; dark mode follows the visitor's system setting.
- `portfolio.html` — redirect only. Old links such as `portfolio.html#diversyfund` forward to the matching section of `index.html`.
- Images live alongside the pages in this folder.

## Adding a personal project
In `index.html`, find the `#projects` section, copy one of the `<article class="project">` cards, and drop a screenshot (1600×1000 works well) into this folder. The dashed "Next up" card is a placeholder; delete it once the grid is full.

## Local preview
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)
Enable Pages on the default branch (root). `index.html` is served at the site root.

Fonts: Geist, Instrument Serif, and JetBrains Mono from Google Fonts. No other dependencies.
