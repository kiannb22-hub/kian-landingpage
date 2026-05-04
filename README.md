# kian-landingpage

Vite + React landing page for GitHub Pages.

## Local build

```bash
npm ci
npm run typecheck
npm run build
```

The production build is written to `dist/`.

## GitHub Pages

This repo includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`.

In GitHub, set **Settings > Pages > Build and deployment > Source** to **GitHub Actions**. Push to `main` to build and deploy the site.

The custom domain is configured with `public/CNAME` for `www.kbmediax.dk`.
