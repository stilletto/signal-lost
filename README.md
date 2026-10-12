# Signal Lost

A mobile-first FPV combat-drone simulator. [Play in your browser](https://stilletto.github.io/signal-lost/) or [download the ARM64 Android APK](https://stilletto.github.io/signal-lost/signal-lost.apk).

The browser now uses photographed dry soil on crater rims and trenches, fixes stretched textures on dugout walls, and shares the depot's weathered steel with cold wrecks while retaining tyre/panel paint. Geometry, collision and cover are retained. The full three-aircraft Third Knock route still wins three stars at 35.2 seconds; it remains over the mobile geometry budget. Local before/after frames, thermal views, Compatibility/Web runtime checks, the full unit suite and all 60 smoke scenarios pass their required evidence. Stable handset 30 FPS remains open.

This is a Web-only player update. The downloadable/installed debug APK remains v238 from source `1ed015ca8972778216a3d91788b6def7c0f790b5`, with FPS enabled; it does not yet contain this material increment. No APK is built, installed or launched in this iteration because the phone is shared with another game's tests. `build.json` records separate Web and APK source commits.

The existing Google Play drone artwork now supplies the shared project icon, including debug Android launcher icons and browser favicons. The illustration was already preserved in source; only the Play-specific preset had selected it. Both v238 player packages update on Samsung with career files preserved, and pulled installed APKs match the audited bytes. This packaging check leaves the foreground phone app alone; it does not claim a fresh gameplay launch or FPS acceptance.

Gunfire now uses nine short recorded AK-47, machine-gun, shotgun and counter-UAS cannon impulses. Distance controls arrival, loudness and spectral loss, without an added room tail. The same bounded 16-voice mixer is retained; its measured desktop 16-report block falls from 13.0 to 2.8 ms. A physical Samsung audio probe confirms nonzero mixed output. Speaker timbre still needs player listening feedback. Graphics are preserved and the stable-30-FPS goal remains open.

Destructible roof cages, supported soldier poses, Two Knocks on Steel and The Open Back are included. The Android APK starts at the mission menu and displays FPS. Click the picture to take the sticks in the browser; use WASD and the on-screen controls. Touch controls appear on a phone.

This repository holds the compiled single-thread WebAssembly build from source `d355ddcb17970dd76b337febea6db8db1953d792` and debug APK v238 from source `1ed015ca8972778216a3d91788b6def7c0f790b5`, produced by Godot 4.7.1. `build.json` identifies the downloadable bytes. Source and validation notes are in [the source repository](https://github.com/stilletto/signal-lost-source).

Third-party art comes from Kenney, Quaternius and Poly Haven; geographic features from OpenStreetMap contributors and NASA SRTM. Gun recordings come from the CC0 Free Firearm Sound Library and credited public-domain DVIDS footage; [sources, edits and limitations](https://github.com/stilletto/signal-lost-source/blob/1ed015ca8972778216a3d91788b6def7c0f790b5/assets/audio/reports/README.md). The appearance of U.S. Department of War (DoW) visual information does not imply or constitute DoW endorsement. [Privacy policy](privacy-policy.html).
