# arcadiovega.com

Personal portfolio of Arcadio "Archie" Vega: 15 years in professional kitchens, now building iOS apps.

Live at [arcadiovega.com](https://arcadiovega.com).

- Plain static HTML, CSS and JavaScript in one file (`index.html`). No build step.
- Hosted on Vercel. Every push to `main` deploys to production.
- Vercel Web Analytics and Speed Insights load from `/_vercel/insights/script.js` and `/_vercel/speed-insights/script.js`.
- The site is a restaurant receipt. A receipt printer prints the portfolio on load, and a Reprint button prints it again. Each line item is a native `<details>` element, so it opens without JavaScript.
- Sections: From the Kitchen, Apps, Specials (work in progress) and Sides (tech stack).
- Cashout Calculator is the featured project: it is always open, with screenshots and links. The other rows open with a `[+]` box and use native `<details>` (keyboard and screen reader support come from the browser; the script mirrors `aria-expanded`).
- Each project has a stable `id`, so a link like `/#wherewolf` opens that row. Keep receipt copy to a line or two. When a case study exists, give it its own page and add a "Case study" `.btn` to the project's `.lk` row.
- The tip picker (native radio buttons) sets the subject of every "Email Archie" `mailto:` link and the coupon text. It never opens the mail app by itself. The tear-off coupon copies the email and reports success or failure in a `role="status"` line.
- With `prefers-reduced-motion: reduce`, the printing, tearing and stamp animations are skipped and everything stays usable.
- The previous interactive iPhone site lives at `/iphone.html`, linked from the bottom of the receipt.
- Ace Bartender and Cashout Calculator are web apps today. Do not label them iOS until the native versions ship.
- Project screenshots live in `shots/` as 600px-wide WebP files and appear inside each app's line item. WhereWolf replaced GeoWho in October 2026; its repo is private, so its page shows no code link.
