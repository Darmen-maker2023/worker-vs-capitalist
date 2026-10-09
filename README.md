# Worker vs Capitalist for Android

Android WebView app containing the standalone game interface extracted from the packaged Windows Electron build.

## Build

Install JDK 17, Android SDK Platform 35, and Android Build Tools 35.0.0. Then set `ANDROID_HOME` (or `ANDROID_SDK_ROOT`) to the SDK directory and run:

```sh
gradle assembleDebug
```

The APK is written to `app/build/outputs/apk/debug/app-debug.apk`.

The GitHub Actions workflow builds this APK on pushes and pull requests and stores it as a downloadable workflow artifact.

After each push or pull request, open the repository's **Actions** tab and download the `worker-vs-capitalist-android-debug` artifact from the completed **Android APK** run.

## App details

- Package: `com.worker.vsc`
- Minimum Android version: Android 6.0 (API 23)
- Target Android version: API 35
- The game runs locally in an Android WebView. It does not request network access.

The APK is a debug build for installation and review. A Play Store release should be signed with a private release key.
