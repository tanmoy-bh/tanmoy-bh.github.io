# tanmoy-bh.github.io

Redirects the GitHub Pages addresses of the tanmoy-bh repos to their Cloudflare homes:

- `/resume/*` to `https://tanmoybh.com/*`
- `/bobia/*` to `https://projects.tanmoybh.com/bobia/*` (only once GitHub Pages is turned off on the bobia repo, whose own site takes precedence)
- everything else to `https://tanmoybh.com/`

GitHub Pages serves `404.html` for any path without a file, and `redirect.js` maps the path.
