# Relay

> The Android Workstation for Windows.

## Documentation

- [FAQ](FAQ.md)
- [License](LICENSE)
- [Third Party Notices](THIRD_PARTY_NOTICES.md)
- [Releases](../../releases/latest)

---
<p align="center">
  <a href="https://github.com/sxwik/Relay/releases/latest">
    <img src="https://img.shields.io/badge/Download-Latest_Release-blue?style=for-the-badge" />
  </a>
</p>

Android Workstation for Control, Analysis, and Diagnostics.
---

## Quick Links

*  Documentation
*  FAQ
*  Installation
*  Supported Devices
*  Features
*  ROM Analysis
*  Troubleshooting

### Frequently Asked Questions

Before opening an issue, check the FAQ:

**[Open FAQ'S.md](./FAQ'S.md)**

The FAQ covers:

* Device detection issues
* BlueStacks and emulator support
* ADB troubleshooting
* Screen mirroring problems
* Fastboot questions
* ROM analysis questions
* File transfer issues
* Common setup mistakes

---

## Why Relay?

Relay combines ADB, scrcpy, Fastboot, file management, package management, device analysis, and Android workstation tools into a single desktop application.

## Features

### Device Management

* Automatic device detection
* USB and Wi-Fi ADB support
* Multi-device management
* Device switching dropdown
* Emulator support
* Device status monitoring
* Real-time connection tracking

### Screen Mirroring

* Integrated scrcpy-based screen mirroring
* Portrait and landscape detection
* Embedded device display
* Resolution-aware rendering
* Low-latency control
* Keyboard and mouse passthrough

### File Manager

* Browse device storage
* Drag and drop file transfers
* Upload files to device
* Download files from device
* Create folders
* Delete files
* Storage usage overview

### Package Manager

* List installed applications
* User and system app filtering
* Install APK files
* Launch applications
* Force stop applications
* Uninstall applications

### Terminal

* Integrated ADB shell
* Command history
* Session logging
* Export terminal logs
* Direct device interaction

### Device Control

* Home
* Back
* Recents
* Power
* Volume controls
* Screen rotation
* Text injection
* Keyboard triggering

### Clipboard Continuity

* Clipboard synchronization
* Quick copy and paste workflows
* Cross-device text transfer

### Notification Center

* Device notification access
* Notification history
* Quick notification actions

### Camera Access

* Remote camera viewing
* Device camera integration
* Quick capture tools

---

## Advanced Tools

### Fastboot Toolkit

* Device detection
* Reboot to bootloader
* Reboot to recovery
* Fastboot information
* Partition inspection
* Recovery environment utilities

### Headless Recovery

Designed for damaged devices.

* Screen-off device management
* D-Pad navigation
* Text injection
* Custom keycodes
* Touch event injection
* Recovery interaction

### Logcat Viewer

* Live log streaming
* Log filtering
* Search functionality
* Tag filtering
* Export support

---

## Device Intelligence

### Hardware Analysis

Relay can analyze:

* CPU
* GPU
* RAM
* Storage
* Sensors
* Camera capabilities
* Display specifications
* Android version
* Security patch level

### Battery Health

* Battery temperature
* Charging state
* Capacity analysis
* Usage statistics
* Health indicators

### Performance Monitor

* CPU usage
* RAM usage
* Storage utilization
* Device temperature
* Runtime statistics

---

## ROM Analysis

Relay can analyze Android devices and determine:

* Device codename
* Treble compatibility
* A/B partition support
* Virtual A/B support
* Bootloader status
* Recovery compatibility
* ROM readiness

### Compatibility Reports

Relay can generate compatibility reports for custom ROMs and provide:

* Supported devices
* Required Android version
* Known issues
* Feature compatibility
* Installation requirements

**Note:** Relay does not automatically unlock bootloaders, root devices, or flash custom ROMs.

Relay is an analysis and guidance platform.

---

## APK Lab

Analyze APK files without installation.

Features:

* Manifest inspection
* Permission analysis
* SDK information
* Package information
* Activity inspection
* Service inspection
* Native library analysis

---

## Device Timeline

Track device history including:

* Connections
* Updates
* Storage changes
* Device events
* System activity

---

## Supported Devices

Relay supports:

* Android phones
* Android tablets
* Android emulators
* USB-connected devices
* Wi-Fi ADB devices

Tested with:

* Xiaomi devices
* POCO devices
* Samsung devices
* Android emulators
* BlueStacks

---

## Built With

* Electron
* React
* TypeScript
* TailwindCSS
* ADB
* scrcpy
* Fastboot

---

## Philosophy

Relay exists because Android users deserve a unified workstation experience.

If your device still has:

* A motherboard
* A USB port

Relay has your back.

---

## Status

Relay V1 is under active development.

Current focus:

* Embedded renderer
* Device intelligence
* ROM analysis
* APK Lab
* Continuity features

---

## License

Relay is proprietary software developed by sxwik.

Copyright © 2026 sxwik. All rights reserved.

Relay includes third-party components:

* scrcpy (Genymobile)
* Android SDK Platform Tools (Google)

These components remain the property of their respective authors and are subject to their own licenses.

See `LICENSE` and `THIRD_PARTY_NOTICES.md` for details.

---

## Credits

Relay was created and developed by **sxwik**.

GitHub: https://github.com/sxwik

---

## Disclaimer

Relay is intended for device management, diagnostics, development, testing, and research purposes.

Users are responsible for any actions performed on their devices. Always create backups before modifying system software, unlocking bootloaders, flashing firmware, or performing recovery operations.

---

**Relay v1.0.0** • Android Workstation for Windows

