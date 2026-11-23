# Maria Krusanova — Personal Website

A responsive, accessible personal academic portfolio built with HTML, CSS, and
minimal JavaScript. It is designed for GitHub Pages and does not require a build
step or third-party dependencies.

## Preview locally

From the repository root, start a local HTTP server:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Edit the website

- `index.html` contains the page structure and placeholder content.
- `styles.css` controls layout, typography, and light/dark themes.
- `script.js` controls the theme button, mobile navigation, and copyright year.
- `cv.html` is a print-friendly, downloadable CV template.

Replace placeholder text, project links, email, LinkedIn URL, experience,
education, publications, and CV details with verified information. Do not add
private information such as a home address, date of birth, or phone number.

The downloadable CV can be customized in `cv.html`, printed to PDF from a
browser, or replaced by a real PDF. If you add a PDF, update the `href` values
from `cv.html` to `assets/your-cv.pdf` in `index.html`.

## Publish with GitHub Pages

1. Commit and push the repository to GitHub.
2. Open **Settings → Pages** in the GitHub repository.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the default branch and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. The URL will be shown in the Pages
   settings.
