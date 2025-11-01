# Android SDK 35 Patched Releases of Godot 4.x

## Why does this repo exist?

Google Play now requires:

> **Android 15 (API level 35) requirement**
> “Starting August 31, 2025: New apps and app updates must target Android 15 (API level 35) or higher to be submitted to Google Play.”
> [Google Play Console Help](https://support.google.com/googleplay/android-developer/answer/11926878?hl=en)

> **16 KB Google Play compatibility requirement**
> Starting November 1st, 2025, all new apps and updates to existing apps submitted to Google Play and targeting Android 15+ devices must support 16 KB page sizes on 64-bit devices.
> [Android Device Compatibility Guide](https://developer.android.com/guide/practices/page-sizes)

This means projects built with earlier versions of Godot will be **rejected during Play Store submission** unless the engine is patched.

## Current status of Godot

At the moment, only **Godot 4.5.1-stable** and **3.6.2-stable** support both of these changes.

| Godot Version  | compileSdk | Release-ready (API 35+) |
|----------------|------------|-------------------------|
| 3.6.1-stable   | 34         | No                      |
| **3.7-dev**    | **35**     | **Yes**                 |
| 4.0.1-stable   | 32         | No                      |
| 4.0.2-stable   | 33         | No                      |
| 4.0.3-stable   | 33         | No                      |
| 4.0.4-stable   | 33         | No                      |
| 4.1.1-stable   | 33         | No                      |
| 4.1.2-stable   | 33         | No                      |
| 4.1.3-stable   | 33         | No                      |
| 4.1.4-stable   | 33         | No                      |
| 4.2.1-stable   | 33         | No                      |
| 4.2.2-stable   | 34         | No                      |
| 4.4.1-stable   | 34         | No                      |
| **4.5-stable** | **35**     | **Yes**                 |

## Looking for 3.x?

- The [3.7 branch](https://github.com/godotengine/godot/tree/3.x) of Godot already supports Android SDK 35.
- To download a release see the latest nightly [release](https://github.com/shipth-is/godot-3.x-builds/releases)

## Releases

- [4.0.5](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.0.5)
- [4.1.5](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.1.5)
- [4.2.3](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.2.3)
- [4.3.1](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.3.1)
- [4.4.2](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.4.2)
