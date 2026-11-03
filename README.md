# Aleks Stepančič

Personal website, published with GitHub Pages.

Website: https://aleks-stepancic.github.io/

- `index.html`: prose homepage.
- `cv/`: separate CV-style layout.
- `courses/`: all 47 courses.
- `taste/`: alternative prose typography and matching course page.

The website is static HTML and CSS. No server or installation is required. GitHub Pages publishes the root of the `main` branch. All links and assets use relative paths.

To update from the original local workspace, rebuild the portfolio and run:

```sh
node aleks-personal/scripts/build-github-pages.mjs
```

Publish changes only when explicitly requested. The export includes only the public site pages and the assets they use. The Newsreader license is in `assets/fonts/Newsreader-OFL.txt`.
