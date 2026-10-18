# stuard-site

The public pages for Stuard, a personal life management app for Apple devices:

- `index.html` — about Stuard
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service

Plain HTML and one stylesheet; no build step. Every push to `main` publishes to GitHub Pages
through `.github/workflows/pages.yml`. To change a page, edit its HTML, update the "Effective"
date when the policy or terms change, and push.
