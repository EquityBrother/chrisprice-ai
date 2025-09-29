# chrisprice.ai

Quick reference for updating the website.

## Creating/Updating Pages

1. Edit files in `src/pages/`
2. Add new `.astro` files for new pages (e.g., `src/pages/about.astro` → chrisprice.ai/about)

## Updating Content

- Books, portfolio items, etc. are in their respective `.astro` files in `src/pages/`
- Static assets (images, PDFs) go in `public/`

## Deploying to Vercel

```bash
git add .
git commit -m "Update content"
git push origin main
```

Vercel automatically deploys when you push to the main branch.

## Local Development

```bash
npm run dev    # Start dev server at localhost:4321
npm run build  # Build for production
```