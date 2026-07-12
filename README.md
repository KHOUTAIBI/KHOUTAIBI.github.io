# khoutaibi.github.io

My personal website — [khoutaibi.github.io](https://khoutaibi.github.io)

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme, deployed automatically to GitHub Pages via GitHub Actions.

## Editing

- **About page**: `_pages/about.md`
- **Projects**: add a markdown file in `_projects/`
- **CV**: fill `_data/cv.yml` (RenderCV format), then set `nav: true` in `_pages/cv.md`
- **Social links**: `_data/socials.yml`
- **Site config**: `_config.yml`

Push to `main` and the `Deploy site` action builds and publishes to the `gh-pages` branch.
