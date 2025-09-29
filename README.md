# Android SDK 35 Patched Releases of Godot 4.x

## Introduction

At the moment, only **Godot 4.5-stable** and **3.7-dev** (unreleased) support Android SDK version 35.

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

### Why is this an issue?

Google Play now requires all new apps and updates to target **Android 15 (API level 35)**.

> “Starting August 31, 2025: New apps and app updates must target Android 15 (API level 35) or higher to be submitted to Google Play.”
> [Google Play Console Help](https://support.google.com/googleplay/android-developer/answer/11926878?hl=en)

This means projects built with earlier versions of Godot (which target SDK 34 or lower) will be **rejected during Play Store submission** unless the engine is patched or upgraded to support SDK 35.

## Progress

- [x] [4.0](https://github.com/shipth-is/godot-android-sdk-upgrade/tree/4.0)
- [x] [4.1](https://github.com/shipth-is/godot-android-sdk-upgrade/tree/4.1)
- [x] [4.2](https://github.com/shipth-is/godot-android-sdk-upgrade/tree/4.2)
- [x] [4.3](https://github.com/shipth-is/godot-android-sdk-upgrade/tree/4.3)
- [x] [4.4](https://github.com/shipth-is/godot-android-sdk-upgrade/tree/4.4)
- [ ] Create releases

## Looking for 3.x?

- The [3.7 branch](https://github.com/godotengine/godot/tree/3.x) of Godot already supports Android SDK 35.
- To download a release see the latest nightly [release](https://github.com/shipth-is/godot-3.x-builds/releases)
