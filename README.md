# contact.page — design previews

One central home for every design preview: mockups, mini-vertical pages, page drafts.
Served as a real clickable site via GitHub Pages.

**Live index:** https://kim-page.github.io/contact-page-design/

Deliberately kept out of Google: `robots.txt` disallows everything and every page
carries `noindex, nofollow`. Only people with the link will find it.

## Publishing convention

1. A seat (or Kiri) produces a **self-contained HTML** preview.
2. Kiri commits it under its section folder (`mini-verticals/<slug>/index.html`, `listing-page/<slug>/index.html`, …).
3. It gets a card on the index. Every committed page must carry the noindex meta tag.

**Rule: a preview isn't done until it's on the index.** Chat artifacts are fine for
instant looks; this repo is the durable, clickable, indexed home.

## Layout

- `index.html` — the catalog
- `robots.txt` + noindex meta — stays out of Google
- `mini-verticals/` — one folder per vertical page
- `listing-page/` — listing page drafts and mockups
- `brand/` — logo & identity explorations
- `.nojekyll` — serve raw HTML, no Jekyll processing
