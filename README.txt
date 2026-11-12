Izzy's Chimera Workout - installable web app (PWA)

FILES: index.html, manifest.json, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png
Keep them together in one folder.

HOST IT (free, any one of these):
- GitHub Pages: put the files in a repo, Settings > Pages > deploy from main branch.
- Netlify Drop (app.netlify.com/drop): drag the folder in.
- Cloudflare Pages / Vercel: upload the folder.
The site must be served over https.

INSTALL ON IPHONE: open the link in SAFARI > Share button > Add to Home Screen > Add.
It then opens full-screen like an app, and works offline after the first load.

NOTE: workout logs save on that phone only (localStorage). Use Setup > Back up your log to move them.
