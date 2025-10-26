# Rheon.ai – Coming Soon Landing Page

Public landing page for Rheon.ai with event details and contact information.

## Preview locally

Open `index.html` directly in a browser, or serve the folder:

```bash
cd /Users/michaelkezhang/code/landing_page
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy to GitHub Pages

1) Push this folder to a GitHub repo (e.g., `rheonai/landing_page`). Ensure the default branch is `main`.
2) The provided workflow at `.github/workflows/deploy.yml` will publish on every push to `main`.
3) In GitHub: Settings → Pages → Build and deployment → Source: GitHub Actions.
4) Your site will be available at `https://<org-or-user>.github.io/<repo>/`.

Notes:
- We include a `.nojekyll` file to serve assets as-is.
- Paths in `index.html` are relative (e.g., `styles.css`, `favicon.svg`) for correctness on Pages.

## Edit content
- Main page: `index.html`
- Styles: `styles.css`
- Favicon: `favicon.svg`

## Contact
Michael Ke Zhang — mk.zhang@rheon.ai
