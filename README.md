# arcadiovega.com

Personal portfolio of Arcadio "Archie" Vega: 15 years in professional kitchens, now building iOS apps.

Live at [arcadiovega.com](https://arcadiovega.com).

- Plain static HTML, CSS and JavaScript in one file (`index.html`). No build step.
- Hosted on Vercel. Every push to `main` deploys to production.
- Vercel Web Analytics and Speed Insights load from `/_vercel/insights/script.js` and `/_vercel/speed-insights/script.js`.
- The site is a restaurant receipt. A receipt printer prints the portfolio on load, and a Reprint button prints it again. Each line item is a native `<details>` element, so it opens without JavaScript.
- Sections: From the Kitchen, Apps, Specials (work in progress) and Sides (tech stack). A tip picker sets the coupon text, and the tear-off coupon copies the contact email.
- The previous interactive iPhone site lives at `/iphone.html`, linked from the bottom of the receipt.
- Ace Bartender and Cashout Calculator are web apps today. Do not label them iOS until the native versions ship.
- Project screenshots live in `shots/` as 600px-wide WebP files and appear inside each app's line item. WhereWolf replaced GeoWho in October 2026; its repo is private, so its page shows no code link.
