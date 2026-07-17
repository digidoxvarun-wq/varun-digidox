# varun-digidox

Portfolio site for Varun Kumar — Google Ads, Meta Ads, and Shopify growth.

**Live:** https://digidoxvarun-wq.github.io/varun-digidox/

> Paid traffic and Shopify stores built to convert, not just launch.

Performance marketing across Google and Meta, plus Shopify development and CRO,
run by one person end to end.

---

## Sections

| Section | Content |
|---|---|
| `#top` | Hero, positioning |
| `#services` | Google Ads · Meta Ads · Shopify Development · Shopify Growth & CRO |
| `#bundles` | Ads management and combined growth packages |
| `#case-studies` | Home services (North India), D2C beauty, fashion D2C |
| `#process` | Audit → Strategy → Build & Launch → Optimize & Scale |
| `#tools` | Day-to-day stack |
| `#contact` | Enquiry links |

## Tech

Single-file static site. Vanilla HTML, CSS, and JavaScript — no framework, no
build step, no dependencies.

```
index.html    entire site (~1,000 lines, all markup/styles/scripts inline)
README.md     this file
```

Assets are embedded directly in the HTML: the hero photo ships as a base64 PNG,
so the page is self-contained apart from Google Fonts.

## Local preview

Open `index.html` in any browser. There is nothing to install or compile.

## Deploy

GitHub Pages serves `main` from the repository root. Pushing to `main` publishes
automatically; no workflow or build step is involved.
