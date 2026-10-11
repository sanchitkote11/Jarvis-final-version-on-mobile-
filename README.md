# J.A.R.V.I.S. Audio Orb - Native Android APK Project

This Android Studio project packages the J.A.R.V.I.S. Multimodal Voice Assistant into a high-performance native Android APK.

## Features Included:
- **AudioOrbActivity.kt**: Immersive fullscreen WebView container with hardware acceleration and microphone WebRTC support.
- **WebAppInterface.kt**: Native Android bridge for vibration haptics and toast notifications.
- **Auto-Configured Permissions**: INTERNET, RECORD_AUDIO, VIBRATE, WAKE_LOCK.
- **GitHub Actions Workflow**: Auto-builds APK in the cloud on every push!

## How to Build the APK:

### Option A: Open in Android Studio
1. Open this folder in Android Studio (version Hedgehog or newer).
2. Wait for Gradle sync to complete.
3. Click **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. Locate your APK in `app/build/outputs/apk/debug/app-debug.apk`!

### Option B: Command Line (CLI)
```bash
./gradlew assembleDebug
```

### Option C: GitHub Actions
Push this repository to GitHub and check the **Actions** tab to download your freshly compiled APK!
