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

## Option 2 — Test on a computer with Android Studio Emulator

If you do not have an Android phone, the APK can be tested with the Android Emulator included with Android Studio.

### A. Create and start an emulator

1. Open **Android Studio**.
2. From the welcome screen choose **More Actions → Virtual Device Manager**. If a project is already open, use **Tools → Device Manager**.
3. Click **Create device**.
4. Choose a phone profile such as **Pixel 8** and click **Next**.
5. Choose an available Android system image. If Android Studio asks to download one, click **Download**, wait for it to finish, then select it.
6. Click **Next → Finish**.
7. In **Device Manager**, click the **▶ Play** button next to the new virtual device.
8. Wait until the Android home screen appears.

### B. Download the APK

1. Return to this GitHub repository.
2. Click **Download the APK** above.
3. Save `mobile-app-demo.apk` somewhere easy to find, for example the **Downloads** folder.

### C. Install the APK — easiest method

1. Keep the Android emulator open.
2. Open Windows File Explorer and locate `mobile-app-demo.apk`.
3. Drag the APK file directly onto the running emulator window.
4. Wait for Android to finish installing it.
5. Open the app from the emulator's app launcher.

### D. Alternative installation with ADB

If you prefer the command line, open a terminal in the folder containing the APK and check that the emulator is detected:

```bash
adb devices
```

You should see an emulator listed with the status `device`.

Then install the APK:

```bash
adb install -r mobile-app-demo.apk
```

When the terminal shows `Success`, open the app from the emulator's app launcher.

## Notes

- This is an Android APK demo build intended only for review/testing.
- It is installed manually and is not distributed through the Google Play Store.
- Android may display a security warning because the APK is being installed directly; this is expected for a manually shared demo build.
- No access to the private source-code repository is required to test the APK.
- This public repository contains only the compiled demo build and the testing instructions.
