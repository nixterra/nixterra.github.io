# Personal Portfolio
This is the source code for my personal website, built with [Quarto](https://quarto.org/) and hosted via GitHub Pages.

**🔗 Live site:** [nixterra.github.io](https://nixterra.github.io)

## Tech Stack
- [Quarto](https://quarto.org/)
- HTML/CSS
- GitHub Pages

## 📁 Structure

- `index.qmd` – Homepage
- `projects/` – Contains project pages like Medium analysis
- `styles.css` – Custom site styles
- `_quarto.yml` – Site configuration
- `docs/` – Rendered HTML output used for GitHub Pages (auto-generated)

The site is automatically built and deployed via GitHub Pages:

- Source branch: `main`
- Publishing folder: `docs/`

To update the site:

1. Edit `.qmd` files.
2. Run `quarto render` to generate the updated HTML in `docs/`.
3. Commit and push changes to GitHub.
