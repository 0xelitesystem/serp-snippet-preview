# SERP Snippet Preview

> See how your page looks in search before it ships, with truncation estimates.

**Live demo:** https://0xelitesystem.github.io/serp-snippet-preview/

Single HTML file. Runs in the browser with no build step, no server, no tracking, and no data leaving the page.

## What it does

- Renders a desktop and a mobile search result from your title, URL, site name, and description
- Estimates title pixel width with a canvas using Arial, close to how Google measures it
- Flags titles that run past the pixel limit and descriptions past the usual character range
- Truncates the preview the way a results page would, so you see the real cutoff

## What it is not

- Not a live SERP. Search engines often rewrite titles and descriptions on their own
- Not a ranking tool. It checks presentation, not position

## Use it

Open the hosted page: https://0xelitesystem.github.io/serp-snippet-preview/

Or download `index.html` and open it in any browser. It works offline.

## Privacy

Everything runs client-side. No analytics, no cookies, no network calls, no local storage.

## Related

- [titles-and-meta-descriptions-reference](https://github.com/0xelitesystem/titles-and-meta-descriptions-reference)
- [open-graph-preview-tester](https://github.com/0xelitesystem/open-graph-preview-tester)
- [heading-outline-checker](https://github.com/0xelitesystem/heading-outline-checker)

## License

MIT, copyright 0xelitesystem 2026.
