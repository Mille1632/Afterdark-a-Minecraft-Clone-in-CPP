<div align="center">

<img src="https://raw.githubusercontent.com/Gooseymille10/Afterdark-a-Minecraft-Clone-in-CPP/main/images/ScreenshotLOGO.png" alt="AfterDark Logo" width="480"/>

# AfterDark™

**A Minecraft-inspired voxel game built from scratch in C++ using raylib.**

[![Build](https://img.shields.io/badge/build-beta-lightgrey)](https://github.com/Gooseymille10/Afterdark-a-Minecraft-Clone-in-CPP/releases)
[![License](https://img.shields.io/badge/license-LPRL-blueviolet)](https://github.com/Gooseymille10/Afterdark-a-Minecraft-Clone-in-CPP/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%20x64-blue)](https://github.com/Gooseymille10/Afterdark-a-Minecraft-Clone-in-CPP/blob/main/afterdarkrl.exe)
[![Platform](https://img.shields.io/badge/platform-Linux%20x64-yellow)](https://github.com/Gooseymille10/Afterdark-a-Minecraft-Clone-in-CPP/blob/main/after_dark)

</div>

---

## Table of Contents

- [About](#about)
- [Screenshots](#screenshots)
- [Features](#features)
- [Getting Started](#getting-started)
- [Controls](#controls)
- [Dependencies](#dependencies)
- [License](#license)

---

## About

AfterDark is a fully self-contained voxel sandbox game written in C++ with [raylib](https://github.com/raysan5/raylib) as its only dependency. No engine. No middleware. Just C++, OpenGL, and a voxel world to explore.

The project started as PyCraft — a Python-based Minecraft launcher — and evolved into this: a ground-up reimplementation of the Minecraft experience with its own renderer, terrain engine, and game logic.

> ⚠️ **AfterDark is currently in Beta.** Expect occasional bugs. Report them in [Issues](https://github.com/Gooseymille10/Afterdark-a-Minecraft-Clone-in-CPP/issues).

---

## Screenshots

<div align="center">

| | |
|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Gooseymille10/Afterdark-a-Minecraft-Clone-in-CPP/main/images/Screenshot1.png" width="420"/> | <img src="https://raw.githubusercontent.com/Gooseymille10/Afterdark-a-Minecraft-Clone-in-CPP/main/images/Screenshot2.png" width="420"/> |

</div>

---

## Features

- 🌍 **Infinite procedurally generated voxel terrain** — no two worlds are the same
- 💡 **Real-time dynamic lighting and shadows**
- 🌊 **Water physics** with depth-based shading
- ⚡ **Async chunk generation** for smooth, stutter-free exploration
- 🎒 **In-game inventory system** and pause menu
- 💾 **Save/Load system** for persistent worlds
- 🖱️ **Keyboard & mouse controls** with adjustable sensitivity
- 🖥️ **Cross-platform** — native binaries for Windows x64 and Linux x64

---

## Getting Started

No build step required. Just grab the binary for your platform and run it.

### Windows

1. Download **`afterdarkrl.exe`** from this repository.
2. Make sure [raylib](https://github.com/raysan5/raylib) is installed (or its DLLs are alongside the executable).
3. Double-click `afterdarkrl.exe` to launch.

### Linux

1. Download **`after_dark`** from this repository.
2. Make sure raylib is installed on your system:
   ```bash
   # Debian/Ubuntu
   sudo apt install libraylib-dev

   # Arch
   sudo pacman -S raylib
   ```
3. Mark the binary as executable and run it:
   ```bash
   chmod +x after_dark
   ./after_dark
   ```

---

## Controls

| Action | Input |
|--------|-------|
| Move Forward | `W` |
| Move Backward | `S` |
| Strafe Left | `A` |
| Strafe Right | `D` |
| Jump | `Space` |
| Look Around | Mouse |
| Place Block | Left Click |
| Remove Block | Right Click |
| Pause Menu | `Esc` |

---

## Dependencies

AfterDark has a single runtime dependency:

- **[raylib](https://github.com/raysan5/raylib)** — a simple and easy-to-use game programming library

Special thanks to [@raysan5](https://github.com/raysan5) and the raylib community for making this project possible.

---

## License

AfterDark is licensed under the **LPRL (Lunar Public Royalty License)**. See [`LICENSE`](https://github.com/Gooseymille10/Afterdark-a-Minecraft-Clone-in-CPP/blob/main/LICENSE) for full terms.

AfterDark is not affiliated with, endorsed by, or sponsored by Mojang Studios or Microsoft.

---

<div align="center">

*Made with ❤️ by [Lunar Software Corporation](https://github.com/Gooseymille10)*

</div>
