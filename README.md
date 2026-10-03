# Zhenyuan Dong's personal website

Visit **[Zhenyuan Dong — Purdue University](https://dzy122.github.io/)** for research interests, publications, academic service, teaching, and honors.

Static academic website for Zhenyuan Dong, adapted from [Jon Barron's website](https://github.com/jonbarron/jonbarron.github.io). The original README welcomes cloning the code for personal use. The original `stylesheet.css` is retained; responsive layout is in `site.css`.

## Content

The website contains News, Research Interests, Publications, Teaching & Service, and Honors. News lists paper acceptance announcements and academic milestones. Teaching & Service includes academic reviewing and courses taught at Purdue University and New York University. Each publication displays a key figure extracted directly from its original paper PDF, with a link to the full-size image.

## Edit

- Update text and links in `index.html`.
- The profile photo is the user-supplied `ZhenyuanDong.jpg`. Replace that file to update the portrait.
- Adjust layout in `site.css`; no build step or JavaScript is required.

## Preview

Run `python3 -m http.server 8000` in this directory and visit `http://localhost:8000`.

## GitHub Pages

In repository Settings → Pages, select **Deploy from a branch**, branch **main**, and folder **/(root)**. The website will be available at https://dzy122.github.io/ after deployment.

## Figure quality

Display figures are self-contained SVG files. AD-L-JEPA Figure 2 and the survey Figure 1 retain their original PDF vector paths. The model-embedding concept panels and DiTAS activation panels preserve the original embedded raster bytes and pixel dimensions. No screenshot or downsampling is used. See `images/figure-sources.json` for provenance.
