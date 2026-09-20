# Tag Paid — static site (upload this whole folder)

This folder is the live website: HTML, CSS, JS.

## Fix for broken styles on GitHub Pages

Upload **everything** in this folder, including:

- `next/` (CSS + JS — required)
- `.nojekyll` (required for GitHub Pages)
- `index.html`, `logo.png`, etc.

If you only upload `index.html`, the site will look broken (no CSS).

## GitHub Pages setup

1. Put these files in your repo `docs/` folder (or set Pages root to this folder)
2. Settings → Pages → Deploy from a branch → **/docs**
3. Custom domain: `tagpaid.app`

Rebuild locally:

```bash
npm run build:static
```
