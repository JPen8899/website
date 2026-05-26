# Jimmy Peng — Personal Site

A single-page personal portfolio for Jimmy Peng (Cyber Threat Intelligence & Red Team).
Built as one self-contained `index.html` — no build step, no dependencies. Fonts load
from Google Fonts via CDN.

## Files

- `index.html` — the entire site (HTML + CSS + JS inline)
- `favicon.svg` — terminal-prompt favicon
- `README.md` — this file

## Preview locally

Just open `index.html` in a browser, or serve the folder:

```
cd website
python -m http.server 8000      # then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a repo (e.g. `JPen8899/jimmy-peng` or a user site `JPen8899.github.io`).
2. Copy `index.html` and `favicon.svg` into the repo root and push to `main`.
3. Repo **Settings → Pages → Build from branch → `main` / root**.
4. The site goes live at `https://JPen8899.github.io/<repo>/` in ~1 minute.

For a custom domain, add a `CNAME` file with the domain and point your DNS at GitHub Pages.

## Source

Content is drawn from the master resume (`../JimmyPengMaster.pdf`). To update the site,
edit the relevant section in `index.html` directly — sections are clearly commented
(`<!-- EXPERIENCE -->`, `<!-- PROJECTS -->`, etc.).
