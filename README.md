# Signal Lost — browser build

A mobile-first FPV combat drone simulator. Open it here: <https://stilletto.github.io/signal-lost/>

Current build: **0.19.0 MVP**, source revision `c65feea` (2026-09-17).
This repository holds the compiled WebAssembly build and Android download.
The source repository remains private; the build can still be inspected just
as any distributed game can.

[Download Android APK — 58.2 MiB](https://stilletto.github.io/signal-lost/signal-lost.apk?release=c65feea)

Android: arm64-v8a, Android 7.0 or later, signed debug build. Package and signing
certificate match 0.18.0, so an in-place update preserves application data.
Back up important saves before uninstalling; uninstalling is not required.
File hashes and exact sizes are recorded in `release.json`.

Click the picture to take the sticks. WASD to fly, mouse to look, SPACE to arm,
BACKSPACE for a new sortie. Phones use on-screen sticks, flight buttons and the
AGAIN control on the results screen. The uncompressed web export is about 79 MiB.

Verification: 1,318 automated tests and all 44 smoke scenarios passed. Handheld
layouts and touch-event paths were checked on desktop. This build has not yet
been run on a physical Android device; no handset FPS claim is made.

Third-party assets are from Kenney, Quaternius and Poly Haven; geographic
features come from OpenStreetMap contributors and NASA SRTM.
