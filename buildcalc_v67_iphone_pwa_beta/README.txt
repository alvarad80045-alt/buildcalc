BuildCalc iPhone Beta

FILES
- index.html
- manifest.webmanifest
- sw.js
- icon-180.png
- icon-192.png
- icon-512.png

HOW TO TEST ON IPHONE
1. Upload the contents of this folder to any HTTPS static host such as Netlify, Vercel, or GitHub Pages.
2. Open the HTTPS address in Safari on your iPhone.
3. Tap Share.
4. Tap Add to Home Screen.
5. Open BuildCalc from the Home Screen.

Important:
- The PWA/service worker requires HTTPS. Opening index.html directly from the iPhone Files app will not behave like the installed app.
- Safari input zoom is disabled by keeping form controls at 16px or larger.
- Safe-area padding is included for the Dynamic Island/notch and Home Indicator.
- Offline caching is included after the first successful load.
