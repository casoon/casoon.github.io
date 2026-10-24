# casoon.github.io

Root of the GitHub Pages domain `casoon.github.io`. The project documentation sites live in their own repositories and are served below it (`https://casoon.github.io/<repo>/`); this repository only serves the root:

- `index.html` – a short overview of the project sites, linking to the catalog on [casoon.dev](https://casoon.dev/).
- `robots.txt` – the only robots.txt crawlers read for this domain. It allows everything and lists the `sitemap.xml` of every project site.
- `google8cf500a7d967f95c.html` – Google Search Console verification for the URL-prefix property `https://casoon.github.io/`, which covers all project sites.

Do not set a custom domain for this repository: GitHub would then redirect every project site to that domain as well.

When a project site is added or gets a sitemap, add its `Sitemap:` line to `robots.txt` and its entry to `index.html`.
