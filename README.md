# Idols of Ash GitHub Gateway

This repository is a search-friendly GitHub Pages landing page for **Idols of Ash**.

Its purpose is simple:
- give Google a real indexable page
- provide a clean and polished user experience
- send visitors to the live product at **https://idolsofash.live**

## Live destination

- Product URL: `https://idolsofash.live`
- Contact: `connect@idolsofash.live`

## Files in this repo

- `index.html` — the landing page
- `styles.css` — the visual design
- `hero-bg.png` — hero background image
- `robots.txt` — crawler directives
- `sitemap.xml` — sitemap for Google indexing

## Before you publish

Replace every `https://YOUR_GITHUB_PAGES_URL/` placeholder with your final GitHub Pages URL.

Example:

`https://cherryyan1987.github.io/idols-of-ash/`

You should update these places:
- canonical URL in `index.html`
- Open Graph URL in `index.html`
- Open Graph image in `index.html`
- structured data URL in `index.html`
- sitemap URL in `robots.txt`
- page URL in `sitemap.xml`

## GitHub Pages setup

1. Push these files to your repository.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. Save.
5. Wait for GitHub Pages to publish.

## Google indexing setup

1. Open Google Search Console.
2. Add your GitHub Pages URL as a property.
3. Submit `sitemap.xml`.
4. Use **URL Inspection** and request indexing for the homepage.

## SEO notes

This page is intentionally not a blank redirect.
It contains:
- unique title and description
- readable page content
- a large hero CTA
- structured data
- canonical tag
- robots and sitemap support

That gives it a better chance to be crawled and understood.
