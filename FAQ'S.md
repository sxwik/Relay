# FAQ

## General

### What is Relay?

Relay is an Android workstation for Windows that combines device management, screen mirroring, file transfers, package management, terminal access, recovery tools, and device analysis into a single desktop application.

---

### Is Relay a replacement for ADB?

No.

Relay uses ADB under the hood and provides a graphical interface for common Android workflows.

Think of Relay as a workstation built on top of Android developer tools.

---

### Is Relay open source?

Refer to the project's license and repository for current source availability.

---

### Who is Relay for?

Relay is designed for:

* Android enthusiasts
* Developers
* Custom ROM users
* Repair technicians
* Power users
* Emulator users

---

## Devices

### What devices are supported?

Most Android devices that support ADB debugging.

Examples include:

* Xiaomi
* POCO
* Samsung
* Motorola
* OnePlus
* Google Pixel
* Android tablets
* Android emulators

---

### Does Relay support emulators?

Yes.

Relay supports Android emulators that expose an ADB connection.

Examples:

* BlueStacks
* Android Studio Emulator
* LDPlayer
* MuMu
* NoxPlayer

---

### My emulator does not appear in Relay.

Verify that the emulator is visible in:

```bash
adb devices
```

If it does not appear there, Relay cannot communicate with it.

For BlueStacks:

```bash
adb connect 127.0.0.1:5555
```

Then restart Relay or refresh the device list.

---

### Why does Relay show multiple devices?

Relay automatically detects all ADB and Fastboot devices connected to your system.

Use the device selector in the top bar to switch between devices.

---

## Screen Mirroring

### Does Relay use scrcpy?

Yes.

Relay uses scrcpy technology for screen mirroring and device control.

---

### Why is screen mirroring not working?

Check the following:

1. USB debugging is enabled.
2. The device is authorized.
3. The device appears in:

```bash
adb devices
```

4. Standalone scrcpy works.

If standalone scrcpy does not work, Relay cannot mirror the device.

---

### Why is the screen black?

This may happen when:

* Device authorization is missing
* The device screen is locked
* The device encoder is unsupported
* The renderer is unable to initialize

Check the Logs and Diagnostics panels for more information.

---

## Files

### Can I transfer files?

Yes.

Relay supports:

* Uploading files
* Downloading files
* Folder browsing
* Drag and drop transfers

---

### Does Relay require root access?

No.

Most features work without root.

Some advanced functionality may require elevated privileges depending on the device.

---

## Packages & APKs

### Can I install APK files?

Yes.

Relay can install APK files directly using ADB.

---

### Can I uninstall applications?

Yes.

Relay supports uninstalling user-installed applications.

System application removal may not be available on all devices.

---

### What is APK Lab?

APK Lab allows inspection of APK files without installing them.

Features include:

* Permission analysis
* Manifest viewing
* SDK inspection
* Component analysis

---

## Custom ROM Analysis

### Can Relay flash custom ROMs?

No.

Relay does not automatically flash ROMs.

Relay focuses on compatibility analysis and guidance.

---

### Can Relay unlock my bootloader?

No.

Relay does not perform bootloader unlocking.

Relay may analyze bootloader status and device compatibility.

---

### Can Relay root my device?

No.

Relay does not root devices.

---

### What does the ROM Analyzer do?

ROM Analyzer evaluates:

* Device codename
* Treble support
* A/B partitions
* Virtual A/B
* Recovery compatibility
* ROM readiness

It provides compatibility information only.

---

## Recovery & Fastboot

### Does Relay support Fastboot?

Yes.

Relay includes Fastboot utilities and diagnostics.

---

### Can Relay enter Fastboot mode?

Yes.

Relay can reboot supported devices into:

* Bootloader
* Recovery
* Fastboot

---

### Can Relay recover devices with broken screens?

Yes.

Relay includes a Headless Recovery mode designed for devices with damaged displays or touchscreens.

---

## Privacy & Security

### Does Relay collect my data?

Relay operates locally on your machine.

Refer to the project's privacy policy for specific details.

---

### Does Relay require an internet connection?

Most functionality works completely offline.

Some optional features may require internet access.

---

## Troubleshooting

### Relay cannot detect my phone.

Verify:

1. USB Debugging is enabled.
2. Developer Options are enabled.
3. The device is authorized.
4. ADB drivers are installed.
5. The device appears in:

```bash
adb devices
```

---

### Relay detects my phone but some features do not work.

Different Android manufacturers expose different APIs and capabilities.

Some features may be limited by:

* Device manufacturer
* Android version
* Security policies
* Bootloader state

---

### Where can I report bugs?

Open an issue in the project's repository and include:

* Device model
* Android version
* Relay version
* Logs
* Steps to reproduce

---

## Philosophy

### Why was Relay created?

Because Android users should not need five separate tools open just to manage one device.

If your device still has:

* A motherboard
* A USB port

Relay has your back.
