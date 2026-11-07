# Steph-Yves Louis — research & applied AI portfolio

A standalone, responsive GitHub Pages site. No npm, build step, external fonts, tracking, or JavaScript dependencies. All content is readable with JavaScript disabled; JavaScript adds publication filtering and the interactive concept graph.

## Try locally

Unzip, open the superlouis-portfolio directory, and double-click index.html.

Or run:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000. Stop with Ctrl+C.

## Publish to superlouis.github.io

1. Back up your existing repository or create a branch first.
2. Copy index.html, styles.css, script.js, favicon.svg, and .nojekyll to the root of your superlouis.github.io checkout. Do not nest them inside another portfolio directory.
3. The old site appears to use Jekyll. This version replaces the homepage with plain static HTML; .nojekyll bypasses Jekyll. Existing old subpages can remain, but their styling is not updated by this package.
4. Commit and push when ready. In repository Settings → Pages, use Deploy from a branch, choose your publishing branch and /(root). If an existing custom Actions workflow builds the old Jekyll site, switch Pages to branch publishing or update that workflow before deployment.

No domain, repository, or live site has been changed by preparing this package.

## Edit content

- index.html: biography, education, experience, papers, project descriptions and links.
- styles.css: palette, typography, responsive layout.
- script.js: concept graph and publication filters.
- favicon.svg: initials mark.

## Editorial choices to review

- SHI is shown as current, as requested; prior employment dates and exact titles are omitted rather than guessed.
- Finance wording is deliberately broad: “cash allocation and financial planning.” Confirm what LTM stands for before adding it.
- Independent projects are described as ongoing work; there are no invented launches, adoption metrics, project URLs, or clinical performance claims.
- LinkedIn, GitHub and ResearchGate provide contact paths. Add your preferred public email if desired; the old university email was not reused.
- Six selected first/second-author works are included. Phonon frequencies now links to its published ACS Omega article (2022). Authorship position does not imply identical contribution across papers.
- Diagrams are original conceptual illustrations, not experimental results or exact model architectures.

## Publication sources

GATGNN: https://doi.org/10.1039/D0CP01474E
NODE-SELECT: https://doi.org/10.1016/j.neucom.2022.04.058
DeeperGATGNN: https://doi.org/10.1016/j.patter.2022.100491
Battery voltage: https://doi.org/10.1021/acsami.2c00029
Remaining useful strength: https://doi.org/10.3390/app10082680
Phonon frequencies: https://doi.org/10.1021/acsomega.2c02765

Career and independent-project descriptions are based on your supplied brief. No confidential examples or financial metrics are included.

## Personal edition

Portrait: bundled locally from https://superlouis.github.io/steph-pic.png (your existing website). Replace assets/steph-louis.png to use a newer photo.
ORCID: https://orcid.org/0000-0003-1954-5791 — linked to Steph-Yves Louis in the ACS Omega publication metadata.
Google Scholar: https://scholar.google.com/citations?user=TXFW-uUAAAAJ — from your existing site.
Personal interests draw on your original bio (running, exercise, video games, PyTorch and Linux).
Remember to copy the assets directory when publishing.

## Corrections and red edition
- DeeperGATGNN is labeled co-first author, per your correction, and included in the first/co-first filter.
- Display title: Deep GNN to predict lattice vibrational frequencies. The linked article retains its formal published title.
- Low-resource settings are described without a geographic restriction.
- Added a connected S–L SVG monogram in the header/footer and favicon.
- Honorable contributions: dFL journal paper (2026), plus DeFT/Ousai APS conference abstract (2021). These are separate from lead-author papers and clearly labeled by publication type.
- Sources: https://doi.org/10.1016/j.fusengdes.2026.115872 and https://meetings-archive.aps.org/dpp/2021/tm10/
