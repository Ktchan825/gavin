# Gavin Chan

Single-page personal site for hiring managers.

**Live:** https://ktchan825.github.io/gavin/

## GitHub Pages

This is a static one-page site (`index.html` + `styles.css`). That is the right shape for GitHub Pages: no React/Vite build, no router.

Pages is already enabled on this repo:

- Source: `main` branch, site root (`/`)
- URL: https://ktchan825.github.io/gavin/

GitHub rebuilds the site on every push to `main`. No GitHub Actions workflow is required.

To change this later: **Settings → Pages → Build and deployment** → Deploy from a branch → `main` / `/ (root)`.

`.nojekyll` tells Pages to serve files as-is instead of running Jekyll.

## Local

```bash
python3 -m http.server 3000 --bind 0.0.0.0
```

Open http://localhost:3000
