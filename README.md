<div align="center">

# ⚡ Fast Animation & Stable FPS 💥

**Make your rooted Android buttery smooth — force GPU rendering, kill HW overlays, and boost animation speed for gaming.** 🎮

![Version](https://img.shields.io/badge/version-v1.0.0-blue?style=for-the-badge)
![Author](https://img.shields.io/badge/author-Sabbir%20Senpai-purple?style=for-the-badge)
![Platform](https://img.shields.io/badge/Magisk%20%7C%20KernelSU%20%7C%20APatch-supported-red?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

</div>

---

## ✨ Features

- 🚀 **Force GPU Rendering** — disable HW overlay via SurfaceFlinger
- ⚡ **0.5x Animation Speed** — window, transition, animator scaled down
- 📱 **90Hz Refresh Lock** — smooth scrolling on supported displays
- 🧠 **VM Swappiness Tuned** — `50` for balanced memory pressure
- 🎮 **Gaming Optimized** — less stutter, faster UI response
- 🛡️ **Safe & Reversible** — disable module & reboot to restore

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

## 🚀 Installation

### Requirements
- Rooted device with **Magisk v20.4+**, **KernelSU**, or **APatch**
- Android 8.0+

### Steps
1. Download the latest `.zip` from [**Releases**](../../releases/latest)
2. Open **Magisk / KernelSU / APatch**
3. Go to **Modules → Install from storage**
4. Select the zip
5. Wait for flashing UI to finish
6. **Reboot** your device

---

## ✅ Verify

After reboot, open Termux / ADB shell:

```sh
settings get global window_animation_scale    # → 0.5
settings get global transition_animation_scale # → 0.5
settings get global animator_duration_scale   # → 0.5
settings get system peak_refresh_rate         # → 90
```

---

## 🖥️ Flashing Preview

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
    ███████╗ █████╗ ███████╗████████╗
    ██╔════╝██╔══██╗██╔════╝╚══██╔══╝
    █████╗  ███████║███████╗   ██║
    ██╔══╝  ██╔══██║╚════██║   ██║
    ██║     ██║  ██║███████║   ██║
    ╚═╝     ╚═╝  ╚═╝╚══════╝   ╚═╝

        >>  FAST ANIMATION  <<
          Smooth • Fast • Gaming
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

 [1/3] Setting up permissions...
       ✓ service.sh → 0755 executable
────────────────────────────────────────────
 [2/3] Verifying module config...
       ✓ LATESTARTSERVICE → enabled
────────────────────────────────────────────
 [3/3] Preparing boot service...
       ✓ Tweaks apply on boot
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

   ╔══════════════════════════════════╗
   ║      ✅   INSTALL  SUCCESSFUL   ✅     ║
   ╚══════════════════════════════════╝

   🎨 Module by : Sabbir Senpai
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

## 🗑️ Uninstall

1. Magisk / KernelSU / APatch → Modules
2. Disable / Remove **Fast Animation**
3. **Reboot**

> ✅ All tweaks revert automatically. No data loss.

---

## ⚠️ Disclaimer

> Educational & personal use only. Not responsible for device damage or data loss. **Use at your own risk.**

---

<div align="center">

**Made with ❤️ by Sabbir Senpai**

⭐ Star this repo if it helped you 🥲
