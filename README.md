# arcadiovega.com

Personal portfolio of Arcadio Vega: 15 years in professional kitchens, now a full stack developer building web and iOS apps.

Live at [arcadiovega.com](https://arcadiovega.com).

- Plain static HTML, CSS and JavaScript in one file (`index.html`). No build step. Images and short videos for the page live in `w/`.
- Hosted on Vercel. Every push to `main` deploys to production.
- Fonts (Geist, Geist Mono, Fraunces and an Inter Tight subset for the wordmark) are self-hosted in `w/fonts/`.
- Vercel Web Analytics and Speed Insights load from `/_vercel/insights/script.js` and `/_vercel/speed-insights/script.js`.
- The site is "Worlds". The page is a stack of full-screen sections that snap one at a time. The first is one sentence that names each project. Each project after it is its own colored world with a small animation of the app doing its job: Ace Cashout, Burp, La Cochina, The Miracle Ghost, the client sites, then a Messages-style "Say hi".
- Burp and La Cochina show working copies of their SwiftUI controls, each labeled with the real code it comes from.
- `short.html` is a plain one-page version for skimmers and text tools, linked from the intro as "Short on time?".
- On phones a Liquid Glass tab bar jumps between worlds. Scrolling forward hands an object from one world to the next (Cashout pill → jar lid → pig snout → ghost → browser window → chat avatar). In La Cochina the visitor can play one domino: only the 5|3 fits, at either end (capicúa).
- Ace Cashout, Burp and La Cochina each open a bottom sheet with build notes. The Say hi chat is an iMessage thread seen from the visitor's phone: Arcadio's messages are gray on the left, the visitor's are blue on the right. It takes "orders for the chef", which arrive only as Vercel Analytics `Order` events and are never shown publicly. The chat says so and points to email, because it can't reply. Other custom events: World, Read the story, Copy email, Email me, Open site preview, Show the code, Burp it, Mesa, Paint the wall, Flip the coin, Domino, Outbound link.
- The Burp shelf ages: each jar's day counts up from 24 Nov 2026 and restarts after its target.
- Copy rule: every claim on the page must come from a project README, a case study or Arcadio. Do not add invented numbers or anecdotes.
- Earlier sites stay online but are hidden from search (`noindex`): Look Closer at `/lens.html`, The Rail at `/rail.html`, the receipt at `/receipt.html` and the iPhone at `/iphone.html`.
- `robots.txt` and `sitemap.xml` list the homepage and `short.html`. The share image is `w/og.jpg`.
- Keyboard: arrows, Page Up/Down and Space move one world at a time. Space on a focused button presses the button instead.
- Ace Bartender and Cashout Calculator are web apps today. Do not label them iOS until the native versions ship.
- Project screenshots live in `shots/` as 600px-wide WebP files.
