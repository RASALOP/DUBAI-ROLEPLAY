<div align="center">

# 🇦🇪 DUBAI ROLEPLAY

### Test Script & Development Repository

**A full SA-MP / PAWN roleplay script with original Dubai Roleplay mappings, custom systems, and a complete development environment.**

[![Release](https://img.shields.io/badge/Release-V1-4287f5?style=flat-square)](#-development)
[![SA-MP](https://img.shields.io/badge/SA--MP%20%2F%20open.mp-2d6a4a?style=flat-square&logo=sa-mp)](https://sa-mp.net)
[![PAWN](https://img.shields.io/badge/PAWN-3.10%20Compiler-blue?style=flat-square)](https://www.compuphase.com/pawn/pawn.htm)
[![MySQL](https://img.shields.io/badge/MySQL-Supported-00627A?style=flat-square&logo=mysql)](https://www.mysql.com)
[![License](https://img.shields.io/badge/License-Credits%20Required-cc3333?style=flat-square)](#%EF%B8%9F-important-information)

</div>

---

## 📖 Overview

Welcome to the official **Dubai Roleplay Test Script** repository.

This repository contains the complete **PAWN script** used for the development and testing of
**Dubai Roleplay**, together with the project's **original mappings** and all related development
resources required to build, run and customise the server.

> **Repository purpose** — development · testing · learning · customization · project reference

| | |
| :-- | :-- |
| **Project** | Dubai Roleplay |
| **Platform** | SA-MP / open.mp |
| **Language** | PAWN (Pawn 3.10) |
| **Database** | MySQL |
| **Release** | V1 |
| **Script Developer** | Rasal |
| **Mappings** | Dubai Roleplay Development Team |

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Management](#-duba-i-roleplay-management)
- [Original Mappings](#%EF%B8%8F-original-dubai-roleplay-mappings)
- [Technologies](#%EF%B8%8F-technologies--development)
- [Repository Structure](#-repository-structure)
- [Getting Started](#-getting-started)
- [Development](#-development)
- [Important Information](#%EF%B8%9F-important-information)
- [Credits](#-project-credits)

---

## 🎮 About the Project

**Dubai Roleplay** is a SA-MP roleplay project focused on delivering a customized **Malayalam
roleplay experience** — with unique gameplay systems, custom-built mappings, and continuous
development driven by community feedback.

The project is designed around structured, self-managed gameplay: every faction, property, business
and vehicle is configured through editable data files, which keeps the server easy to maintain and
expand.

---

## ✨ Features

| Area | Details |
| :-- | :-- |
| 🎮 **Full PAWN Roleplay Script** | Complete roleplay gamemode with factions, housing, businesses, banks and vehicles |
| 🗺️ **Original Dubai Roleplay Mappings** | Custom, hand-built mapping and interior system included with the script |
| ⚙️ **Custom Roleplay Systems** | Job & faction duty, property ownership, business management, economy and progression |
| 💬 **Custom Commands & Features** | Extended command set, selection menus, dialogs and admin tooling |
| 🗄️ **MySQL Driven** | Fully database-backed accounts, properties, businesses and vehicle data |
| 🧩 **Structured Script** | Clean separation of gamemode, filterscripts and text/INI data files |
| 🔄 **Continuous Updates** | Regular improvements, optimisations and new systems |
| 🧪 **Development Ready** | Complete test environment for learning, testing and customization |

---

## 👑 Dubai Roleplay Management

### Owners

| Owner | Handle |
| :---: | :--- |
| 👤 | **Rasal** |
| 👤 | **Kannappi** |
| 👤 | **Sachu** |
| 👤 | **David** |

### 💻 Script Developer

| Role | Name |
| :-- | :-- |
| **Script Developer & Maintainer** | **Rasal** |

The PAWN script included in this repository was **developed and maintained by Rasal** as part of the
Dubai Roleplay project.

---

## 🗺️ Original Dubai Roleplay Mappings

This repository includes the **original Dubai Roleplay mappings** created and used as part of the project.

The mappings are designed to work alongside the provided script out of the box and form a core part of
the project's custom development environment.

> Mappings are original project assets. Please do not redistribute or repurpose them without the
> permission of the Dubai Roleplay owners.

---

## 🛠️ Technologies & Development

The project is built using a combination of SA-MP development technologies and custom resources:

| Layer | Technology |
| :-- | :-- |
| **Language** | PAWN |
| **Platform** | SA-MP / open.mp |
| **Database** | MySQL |
| **Game Logic** | Custom SA-MP Systems |
| **World** | Custom Mappings |
| **Tooling** | PAWN Includes |
| **Runtime** | SA-MP Plugins |

---

## 📁 Repository Structure

```text
Dubai-Roleplay/
│
├── gamemodes/            # Main gamemode and script modules
├── filterscripts/        # Filterscripts and original Dubai Roleplay mappings
├── includes/             # Custom PAWN includes used by the script
├── mappings/             # Mapping data and original map resources
├── scriptfiles/          # Vehicles, properties, businesses, banks, server info
├── pawno/                # PAWN 3.10 compiler, includes and libraries
├── plugins/              # Server plugins (.so / .dll)
├── server.cfg            # Server configuration
└── README.md
```

> The repository structure may vary depending on the version and development stage of the test script.

---

## 🚀 Getting Started

### Requirements

| Requirement | Version |
| :-- | :-- |
| SA-MP / open.mp Server | 0.3.DL / 0.3.7 |
| PAWN Compiler | 3.10 (bundled in `pawno/`) |
| MySQL Server | 5.x / 8.x |

### Installation

1. **Install the server files** — extract the repository into your SA-MP / open.mp server directory.
2. **Configure the database** — start MySQL, create the database and set the connection details inside
   the script.
3. **Compile the script** — open `gamemodes/DURP.pwn` with the bundled compiler, or build from the
   command line:

   ```bash
   pawncc gamemodes\DURP.pwn
   pawncc filterscripts\DURP.pwn
   ```

4. **Review `server.cfg`** — gamemode, filterscripts and plugins are pre-configured for the test
   environment.
5. **Start the server** — run `samp03svr.exe` and connect with the SA-MP 0.3.DL or open.mp client.

---

## 🛠️ Development

**Dubai Roleplay** is an actively developed project.

The development process includes new systems, gameplay improvements, bug fixes, mapping updates,
performance optimizations, and additional features.

This repository represents a **test and development version** of the project. Some systems or features
may be unfinished, experimental, or subject to change.

---

## ⚠️ Important Information

This repository is associated with the **Dubai Roleplay project** and contains project-specific
development work.

- Please **preserve the original project and developer credits** when using or modifying any part of the
  source.
- If portions of this project are used within another server or project, **appropriate credit must be
  given** to the original developers and creators.
- Original mappings, artwork and scripts may **not be resold or redistributed** without written
  permission from the Dubai Roleplay owners.
- This project is published for **educational, testing and development purposes only**.

---

## 📜 Project Credits

### Dubai Roleplay

**Owners**

> Rasal • Kannappi • Sachu • David

**Script Developer**

> Rasal

**Original Mappings**

> Dubai Roleplay Development Team

---

## ❤️ Dubai Roleplay

Built with dedication for the **SA-MP Roleplay community**.

> **Dubai Roleplay — Developed, Tested & Maintained by the Dubai Roleplay Team.**

---

<div align="center">

**© 2025 Dubai Roleplay. All Rights Reserved.**

</div>
