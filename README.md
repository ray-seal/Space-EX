# SPACE-EX

Interactive universe explorer with a Solar System, deep-space objects, missions, quizzes, sky chart, satellite passes, sky calendar, camera-backed AR sky finder, spacecraft tracker, linked cosmic rabbit hole and Conner's explorer journal.

## Web and PWA
https://space-ex-ebon.vercel.app

Install from a supported browser using **Install app** or **Add to Home Screen**. The service worker caches the application shell and feature bundle for offline access. Fresh orbital data and live sky calculations still need connectivity.

## Android APK
SPACE-EX also builds as a separate Android application using Capacitor, not an Edge-installed PWA. Every push to main and manual workflow runs build a debug APK. Open GitHub Actions, select **Build SPACE-EX Android APK**, open the latest successful run, download **SPACE-EX-Android-APK**, extract it and install app-debug.apk.

The APK includes native geolocation and camera-preview plugins. Android asks for permission when the relevant feature is used. It appears as its own installed app, though Android parental controls can still apply app-specific limits. Debug-signed testing build, not a Play Store release.

## Four expeditions
- AR Sky Finder: camera overlay with celestial labels positioned using location, compass and calculated sky coordinates.
- Spacecraft Tracker: orbital position estimates for ISS, Hubble, Tiangong and a Starlink sample using CelesTrak data.
- Cosmic Rabbit Hole: linked exploration of galaxies, black holes, stars, exoplanets, dark matter and more.
- Conner's Explorer Journal: local notes, discoveries, badges and JSON import/export.

Location is processed on-device and not sent to SPACE-EX servers. Camera starts only when requested. Journal data is local unless manually exported. Orbital positions are propagated estimates, not live GPS telemetry or visibility guarantees. Phone compass accuracy varies. Offline mode caches the app shell, not live data.

## Stack
Static HTML/CSS/JS, Astronomy Engine, satellite.js, Capacitor, Capacitor Geolocation, Camera Preview, GitHub Actions and Vercel.
