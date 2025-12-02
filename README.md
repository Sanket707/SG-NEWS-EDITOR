# SN Video Editor - Android Starter Project

This is a starter Android Studio project for an SN-style short video editor.
It contains Compose UI, FFmpegKit integration and basic features:
- Pick multiple videos
- Merge (concat)
- Speed change (basic)
- Text overlay (drawtext)
- Export MP4

## How to build
1. Install Android Studio and Android SDK.
2. Open this project folder in Android Studio.
3. Let Gradle sync. You may need to install Kotlin and Android Gradle Plugin versions.
4. Connect a physical Android device (recommended) and run `app` module.
5. To create APK: Build > Build Bundle(s) / APK(s) > Build APK(s).

## Notes & Limitations
- FFmpegKit adds size to APK. For production consider slimmer builds or server-side processing.
- `drawtext` may require a fontfile path on some devices; adapt code accordingly.
- This project is a starter template — UI polishing, timeline thumbnails, stickers, transitions are left as next steps.

If you want, I can:
- Generate the full Git repo with more features (stickers, filters, transitions)
- Create a GitHub Actions workflow to build APK automatically and publish a downloadable APK
- Provide step-by-step video showing how to open & build in Android Studio
