# Minimal Blog Template

This repository contains a minimal static blog scaffold designed for GitHub Pages.

## Structure

- `index.html`: blog top page with post list
- `posts/welcome.html`: first post template
- `assets/styles.css`: shared styles

## Local preview

Open `index.html` in your browser, or run a local static server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a GitHub repository and push this directory.
2. Go to repository settings -> `Pages`.
3. In `Build and deployment`, select:
   - Source: `Deploy from a branch`
   - Branch: `main` (or your default branch)
   - Folder: `/ (root)`
4. Save and wait for deployment.

Your site will be published at:

- User/Org site: `https://<username>.github.io/`
- Project site: `https://<username>.github.io/<repository>/`
