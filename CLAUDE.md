# aleksiuno.github.io

Personal site and CV of Darius Aleksiūnas, served as plain GitHub Pages from the repo root.

## Layout

- `index.html` — the whole site; all page content lives here
- `assets/css/site.css` — the only stylesheet (custom properties, light/dark via `prefers-color-scheme`)
- `assets/fonts/` — Fraunces, self-hosted (OFL); `assets/img/` — favicon and touch icon only
- `cv-src/cv.html` — source of the CV PDF; see `cv-src/README.md` to regenerate
- `CVDariusAleksiunas.pdf` — the CV, generated from `cv-src/cv.html`

## Rules

- Static HTML + CSS only. No framework, no build step, no JavaScript, no analytics.
- Content changes go to both `index.html` and `cv-src/cv.html`, then regenerate the PDF.
- Positioning is "Backend Developer — PHP, Symfony, Ecommerce Platforms"; keep PrestaShop as evidence, not the headline.
- No phone number on the public site (it is in the PDF only). No photo until a current one exists.
- Don't invent facts; if something is missing, leave a visible `TODO:` and ask.
- Keep the page readable at 380px wide and Lighthouse 95+ on all four scores.
