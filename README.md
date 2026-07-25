# liuhao04.github.io

Static site for small free tools. No build step, no Jekyll (`.nojekyll` is present), no
dependencies — plain HTML/CSS/JS, one directory per page.

- `index.html` — hub listing the in-browser tools and the open-source Chrome extensions
- `table-to-csv/` — paste an HTML table, get CSV / TSV / Markdown, rowspan/colspan expanded
- `nonogram-no-guess-check/` — article: why a unique-solution nonogram can still force a guess,
  and the line-solvable check that catches it
- `robots.txt`, `sitemap.xml` — crawlable by default; add every new page to the sitemap

## Rules for pages added here

1. **Self-contained.** No CDN, no external font, no analytics. A page must work offline once loaded.
2. **Real utility before any link out.** The tool works fully on the page; links to extensions or
   books sit at the bottom, never behind a gate.
3. **Every new page gets** a `<title>`, a `meta description`, a `link rel=canonical`, and a
   `sitemap.xml` entry — otherwise it is not discoverable and does not belong here.
