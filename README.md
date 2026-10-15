# Program Monitoring Demo (synthetic data)

Static browser demo. No backend, login or live data. Everything is synthetic.

## Files
- `index.html`: the whole app (HTML, CSS, JS). No build step, no libraries. The IBM Plex Sans font loads from Google Fonts and falls back to system fonts offline.
- `synthetic-dataset.json`: the dataset reference. Its values are also embedded in `index.html` (constants `HIST`, `ONG`, `seed()`). Edit both if you change the data.

## Run locally
Open `index.html` in a browser, or run `npx serve .` in this folder.

## Deploy on Vercel
1. Put these files in a GitHub repo.
2. In Vercel choose Add New > Project, import the repo.
3. Framework preset: Other. No build command, no output directory. Click Deploy.

## Kiosk use
- "Reset demo" (top right) restores all state.
- Press F11 for full screen. Reload the page to reset too.

## What it covers
Monitoring periods, assumption sliders, decision log, suggested actions (scripted), simulated funnel, journey view.
Scenario results are illustrative, not guaranteed outcomes.