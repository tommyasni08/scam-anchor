# Deploying the ScamAnchor site to GitHub Pages

This folder is **self-contained** — `index.html` + the two images. To get a public URL:

> ⚠️ **Do not host from the `OGP-SWE-SCAMSHIELD-Pivot` repo** — it's your private
> career-strategy working folder. Publish this `site/` folder to a *separate public
> repo*, exactly like you did with `gasp-pm-portfolio`.

## Steps

1. **Create a new public repo** on GitHub, e.g. `scamanchor` (the repo name becomes the
   URL slug → `https://tommyasni08.github.io/scamanchor/`).
2. **Copy the contents of this `site/` folder** into the new repo:
   - `index.html` — the page (the architecture diagram is now inline SVG, so no separate
     image file is needed for it)
   - `review-console.png` — the console screenshot
3. **Commit and push** to the new repo's `main` branch.
4. In the repo: **Settings → Pages → Build and deployment → Source: "Deploy from a branch"
   → Branch: `main` / `/ (root)` → Save.**
5. Wait ~1 minute. Your public URL appears at the top of the Pages settings:
   **`https://tommyasni08.github.io/<repo-name>/`** — that's the link to share in outreach.

## Before you share it
- **Voice pass.** The prose is a first draft — read it in your own voice and adjust,
  especially any "I" statements. (It's `index.html`; the copy is in plain `<p>`/`<h2>`
  tags, easy to edit.)
- **GitHub link.** The hero and footer link to your profile (`github.com/tommyasni08`).
  If you publish the *code* (the classifier/taxonomy) to a public repo, point those at it.
- **Quick local check:** double-click `index.html` (or `open index.html`) to view before
  pushing.
