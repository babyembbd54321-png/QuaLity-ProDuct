# Quality Product — GitHub Pages Website

Responsive single-page embroidery atelier website using plain HTML, CSS and JavaScript. No build step or package installation is needed.

## Deploy on GitHub Pages

1. Create a GitHub repository (for example, `quality-product-site`).
2. Upload all files and folders from this project. Keep `index.html` at the repository root.
3. Open **Settings → Pages** and set the source to **GitHub Actions**.
4. Push the files to the `main` branch. The included workflow deploys the site automatically.
5. When deployment finishes, copy the published URL from **Settings → Pages**.

## Before publishing

- Replace sample business details, email addresses, prices, statistics, testimonials and workshop address with accurate information.
- The contact form opens the visitor's email app with a prepared message addressed to `hello@qualityproduct.co`. Change that address in `index.html` to your real enquiry email. It does not send mail directly or store submissions on a server.
- Optional photo filenames and instructions are in `images/README.md`. Without photos, built-in vector illustrations remain visible.
- Google Fonts and the optional Lenis smooth-scroll library load from third-party CDNs.

## Files

- `index.html` — website
- `.github/workflows/deploy.yml` — automatic GitHub Pages deployment
- `.nojekyll` — disables Jekyll processing
- `404.html` — simple not-found page
- `favicon.svg` — browser tab icon
- `images/README.md` — optional photo instructions
