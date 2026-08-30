VOCAB TRAINER — INSTALLABLE PWA

This package is ready to deploy as a Progressive Web App.

Files:
- vocab-trainer.html — the app
- manifest.webmanifest — installation metadata
- sw.js — offline caching
- icons/ — app icons

IMPORTANT:
A PWA must be served from HTTPS (or localhost during development). Opening the HTML
directly from Android Downloads/content:// will NOT make it a proper installable PWA.

Recommended setup:
1. Upload the contents of this folder to any static HTTPS host.
2. Open the HTTPS URL in Chrome on Android.
3. Use the Install button in the app, or Chrome menu -> Install app/Add to Home screen.
4. Launch it from the new Vocab Trainer icon.

Once installed from a stable HTTPS origin, browser storage is tied to that app origin,
so your learning progress will no longer depend on Android's content:// file provider.

The app retains the v2.3 features: adaptive review, separate numbered meanings,
sample-sentence handling, flexible definition checking, daily randomization,
and progress backup.
