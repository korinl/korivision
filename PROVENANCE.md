# Provenance: Hadamard research note

Creation date: 2026-09-20.

Scope: `research/hadamard-autonomous-vision.html`, `research/research.css`, its original inline SVG, and the single homepage Research Notes link update. This statement covers this addition, not a retrospective audit of all repository history.

## Origin and personal history

The article and diagram were newly prepared from Korin Lifshits's explicitly supplied personal account and the public references below. Personal statements about graduate research and Mobileye implementation/experimentation are supplied recollections, not claims independently verified by the paper. Korin Lifshits is not listed as an author of the related CVPR publication and the article makes that distinction explicit.

No former-employer code, data, confidential material, private communications, proprietary implementation details, architecture, configurations, screenshots, or metrics were used. No former-employer private repository or archive was inspected for this work. Mention of historical work on code is a personal recollection only; no such code was accessed or reproduced.

## Public references used

Verified 2026-09-20:

- Yaniv Alon, Andras Ferencz, Amnon Shashua, “Off-road Path Following using Region Classification and Geometric Projection Constraints,” CVPR 2006, vol. 1, pp. 689–696. [Author-hosted PDF](https://www.cs.huji.ac.il/~shashua/papers/cvpr06-final.pdf). Title/authors and DARPA/Walsh–Hadamard context verified from the paper. No figures, code, datasets, or quantitative results reproduced.
- [Prof. Shashua's public university publication list](https://pages.cs.huji.ac.il/shashua/pages/publications.html): confirms title, authors, venue, and year.
- [IEEE-deposited Crossref metadata](https://api.crossref.org/works/10.1109/CVPR.2006.213): confirms publisher, title, author initials, conference, volume, pages, and DOI. IEEE Xplore presented an automated-access challenge; the university source and deposited metadata were used for verification.
- [Indian Statistical Institute, Discrete Mathematics §9.7](https://www.isibang.ac.in/~d.yogesh/Course_Notes/DM1/Ch9.S7.html): definition, orthogonality, normalized balance, and incidence construction. The article explicitly distinguishes order n from order 4t in the construction.
- [Padraig Ó Catháin, Difference sets and Hadamard matrices](https://maths.nuigalway.ie/~padraig/Docs/PadraigOCathainMaynooth.pdf), 2012, slides 5–9: design parameters and the Hadamard/design relationship.
- [Ruye Wang, The Walsh-Hadamard Transform (Hadamard Ordered)](https://pages.hmc.edu/ruye/e161/lectures/wht/node2.html), Harvey Mudd College, 2013: projections, recursive decomposition, and fast-transform complexity.
- [Ruye Wang, Sequency Ordered Walsh-Hadamard Matrix](https://pages.hmc.edu/ruye/e161/lectures/wht/node3.html): basis ordering by sign changes.

The conceptual bridge and proposed modern research question are retrospective interpretation and hypotheses, not asserted historical derivation or demonstrated new results.

## Open-source dependencies

No new runtime dependencies. The note uses the existing public KoriVision stylesheet plus newly written static HTML, CSS, and SVG. It reuses the site's existing native mobile-menu behavior with links directed to the homepage sections. No framework, font download, remote image, analytics, or build system was added.

Local review only: Python standard library and Playwright for browser validation, Pillow for screenshot comparison, and installed Google Chrome. These are not shipped to the website.

## Datasets used

None. No images, videos, experimental data, benchmarks, models, or historical project files were downloaded or incorporated into the note. Public publications were read only as references.
