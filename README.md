# Driver Assignment Prototype

This is an interactive UX prototype demonstrating **Driver Assignment** within a
"Dispatcher Dashboard" shell — a freight-order-first workflow for assigning drivers to
freight orders, reviewing driver capacity, and simulating assignment status changes.

> **Disclaimer:** This is an interactive UX prototype. All customer, driver, shipment,
> facility, identifier, and operational data shown in the prototype is fictional and used
> for demonstration purposes only. Geographic references may use real cities/states for
> realism. This is not a production system.

**Entry point:** [`index.html`](index.html) — a self-contained, single-file HTML/CSS/JS
page. No build step, no framework, no external dependencies. All markup, styling, mock
data, and interaction logic live in this one file. Open it directly in a browser, or view
it via the live prototype URL below.

**Live prototype:** https://danielaverisanu.github.io/driver-assignment-prototype/

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
