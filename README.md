# Hasan A. Azim — Portfolio

Personal portfolio: sourcing &amp; supply chain, ERP automation, IE tools and dashboards.
Built with AI assistance.

Live at <https://hasan-azim-portfolio.pages.dev/>

## What is in here

| File | What it is |
|---|---|
| `index.html` | the portfolio itself — everything else is linked from it |
| `pr-bot.html` | case study: the Oracle PR Booking Bot, written for an outside reader |
| `favicon.svg` | the browser-tab icon (HA monogram) |
| `og-preview.png` | 1200×630 social card — what LinkedIn/WhatsApp show when the link is shared |
| `img/` | screenshots used by `index.html` and `pr-bot.html` |
| `st-layout.html` · `st-layout-sample.html` | sewing line layout period visual, and a sample output |
| `capacity-card.html` · `capacity-card-sample.html` | capacity sticker generator, and a sample output |
| `cutting-dashboard.html` | cutting section daily efficiency dashboard (dummy data) |
| `overall-dashboard.html` | group-level OWE / OEE / production dashboard (dummy data) |
| `problem-dashboard.html` | problem-solving and follow-up dashboard (dummy data) |
| `cpm-dashboard.html` | CPM / production dashboard |
| `dpr-sample.html` · `indus-sample.html` | demo previews of the two on-floor Android tools |
| `azim-photo.jpg` | the portrait on the hero card |
| `Hasan_A_Azim_CV_2026.pdf` | the CV the "Download CV" button serves |

## Rules worth keeping

**Paths are relative and flat**, apart from `img/`. There is no `assets/` folder —
a link written as `assets/something` will 404 on the live site. That exact
mistake made "Download CV" dead for a while.

**The CV must agree with the page.** The site says the current role is
Merchandiser — Sourcing at DBL Group; the PDF must say the same. An out-of-date
CV behind a live page is worse than no CV.

**`pr-bot.html` is the public version of the project story.** It deliberately
contains no colleague names, nothing about internal role or recognition, and no
comment on any employer's existing systems. Keep it that way — the internal
presentation is a separate file and is not published here.

**Screens shown use demonstration data.** No real supplier, price, buyer or
tracking number appears in any image.

## Publishing

Push this folder to GitHub; Cloudflare Pages serves it. Nothing is built,
compiled or bundled — the HTML is the deployable.
