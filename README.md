# GameTranslator

An experimental Android app intended to help translate on-screen game dialogue into Vietnamese.

## Build APK

GitHub Actions builds a debug APK whenever code is pushed to `main`, and also supports manual runs.

1. Open the **Actions** tab.
2. Select **Build GameTranslator APK**.
3. Choose **Run workflow** if needed.
4. Open a completed run and download the `GameTranslator-debug-apk` artifact.

The project is an early prototype. Screen capture and overlay behavior must be tested on the target Android device. Screen capture requires Android's system consent dialog, and showing an overlay requires the user's explicit permission.
