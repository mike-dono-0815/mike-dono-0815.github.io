# mike-dono-0815.github.io

Root GitHub Pages site for Michael Donoser. A short landing page that links to the main homepage at `/homepage/`.

Do not turn this into a redirect. Google takes the site name shown in search results (e.g. "Michael Donoser") only from this root URL, through the `WebSite` JSON-LD in `index.html`. If the root redirects or canonicalizes to `/homepage/`, Google can't read a site name and falls back to the parent `github.io` domain ("GitHub Pages documentation").
