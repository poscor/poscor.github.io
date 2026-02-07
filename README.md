# poscor.github.io

Astro static site deployed to GitHub Pages.

## Local development

```sh
npm install
npm run dev
```

Build and preview locally:

```sh
npm run build
npm run preview
```

## GitHub Pages deployment

Deployment is handled by GitHub Actions on every push to `main`:

- Installs dependencies with npm
- Builds the static site to `dist/`
- Uploads the build as a Pages artifact
- Deploys via GitHub Pages Actions

## Live site

The site is available at https://poscor.github.io/
