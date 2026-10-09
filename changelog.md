# 📜 Changelog

All notable changes to **Fast Animation** will be documented here.

*Format based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).*

---

## [v0.2] — 2026-10-09

### 🧹 Recent Apps Cleanup Update

### Added
- 🧹 Recent Apps cleanup on boot (recents & thumbnails)
- 🎨 Launcher force-stop for fresh recents screen
- 📱 Multi-user support (secondary & work profiles)
- 🏷️ ReSukiSU compatibility badge

### Changed
- 🎨 Cleaner flashing UI with dynamic module info (name · version · author)
- ⚡ Optimized `service.sh` boot timing (`sleep 8` for storage unlock)
- 📝 Refined README with better structure & compatibility table

### Fixed
- 🐛 `Verify` code block markdown rendering issue
- 🐛 Flashing UI alignment and spacing

---

## [v0.1] — 2026-10-09

### 🎉 Initial Release

### Added
- 🚀 Force GPU rendering (HW overlay disabled via SurfaceFlinger)
- ⚡ 0.5× animation speed (window, transition, animator)
- 📱 90Hz refresh rate lock
- 🧠 VM swappiness tuning (`50`)
- 🎨 Custom styled flashing UI with ASCII banner
- ✅ Support for **Magisk v20.4+**, **KernelSU**, **APatch**
- 🔄 Auto-applies tweaks after boot via `service.sh`

---

<!--
======================= TEMPLATE =======================

## [vX.Y.Z] — YYYY-MM-DD

### Added
- 

### Changed
- 

### Fixed
- 

========================================================
-->