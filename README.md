# Signal Lost

A mobile-first FPV combat-drone simulator. [Play in your browser](https://stilletto.github.io/signal-lost/) or [download the ARM64 Android APK](https://stilletto.github.io/signal-lost/signal-lost.apk).

Gunfire now uses nine short recorded AK-47, machine-gun, shotgun and counter-UAS cannon impulses. Distance controls arrival, loudness and spectral loss, without an added room tail. The same bounded 16-voice mixer is retained; its measured desktop 16-report block falls from 13.0 to 2.8 ms. A physical Samsung audio probe confirms nonzero mixed output. Speaker timbre still needs player listening feedback. Graphics are preserved and the stable-30-FPS goal remains open.

Destructible roof cages, supported soldier poses, Two Knocks on Steel and The Open Back are included. The Android APK starts at the mission menu and displays FPS. Click the picture to take the sticks in the browser; use WASD and the on-screen controls. Touch controls appear on a phone.

This repository holds the compiled single-thread WebAssembly build and debug APK v237, produced by Godot 4.7.1 from source commit `50a747e3c67151da886fad1ca38beb45783d68df`. `build.json` identifies the downloadable bytes. Source and validation notes are in [the source repository](https://github.com/stilletto/signal-lost-source).

Third-party art comes from Kenney, Quaternius and Poly Haven; geographic features from OpenStreetMap contributors and NASA SRTM. Gun recordings come from the CC0 Free Firearm Sound Library and credited public-domain DVIDS footage; [sources, edits and limitations](https://github.com/stilletto/signal-lost-source/blob/50a747e3c67151da886fad1ca38beb45783d68df/assets/audio/reports/README.md). The appearance of U.S. Department of War (DoW) visual information does not imply or constitute DoW endorsement. [Privacy policy](privacy-policy.html).
