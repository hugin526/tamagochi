# Snack Pal (PWA)

## Put it online (needs HTTPS)
- Netlify: drag this folder onto app.netlify.com/drop. Done.
- GitHub Pages: upload these files to a repo, then Settings > Pages > deploy from main branch.
- Cloudflare Pages also works.

## Install on Android
Open the site in Chrome, menu (three dots) > Install app (or Add to Home screen).
It then opens full screen and works offline.

## Notes
- Data is stored on the device. Use Settings > Backup > Export now and then.
- A new web address means a fresh start. Export from the old one, import on the new one.
- To ship an update, change the files and bump V in sw.js (e.g. snackpal-v2).
