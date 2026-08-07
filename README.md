# Aryze iGaming Brochure

Customer-facing interactive flipbook for the Aryze iGaming concept — 16 pages, single self-contained HTML file (fonts, images and logos embedded). `aryze-igaming-brochure.pdf` is the flat export used as the outreach attachment.

## Deploy on Vercel

Push this folder to a GitHub repository, then import the repository at vercel.com/new. No framework, no build step — Vercel serves `index.html` as a static site. `vercel.json` enables clean URLs and sets `X-Robots-Tag: noindex` so the link stays out of search engines while the material is in the friends-and-family round.

## Updating

The brochure is generated from the build scripts in the internal working folder, not edited by hand. Replace `index.html` and the PDF with the latest builds and push.
