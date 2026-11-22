# Nicholas Yaple — Portfolio Website

Built using Quarto and published using GitHub Pages.

## Local preview

1. Install Quarto: https://quarto.org/docs/getting-started/
2. In this directory, run:

   ```bash
   quarto preview
   ```

## Publish

The included GitHub Actions workflow publishes the site to the `gh-pages` branch when changes are pushed to `main`.

In GitHub, open **Settings → Actions → General → Workflow permissions** and ensure workflows have permission to write to the repository if publishing fails.

Then open **Settings → Pages** and select the `gh-pages` branch (root), if it isn't automatically configured.

## Personalize

- Replace bracketed placeholders in `index.qmd`, `projects.qmd`, and `research.qmd`.
- Replace `YOUR_EMAIL`.
- Add `resume.pdf` in the project root.
- Update LinkedIn URL.
- Add project images under a folder such as `images/` and reference them in Quarto pages.
