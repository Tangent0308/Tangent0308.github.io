# Yue Tan Homepage

This repository hosts Yue Tan's personal website built with the Hugo Blox Academic CV template family.

## Local development

The site uses Hugo Extended together with Node.js and pnpm.

```bash
pnpm install
hugo server --disableFastRender
```

## Production build

```bash
pnpm install
hugo --minify
pnpm run pagefind
```

## Main content locations

- `content/_index.md` — homepage section layout
- `data/authors/me.yaml` — profile data
- `content/publications/` — publication pages
- `assets/media/authors/me.jpg` — profile photo
- `config/_default/` — site configuration

## Deployment

GitHub Pages deployment is configured through `.github/workflows/build.yml` and `.github/workflows/deploy.yml` on the `master` branch.
