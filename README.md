# SPACE-EX

An interactive universe explorer and sky guide, with a Solar System explorer, deep-space objects, missions, quizzes, live sky chart, satellite pass predictions and an astronomy calendar.

## Try it on the web

https://space-ex-ebon.vercel.app

## Android app (APK)

SPACE-EX can also be built as an Android app using Capacitor.

Every push to `main`, and every manual run of the Android workflow, builds a debug APK. To download it:

1. Open the repository's **Actions** tab.
2. Select **Build SPACE-EX Android APK**.
3. Open the latest successful run.
4. Download the **SPACE-EX-Android-APK** artifact.
5. Extract the ZIP and install `app-debug.apk` on the Android phone.

Android may ask you to allow installation from the browser or file manager used to open the APK. The app requests location access only when the sky-location feature is used. Location coordinates are processed on-device by the sky chart and are not sent to SPACE-EX servers.

This is a debug-signed APK for direct testing, not a Play Store release.

## Sky guide notes

- Sky positions are calculated on-device using Astronomy Engine.
- Satellite pass predictions use public CelesTrak orbital data, cached locally for two hours.
- A predicted satellite pass is geometric and is not a guarantee of naked-eye visibility.
- Starlink train predictions link to dedicated external trackers.
- Sky visibility depends on the observer's location, time, horizon, weather and light pollution.

## Technology

- Static HTML, CSS and JavaScript
- Astronomy Engine
- satellite.js
- Capacitor Android wrapper
- GitHub Actions Android build
- Vercel web deployment
