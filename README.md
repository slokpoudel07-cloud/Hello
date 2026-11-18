# ReelCut Android APK Project

Target App URL: https://ais-dev-es4wd2n3pvi4bfwiy7mepq-176218015895.asia-east1.run.app

## Option A — Build APK in the Cloud (No Android Studio Required)
1. Push this folder to a new GitHub repository.
2. Open the **Actions** tab and run **Build Android APK**.
3. Download the generated **reelcut-debug-apk** artifact (`app-debug.apk`) directly on your Android phone and tap it to install.

## Option B — Build APK Locally in Android Studio
1. Open this folder in **Android Studio**.
2. Wait for Gradle sync to complete.
3. Click **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. Copy `app/build/outputs/apk/debug/app-debug.apk` to your phone and install.

## Notes
- Supports `<input type="file">` video picking from Android gallery/files.
- Supports exporting rendered MP4/WebM clips directly to Downloads.
- To update the server URL later, edit `APP_URL` in `app/src/main/java/studio/reelcut/app/MainActivity.kt`.
