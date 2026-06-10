# cognoss

Static landing lives in `landing/`.

Deployment is handled by GitHub Actions:

- workflow: `.github/workflows/deploy-pages.yml`
- artifact path: `landing/`
- target: GitHub Pages

In repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**.
