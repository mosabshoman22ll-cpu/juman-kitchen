Juman Kitchen - installable web app (Beta test build)

Upload this whole folder, as it is, to any static HTTPS host (GitHub Pages, Netlify, Cloudflare Pages).
index.html must be at the top level of the site.
Files: index.html (app), manifest.webmanifest, sw.js (service worker), icons/, splash/, oidn/ (render denoiser data).

To publish a new version, replace index.html and change VERSION in sw.js (e.g. juman-kitchen-v2),
so installed copies pick up the update on their next launch.
