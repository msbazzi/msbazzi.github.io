# msbazzi.github.io

Personal website for Marisa Schmidt Bazzi, built with [Quarto](https://quarto.org).

## Local development

```bash
quarto preview        # live-reload preview
quarto render         # one-shot build into _site/
```

## Deployment

GitHub Pages serves from the `gh-pages` branch (or `docs/` — set in repo settings).
The simplest workflow:

```bash
quarto render
# commit _site contents to whichever branch GitHub Pages is configured to serve
```

For a hands-off setup, switch to a GitHub Action that runs `quarto render` on push.

## Structure

- `index.qmd` — landing page / about
- `research.qmd` — research themes
- `publications.qmd` — peer-reviewed publications + talks
- `projects.qmd` — software & open-source projects
- `cv.qmd` — full CV (links to PDF)
- `_quarto.yml` — site config (navbar, theme, social links)
- `styles.css` — custom styling
- `profile.jpg` — headshot (drop into the repo root)
- `Marisa_Bazzi_CV.pdf` — downloadable CV
