# Signal Lost — browser build

A mobile-first FPV combat drone simulator. Open it here: <https://stilletto.github.io/signal-lost/>

Current build: **0.19.0 MVP — airframe and controls update**, source revision
`7e5aebf` (2026-09-24).
This repository holds the compiled WebAssembly build and Android download.
The source repository remains private; the build can still be inspected just
as any distributed game can.

[Download Android APK — 58.4 MiB](https://stilletto.github.io/signal-lost/signal-lost.apk?release=7e5aebf)

Android: arm64-v8a, Android 7.0 or later, signed debug build. Package and signing
certificate match the previous 0.19.0 build, so an in-place update preserves application data.
Back up important saves before uninstalling; uninstalling is not required.
File hashes and exact sizes are recorded in `release.json`.

Click the picture to take the sticks. WASD to fly, mouse to look, SPACE to arm,
BACKSPACE for a new sortie. Phones use on-screen sticks, flight buttons and the
AGAIN control on the results screen. Control settings are available from the
mission menu and during flight. The uncompressed web export is about 79.1 MiB.

The aircraft now has an open frame, separate blades and motors, battery,
camera and build-specific underside. Its own hull stays out of the live FPV
lens but remains visible in external views and replays. Mantis uses 2,480
triangles versus the previous 3,096; the default replay cameras remain distant
and the blades are not animated yet.

Verification: 1,371 automated tests and all 44 smoke scenarios passed. Rendered
camera tests passed on Mobile and Compatibility. The Web export opened its
mission menu without browser console warnings/errors. Handheld
layouts and touch-event paths were checked on desktop. This build has not yet
been run on a physical Android device; no handset FPS claim is made. The existing
FIRST LIGHT scene triangle-budget excess remains unchanged by this model update.

Third-party assets are from Kenney, Quaternius and Poly Haven; geographic
features come from OpenStreetMap contributors and NASA SRTM.
