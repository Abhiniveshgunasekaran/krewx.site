# krewx.site

**Public** repo (GitHub Pages) serving https://krewx.app. Everything here is world-readable:
no account IDs, keys, internal notes or plans. Shared workspace memory is in `../CLAUDE.md`
(the workspace repo, private).

- Made 2026-11-24 (user) so krewx.app no longer depends on an AWS account (API Gateway custom
  domains). Pages copied from krewx.ui.web (`index.html`, `get.html`, `invite.html`,
  `krewx-share.png`); **edit them here**, krewx.ui.web keeps only the AWS hosting.
- `404.html` = invite page for `/invite/<token>`, "page not found" for anything else.
- `CNAME` = `krewx.app`; `.nojekyll` so files are served as they are.
