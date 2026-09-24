# LiteWing Blockly

[![Latest Release](https://img.shields.io/github/v/release/Circuit-Digest/LiteWing-Blockly?color=orange&label=Latest%20Release)](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Circuit-Digest/LiteWing-Blockly/total?color=blue&label=Downloads)](https://github.com/Circuit-Digest/LiteWing-Blockly/releases)
[![Platform Windows](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20%2864--bit%29-0078D6?logo=windows)](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest)
[![Platform macOS](https://img.shields.io/badge/Platform-macOS%20ARM64%20%28Apple%20Silicon%29-000000?logo=apple)](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest)
[![Documentation](https://img.shields.io/badge/Wiki-Circuit%20Digest%20Wiki-f59e0b)](https://circuitdigest.com/wiki/litewing-blockly-wiki-page/#Introduction)
[![License: Freeware](https://img.shields.io/badge/License-Freeware%20%2F%20EULA-blue.svg)](LICENSE)

LiteWing Blockly is the visual block-based programming environment for the **LiteWing Drone**. It allows learners to program autonomous drone flights using intuitive drag-and-drop blocks while simultaneously generating clean, real-time Python code compatible with the official `litewing` library.

This repository serves as the official distribution channel for pre-compiled, standalone release binaries.

---

## Download Official Release

Pre-compiled standalone packages are available for Windows (64-bit) and macOS (Apple Silicon ARM64). No installation of Python, Node.js, or external development dependencies is required.

### Windows (64-bit)

| Package | Format | Direct Download | SHA-256 Checksum |
| :--- | :---: | :---: | :--- |
| **LiteWing Blockly Standalone** | Portable `.exe` | [**Download**](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest/download/LiteWingBlockly.exe) | `c30f2d18a8fecddb04adb662eb707238ba26850ac4e39f67e439b3da79292498` |
| **LiteWing Blockly Bundle** | Compressed `.zip` | [**Download**](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest/download/LiteWingBlockly-v1.0.0-windows-x64.zip) | `26bdc298f05b2374ea352ee69f0e275ef18fbda52c3745160ea4e8436776f61f` |

### macOS (Apple Silicon M1 / M2 / M3 / M4)

| Package | Format | Direct Download | SHA-256 Checksum |
| :--- | :---: | :---: | :--- |
| **LiteWing Blockly Installer** | Apple Disk Image `.dmg` | [**Download**](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest/download/LiteWingBlockly-v1.0.0-macos-arm64.dmg) | `b4afdcd870e5406e21847530ba3eed868959351c1bd32cb6ccbeb04ce83d5251` |
| **LiteWing Blockly Archive** | Compressed `.zip` | [**Download**](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest/download/LiteWingBlockly-v1.0.0-macos-arm64.zip) | `68bc47642517ab4a3542aeb9582272d0f6283768849f38d4177fca6ac3ce1b84` |

> [!NOTE]
> **First-Time Launch on macOS (Apple Silicon)**:
> 1. Drag **LiteWingBlockly** into your **Applications** folder.
> 2. If macOS displays *"Apple cannot verify that this app is free from malware"*, click **Done**.
> 3. Open **System Settings  &rarr; Privacy & Security**, scroll down to the **Security** section, and click **Open Anyway**.
> 4. You only need to do this once. The app will open directly thereafter.

> [!TIP]
> All versioned releases, release notes, changelogs, and asset downloads are available on the [**GitHub Releases Page**](https://github.com/Circuit-Digest/LiteWing-Blockly/releases).

---

## Official Documentation and Wiki

For step-by-step connection tutorials, block reference catalogs, and sensor telemetry guides, visit the official documentation:

**[LiteWing Blockly Wiki Page](https://circuitdigest.com/wiki/litewing-blockly-wiki-page/#Introduction)**

---

## System Requirements

- **Windows:** Windows 10 or Windows 11 (64-bit)
- **macOS:** macOS 12 (Monterey), 13 (Ventura), 14 (Sonoma), or 15 (Sequoia) on Apple Silicon (M1, M2, M3, M4)
- **Wi-Fi Connectivity:** Computer Wi-Fi adapter to connect to the LiteWing drone access point (`LiteWing_XXXXXXXXXXXX`)
- **Hardware:** LiteWing Drone with Drone Positioning Module (Time of Flight height sensor & Optical Flow sensor) installed
- **Firmware:** LiteWing firmware **v3.0.0 or later**

---

## Related Repositories

- **LiteWing Hardware & Firmware:** [Circuit-Digest/LiteWing](https://github.com/Circuit-Digest/LiteWing.git)
- **LiteWing Python Library:** [Circuit-Digest/LiteWing-Library](https://github.com/Circuit-Digest/LiteWing-Library.git)
- **Positioning Module Guide:** [Drone Positioning Module Installation](https://circuitdigest.com/wiki/litewing-drone-positioning-module/)

---

## License and Terms of Use

LiteWing Blockly is distributed free of charge as a pre-compiled binary executable for educational, personal, and research drone operations. See the [LICENSE](LICENSE) file for the complete terms and conditions.

- **LiteWing Blockly Application:** Copyright (c) 2026 Dharagesh and Circuit Digest. All rights reserved.
- **Visual Programming Engine:** Built with [Google Blockly](https://developers.google.com/blockly) (Licensed under the Apache License, Version 2.0).
