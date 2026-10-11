# junoravin.github.io

Personal academic website, built with [Quarto](https://quarto.org) and published with GitHub Pages.

## Edit and preview

```bash
quarto preview    # live-reloading preview in the browser
```

- `index.qmd`: home page (intro, links)
- `publications.qmd`: publication list (plain Markdown, edited by hand)
- `teaching.qmd`: courses and lecture materials
- `styles/wvu.scss`: colors and fonts. WVU Blue `#002855` for text, headings and links; WVU Gold `#EAAA00` for accents only (rules, underlines), never for text.
- `files/`: CV PDF. `images/`: headshot.

## Publish

Push to `main`. The workflow in `.github/workflows/publish.yml` renders the site and deploys it to GitHub Pages.
