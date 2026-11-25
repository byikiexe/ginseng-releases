# Changelog

All notable changes to Ginseng will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project follows [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [0.1.1] - 2026-11-24

### Added

- Single-instance enforcement using the official Tauri single-instance plugin.
- D-Bus session interface for communication between application instances on Linux.

### Improved

- Existing window restoration when launching Ginseng while another instance is already running.
- Application lifecycle management on Linux.

### Fixed

- Duplicate application processes when launching Ginseng multiple times.
- Duplicate system tray icons caused by multiple application instances.

## [0.1.0]

### Added

- Initial version of Ginseng.
- Keep-awake functionality to prevent automatic screen locking due to inactivity.
- Awake and Sleeping application states.
- Configurable session duration.
- Unlimited keep-awake mode.
- Countdown timer and session progress indicator.
- System tray integration.
- Background operation when the application window is closed.
- Automatic release of idle inhibition when a timed session ends.
- Linux GNOME idle inhibition support.
- Custom pixel-art mascot with Awake and Sleeping states.
- Lightweight desktop interface built with Tauri, Vue and TypeScript.
- Linux installation packages.

---

Developed and maintained by [byiki.exe](https://byikiexe.com).
