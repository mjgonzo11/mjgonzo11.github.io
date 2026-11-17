# Martin Gonzalez — AI & Machine Learning Portfolio

A responsive, accessible, single-page portfolio built with plain HTML, CSS, and JavaScript. It highlights my AI and machine-learning projects, professional experience, education, AWS certification, and a downloadable PDF resume.

## Live site

This repository is designed for GitHub Pages at **https://mjgonzo11.github.io/** when the repository is named `mjgonzo11.github.io`.

## Publish using GitHub Pages

1. Create a **public** GitHub repository named `mjgonzo11.github.io` (if you do not already have one).
2. Add the contents of this repository to its `main` branch, with `index.html` in the **repository root**. Do not replace the existing `Moving_website` repository.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then save.
5. After GitHub finishes publishing, visit **https://mjgonzo11.github.io/**.

For a different repository name, the default URL becomes `https://mjgonzo11.github.io/REPOSITORY/`. All website asset paths are relative, so either setup works.

## Editing the website

- `index.html` — text, sections, project links, and SEO metadata.
- `styles.css` — responsive visual design.
- `script.js` — navigation and subtle scroll effects.
- `assets/Martin_Gonzalez_Res.pdf` — original resume; downloadable through the site.
- `assets/favicon.svg` — site favicon.

The **Moving Services Website** project links to [Moving_website](https://github.com/mjgonzo11/Moving_website). Only add a live-demo link after the demo URL is verified.

## Optional local preview

Open `index.html` in a browser, or serve the folder from a local static server.

The `npm run build` command copies the site into `dist/` for the companion Sites preview/deployment. GitHub Pages serves the files directly from the repository root and does not require a build step.

## Notes

- Project status labels distinguish finished coursework from ongoing research.
- The resume PDF is public when GitHub Pages is enabled. Review personal contact details before sharing it widely.
- No backend, database, or analytics service is required.
