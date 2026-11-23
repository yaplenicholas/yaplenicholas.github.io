# Nicholas Yaple — Portfolio

Quarto portfolio site published at https://yaplenicholas.github.io

## Structure
- `index.qmd` — home
- `projects.qmd` — engineering projects
- `research.qmd` — Ph.D. research overview (dissertation chapters, figures, code, citation)
- `research/figs/` — web figures exported from the dissertation
- `research/dissertation/` — dissertation PDF and ASB 2024 abstract
- `resume.pdf`

## Local preview
Install Quarto, then run `quarto preview`.

## Publishing
Pushing to `main` triggers `.github/workflows/publish.yml`, which renders the site and publishes it to the `gh-pages` branch.
In **Settings → Pages**, the source should be the `gh-pages` branch, root folder.

## To do
- Add the LinkedIn URL in `_quarto.yml` (currently commented out).
- Create the `yaplenicholas/DSR` repository for the MATLAB simulation code (linked from the Research page).
- Add visuals for the teleoperation and disc-flight projects.
