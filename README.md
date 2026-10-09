# Lincoln Elias — Portfolio

A responsive, bilingual portfolio built with semantic HTML, CSS, and vanilla JavaScript. Static and ready for GitHub Pages; no build step or npm dependencies.

## Preview locally

From this directory, run:

    python -m http.server 4173 --bind 127.0.0.1

Open http://127.0.0.1:4173/. Stop the server with Ctrl+C.

## Main files

- index.html: profile, career highlights, Claro tv+, Novibet, Oi Play, experience, expertise, education, and contact.
- portfolio-details-oi.html: Oi Play project and keyboard-accessible screenshot gallery.
- assets/css/main.css: visual design, responsive breakpoints, reduced-motion support, and print styles.
- assets/js/main.js: EN/PT translation, mobile navigation, email copying, and gallery controls.
- assets/docs/lincoln-elias-resume.pdf: the supplied English résumé.
- assets/docs/lincoln-elias-resume-pt-br.pdf: the supplied Portuguese résumé.
- assets/img/lincoln-elias.png: the supplied portrait.
- assets/img/portfolio/oi-*.png: original Oi Play screenshots.

Every résumé download control offers English (EN-US) and Portuguese (PT-BR), independently of the selected website language.

English is the default. The language selector remembers a visitor’s choice; ?lang=en or ?lang=pt can select a language directly.

Edit the English text in the two HTML files and the Portuguese text in the pt dictionary in main.js. Retain the data-i18n keys when changing copy.

## Publish on GitHub Pages

Commit and push the site files to the lincolnrelias.github.io repository and use the repository root as the Pages source. .nojekyll keeps this a plain static site; no build step is required.

Old about, résumé, portfolio, and contact URLs redirect to the corresponding homepage sections. The personal-project pages, old portraits, and Bootstrap template dependencies have been removed.

## Content and assets

Career dates, skills, education, and impact figures come from the supplied résumé. The 1M+ users and session-stability results belong to Global Hitss; the rating improvement belongs to Open Labs. They are not attributed to Oi Play. Oi Play details and screenshots come from the original portfolio.

The design combines a dark atmospheric hero, translucent panels, subtle lighting, a small profile portrait, and product-focused showcases. Claro tv+ and Novibet imagery was downloaded from the official Google Play listings; full source URLs and retrieval dates are recorded in assets/img/products/sources.json. CSS crops keep the downloaded originals intact. Public imagery may differ by version or region and does not document the exact features implemented by Lincoln. Claro tv+ is associated with the Global Hitss role based on the owner’s identification of the product. Fonts are self-hosted DM Sans and Instrument Serif from Google Fonts, with their SIL Open Font License files in assets/fonts. The original Google Analytics property is retained on the production domain only.

A copy of the original site was saved outside this folder under C:/Users/linco/.codex/backups/ before replacement.
