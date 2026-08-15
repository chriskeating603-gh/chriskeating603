# chriskeating603.com

Personal site, rebuilt from the Squarespace version (canceled Sep 14, 2026 —
this repo replaces it). Plain HTML/CSS, no build step, no framework.

## Layout

```
index.html   the whole site
style.css    styling
favicon.ico  pulled from the old Squarespace CDN before cancellation
```

## Editing

Just edit `index.html` / `style.css` directly and reload — no build step.

## Deploying

Not yet deployed. The domain (`chriskeating603.com`) is registered through
Squarespace but the website hosting subscription is canceled as of the end
of the current billing cycle (Sep 14, 2026). To go live on this repo instead:

1. Pick a static host (GitHub Pages, Cloudflare Pages, Netlify, Vercel all work
   for a no-build static site).
2. Point the domain's DNS at that host (may require moving DNS off Squarespace,
   similar to what was done for `keachuangting.com` — see that project's
   `DECISIONS.md` for the Squarespace DNS panel limitations hit there).
3. If using GitHub Pages, add a `CNAME` file containing `chriskeating603.com`.

## Fonts

- Headline: Fraunces (Google Fonts) — stand-in for Squarespace's licensed
  "Freight Display Pro", which isn't available outside Squarespace.
- Body: Archivo (Google Fonts) — matches the original site's body font exactly.
