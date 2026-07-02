# Multi-Platform Emulation Registry by Host Operating System

A system-by-system matrix categorizing S-Tier and A-Tier desktop and mobile emulators, prioritized by native architecture compatibility.

---

## 1. Apple Ecosystem

### macOS (Apple Silicon M-Series)
| Generation / Console | Tier | Emulator | Video / Rendering Backend | Download / Project Source |
| :--- | :---: | :--- | :--- | :--- |
| **All-in-One Retro** | **S** | RetroArch | Metal / Vulkan | [retroarch.com](https://www.retroarch.com/) |
| **GameCube / Wii** | **S** | Dolphin (Nightly) | Native Metal | [dolphin-emu.org](https://dolphin-emu.org/) |
| **Nintendo Switch** | **S** | Ryubing (Forks) | Native Metal (via Hypervisor) | [github.com/Ryujinx](https://github.com/Ryujinx) |
| | **A** | Eden | Vulkan / MoltenVK | [sudachiemulator.org](https://sudachiemulator.org/) |
| **PlayStation 1** | **S** | DuckStation | Vulkan / Metal | [duckstation.org](https://www.duckstation.org/) |
| **PlayStation 2** | **S** | PCSX2 (Nightly) | Native Metal | [pcsx2.net](https://pcsx2.net/) |
| | **A** | ARMSX2 (MacOS) | Native Metal / ARM64 JIT | [armsx2.net](https://armsx2.net/) |
| **PlayStation Portable**| **S** | PPSSPP | Vulkan / Metal | [ppsspp.org](https://www.ppsspp.org/) |
| **PlayStation 3** | **S** | RPCS3 | Native ARM64 Translation | [rpcs3.net](https://rpcs3.net/) |
| **PlayStation 4** | **S** | shadPS4 | MoltenVK / Metal translation | [shadps4.net](https://shadps4.net/) |

### macOS (Legacy Intel x86_64)
| Generation / Console | Tier | Emulator | Video / Rendering Backend | Download / Project Source |
| :--- | :---: | :--- | :--- | :--- |
| **All-In-One Retro** | **S** | OpenEmu | OpenGL / Metal | [openemu.org](https://openemu.org/) |
| **GameCube / Wii** | **S** | Dolphin | OpenGL / Vulkan | [dolphin-emu.org](https://dolphin-emu.org/) |
| **Nintendo Switch** | **S** | Ryujinx (Legacy x86) | Vulkan (Requires Dedicated AMD GPU) | [github.com/Ryujinx](https://github.com/Ryujinx) |
| **PlayStation 1** | **S** | DuckStation | OpenGL / Vulkan | [duckstation.org](https://www.duckstation.org/) |
| **PlayStation 2** | **S** | PCSX2 (Legacy Mac) | OpenGL | [pcsx2.net](https://pcsx2.net/) |
| **PlayStation 3** | **S** | RPCS3 | Vulkan (Requires AVX2 Extension) | [rpcs3.net](https://rpcs3.net/) |
| **PlayStation 4** | **S** | shadPS4 | Vulkan / MoltenVK (Discrete GPU req.) | [shadps4.net](https://shadps4.net/) |

### iOS (iPhone / iPad)
| Generation / Console | Tier | Emulator | Access Vector / Requirements | Download / Project Source |
| :--- | :---: | :--- | :--- | :--- |
| **All-In-One Retro** | **S** | Delta | App Store / Native UI | [deltaemulator.com](https://deltaemulator.com/) |
| | **A** | RetroArch | App Store | [retroarch.com](https://www.retroarch.com/) |
| **GameCube / Wii** | **S** | Dolphin iOS | Side-load (Requires JIT environment) | [dolphin-emu.org](https://dolphin-emu.org/) |
| | **A** | Dolphiiini | App Store (JIT-less, lower performance) | [github.com/OatmealDome/Dolphiiini](https://github.com/OatmealDome/Dolphiiini) |
| **PlayStation 1** | **S** | Gamma | App Store / Native | [gammaemulator.com](https://gammaemulator.com/) |
| **PlayStation 2** | **S** | ARMSX2 (iOS Refresh) | Side-load (Requires AltStore/SideStore JIT) | [armsx2.net](https://armsx2.net/) |
| **PlayStation Portable**| **S** | PPSSPP | App Store / Native | [ppsspp.org](https://www.ppsspp.org/) |

---

## 2. Android Ecosystem

| Generation / Console | Tier | Emulator | Video Backend / Optimization | Download / Project Source |
| :--- | :---: | :--- | :--- | :--- |
| **All-In-One Retro** | **S** | RetroArch | Vulkan / OpenGL ES | [retroarch.com](https://www.retroarch.com/) |
| | **A** | Lemuroid | Simplified UI framework | [github.com/Swordfish90/Lemuroid](https://github.com/Swordfish90/Lemuroid) |
| **Nintendo DS** | **S** | melonDS | High-accuracy layout | [melonds.kuribo64.net](https://melonds.kuribo64.net/) |
| | **A** | DraStic | Tailored for lower-end SoC architectures | [play.google.com](https://play.google.com/store/apps/details?id=com.dsemu.drastic) |
| **GameCube / Wii** | **S** | Dolphin (Android) | Vulkan (Supports Custom Turnip Drivers) | [dolphin-emu.org](https://dolphin-emu.org/) |
| **Nintendo Switch** | **S** | Sudachi | Vulkan | [sudachiemulator.org](https://sudachiemulator.org/) |
| | **A** | Uzuy | Community performance fork | Community Sourced |
| **PlayStation 1** | **S** | DuckStation | Vulkan / Hardware Downscaling | [duckstation.org](https://www.duckstation.org/) |
| **PlayStation 2** | **S** | ARMSX2 (Refresh) | Native ARM64 Recompiler / Vulkan | [armsx2.net](https://armsx2.net/) |
| | **A** | NetherSX2 | Archival branch | Community Sourced |
| **PlayStation Portable**| **S** | PPSSPP | Vulkan | [ppsspp.org](https://www.ppsspp.org/) |

---

## 3. Desktop Systems (PC Architecture)

### Windows (x64)
| Generation / Console | Tier | Emulator | Video / Rendering Backend | Download / Project Source |
| :--- | :---: | :--- | :--- | :--- |
| **GameCube / Wii** | **S** | Dolphin | DirectX 12 / Vulkan | [dolphin-emu.org](https://dolphin-emu.org/) |
| **Nintendo Switch** | **S** | Ryujinx (Legacy / Forks) | Vulkan | [github.com/Ryujinx](https://github.com/Ryujinx) |
| | **A** | Sudachi | Vulkan | [sudachiemulator.org](https://sudachiemulator.org/) |
| **PlayStation 2** | **S** | PCSX2 (Nightly) | DirectX 12 / Vulkan | [pcsx2.net](https://pcsx2.net/) |
| **PlayStation 3** | **S** | RPCS3 | Vulkan / Native x86 Optimizations | [rpcs3.net](https://rpcs3.net/) |
| **PlayStation 4** | **S** | shadPS4 | Direct Vulkan Execution | [shadps4.net](https://shadps4.net/) |
| | **A** | fpPS4 | Compatibility Layer (Indie target focus) | [github.com/red-founder/fpPS4](https://github.com/red-founder/fpPS4) |

### Linux (x64)
| Generation / Console | Tier | Emulator | Distribution / Target Backend | Download / Project Source |
| :--- | :---: | :--- | :--- | :--- |
| **GameCube / Wii** | **S** | Dolphin | Flatpak / Native Vulkan | [dolphin-emu.org](https://dolphin-emu.org/) |
| **Nintendo Switch** | **S** | Ryujinx | Native Linux Build / Vulkan | [github.com/Ryujinx](https://github.com/Ryujinx) |
| **PlayStation 2** | **S** | PCSX2 (Nightly) | AppImage / Vulkan | [pcsx2.net](https://pcsx2.net/) |
| **PlayStation 3** | **S** | RPCS3 | Native Vulkan Environment | [rpcs3.net](https://rpcs3.net/) |
| **PlayStation 4** | **S** | shadPS4 | Linux Vulkan Pipeline Architecture | [shadps4.net](https://shadps4.net/) |
