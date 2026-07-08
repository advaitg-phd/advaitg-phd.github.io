# advaitg-phd.github.io

Personal teaching website — a hub of courses, each with interactive tools & simulations.

Live at: `https://advaitg-phd.github.io/`  (replace advaitg-phd once your repo is created)

## Structure
- `index.html` — personal landing page (lists courses)
- `15516/index.html` — 15.516 Corporate Financial Accounting (lists that course's tools)
- `15516/balance-sheet/index.html` — Balance Sheet Simulator  → `/15516/balance-sheet/`

## Add a new tool to a course
1. Create a subfolder under the course, e.g. `15516/t-accounts/`, with its own `index.html`.
2. Add a matching tile in `15516/index.html`.

## Add a new course
1. Create a new course folder, e.g. `15501/`, with its own `index.html`.
2. Add a matching card in the top-level `index.html`.

## Deploy (GitHub Pages)
Repo **Settings → Pages → Deploy from a branch → main / root**. All static, no build step.
