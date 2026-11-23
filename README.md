# CORE LABS Studio (v0.5.34)

**Lightweight, 100% offline, portable Windows x64 hardware telemetry and sensor panel application for TURZX USB IPS displays.**

No installer. No cloud account. No subscription. No background bloat.

[![Download FREE](https://img.shields.io/badge/Download-FREE%20Edition-2ea44f?style=for-the-badge)](https://corelabsstudio.gumroad.com/l/rbufw)
[![Get PRO](https://img.shields.io/badge/Upgrade-PRO%20(One--Time)-0969da?style=for-the-badge)](https://corelabsstudio.gumroad.com/l/klbgdf)
[![Storefront](https://img.shields.io/badge/Gumroad-Storefront-ff90e8?style=for-the-badge)](https://corelabsstudio.gumroad.com)

---

## 15 Built-In Public Themes (8 FREE + 7 PRO)

![CORE LABS Studio 15 Public Themes](assets/public_theme_gallery.png)
*Renderer sample data shown across all 15 public themes (portrait & landscape, dark & light).*

---

## Key Features

- **Honest Hardware Telemetry:** Real-time CPU, GPU, RAM, storage, network, and liquid-cooling telemetry (coolant temperature, flow rate, pump RPM, air temperature where supported by sensors).
- **Game Performance & Frametime:** Live FPS, 1% / 0.1% lows, and a 60-second frametime history graph to spot micro-stutters immediately.
- **Dedicated Power Modes:** `LIVE` (up to 10 FPS), `GAME` (2 Hz), plus `ECO` (0.5 Hz) and `DEEP SLEEP` in PRO.
- **Zero Cloud / Zero Subscription:** Runs fully offline from a portable ZIP archive. PRO unlocks locally via an offline Ed25519 license key (`CLS1.`) with no hardware-ID lock.
- **Multi-Language UI:** English, Czech, and German localization.

### Frametime & Workstation Views

![ESPORTS FRAME Frametime Detail](assets/frame_time_detail.png)

![WORKSTATION PRO Light Theme](assets/workstation_light.png)

---

## Hardware Compatibility (v0.5.34)

> **Always test your display with the FREE edition first before purchasing PRO.**

| Display / Size | Status in v0.5.34 | Technical Details |
| :--- | :--- | :--- |
| **TURZX 9.2" USB IPS** (`1920 × 462` active / `1920 × 480` transport) | **Hardware-Verified** | Native WinUSB bulk transport for USB VID:PID **`1CBE:0092`** (portrait & landscape, configurable border offset). |
| **8.8" USB IPS** (`1920 × 480`) | **Conditional (Not HW Tested)** | Supported **only** if your specific unit uses the identical **`1CBE:0092`** WinUSB interface and protocol. |
| **5.0" (`800 × 480`) & 3.5" (`320 × 480`)** | **Preview Only** | Available in *Render Preview* only. USB-Serial / COM panels are not supported for physical USB output in v0.5.34. |

If you own another TURZX panel variant and want it considered for a future update, open an **Issue** in this repository with your panel's size, resolution, and USB `VID:PID` from Windows Device Manager.

---

## FREE vs. PRO Comparison

Both editions share the exact same portable Windows x64 binary, telemetry engine, and stability.

| Feature | FREE ($0) | PRO (One-Time Unlock) |
| :--- | :---: | :---: |
| Portable Windows x64 build (offline, no account) | Yes | Yes |
| Honest CPU / GPU / RAM / cooling telemetry core | Yes | Yes |
| Public themes included | **8 themes** *(incl. WORKSTATION PRO & ESPORTS FRAME)* | **All 15 themes** |
| Manual `LIVE` (10 FPS) & `GAME` (2 Hz) modes | Yes | Yes |
| Automatic game detection & idle power saving (`ECO` / `DEEP SLEEP`) | — | Yes |
| Local profiles | 1 profile | Up to 16 profiles |
| Game recording & PNG / APNG exports | — | Yes |
| Manual sensor probe mapping & advanced cooling topologies | — | Yes |
| Offline Ed25519 license key (`CLS1.`, no HWID lock) | — | Yes |

---

## Quick Start & Verification

1. Download the portable ZIP from [Gumroad](https://corelabsstudio.gumroad.com).
2. Extract the archive to any local folder.
3. Right-click the executable and choose **Run as administrator** (required on Windows for low-level hardware sensor access).
4. Connect your `1CBE:0092` TURZX USB panel, select your theme and orientation, and click **Activate on display**.

### Release Verification (v0.5.34)

- **Automated & Visual Checks:** 2,187 regression tests passed, 1,200 / 1,200 pixel-identical theme renders, 31 native licensing and edition tests passed.
- **Hardware Burn-In:** Owner-verified 24-hour continuous desktop run, protected EXE FREE/PRO smoke test, and laptop acceptance.
- **Portable ZIP SHA-256:**
  ```text
  c322abb22a4e0de812b90a2d635b0b2f8fcfddb6c2b085456993e5c090612836
  ```

---

## Support & Feedback

- **Bug reports & panel compatibility requests:** Open an issue in the [Issues](../../issues) tab.
- **Downloads & updates:** [corelabsstudio.gumroad.com](https://corelabsstudio.gumroad.com)
