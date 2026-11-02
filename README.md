# Android SDK 36 Patched Releases of Godot 4.x

## Why does this repo exist?

Google Play now requires:

> **Android 16 (API level 36) requirement**
> "New apps and app updates must target Android 16 (API level 36) or higher to be submitted to Google Play." This started on August 31, 2026, with extensions up to November 1, 2026.
> [Google Play Console Help](https://support.google.com/googleplay/android-developer/answer/11926878?hl=en)

> **16 KB Google Play compatibility requirement**
> Starting November 1st, 2025, all new apps and updates to existing apps submitted to Google Play and targeting Android 15+ devices must support 16 KB page sizes on 64-bit devices.
> [Android Device Compatibility Guide](https://developer.android.com/guide/practices/page-sizes)

So projects built with older versions of Godot will be **rejected by Google Play** unless the engine is patched.

## Current status of Godot

Only **Godot 3.6.3**, **4.6.3**, **4.7.x** and **4.8** target API 36 out of the box.

| Godot Version  | targetSdk | Release-ready (API 36) |
|----------------|-----------|------------------------|
| 3.6.2-stable   | 35        | No                     |
| **3.6.3-stable** | **36**  | **Yes**                |
| 4.0.4-stable   | 33        | No                     |
| 4.1.4-stable   | 33        | No                     |
| 4.2.2-stable   | 34        | No                     |
| 4.3-stable     | 34        | No                     |
| 4.4.1-stable   | 34        | No                     |
| 4.5.2-stable   | 35        | No                     |
| 4.6.2-stable   | 35        | No                     |
| **4.6.3-stable** | **36**  | **Yes**                |
| **4.7.x-stable** | **36**  | **Yes**                |

## What's in these builds

Each branch here is Godot's own maintenance branch for that version, plus:

- compileSdk and targetSdk 36 ([Godot #113761](https://github.com/godotengine/godot/pull/113761))
- the back button fix for API 36 ([Godot #117653](https://github.com/godotengine/godot/pull/117653))
- [16 KB page size](https://developer.android.com/guide/practices/page-sizes) support

The version is one patch higher than the last Godot release (e.g. 4.4.3), so you can tell them apart.

Each release has the Linux editor and the Android release templates (arm64 and armeabi-v7a). These are the standard builds, not .NET.

## Looking for 3.x?

Use the official [3.6.3](https://github.com/godotengine/godot/releases/tag/3.6.3-stable) - it already targets API 36.

## Releases

- [4.0.6](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.0.6-5d33a1a)
- [4.1.6](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.1.6-b45380c)
- [4.2.4](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.2.4-d751c12)
- [4.3.2](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.3.2-4953d76)
- [4.4.3](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.4.3-9f96eb7)
- [4.5.3](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.5.3-90c6082)

### Older releases (API 35)

These target API 35, so Google Play won't accept them any more.

- [4.0.5](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.0.5-df6989b)
- [4.1.5](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.1.5-b68debd)
- [4.2.3](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.2.3-d33f443)
- [4.3.1](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.3.1-28eb575)
- [4.4.2](https://github.com/shipth-is/godot-android-sdk-upgrade/releases/tag/4.4.2-ca113b3)
