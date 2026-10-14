# Snakes & Ladders 3D: Power-Up Edition (Android Offline APK Project)

This archive contains the complete Android Studio project wrapping the 100% offline 3D Snakes & Ladders game inside a hardware-accelerated native Android `WebView`.

## Option 1: Instant Play on Android Without Compiling
Open `app/src/main/assets/index.html` (or the standalone `snake_and_ladder_3d_offline.html` file) directly in Chrome or any browser on your Android phone. It works 100% offline with touch orbit controls, synthesized audio, and automatic save states.

## Option 2: Build the `.apk` Locally in Android Studio or CLI
1. Extract this `.zip` folder and open it in **Android Studio** (or ensure the Android SDK is installed).
2. Run:
   ```bash
   gradle assembleDebug
   ```
3. Your installable APK will be generated at:
   `app/build/outputs/apk/debug/app-debug.apk`

## Option 3: Free 1-Click Cloud APK Build via GitHub Actions (No Local Install Needed)
1. Upload the extracted files to a new GitHub repository.
2. Open the **Actions** tab in your GitHub repository and run the **Build Android APK** workflow.
3. Download `SnakeAndLadder3D-Offline-APK` (`app-debug.apk`) directly from the workflow summary page and install it on your Android device!
