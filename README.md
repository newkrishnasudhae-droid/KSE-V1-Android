# KSE Version 1 Android Project

This project wraps the KSE website in an Android WebView.

Website:
https://newkrishnasudhae-droid.github.io/KSE/

## Build APK

1. Install Android Studio.
2. Open this folder: `KSE_V1_Android`
3. Let Gradle sync.
4. Select **Build > Build App Bundle(s) / APK(s) > Build APK(s)**.
5. The debug APK will be generated under:
   `app/build/outputs/apk/debug/app-debug.apk`

## Notes

- Internet permission is included.
- Android back button navigates WebView history first.
- Pull down to refresh.
- A retry screen appears if the main page cannot load.
- Version 1 uses the live website, so website changes appear in the app without rebuilding the APK.
