# Among Us Mod Manager

A simple Android Studio project for importing mod files, keeping them in app-private storage, and extracting ZIP archives.

## Features
- Import files using Android's system file picker.
- Store imported files in the app's private `files/mods` directory.
- Show imported files and file sizes.
- Extract ZIP files, with protection against ZIP path traversal.
- Delete imported files and extracted folders.

## Build an APK
1. Open this folder in Android Studio (Hedgehog or newer).
2. Let Gradle sync and install the Android SDK Platform 35 if prompted.
3. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. Find the APK at `app/build/outputs/apk/debug/app-debug.apk`.

## Important
This is a file manager, not a mod installer or compatibility patcher. It can store APK, ZIP, and other files selected from the picker. PC Among Us mods generally cannot run on Android; only use mods that are made for your exact game/platform/version. RAR extraction is not included in this starter build.
