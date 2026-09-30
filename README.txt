# Work Hours Tracker — Home Screen App

Files:
- index.html — working tracker
- manifest.webmanifest — installable app metadata
- sw.js — offline caching
- icon-192.png / icon-512.png — app icons

IMPORTANT:
A browser only allows PWA installation/home-screen app behavior when the site is served
over HTTPS (or from localhost during development). A downloaded HTML file cannot provide
the full PWA installation experience.

After hosting these files at an HTTPS address:
Android/Chrome: open the address -> browser menu -> Add to Home screen / Install app.
iPhone/Safari: open the address -> Share -> Add to Home Screen.

The tracker itself stores records in the browser on that device.
