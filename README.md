# sandeepsulhan.com — Site Build

## What's here
- `index.html` — homepage (blue/black theme, real section structure, placeholder content)
- `public/images/` — drop real photos/covers here, matching the filenames referenced in index.html
- `vercel.json` — basic Vercel config (clean URLs)

## Placeholders to replace before launch
1. `/images/hero-photo.jpg` — wide event or DJ-booth shot (referenced in the hero background)
2. `/images/release-1.jpg`, `release-2.jpg`, `release-3.jpg` — discography cover art
3. `YOUR_VIDEO_ID` in the YouTube embed — swap for your latest upload's video ID
4. Label logos in "Trusted By" — currently text only; confirm logo usage rights with each label before adding actual logo images
5. Booking form — currently just styled fields, not yet wired to submit anywhere (email, Formspree, etc. — decide this before launch)

## Deploying to Vercel
1. Push this folder to a GitHub repo (or use `vercel` CLI directly from this folder)
2. In your existing Vercel account: New Project → import the repo → deploy (no build step needed, it's static HTML)
3. In Vercel project settings → Domains → add `sandeepsulhan.com`
4. In GoDaddy DNS settings, point the domain at Vercel (Vercel will show you the exact A record / CNAME once you add the domain — usually an A record to `76.76.21.21` for the root domain, or a CNAME for a `www` subdomain)
5. Remove the current forward to linktr.ee once DNS propagates and the new site is live
