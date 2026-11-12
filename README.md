# Portfolio site (exported from Framer)

Static export of the Framer site, restructured to run on GitHub Pages.

## Deploy

The site must be served from a domain **root** (Framer's in-page router uses `/` and `/dive`).
Use one of these:

- A repo named `<your-github-username>.github.io` → served at `https://<username>.github.io/`
- Any repo + a custom domain (Settings → Pages → Custom domain)

Then: Settings → Pages → Source: "Deploy from a branch" → `main` / `/ (root)`.

## Preview locally

Don't double-click `index.html` — browsers block JavaScript modules on `file://`, which
kills all interactivity. Run a local server from this folder instead:

    python3 -m http.server 8000

and open http://localhost:8000
