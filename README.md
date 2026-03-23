# Kritrim-ai Website (Static Build)

Static build of the [Kritrim-ai](https://github.com/MrinalGitHub/Kritrim_Website) website, optimized for GitHub Pages hosting.

## Live Site

**[https://mrinalgithub.github.io/Kritrim_Website_Static/](https://mrinalgithub.github.io/Kritrim_Website_Static/)**

## About

Kritrim-ai is an AI solutions platform that helps MSMEs, Research Labs, and Startups with affordable AI Pilots and Proof-of-Concepts. This repository contains the pre-built static frontend optimized for GitHub Pages.

## Pages

| Page | Hash Route | Description |
|------|-----------|-------------|
| Home | `/#/` | Landing page with services, client ribbon, and CTAs |
| About | `/#/about` | Company story, team, and contact information |
| Resources | `/#/resources` | Whitepapers, case studies, guides, and blog posts |
| Resource Detail | `/#/resources/:slug` | Individual resource pages with full content |
| Login | `/#/login` | Admin login (requires backend) |

## Navigation

This static build uses **hash-based routing** (e.g., `/#/about` instead of `/about`) to ensure all routes work correctly on GitHub Pages without server-side URL rewriting.

## Features

- Responsive design optimized for mobile and desktop
- GDPR-compliant cookie consent banner
- Open Graph meta tags for social media previews
- JSON-LD structured data for SEO
- Scrolling client logo ribbon
- Sticky WhatsApp FAB and back-to-top button on mobile
- Hamburger menu for mobile navigation

## Limitations (Static Build)

Since this is a static frontend without a backend server, the following features are not available:

- **User authentication** (OAuth login/logout)
- **Database-driven content** (resources are rendered from bundled data)
- **Admin panel** (resource management requires backend)
- **Contact form submission** (requires server-side API)
- **File uploads** (requires S3 storage backend)

For the full-featured version with backend support, see the [main repository](https://github.com/MrinalGitHub/Kritrim_Website).

## Deployment

This repository is configured for GitHub Pages deployment:

1. Go to **Settings > Pages** in this repository
2. Set **Source** to "Deploy from a branch"
3. Select **Branch:** `main`, **Folder:** `/ (root)`
4. Click **Save**
5. Site will be live at `https://mrinalgithub.github.io/Kritrim_Website_Static/`

## Tech Stack

- **React 19** with TypeScript
- **Tailwind CSS 4** for styling
- **Wouter** for client-side routing (hash mode)
- **Lucide React** for icons
- **Vite** for build tooling

## Source Code

The full source code with backend, database, and all features is available at:
[github.com/MrinalGitHub/Kritrim_Website](https://github.com/MrinalGitHub/Kritrim_Website)

## License

Copyright 2026 Kritrim-ai. All rights reserved.
