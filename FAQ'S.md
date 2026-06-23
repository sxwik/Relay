# Frequently Asked Questions (FAQ)

## What is Relay?

Relay is an Android workstation for Windows that combines screen mirroring, device diagnostics, ROM compatibility analysis, APK inspection, file management, and Android development tools into a single application.

---

## Does Relay require root?

No.

Most Relay features work through Android Debug Bridge (ADB) and do not require root access.

Some advanced device information may be available only on rooted devices.

---

## Does Relay support wireless devices?

Yes.

Relay supports:

* USB Debugging
* Wireless ADB
* ADB over TCP/IP

Wireless devices will appear in the device selector once connected.

---

## Does Relay support Android emulators?

Yes.

Relay supports most ADB-compatible emulators including:

* BlueStacks
* LDPlayer
* Android Studio Emulator
* MuMu Player
* Other ADB-compatible emulators

---

## Why won't my device appear in Relay?

Check the following:

1. USB Debugging is enabled.
2. The device is authorized.
3. ADB detects the device.
4. The USB cable supports data transfer.

You can verify detection using:

adb devices

---

## Why does screen mirroring open a native window?

Relay uses the native scrcpy renderer for maximum performance and compatibility.

This provides:

* Lower latency
* Better hardware acceleration
* Reliable keyboard support
* Reliable mouse support

---

## What is UHID mode?

UHID allows Relay to emulate real keyboard and mouse hardware.

This improves compatibility with many physical Android devices.

Most emulators do not require UHID.

---

## Can Relay unlock my bootloader?

No.

Relay can analyze bootloader status and device capabilities but does not bypass manufacturer restrictions.

---

## Can Relay flash custom ROMs?

No.

Relay currently provides ROM compatibility analysis and device intelligence.

Flashing firmware remains the responsibility of the user.

Always create backups before modifying device software.

---

## Is APK Lab accurate?

APK Lab is currently experimental.

Results are generated using static APK analysis and heuristics.

Some applications may:

* Obfuscate information
* Dynamically register components
* Hide activities
* Restrict metadata

APK Lab results should be considered informational.

---

## Why does APK Lab show a high risk score?

The risk engine is experimental.

Applications with many permissions, network access, or background components may receive elevated scores.

A high score does not necessarily indicate malware.

---

## Does Relay collect data?

No.

Relay performs analysis locally on your computer and connected devices.

Relay does not upload device information to external servers.

---

## Is Relay open source?

No.

Relay is proprietary software developed by sxwik.

The source code is not publicly available.

---

## What operating systems are supported?

Currently:

* Windows 10
* Windows 11

---

## Where can I download Relay?

Official releases are available from the GitHub Releases page.

Always download Relay from official sources.

---

## I found a bug. What should I do?

Open an issue on the Relay GitHub repository and include:

* Relay version
* Device model
* Android version
* Steps to reproduce the issue
* Screenshots if available

---

## Can Relay recover a bricked device?

Not currently.

Future versions may include additional diagnostic and recovery tools.

---

## Is Relay safe?

Relay executes commands only on devices that you explicitly connect and authorize.

Always review actions before modifying device software.
