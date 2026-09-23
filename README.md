```text
██╗      ██╗ ████████╗ ███████╗ ██╗    ██╗ ██╗ ███╗   ██╗  ██████╗     ██████╗  ██╗       ██████╗   ██████╗ ██╗  ██╗ ██╗      ██╗   ██╗
██║      ██║ ╚══██╔══╝ ██╔════╝ ██║    ██║ ██║ ████╗  ██║ ██╔════╝     ██╔══██╗ ██║      ██╔═══██╗ ██╔════╝ ██║ ██╔╝ ██║      ╚██╗ ██╔╝
██║      ██║    ██║    █████╗   ██║ █╗ ██║ ██║ ██╔██╗ ██║ ██║  ███╗    ██████╔╝ ██║      ██║   ██║ ██║      █████═╝  ██║       ╚████╔╝ 
██║      ██║    ██║    ██╔══╝   ██║███╗██║ ██║ ██║╚██╗██║ ██║   ██║    ██╔══██╗ ██║      ██║   ██║ ██║      ██╔═██╗  ██║        ╚██╔╝  
███████╗ ██║    ██║    ███████╗ ╚███╔███╔╝ ██║ ██║ ╚████║ ╚██████╔╝    ██████╔╝ ███████╗ ╚██████╔╝ ╚██████╗ ██║ ╚██╗ ███████╗    ██║   
╚══════╝ ╚═╝    ╚═╝    ╚══════╝  ╚══╝╚══╝  ╚═╝ ╚═╝  ╚═══╝  ╚═════╝     ╚═════╝  ╚══════╝  ╚═════╝   ╚═════╝ ╚═╝  ╚═╝ ╚══════╝    ╚═╝   
```

# LiteWing Blockly

[![Latest Release](https://img.shields.io/github/v/release/Circuit-Digest/LiteWing-Blockly?color=orange&label=Latest%20Release)](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Circuit-Digest/LiteWing-Blockly/total?color=blue&label=Downloads)](https://github.com/Circuit-Digest/LiteWing-Blockly/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(64--bit)-0078D6?logo=windows)](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest)
[![Documentation](https://img.shields.io/badge/Wiki-Circuit%20Digest%20Wiki-f59e0b)](https://circuitdigest.com/wiki/litewing-blockly-wiki-page/#Introduction)
[![License: Freeware](https://img.shields.io/badge/License-Freeware%20%2F%20EULA-blue.svg)](LICENSE)

LiteWing Blockly is the official visual block-based programming environment for the **LiteWing Drone**. It allows learners, hobbyists, and researchers to program autonomous drone flights using intuitive drag-and-drop blocks while simultaneously generating clean, real-time Python code compatible with the official `litewing` library.

This repository serves as the official distribution channel for pre-compiled, standalone release binaries.

---

## 🚀 Download Official Release

The application is distributed as a portable standalone Windows executable. It requires no installation of Python, Node.js, or external development dependencies.

| Package | Format | Direct Download | SHA-256 Checksum |
| :--- | :---: | :---: | :--- |
| **LiteWing Blockly Standalone** | Portable `.exe` | [⬇ **Download .exe**](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest/download/LiteWingBlockly.exe) | `c30f2d18a8fecddb04adb662eb707238ba26850ac4e39f67e439b3da79292498` |
| **LiteWing Blockly Bundle** | Compressed `.zip` | [⬇ **Download .zip**](https://github.com/Circuit-Digest/LiteWing-Blockly/releases/latest/download/LiteWingBlockly-v1.0.0-windows-x64.zip) | `26bdc298f05b2374ea352ee69f0e275ef18fbda52c3745160ea4e8436776f61f` |

> [!TIP]
> All versioned releases, release notes, changelogs, and asset downloads are available on the [**GitHub Releases Page**](https://github.com/Circuit-Digest/LiteWing-Blockly/releases).

---

## 📖 Official Documentation & Wiki

For step-by-step connection tutorials, block reference catalogs, sensor telemetry guides, and flight safety rules, visit the official documentation:

👉 **[LiteWing Blockly Wiki Page](https://circuitdigest.com/wiki/litewing-blockly-wiki-page/#Introduction)**

---

## ⚙️ System Requirements

- **Operating System:** Windows 10 or Windows 11 (64-bit)
- **Wi-Fi Connectivity:** Computer Wi-Fi adapter to connect to the LiteWing drone access point (`LiteWing_XXXXXXXXXXXX`)
- **Hardware:** LiteWing Drone with Drone Positioning Module (Time of Flight height sensor & Optical Flow sensor) installed
- **Firmware:** LiteWing firmware **v3.0.0 or later**

---

## 🛠️ Quick Start Guide

1. **Power on the Drone:** Place LiteWing on a flat, well-lit surface and power it on. Wait for the Drone Positioning Module LED to turn solid green.
2. **Connect to Wi-Fi:** Open Windows Wi-Fi settings and connect to your drone's access point (e.g. `LiteWing_F412FAB64AB9`).
3. **Launch LiteWing Blockly:** Run `LiteWingBlockly.exe`.
4. **Connect in App:** Ensure the drone IP is set to `192.168.43.42` in the bottom status bar and click **Connect**.
5. **Program & Fly:** Drag blocks from the toolbox (e.g., `when run clicked` &rarr; `takeoff` &rarr; `fly forward` &rarr; `land`), and click **▶ Run code** to begin autonomous flight!

---

## 🔗 Related Repositories

- **LiteWing Hardware & Firmware:** [Circuit-Digest/LiteWing](https://github.com/Circuit-Digest/LiteWing.git)
- **LiteWing Python Library:** [Circuit-Digest/LiteWing-Library](https://github.com/Circuit-Digest/LiteWing-Library.git)
- **Positioning Module Guide:** [Drone Positioning Module Installation](https://circuitdigest.com/wiki/litewing-drone-positioning-module/)

---

## 📄 License & Terms of Use

LiteWing Blockly is distributed free of charge as a pre-compiled binary executable for educational, personal, and research drone operations. See the [LICENSE](LICENSE) file for the complete terms and conditions.

- **LiteWing Blockly Application:** Copyright © 2026 Circuit Digest. All rights reserved.
- **Visual Programming Engine:** Built with [Google Blockly](https://developers.google.com/blockly) (Licensed under the Apache License, Version 2.0).
