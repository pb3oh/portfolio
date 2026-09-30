# Portfolio — Phillip

Personal portfolio site. A single static page, no build step.

- `index.html` — the whole site, written as a blog-style timeline, newest first: Curator, Cairn, Intuit (with the Dependency Planner prototype), DiversyFund, Fitify, HodlFeed, Omni. Each entry pairs the work with a "What it gave me" note.
- `styles.css` — all styles. Colors are CSS variables at the top of the file; dark mode follows the visitor's system setting.
- `portfolio.html` — redirect only. Old links such as `portfolio.html#diversyfund` forward to the matching section of `index.html`.
- Images live alongside the pages in this folder.

## Adding an entry
In `index.html`, copy an `<article class="entry">` block and paste it at the top of the timeline (newest first). Screenshots at 1600×1000 work well.

## Local preview
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)
Enable Pages on the default branch (root). `index.html` is served at the site root.

Fonts: Geist, Instrument Serif, and JetBrains Mono from Google Fonts. No other dependencies.
