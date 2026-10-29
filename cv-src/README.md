# CV source

`cv.html` is the source of the CV PDF in the repo root. It uses the site's Fraunces font files
(`../assets/fonts/`). Regenerate after editing:

    npx playwright pdf --format A4 --prefer-css-page-size cv-src/cv.html CVDariusAleksiunas.pdf
