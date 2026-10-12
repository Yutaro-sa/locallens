Replace these three files in the SAME folder that contains your current LocalLens index.html:
- index.html
- app.js
- style.css

Do NOT replace config.js.

The index.html includes cache-busting query strings so the browser/CDN loads the new JS/CSS instead of the old cached pill-marker version.
After replacing the files, reopen the page. If needed, use Ctrl+Shift+R once.
