# OpenZilo project website

Academic project page for **OpenZilo: An Open Smart-Ring Platform for Human-Centric Sensing and Interaction with Robots**.

Live website: https://ziloai.github.io/openzilo-paper-website/

## Edit and preview

This is a buildless static website. Edit `index.html` for content and `assets/openzilo.css` / `assets/openzilo.js` for project-specific layouts and interactions.

```sh
python -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173/ to preview. All local assets use relative paths so the website works under the GitHub Pages project path.

## Deployment

GitHub Pages publishes the root directory of the `main` branch. Push updates to `main` to redeploy. `.nojekyll` keeps this a plain static site; no npm installation or build step is needed.

The `og:image` metadata in `index.html` uses the GitHub Pages URL. Update it if the website moves to another domain.

## Content

- `figures/`: figures rendered from the OpenZilo paper.
- `paper/openzilo.pdf`: the validated November 3, 2026 v3 preprint.
- `paper/openzilo.bib`: preprint citation; no unconfirmed arXiv ID or DOI.
- `assets/template.css`: retained ICS template styles, with forced uppercase removed as requested.
- `assets/openzilo.css`: OpenZilo-specific layouts; shared heading, author, affiliation and button typography inherits the original template.

## Attribution

Adapted from the [Input-Conditioned Search project page](https://github.com/icsearch/icsearch.github.io). Template attribution is also retained in the page footer. The downloaded upstream repository did not include a separate license; this repository does not grant a new license for upstream material. OpenZilo research content, figures and branding retain their original authors' rights.
