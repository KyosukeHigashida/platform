# Higashida Kyosuke — Personal Blog

Personal blog of Higashida Kyosuke. Built as a static site, hosted on GitHub Pages.

**URL**: https://kyosukehigashida.github.io/platform/

## Structure

- `index.html` — top page
- `about.html` — about
- `works.html` — works (drawings, math slides, etc.)
- `notes.html` — short notes
- `links.html` — links
- `posts/` — blog posts
- `assets/styles.css` — shared styles

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

1. Push to GitHub.
2. Repository settings → Pages → Deploy from branch → `main` / `(root)`.
3. Save and wait for deployment.
