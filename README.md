# CineWorld

A responsive, English-language movie discovery starter site.

## Run locally
Open `index.html` in a modern browser. No build step or paid service is required.

## Publish free
1. Connect this public GitHub repository to Cloudflare Pages.
2. Choose **Create a project** → **Connect to Git**.
3. Select `cineworld`. For this static site, choose no build command and set the output directory to `/`.
4. Deploy. Cloudflare will provide a public `pages.dev` address.

## Notes
- This is a front-end demo with a small sample movie catalog. It does not host movies or unauthorized streams.
- “Find legal ways to watch” opens JustWatch search results; availability varies by country and changes over time.
- Trailer buttons open YouTube search results for the official trailer, rather than embedding unverified uploads.
- Movie poster images are loaded from TMDB image CDN. The site is not affiliated with TMDB. For a production catalog, integrate TMDB API under its terms and attribution requirements.
- Google Fonts and poster images need an internet connection. The layout and sample content remain usable without an API key.
