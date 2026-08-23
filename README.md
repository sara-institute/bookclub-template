# SARA Institute Book Club — Presentation Template

A [Quarto](https://quarto.org) reveal.js template for SARA Institute book club presentations.

## Using this template

This repo is set up as a GitHub template repository. To start a new book club presentation:

1. Click **Use this template** → **Create a new repository** on GitHub (or, from the CLI: `gh repo create my-bookclub-talk --template <org>/bookclub-template`).
2. Clone your new repo locally.
3. Open `presentation.qmd` and update the title, author, and date in the YAML front matter.
4. Add any images to the `img/` folder and reference them in your slides.
5. Render the presentation:

   ```bash
   quarto render presentation.qmd
   ```

   Or preview it live while you edit:

   ```bash
   quarto preview presentation.qmd
   ```

## Files

- `presentation.qmd` — the Quarto source for the slide deck (reveal.js format).
- `sara-theme.scss` — SARA Institute branding (colors, fonts, logo placement) applied to the reveal.js theme.
- `img/` — put slide images, logos, and figures here. Includes `logo-sara.png`, the SARA Institute logo.
- `.gitignore` — excludes Quarto's build artifacts (`.quarto/`, `*_files/`, `*_cache/`, rendered `.html`) from version control.

## Requirements

- [Quarto](https://quarto.org/docs/get-started/) installed locally.
