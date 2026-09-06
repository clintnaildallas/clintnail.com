# clintnail.com

This repository powers the public website for Clint Nail at clintnail.com, also known as Clinton Nail. 

The site is a lightweight static personal and professional website focused on identity, technology, cloud architecture, and life in Dallas. It is designed to be a trustworthy digital home for Clint Nail without leaning into résumé-style content, generic portfolio patterns, or marketing-heavy branding.

## Purpose

- Present a clear public identity for Clint Nail
- Support search visibility and entity recognition
- Share professional themes and personal context in balance
- Keep privacy boundaries appropriate for a public-facing personal site

## Hosting and deployment

This project is hosted through Cloudflare Workers Static Assets and is source-controlled in GitHub. Deployment is handled through the connected Cloudflare/GitHub workflow rather than a custom app deployment process.

Production deployment configuration is contained in the project root file named wrangler.jsonc.

## Local development

Because this is a static site, no build step is required. You can view it locally with any simple static file server, such as:

- Python: `python -m http.server`
- VS Code Live Server

Open the local site in a browser to review the homepage, 404 page, SEO metadata, and styling.

## Repository structure

- `public/` contains the static website files, including the homepage, 404 page, robots.txt, sitemap.xml, CSS, JavaScript, and placeholder asset directory.
- `wrangler.jsonc` contains the Cloudflare Worker configuration for static assets.
- `.gitignore` excludes local build and editor artifacts while leaving the site files in place.

## Notes

This is intentionally a minimal static implementation without frameworks, JavaScript libraries, analytics, CMS, or database dependencies. Any future content updates should be added carefully and only with verified public information.
