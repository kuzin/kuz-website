# kuz-website

Simple "coming soon" placeholder page for GitHub Pages, with a link to a resume PDF. Set as the redirect target for the old site.

## Structure

- `index.html` — the coming soon page (font: Source Code Pro)
- `assets/resume.pdf` — resume, linked from the page

## Deploying to GitHub Pages

1. Push this repo to GitHub.
2. In the repo settings, go to **Pages** and set the source to the `main` branch, root folder.
3. GitHub will publish at `https://<username>.github.io/<repo>/` (or a custom domain if configured below).

## Custom domain (optional)

If the old domain should point here, add a `CNAME` file to the repo root containing just the domain name (e.g. `example.com`), then point the domain's DNS at GitHub Pages per [GitHub's docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
