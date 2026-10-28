SHARDBOUND KINGDOMS — INSTALLABLE WEB GAME

FILES
- index.html: game
- manifest.webmanifest: install metadata
- sw.js: app-shell and runtime cache
- icons/: app icons

RUN LOCALLY
For a quick test, open index.html in a current browser. Some PWA features only work when hosted over HTTPS or localhost. The game currently loads Three.js from jsDelivr, so the first launch needs internet. The service worker attempts to cache the engine after it loads, but offline support depends on browser cache policies.

HOST AS A WEBSITE (free options)
1. Create a GitHub repository and upload every file in this folder (keep index.html at the root).
2. In repository Settings -> Pages, deploy from the main branch / root.
3. Open the HTTPS Pages URL on Android Chrome. Use the browser menu -> Install app / Add to Home screen.
Alternative: upload the folder to a static HTTPS host such as Netlify Drop.

LIMITS
This is an expanded playable prototype, not a finished commercial release. Hosting is not performed automatically; you must publish these files to an account you control. Progress saves locally per browser/device and does not sync across devices.
