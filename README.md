# Godot 4.0 - 4.5 builds for Google Play

Google Play needs Android apps to:

- target Android 16 (API 36) - from 31 August 2026 ([Play Console Help](https://support.google.com/googleplay/android-developer/answer/11926878))
- support 16 KB page sizes on 64-bit devices - from 1 November 2025 ([Android docs](https://developer.android.com/guide/practices/page-sizes))

Godot has fixed both in 3.6.3, 4.6.3 and 4.7, but older 4.x versions don't get updates any more. These builds backport Godot's own fixes so games on 4.0 - 4.5 can still go to Play.

## Why not just change the export settings?

You can set **Target SDK** to 36 in the Android export preset on any 4.x version, and Play will accept it. But:

- 16 KB support needs the engine rebuilt with a newer NDK - there's no setting for it. Godot added it in 4.5.
- On Android 16 and later, targeting 36 changes how the back gesture works. Without Godot's fix the game never gets the back event, so back buttons and pause menus stop working.

## What's in these builds

Each branch is Godot's own maintenance branch for that version, plus:

- [16 KB page size](https://developer.android.com/guide/practices/page-sizes) support (already in 4.5)
- compileSdk and targetSdk 36 ([Godot #113761](https://github.com/godotengine/godot/pull/113761))
- the back gesture fix ([Godot #117653](https://github.com/godotengine/godot/pull/117653))

Nothing else is changed. The version is one patch higher than the last Godot release (e.g. 4.4.3), so you can tell them apart.

Each release has the Linux editor and the Android release templates (arm64 and armeabi-v7a). These are the standard builds, not .NET.

## Which Godot versions need this?

| Godot version | targetSdk | 16 KB | Play-ready |
|---------------|-----------|-------|------------|
| 3.6.3         | 36        | Yes   | **Yes**    |
| 4.0 - 4.4     | 33 - 34   | No    | No - use these builds |
| 4.5.2         | 35        | Yes   | No - use these builds |
| 4.6.3, 4.7.x  | 36        | Yes   | **Yes**    |

On 3.x, use the official [3.6.3](https://github.com/godotengine/godot/releases/tag/3.6.3-stable).

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
