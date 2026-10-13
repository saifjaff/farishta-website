# Farishta website

The marketing site for Farishta, the shared family dhikr counter. The app itself lives at dhikr.farishta.si.

It is a static site: `index.html` plus the images in `assets/`. No build step.

## Deploy on Vercel

1. In Vercel, choose **Add New → Project** and import this repo.
2. Leave Framework Preset as **Other**, with no build command and no output directory.
3. Deploy. The site goes live at a `*.vercel.app` address straight away.
4. Under **Settings → Domains**, add `farishta.si` and `www.farishta.si` once DNS is set up in Cloudflare.

## Run locally

Open `index.html` in a browser, or run `npx serve .` from this folder.
