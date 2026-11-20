# harang-dev.github.io host configuration

Publishes files that must be served at the root of `https://harang-dev.github.io/`.

- `robots.txt`: host-wide crawl policy and Poke-Dict sitemap location.
- `ads.txt`: authorizes the existing AdSense publisher for this host. It does not activate advertising or replace site registration and review.
- `index.html`: a non-indexable entry point linking to Poke-Dict; the app is deployed separately.

GitHub Pages serves the `main` branch root. `.nojekyll` keeps the files as static assets.

Poke-Dict source: https://github.com/Harang-Dev/Poke-Dict.io

When adding other project sites, preserve their host-wide crawl requirements and merge additional sitemap declarations or authorized ad sellers rather than replacing this host policy.
