# kuz-website

Simple "coming soon" placeholder page for GitHub Pages, with a link to a resume PDF. Set as the redirect target for the old site.

## Structure

- `index.html` — the coming soon page (font: Source Code Pro)
- `assets/resume.pdf` — resume, linked from the page

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. In the repo settings, go to **Pages** and set the source to the `main` branch, root folder.
3. GitHub will publish at `https://<username>.github.io/<repo>/` (or a custom domain if configured below).

## Custom domain

This repo is configured for `kuzn.me` via the `CNAME` file. Point the domain's DNS at GitHub Pages per [GitHub's docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) — typically an `A`/`ALIAS` record at the apex (or a `CNAME` record if using a `www` subdomain) pointing to GitHub Pages' servers.
