# andreatizzani.github.io

Personal academic website of Andrea Tizzani, served with GitHub Pages at
[www.andreatizzani.com](https://www.andreatizzani.com).

Plain hand-written HTML and CSS — no build step, no dependencies.

## Structure

The site is a single page: `index.html` holds every section (About, Research,
Teaching, News), reached by scrolling or by anchors (`/#research`, `/#teaching`,
`/#news`). `research.html`, `teaching.html` and `news.html` are tiny redirect
stubs so those addresses also work.

| File | Purpose |
|---|---|
| `index.html` | The whole site: About · latest-news highlight · Research · Teaching · News |
| `research.html`, `teaching.html`, `news.html` | Redirects to the matching section of `index.html` |
| `assets/style.css` | All styling (colors, fonts, layout) |
| `assets/fonts/` | Latin Modern Roman webfonts (self-hosted) |
| `assets/portrait.png` | Profile photo (transparent background) |
| `assets/map.jpg` | Archival map used as the homepage backdrop |
| `files/Tizzani_CV.pdf` | CV linked from the nav |
| `CNAME` | Custom domain for GitHub Pages — do not delete |

## How to edit

Everything is plain text. Edit any `.html` file directly on GitHub (pencil icon)
and commit — the live site updates in about a minute.

Common edits (all inside `index.html`):

- **New paper** — copy an `<article class="paper">…</article>` block and change the text.
- **New course** — copy a `<div class="course">…</div>` block.
- **New news item** — copy a `<div class="news-item">…</div>` block at the top of
  the `#news` section, and update the one-liner in the `news-flash` box near the
  top of the page to match your latest highlight.
- **New CV** — replace `files/Tizzani_CV.pdf` with the new file (same name).
- **Colors** — change the values at the top of `assets/style.css` (`:root` block).
