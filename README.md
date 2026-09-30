# Zhenyuan Dong's personal website

Static academic website for Zhenyuan Dong, adapted from [Jon Barron's website](https://github.com/jonbarron/jonbarron.github.io). The original README welcomes cloning the code for personal use. The original `stylesheet.css` is retained; responsive layout is in `site.css`.

## Content

The website contains exactly four sections, in order: News, Research Interests, Publications, and Teaching & Service. News uses dated milestones from the provided CV; Teaching & Service contains the supplied conference reviewer information. No teaching roles were supplied, so none are invented. Education, Research Experience, Honors & Awards, and Technical Skills do not appear as separate sections. The downloadable CV is the original complete PDF supplied by Zhenyuan Dong. Publication statuses and dates follow that CV. The memory-retrieval manuscript is omitted at the user’s request. Each of the four remaining publications displays its key figure extracted directly from the original paper PDF, with a link to the full-size image. The model embedding paper links to the supplied NeurIPS PDF.

## Edit

- Update text and links in `index.html`.
- Replace `ZhenyuanDong-CV.pdf` when updating the CV.
- The profile photo is the user-supplied `ZhenyuanDong.png`. Replace that file to update the portrait.
- Adjust layout in `site.css`; no build step or JavaScript is required.

## Preview

Run `python3 -m http.server 8000` in this directory and visit `http://localhost:8000`.

## GitHub Pages

In repository Settings → Pages, select **Deploy from a branch**, branch **main**, and folder **/(root)**. The website will be available at https://dzy122.github.io/ after deployment.

## Figure quality

Display figures are self-contained SVG files. AD-L-JEPA Figure 2 and the survey Figure 1 retain their original PDF vector paths. The model-embedding concept panels and DiTAS activation panels preserve the original embedded raster bytes and pixel dimensions. No screenshot or downsampling is used. See `images/figure-sources.json` for provenance.
