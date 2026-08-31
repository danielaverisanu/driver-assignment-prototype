# Driver Assignment Prototype

A self-contained, single-file HTML/CSS/JS prototype of the Driver Assignment workspace
inside a "Dispatcher Dashboard" shell (freight-order-first assignment flow, driver side
panel, Work Today capacity visualization, status simulation, fallout/reconciliation, etc.).

**Entry point:** [`index.html`](index.html) — no build step, no framework, no external
dependencies. All markup, styling, mock data, and interaction logic live in this one file.
Open it directly in a browser, or view it via the live GitHub Pages URL below.

**Live prototype:** _(filled in once GitHub Pages is enabled — see repository Settings → Pages)_

## Updating the live prototype

The live URL always serves whatever is on `main`. To ship a change:

1. Edit `index.html` locally.
2. Open it directly in a browser (double-click the file, or `open index.html` on macOS) and
   click through the change — there's no build/dev-server step to run first.
3. Commit the change:
   ```bash
   git add index.html
   git commit -m "Describe the change"
   ```
4. Push to `main`:
   ```bash
   git push origin main
   ```
5. GitHub Pages rebuilds automatically from `main` and the same live URL updates —
   no new link, no re-share needed. A deployment usually finishes within a minute or two;
   check progress under the repository's **Actions** tab or **Settings → Pages**.
