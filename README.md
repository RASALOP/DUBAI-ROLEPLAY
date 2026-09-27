<div align="center">

# DUBAI ROLEPLAY — Test Script

### *Developed, Tested & Maintained by the Dubai Roleplay Team*

[![SA-MP](https://img.shields.io/badge/SA--MP%20%2F%20open.mp-Compatible-2d6a4a?style=flat-square&logo=sa-mp)](https://sa-mp.net)
[![PAWN](https://img.shields.io/badge/PAWN-3.10-blue?style=flat-square)](https://www.compuphase.com/pawn/pawn.htm)
[![MySQL](https://img.shields.io/badge/MySQL-Supported-00627A?style=flat-square&logo=mysql)](https://www.mysql.com)
[![Version](https://img.shields.io/badge/Release-V1-4287f5?style=flat-square)](#-project-structure)

</div>

---

## 📖 About

**Dubai Roleplay** is a SA-MP multiplayer roleplay project built around a customised Malayalam roleplay
experience, featuring unique gameplay systems, custom mappings, and continuous development.

This repository holds the **complete PAWN script** used for the testing and ongoing development of Dubai
Roleplay, together with the **original Dubai Roleplay mappings** and the related development resources
required to build and run the server.

> **Purpose** — development, testing, learning and project reference.

---

## ✨ Features

| | |
|---|---|
| 🎮 **Complete PAWN Roleplay Script** | Full-featured gamemode with jobs, houses, businesses, banks, vehicles and more |
| 🗺️ **Original Dubai Roleplay Mappings** | Custom, hand-built map and interior mapping system |
| ⚙️ **Custom Roleplay Systems** | Faction, property, economy, documentation and progression systems |
| 💬 **Custom Commands & Features** | Extended command set, selection menus, dialogs and anti-abuse protections |
| 🛡️ **Anti-Cheat & Stability** | Crash detection, native checking, anti-teleport and anti-cheat layers |
| 🗄️ **MySQL Driven** | Fully database-backed accounts, properties, businesses and vehicles |
| 🧩 **Organised Development Structure** | Clean gamemode / filterscript / scriptfile separation |
| 🔄 **Continuous Improvements** | Actively developed — new systems, fixes and features land regularly |

---

## 👑 Project Management

### Owners

| Owner | Handle |
| :---: | :---: |
| Rasal | **Rasal** |
| Kannappi | **Kannappi** |
| Sachu | **Sachu** |
| David | **David** |

### 💻 Script Developer

| Role | Name |
| :--- | :--- |
| **Script Developer & Maintainer** | **Rasal** |

The PAWN script in this repository was developed, documented and maintained by **Rasal** for the
Dubai Roleplay project.

---

## 🗺️ Original Mappings

The repository includes the **original Dubai Roleplay mappings** created and used by the project
(`filterscripts/mapping.pwn`, with 275 registered static objects and full interior definitions).

These mappings are part of the Dubai Roleplay development environment and are designed to work
alongside the provided script out of the box.

---

## 🛠️ Technologies

- **PAWN** (Pawn 3.10 compiler, bundled in `pawno/`)
- **SA-MP / open.mp**
- **MySQL** (`mysql_static` plugin)
- Custom SA-MP systems and filterscripts
- Custom mappings and map assets
- PAWN includes and server plugins (streamer, sscanf, SKY, sampvoice, and more)

---

## 📁 Project Structure

```text
Dubai-Roleplay/
├── gamemodes/            # Main gamemode and modules (DURP.pwn, anims.pwn)
├── filterscripts/        # Filterscripts & original Dubai Roleplay mappings
├── scriptfiles/          # Text / INI data (vehicles, properties, server info)
├── plugins/              # Server plugins (.so / .dll)
├── pawno/                # PAWN compiler, includes and libraries
├── server.cfg            # Server configuration
├── samp03svr            # SA-MP server binary
├── samp-npc              # NPC plugin binary
├── announce              # Server announcement file
└── README.md
```

> The exact folder structure may change between versions of the test script.

---

## 🚀 Getting Started

1. **Install the server files** — extract the repository into your SA-MP server directory.
2. **Start MySQL** and import/create your database, then set the connection details in the script.
3. **Compile** — open `gamemodes/DURP.pwn` and `filterscripts/DURP.pwn` with the bundled PAWN compiler
   (`pawno/pawnc.exe`), or build them from the command line:

   ```bash
   pawncc gamemodes\DURP.pwn
   pawncc filterscripts\DURP.pwn
   ```

4. **Configure** `server.cfg` — plugins, gamemode and filterscripts are already wired up.
5. **Run** the server with `samp03svr.exe` and connect with SA-MP 0.3.DL / open.mp client.

---

## 📈 Development Status

Dubai Roleplay is an actively developed project. New systems, improvements, fixes, mappings and
features are added over time.

This repository represents a **test / development version** and may contain unfinished or
experimental features.

---

## ⚠️ Important Notice

- This repository is related to the **Dubai Roleplay** project.
- Please **do not remove or modify** the original developer and project credits when using or
  modifying this source.
- If you use parts of this project in another server or project, please provide **appropriate
  credit** to the original developers and creators.
- This script is provided for **educational, testing and development purposes only**. Any commercial
  or public redistribution requires prior permission from the Dubai Roleplay owners.

---

## 📜 Credits

**DUBAI ROLEPLAY**

**Owners:** Rasal • Kannappi • Sachu • David

**Script Developer:** Rasal

**Original Mappings:** Dubai Roleplay Development Team

---

<div align="center">

### ❤️ Dubai Roleplay

*Built with passion for the SA-MP Roleplay community.*

**DUBAI ROLEPLAY — Developed, Tested & Maintained by the Dubai Roleplay Team.**

`© 2025 Dubai Roleplay. All Rights Reserved.`

</div>
