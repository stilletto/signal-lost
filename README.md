# Signal Lost

A mobile-first FPV combat-drone simulator. [Play in your browser](https://stilletto.github.io/signal-lost/) or [download the ARM64 Android APK](https://stilletto.github.io/signal-lost/signal-lost.apk).

This update prepares unchanged explosion images and materials during loading. A physical Samsung SM-G998B combat probe reduced synchronous detonation setup from 153 to 4.5 ms. Scene density, shadows, feed resolution and particle counts are preserved. Stable 30 FPS remains an open target; isolated GPU and presentation spikes still occur.

Destructible roof cages, supported soldier poses, Two Knocks on Steel and The Open Back are included. The Android APK starts at the mission menu and displays FPS. Click the picture to take the sticks in the browser; use WASD and the on-screen controls. Touch controls appear on a phone.

This repository holds the compiled single-thread WebAssembly build and debug APK v236, produced by Godot 4.7.1 from source commit `aad22361c70b50a5ffcecd3e30aa335eb1cce223`. `build.json` identifies the downloadable bytes. Source and validation notes are in [the source repository](https://github.com/stilletto/signal-lost-source).

Third-party assets are from Kenney, Quaternius and Poly Haven; geographic features come from OpenStreetMap contributors and NASA SRTM. [Privacy policy](privacy-policy.html).
