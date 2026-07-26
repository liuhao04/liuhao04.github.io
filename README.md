# liuhao04.github.io — redirect shell only

The content moved to **https://minty-modesty.github.io/** (a neutral GitHub organisation).
Nothing new is published here.

This repository is kept alive on purpose: the old URLs were submitted to IndexNow and Google
Search Console, and six of them were also filed as privacy-policy URLs in the Chrome Web Store.
Deleting them would turn live references into dead links. So every path here is a stub that
carries `rel=canonical` plus a `meta refresh` to its new address:

- `/` , `/table-to-csv/` , `/nonogram-no-guess-check/` — the three pages that used to live here
- `/<extension>/index.html` and `/<extension>/privacy.html` for the six extensions whose
  repositories (and therefore their project Pages sites) moved to the organisation

Also kept: `googlec66ab11295e96deb.html` and the `google-site-verification` meta tag on `/`
(so the old Search Console property stays verified while Google processes the move) and
`912cd37ca8ec6aec4299a06773f57a0e.txt` (IndexNow key), and `sitemap.xml` still lists the old
URLs on purpose — that is what makes crawlers revisit them and pick up the redirects.
