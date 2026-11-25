
# 🌱 Ginseng

**Stay awake. Stay focused.**

Ginseng is a lightweight desktop utility that keeps your
computer awake when you need it, preventing automatic
screen locking due to inactivity.

Built for developers, creators and anyone who wants
more control over their desktop experience.

Developed and maintained by [byiki.exe](https://byikiexe.com).

---

## Features

- Prevent automatic screen locking.
- Configurable keep-awake sessions.
- Unlimited awake mode.
- Countdown timer and progress indicator.
- System tray integration.
- Lightweight background operation.
- Automatic deactivation when a session ends.
- Custom pixel-art mascot with Awake and Sleeping states.

## Downloads

Ginseng is currently available for Linux.

| Platform | Package | Status |
|----------|---------|--------|
| Debian / Ubuntu | `.deb` | Available |
| Linux | `.snap` | Available |
| Snap Store | Snap | Under review |
| Windows | Installer | Planned |

### [Download the latest release](https://github.com/byikiexe/ginseng-releases/releases/latest)

## Installation

### Debian / Ubuntu

Download the `.deb` package from the latest release
and install it using:

```bash
sudo apt install ./ginseng_*.deb
```

### Snap

Download the `.snap` package from the latest release
and install it using:

```bash
sudo snap install --dangerous ./ginseng_*.snap
```

The `--dangerous` flag is required when installing
a local Snap package without a store assertion.

Official Snap Store distribution is currently
under review.

## Getting started

1. Launch Ginseng.
2. Select your preferred session duration.
3. Enable Keep awake.
4. Continue working while Ginseng runs in the background.

Ginseng automatically returns to its Sleeping state
when the selected session ends.

You can also stop an active session manually at any time.

## Technology

Ginseng is built using:

- Tauri
- Rust
- Vue 3
- TypeScript

Designed to provide a lightweight desktop experience
without unnecessary complexity.

## Release notes

See the [Changelog](CHANGELOG.md) for version history,
improvements and bug fixes.

## About this repository

This repository is the official public distribution
channel for Ginseng.

It contains installation packages, release notes
and product documentation.

Ginseng is proprietary software. Its source code
is maintained in a separate private repository
and is not publicly distributed.

## License

Ginseng is currently free to use and is distributed
under a proprietary software license.

See the [LICENSE](LICENSE) file for the full terms
and conditions.

Copyright © 2026 byiki.exe. All rights reserved.

## Contact

For feedback, support or licensing inquiries:

- Website: [byikiexe.com](https://byikiexe.com)
- Email: [contacto@byikiexe.com](mailto:contacto@byikiexe.com)

---

Made with curiosity and care by **byiki.exe**.
