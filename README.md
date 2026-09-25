# Android Mobile App Demo

This repository contains the installable Android demo build provided for interview review.

## Quick download

**[Download the APK](https://raw.githubusercontent.com/Johnallan27/Android-mobile-app-demo/main/mobile-app-demo.apk)**

File: `mobile-app-demo.apk`

## Option 1 — Test on a physical Android device

1. Open the **Download the APK** link above on an Android device.
2. Download `mobile-app-demo.apk`.
3. Open the downloaded file.
4. If Android blocks the installation, allow **Install unknown apps / Allow from this source** for the browser or file manager being used.
5. Tap **Install**.
6. When installation finishes, tap **Open** to launch the demo.

## Option 2 — Test with an Android emulator on a computer

If you do not have an Android phone, you can test the APK with an Android emulator.

### Prerequisites

- Android Studio installed
- An Android Virtual Device (AVD) created in **Device Manager**
- `adb` available from the Android SDK platform-tools

### Steps

1. Open **Android Studio**.
2. Open **Device Manager** and start any Android emulator.
3. Download `mobile-app-demo.apk` from this repository to your computer.
4. Open a terminal in the folder containing the APK.
5. Check that the emulator is detected:

```bash
adb devices
```

You should see an emulator listed as `device`.

6. Install the APK:

```bash
adb install -r mobile-app-demo.apk
```

7. When the terminal shows `Success`, open the app from the emulator's app launcher.

## Notes

- This is an Android APK demo build intended for review/testing.
- It is installed manually and is not distributed through the Google Play Store.
- Android may display a security warning because the APK is being installed directly; this is expected for a manually shared demo build.
- The emulator steps above are generic and do not require access to the private source-code repository.
- This repository contains only the compiled demo build and does not expose the private source-code repository.
