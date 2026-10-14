# Neighborhood Experts Home Prep Guide

A photo-day checklist for home sellers. It is a single-page web app with no build step.

- Light, dark, and system appearance
- Shoot date countdown
- Saved checkmarks (stored on the device)
- Works offline once opened, and installs to the iPhone home screen

## Install on iPhone

1. Open the site in Safari.
2. Tap Share, then Add to Home Screen.

## Update the app

Edit `index.html`, commit, and push. GitHub Pages redeploys in about a minute.
If a phone shows an old version, bump `CACHE` in `sw.js` (for example `ne-home-prep-v2`).
