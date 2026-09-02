# Picking & Packing Audits Board

This is the exact live app currently at `regal-macaron-b82f47.netlify.app`,
pulled down as its actual deployed file so it can be redeployed somewhere
that isn't blocked by Netlify's credit limit. Nothing about the app changed
— it's byte-for-byte what's live now, just repackaged as a file you can
host anywhere.

## What's in this folder

- `index.html` — the entire app: structure, styling, and logic, all in one
  file (same architecture as the Shift Handover app). It already has your
  live Supabase project's URL and key embedded, so it's ready to deploy
  as-is — no setup needed.

## Important: your data is untouched

All of this app's data — every audit, every photo — lives in Supabase, not
in Netlify. Moving where the *website files* are hosted doesn't touch the
database at all. Once this is deployed to a new URL, it'll show all the
same history your team already has, live-synced the same way it is now.
The only thing that changes is the web address people use to open it.

## Deploying to GitHub Pages (free, no credit limit)

See `GITHUB-PAGES-DEPLOY.md` one level up — the same steps apply to both
this app and the Shift Handover app, just pick a different repo name for
each.
