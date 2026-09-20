# Tag Paid static site

This folder is a static build (HTML, CSS, JS) for GitHub Pages.

## GitHub Pages setup

1. Repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` (or `master`), folder: **/docs**
4. Save

If the site is at `https://USERNAME.github.io/REPO/`, rebuild with:

```bash
NEXT_BASE_PATH=/REPO npm run build:static
```

Then commit and push the updated `docs/` folder.
