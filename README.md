# Beauty Berry - Android app
Lightweight WebView wrapper for https://beautyberry.free.nf/ (no third-party libraries).

## Build APK with GitHub
1. Create a new GitHub repo and upload all these files (keep the `.github` folder).
2. Push to `main` -> open **Actions** tab -> **Build Android APK** -> download `BeautyBerry-apk` artifact.
3. Optional: tag `v1.0` to publish the APK under **Releases**.

Change the site URL in `app/src/main/java/com/beautyberry/gallery/MainActivity.java` (`HOME_URL`, `HOST`).
