# Kritrim.ai - Static Website Build

This repository contains the static build output of the Kritrim.ai website.

## Architecture

- **Source code:** [MrinalGitHub/kritrim-ai](https://github.com/MrinalGitHub/kritrim-ai)
- **Static assets (images, videos, PDFs):** Hosted on Supabase Storage
- **Database (leads, resources, LinkedIn articles):** Supabase PostgreSQL
- **Authentication:** Manus OAuth (users table in MySQL)

## Asset Hosting

All static assets are served from Supabase Storage:
- `https://pcqkgvxfivdmroyxczeh.supabase.co/storage/v1/object/public/kritrim-resources/`

No CloudFront or Manus CDN dependencies remain.

## Deployment

This build is generated from the `kritrim-ai` source repository using `pnpm build`.
The output is a single `index.html` + `assets/` directory suitable for GitHub Pages or any static hosting.

## Last Updated

April 28, 2026 — Full Supabase migration complete.
