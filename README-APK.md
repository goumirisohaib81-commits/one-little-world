# One Little World — standalone APK

This project is configured to build a directly installable Android APK with GitHub Actions.
The installed APK does not require Expo Go, Metro, EAS, Google Play, or a runtime server.

## Build
1. Upload this project to a GitHub repository.
2. Use the `main` branch.
3. Open **Actions** → **Build Standalone Android APK** → **Run workflow**.
4. When it finishes, open the run and download the artifact `one-little-world-apk`.
5. Extract the downloaded artifact and install `app-debug.apk` on Android.

The GitHub account is only used to perform the build and download the APK artifact. The installed app itself does not need GitHub.
