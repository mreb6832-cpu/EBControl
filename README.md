# EBCONTROL

A responsive Universal Smart TV Remote PWA starter.

## Files
- `index.html` — website UI and demo controls
- `manifest.json` — PWA metadata
- `sw.js` — service worker and basic offline caching
- `icon.svg` — app icon

## Deploy with GitHub + Vercel
1. Upload all four files to the root of your GitHub repository.
2. In Vercel, import the repository.
3. Keep the framework preset as **Other** (static site) and deploy.
4. Open the HTTPS deployment on your phone. Use the browser menu to install/add it to the Home Screen.

## Important limitation
This is a front-end demo/PWA starter. The buttons currently show demo messages; they do not send commands to a real TV. Real TV control needs supported manufacturer integrations and a network connection path that browsers can access. A Vercel-hosted website alone cannot directly discover or control every device on a user's private Wi-Fi network.
