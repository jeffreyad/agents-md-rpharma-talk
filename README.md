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
- `assets/` — hex logos ({admiral}, {admiralpeds}), QR code, and
  illustrations
- `_quarto.yml` — project/render config
- `.github/workflows/publish.yml` — renders and publishes to GitHub Pages
  (`gh-pages` branch) on every push to `master`

## AI disclosure

In keeping with the talk's subject:

- Illustrations in `assets/` were generated with Gemini Flash.
- The `{admiral}` AGENTS.md generator and the workflow that delivers it had
  contributions from Claude Code (Sonnet 4.6 through Opus 5.5) and GitHub
  Copilot.
- This deck was edited with help from Claude Code: the live demo links,
  offline backup slides, and layout changes.

All content was reviewed by the author.

## Live site

<https://jeffreyad.github.io/agents-md-rpharma-talk/>
