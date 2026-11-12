# Xingguang · AI4S Notes

Source for [xingguangz.github.io](https://xingguangz.github.io/), a bilingual site for learning and research notes in AI for Science.

## Local preview

Install [Quarto](https://quarto.org/docs/get-started/) and run:

```sh
quarto preview
```

## Publish

Push to `main`. GitHub Actions renders the site and deploys it to GitHub Pages. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**.

## Add a note

Create a `.qmd` file under `notes/` and, if you want an English translation, another under `en/notes/`. Add links to both note indexes. The [research log template](notes/research-log-template.qmd) provides a starting structure.

## Update the CV

Edit `cv.qmd` and `en/cv.qmd` with public education, work experience, and project details. The navigation links to both language versions.
