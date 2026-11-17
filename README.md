# sonic-colors-ultimate-android-60fps-720p-optimizer
Sonic Colors: Ultimate 720p/60 FPS optimization preset for Nintendo Switch emulation on Android. Tested on Eden Stable with the Snapdragon 8 Gen 2.
Sonic Colors: Ultimate — Android 720p / 60 FPS Optimizer

A performance-focused optimization preset for Sonic Colors: Ultimate on Nintendo Switch emulators running Android.

This project combines existing community FPS and resolution modifications to deliver a smoother gameplay experience on Android handheld devices.

The configuration has been successfully tested on Eden Stable, achieving a consistent 60 FPS at 720p during tested gameplay.

Performance Results

Category| Results
Game| Sonic Colors: Ultimate
Platform| Nintendo Switch
Emulator| Eden Stable (Android)
Device| AYN Thor Max
Processor| Snapdragon 8 Gen 2
GPU| Adreno 740
Target resolution| 1280 × 720
Target frame rate| 60 FPS
Observed performance| Stable 60 FPS during testing
Game version| 1.0.9
Title ID| 010040E0116B8000
Build ID| 957E1E19958A93F9

Note: Results are based on the tested configuration. Performance and graphical compatibility may vary depending on your device, GPU driver, emulator build, and game version.

Features

60 FPS Gameplay

- Unlocks the game's original 30 FPS limit.
- Targets 60 FPS gameplay.
- Achieved stable 60 FPS during testing on the AYN Thor Max.
- Designed for Android-based Nintendo Switch emulation.

Native 720p Optimization

- Adjusts the game's internal docked rendering resolution to 720p.
- Reduces the pixel-rendering workload compared with the default 900p docked resolution.
- Aims to improve performance while maintaining acceptable image quality.
- Uses a version-specific ExeFS patch.

Android Compatibility

- Tested using Eden Stable for Android.
- Designed with Snapdragon and Adreno devices in mind.
- May work on other compatible Android devices, but results are not guaranteed.

Installation

Requirements

- Eden emulator for Android.
- Sonic Colors: Ultimate, version 1.0.9.
- A compatible 60 FPS patch.
- The 720p optimization patch provided with this project.

Step 1 — Download

Download the optimization files from the repository's Releases section.

The 720p optimization package contains an ExeFS directory:

Sonic Colors Ultimate 720p/
└── exefs/
    └── native_720p_v1.0.9.pchtxt

The 60 FPS modification is a separate component unless explicitly included in the release.

Step 2 — Install in Eden

1. Extract the downloaded ZIP.
2. Open Eden.
3. Locate Sonic Colors: Ultimate.
4. Long-press the game.
5. Open the game's Add-ons section.
6. Select the option to install mods or cheats.
7. Select the extracted folder containing "exefs/".
8. Enable the optimization patch.
9. Ensure your compatible 60 FPS modification is also enabled.
10. Restart the game.

Important: Eden requires a valid "exefs/", "romfs/", or "cheats/" directory when importing modifications. Do not select an individual ".pchtxt" file.

Avoid installing multiple resolution patches that modify the same game addresses.

Step 3 — Recommended Settings

Setting| Configuration
Emulator| Eden Stable
Graphics API| Vulkan
Resolution Scale| 1×
Console Mode| Docked
Target FPS| 60
Frame Generation| Disabled for baseline testing
GPU Driver| Compatible driver for your device

For best results, test different GPU drivers and emulator settings individually.

Known Issues

2D Text / Interface Flickering

Certain 2D text elements may intermittently flicker between purple and black.

During testing:

- Gameplay maintained a stable 60 FPS.
- The issue primarily affected 2D text or UI elements.
- The rendering issue was not considered significant enough to prevent normal gameplay.

The exact cause has not been confirmed. GPU driver compatibility, shader handling, and emulator rendering behavior are possible factors.

This project does not currently include a verified fix for the flickering.

Compatibility

The included 720p patch targets game version 1.0.9.

Other versions may require different memory addresses or patches. Compatibility should not be assumed.

Credits

This project builds upon existing Nintendo Switch modding community work.

Original community resources:

- "ChanseyIsTheBest — NX 60FPS, Resolution and Graphics Cheats" (https://github.com/ChanseyIsTheBest/NX-60FPS-RES-GFX-Cheats)
- "Fl4sh9174 — Switch Emulator Ultrawide and FPS Mods" (https://github.com/Fl4sh9174/Switch-Emulator-Ultrawide-FPS-Mods)

Credit belongs to the respective developers for their original patches and discoveries.

This repository focuses on organizing, testing, and documenting a working Android optimization configuration.

Disclaimer

This is an unofficial community optimization project.

It is not affiliated with Nintendo, SEGA, Sonic Team, or the Eden emulator developers.

No game files, copyrighted game assets, or Nintendo encryption keys are distributed.

Performance varies between hardware configurations.

Feedback

If you test this configuration, consider sharing:

- Android device and chipset
- Emulator version
- GPU driver
- Average FPS
- Any graphical issues

Community testing is useful for improving compatibility and identifying reliable settings.

---

Maintained by MPDERPER

Focused on improving Nintendo Switch emulation performance on Android.
