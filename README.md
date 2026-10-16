# VelocityPro Releases

Official public release distribution and Over-The-Air (OTA) update feed for **VelocityPro** — high-performance AI photo sorting, facial clustering, and athlete identification for macOS.

[![Latest Release](https://img.shields.io/badge/Release-v1.0.8-blue.svg)](https://github.com/joepluis1/VelocityPro-Releases/releases/latest)
[![Build](https://img.shields.io/badge/Build-9-green.svg)](https://github.com/joepluis1/VelocityPro-Releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-macOS%20Apple%20Silicon%20(M1--M5)-black.svg)](https://github.com/joepluis1/VelocityPro-Releases/releases/latest)
[![Self-Contained](https://img.shields.io/badge/Runtime-Standalone%20Bundled-purple.svg)](https://github.com/joepluis1/VelocityPro-Releases/releases/latest)

---

## 🚀 Latest Release: VelocityPro v1.0.8 (Build 9)

### 📥 Direct Download
- **[Download VelocityPro-1.0.8.zip](https://github.com/joepluis1/VelocityPro-Releases/releases/download/v1.0.8/VelocityPro-1.0.8.zip)** *(1.46 GB)*
- **[View All Releases & Assets](https://github.com/joepluis1/VelocityPro-Releases/releases/latest)**

### 🔐 Integrity Verification
| Attribute | Value |
| :--- | :--- |
| **Version** | `1.0.8` (Build `9`) |
| **Release Date** | October 15, 2026 |
| **File Name** | `VelocityPro-1.0.8.zip` |
| **File Size** | `1,564,306,254 bytes` (~1.46 GB) |
| **SHA-256** | `d168ca62660da2a6f75475d86424553e4f260cfaae9d35e5b27f225e476e2afe` |

Verify checksum in Terminal:
```bash
shasum -a 256 ~/Downloads/VelocityPro-1.0.8.zip
```

---

## 📦 What's New in v1.0.8
- **Standalone Bundled Python Runtimes**: All AI inference tools (`ai_sorter`, `reference_matcher`, `update_memory`) are compiled and packaged into independent `.bundle` runtimes inside `VelocityPro.app`. Zero external Python, conda, or pip dependencies required.
- **Active Sort Protection**: Safeguards active sorting runs by disabling update relaunch triggers and displaying warnings until current operations safely conclude.
- **Memory-Piped RAW Extraction**: Native stream-piped CoreGraphics decoding with zero intermediate SSD cache writes, preserving flat green memory pressure across massive batches (1,800+ RAW images).
- **Sub-Second Camera Burst Wedging**: 4-stage sweep engine with camera stream isolation to resolve high-speed bursts and loose singles.

---

## 💻 Installation

1. **Download**: Grab [`VelocityPro-1.0.8.zip`](https://github.com/joepluis1/VelocityPro-Releases/releases/download/v1.0.8/VelocityPro-1.0.8.zip).
2. **Extract**: Double-click to extract `VelocityPro.app`.
3. **Install**: Drag `VelocityPro.app` to your `/Applications` folder.
4. **Launch**: Double-click to open. VelocityPro includes all necessary neural network weights and machine learning libraries out-of-the-box.

---

## 🔄 Automatic In-App Updates

VelocityPro features native in-place auto-updates powered by the [`appcast.json`](appcast.json) manifest in this repository:
- The app checks for new releases on startup and periodically in the background.
- You can manually check anytime via **AutoSorterPro → Check for Updates...** (`Cmd+U`) or by clicking the version badge in the sidebar.
- Updates download and install in-place without manual file juggling.

---

## 📋 Release History

| Version | Build | Release Date | Highlights |
| :--- | :--- | :--- | :--- |
| **[v1.0.8](https://github.com/joepluis1/VelocityPro-Releases/releases/tag/v1.0.8)** | `9` | 2026-10-15 | Standalone bundled Python ML runtimes, active sort protection, bounded green memory |
| **[v1.0.7](https://github.com/joepluis1/VelocityPro-Releases/releases/tag/v1.0.7)** | `8` | 2026-10-15 | Stream-piped RAW extraction with zero temp disk writes, memory decommit |
| **[v1.0.6](https://github.com/joepluis1/VelocityPro-Releases/releases/tag/v1.0.6)** | `7` | 2026-10-15 | Hardened in-place update with detached nohup relaunch |
| **[v1.0.5](https://github.com/joepluis1/VelocityPro-Releases/releases/tag/v1.0.5)** | `6` | 2026-10-15 | De-translocated in-place auto-update |
| **[v1.0.4](https://github.com/joepluis1/VelocityPro-Releases/releases/tag/v1.0.4)** | `5` | 2026-10-15 | Automated in-place OTA update verification |
| **[v1.0.3](https://github.com/joepluis1/VelocityPro-Releases/releases/tag/v1.0.3)** | `4` | 2026-10-15 | In-place auto-relaunch and background checks |
| **[v1.0.2](https://github.com/joepluis1/VelocityPro-Releases/releases/tag/v1.0.2)** | `3` | 2026-10-15 | Sidebar system version badge |
| **[v1.0.1](https://github.com/joepluis1/VelocityPro-Releases/releases/tag/v1.0.1)** | `2` | 2026-10-15 | Deep code-signing and version comparison tests |
