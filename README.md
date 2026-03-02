# MalachiteOpt v1.1
**By mujinn**

A performance module build for Malachite devices (Poco X7 / Redmi Note 14 Pro 5G — Dimensity 7300-Ultra). This module features a built-in WebUI where changes apply live with no reboot needed.

## Features
* **4 Performance Profiles:** Balanced, Performance, Powersave, and Eco.
* **Governor Selector:** Choose between `schedutil`, `sugov_ext`, or `performance`.
* **QuartzAI:** Auto-detects games to boost on launch and restores settings on exit.
* **GPU Tuning:** Includes GED, FPSGO, power limiter bypass, and DDR boost.
* **Network Optimization:** TCP optimizer (BBR/FQ) with auto-switching and Cloudflare DoT (1.1.1.1) DNS.
* **Display & Smoothing:** SurfaceFlinger phase offset tuning for smoother frame pacing and refresh rate locking.
* **System Tweaks:** dex2oat ART compiler speed-profile, WALT tuning, and kernel trace/logd management.
* **Thermal Control:** Option to enable or fully disable thermal throttling.
* **Power Management:** Render engine tuning and CPU underclocking options.

## Compatibility
* **Managers:** Magisk, KernelSU, KernelSU-Next, and APatch.
* **ROMs:** MIUI, HyperOS, PixelOS, and AOSP.
