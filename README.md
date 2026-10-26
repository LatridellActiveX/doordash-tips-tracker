# DoorDash Tips Tracker

Installable Progressive Web App (PWA) to track your daily DoorDash tips.

## Features
- Log tips by date
- View total, average per day, and history
- Works offline
- Installable on mobile (Add to Home Screen)
- Data stored locally in your browser

## Deploy to Cloudflare Pages

1. Go to [Cloudflare Dashboard](https://dash.cloudflare.com) → Workers & Pages → Create application → Pages → Connect to Git
2. Select this GitHub repository: `LatridellActiveX/doordash-tips-tracker`
3. Build settings:
   - Framework preset: None
   - Build command: `exit 0`
   - Build output directory: `/` (root)
4. Save and Deploy

Your app will be live at `https://doordash-tips-tracker.pages.dev` (or your chosen name).

## Install on Mobile
1. Open the deployed URL in Chrome/Safari
2. Tap the share/menu button → "Add to Home Screen" / "Install"
3. Use it like a native app

## Local Development
Just open `index.html` in a browser, or serve with any static server.
