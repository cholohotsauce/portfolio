# arcadiovega.com

Personal portfolio of Arcadio "Archie" Vega: 15 years in professional kitchens, now building iOS apps.

Live at [arcadiovega.com](https://arcadiovega.com).

- Plain static HTML, CSS and JavaScript in one file (`index.html`). No build step.
- Hosted on Vercel. Every push to `main` deploys to production.
- Vercel Web Analytics and Speed Insights load from `/_vercel/insights/script.js` and `/_vercel/speed-insights/script.js`.
- The site is an interactive iPhone: lock screen, home screen, and one "app" per section. On screens 560px wide or less, the iOS UI fills the screen instead of showing the device frame.
- Project pages, Notes, Recipe, Contacts, Mail and Settings render from the `projects` and `views` objects in the script at the bottom of `index.html`.
- The Chef Mode switch in Settings rewrites the copy. Each element keeps its two versions in `data-dev` and `data-chef` attributes.
- Ace Bartender and Cashout Calculator are web apps today. Do not label them iOS until the native versions ship.
- Project screenshots live in `shots/` as 600px-wide WebP files and are listed in each project's `shots` array. WhereWolf replaced GeoWho in October 2026; its repo is private, so its page shows no code link.
