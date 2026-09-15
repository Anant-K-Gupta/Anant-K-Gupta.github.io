# anant-k-gupta.github.io

Personal site. Hand-written static HTML, no build step, served from this repo
by GitHub Pages.

- `index.html` — the whole site. CSS and JS are inline, so a visit is one
  request for the document plus fonts and the avatar.
- `fonts/` — self-hosted woff2, subset to Latin. Zodiak (headings) and Erode
  (body) are Fontshare faces, free for commercial use. JetBrains Mono
  (metadata) is SIL OFL 1.1.
- `img/` — AVIF with WebP fallback. Project previews are lazy-loaded.
- `.nojekyll` — skips Jekyll processing.

Page weight is about 82KB on first load.
