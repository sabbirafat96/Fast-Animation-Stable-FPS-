<div align="center">
<img src="banner.png" alt="Banner" width="100%">

# ⚡ Fast Animation & Stable FPS 💥

**Make your rooted Android buttery smooth — force GPU rendering, kill HW overlays, and boost animation speed for gaming.** 🎮

![Version](https://img.shields.io/badge/version-v0.2-blue?style=for-the-badge)
![Author](https://img.shields.io/badge/author-Sabbir%20Senpai-purple?style=for-the-badge)
![Platform](https://img.shields.io/badge/Magisk%20%7C%20KernelSU%20%7C%20APatch-supported-red?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![Android](https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white)

</div>

---

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🚀 | **Force GPU Rendering** | Disable HW overlay via SurfaceFlinger |
| ⚡ | **0.5× Animation Speed** | Window, transition, animator scaled down |
| 📱 | **90Hz Refresh Lock** | Smooth scrolling on supported displays |
| 🧠 | **VM Swappiness Tuned** | Balanced memory pressure |
| 🎮 | **Gaming Optimized** | Less stutter, faster UI response |
| 🧹 | **Recent Apps Cleanup** | Clears recents on boot for fresh start |
| 🛡️ | **Safe & Reversible** | Disable module & reboot to restore |

---

## ⚙️ What It Does

| Tweak | Effect |
|-------|--------|
| `peak_refresh_rate = 90` | Max refresh capped at 90Hz |
| `min_refresh_rate = 0` | Adaptive min refresh |
| `user_refresh_rate = 90` | User-facing refresh 90Hz |
| `window_animation_scale = 0.5` | 2× faster window animations |
| `transition_animation_scale = 0.5` | 2× faster transitions |
| `animator_duration_scale = 0.5` | 2× faster animators |
| `vm.swappiness = 50` | Balanced memory tuning |
| `SurfaceFlinger 1008 i32 1` | HW overlay disabled → GPU render |

> ✅ Applied automatically **after boot completes** via `service.sh`

---

## 📱 Compatibility

<div align="center">

![Magisk](https://img.shields.io/badge/Magisk-00AF9C?style=for-the-badge)
![KernelSU](https://img.shields.io/badge/KernelSU-3D5AFE?style=for-the-badge)
![KernelSU Next](https://img.shields.io/badge/KernelSU_Next-3D5AFE?style=for-the-badge)
![SukiSU](https://img.shields.io/badge/SukiSU-3D5AFE?style=for-the-badge)
![ReSukiSU](https://img.shields.io/badge/ReSukiSU-9D4EDD?style=for-the-badge)
![APatch](https://img.shields.io/badge/APatch-FF5722?style=for-the-badge)

</div>

- ✅ Android **8.0** and higher
- ✅ Works on all mainstream brands
- ✅ Transsion optimized (XOS · HiOS · itelOS)

---

## 🚀 Installation

### Requirements
- Rooted device with **Magisk v20.4+**, **KernelSU**, or **APatch**
- Android 8.0+

### Steps
1. 📥 Download the latest `.zip` from [**Releases**](../../releases/latest)
2. 🔧 Open **Magisk / KernelSU / APatch**
3. 📂 Go to **Modules → Install from storage**
4. ✅ Select the zip
5. ⏳ Wait for flashing UI to finish
6. 🔄 **Reboot** your device

---

## ✅ Verify

After reboot, open Termux / ADB shell:

```sh
settings get global window_animation_scale
settings get global transition_animation_scale
settings get global animator_duration_scale
settings get system peak_refresh_rate
```

Expected output: `0.5` · `0.5` · `0.5` · `90`

---

## 🗑️ Uninstall

1. Open **Magisk / KernelSU / APatch**
2. Go to **Modules**
3. Find **Fast Animation** → tap **Remove**
4. **Reboot**

> ✅ All tweaks revert automatically. No data loss.

---

## ⚠️ Disclaimer

> Educational & personal use only. Not responsible for device damage or data loss. **Use at your own risk.**

---

<div align="center">

### 🌟 If this project helped you, don't forget to star the repo! 🌟

**Made with ❤️ by Sabbir Senpai 😎**

---

### ❤️ From Bangladesh 🇧🇩
### ✊ Free Palestine 🇵🇸

<br>

<img src="Palestine.png" alt="Palestine" width="100%">

</div>
