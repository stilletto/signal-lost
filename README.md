# Signal Lost — browser build

A mobile-first FPV combat drone simulator. Open it here: <https://stilletto.github.io/signal-lost/>

Current build: **0.20.0 — Albatross terminal approach**, source revision
`4ae2c52` (2026-09-25).
This repository holds the compiled WebAssembly build and Android download.
The source repository remains private; the build can still be inspected just
as any distributed game can.

[Download Android APK — 58.5 MiB](https://stilletto.github.io/signal-lost/signal-lost.apk?release=4ae2c52)

Android: arm64-v8a, Android 7.0 or later, signed debug build. Package and signing
certificate match the previous 0.19.0 build, so an in-place update preserves application data.
Back up important saves before uninstalling; uninstalling is not required.
File hashes and exact sizes are recorded in `release.json`.

Click the picture to take the sticks. WASD to fly, mouse to look, SPACE to arm,
BACKSPACE for a new sortie. Phones use on-screen sticks, flight buttons and the
AGAIN control on the results screen. Control settings are available from the
mission menu and during flight. The uncompressed web export is about 79.2 MiB.

Choose **OPERATION FAR HORIZON / ДАЛЬНИЙ РУБЕЖ**, then
**THE LAST MILE / ПОСЛЕДНЯЯ МИЛЯ**. This one-contract preview is unlocked at
zero rank. Follow the compressed autopilot route on a schematic map, skip if
desired, then explicitly take control about 650 m from the industrial site.
The world, battery and deadline wait for that handoff.

Albatross has a separate, stabilized fixed-wing flight model and a new original
1,288-triangle model: it banks, glides and cannot hover. On a phone the left
stick changes speed; the right stick turns and commands climb/dive. The $5
operator denoiser remains available. The destination adds connected roads,
roofed buildings and wooded groups, reusing existing textures and assets.
No new satellite imagery or city dataset is bundled.

Verification: 1,428 automated tests / 47,239 assertions and all 45 smoke scenarios
passed. A rendered terminal strike completed in 28.3 s, with p95 201 submissions
and 121,858 visible triangles. These are desktop render-budget figures, not
handset FPS. Handheld layouts and real touch-event paths were checked on desktop;
this release has not been tested on a physical Android device.

The web menu, route, handoff and FPV scene were tested. Codex's in-app browser
refused pointer lock even in a visible tab; mouse capture there remains an open
limitation, and an external desktop browser was not tested for this release.
The existing FIRST LIGHT triangle-budget excess and engine teardown warnings
are not fixed here. This is not the full long-range campaign: additional aircraft,
urban missions, strategic choices and missile air defence remain future work.

Third-party assets are from Kenney, Quaternius and Poly Haven; geographic
features come from OpenStreetMap contributors and NASA SRTM.
