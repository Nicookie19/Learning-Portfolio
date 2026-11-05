# Nico Mahipus — Learning Portfolio

A buildless learning portfolio adapted from https://github.com/Nicookie19/Nicookies-Portfolio. The original dark/green design system is retained in `dist/base.css`; portfolio additions are in `dist/styles.css`.

## Run locally

From this directory, run `python3 -m http.server 8080 --directory dist` and visit http://localhost:8080.

## Content

- Nine original activities from the supplied folder, with visual summaries and original artifact links.
- Five clearly labeled reconstructed drafts based on instruction screenshots. Drafts are also in `content/*-draft.md` and can be downloaded from each showcase.
- TLA #1: Translating Learning Principles into Educational Technology Solutions includes the [original Figma prototype](https://font-curry-74082259.figma.site) and `Mahipus_Learning Principles.pdf`.
- The arrays lab is a new implementation inspired by the supplied theoretical alignment document, not a recovered Figma file.
- The strategy analysis provisionally uses Computer Components; the assigned group and exact three-filter rubric were not visible.
- Source inconsistencies are noted inside the applicable showcases. Original artifacts remain unchanged.

Edit `content/build_content.py`, then run `python3 content/build_content.py` to regenerate `dist/data.js` and draft Markdown. No dependencies or build command are required to serve the site.

`dist/assets` contains the original supplied files, PDF page previews, and a cropped classroom diagram for the showcase. The crop is derived from the supplied PDF. All 15 supplied files are retained.
