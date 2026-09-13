# KSE Version 1 — GitHub Actions Ready

This version is designed for building from an Android phone using GitHub Actions. You do **not** need Android Studio on your phone.

## Upload
Upload every file and folder inside this project to the root of a GitHub repository. The `.github/workflows/build-apk.yml` file must also be uploaded.

## Build
1. Open the repository on GitHub.
2. Tap **Actions**.
3. Select **Build KSE APK**.
4. Tap **Run workflow**.
5. Wait for the green check mark.
6. Open the completed run.
7. Under **Artifacts**, download **KSE-V1-APK**.
8. Extract the artifact and install `app-debug.apk`.

## Important
The workflow installs Gradle 8.10.2 on the GitHub runner and generates the Gradle Wrapper during the build. This avoids the `gradlew: No such file or directory` error when the wrapper was not included in an uploaded project.

Website:
https://newkrishnasudhae-droid.github.io/KSE/
