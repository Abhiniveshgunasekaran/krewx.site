# krewx.app

The public KrewX website, served by GitHub Pages at https://krewx.app.

| Address | File |
|---|---|
| `/` | `index.html` |
| `/get` | `get.html` (app download link) |
| `/invite/<token>` | `404.html` (club invite; GitHub Pages can't rewrite paths, so the not-found page shows it) |
| anything else | `404.html` (page not found) |

Plain HTML, no build step. A push to the default branch publishes it.
