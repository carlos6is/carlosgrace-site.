# carlosgrace.com

Personal GIS portfolio, built with [Quarto](https://quarto.org) and hosted on GitHub Pages.

## Folder layout

```
_quarto.yml            site settings, navbar, links
styles.scss            colours, fonts, layout
index.qmd              home page
projects.qmd           project grid (lists everything in projects/)
about.qmd              bio, education, skills
contact.qmd            email and links
projects/<name>/       one folder per project: index.qmd + thumbnail.png
files/                 CV PDF, favicon, hero contour graphic
CNAME                  tells GitHub Pages the domain is carlosgrace.com
docs/                  the rendered website (don't edit by hand)
```

## Edit, preview, publish

1. Open the folder in RStudio (File > Open Project in New Session, or just open the folder).
2. In the Terminal tab run `quarto preview` to see the site live in your browser.
3. Edit any `.qmd` file and save. The preview refreshes.
4. When happy, run `quarto render`. This rebuilds `docs/`.
5. Commit and push to GitHub. The live site updates within a minute or two.

## Add a new project

1. Copy an existing folder in `projects/`, e.g. `projects/ev-charger-access` to `projects/my-new-project`.
2. Edit its `index.qmd` (title, description, categories, the five sections).
3. Replace `thumbnail.png` with your map export (3:2 ratio, around 1800 x 1200 px).
4. Add the new path to the `contents:` list in `projects.qmd` (and `index.qmd` if it should be on the home page).
5. Render and push.

## Edits still to make

- [ ] `_quarto.yml` and `contact.qmd`: replace `YOUR-LINKEDIN-HANDLE` and `YOUR-GITHUB-USERNAME`
- [ ] Add your CV as `files/Carlos-Grace-CV.pdf`
- [ ] Replace each `thumbnail.png` with a real map
- [ ] Fill in every yellow **Add:** box on the project pages, then delete the box
