# AGENTS.md, {admiral}, and the AI-Assisted Clinical Programmer

R/Pharma talk slides (Quarto + revealjs).

## Render

```sh
quarto render
# or, for live preview while editing:
quarto preview slides.qmd
```

Output: `slides.html` (self-contained; open directly in a browser).

## Structure

- `slides.qmd` — talk content
- `theme.scss` — pharmaverse-ish revealjs theme tweaks
- `assets/` — hex logos ({admiral}, {admiralpeds})
- `_quarto.yml` — project/render config
- `.github/workflows/publish.yml` — renders and publishes to GitHub Pages
  (`gh-pages` branch) on every push to `master`

## Live site

<https://jeffreyad.github.io/agents-md-rpharma-talk/>
