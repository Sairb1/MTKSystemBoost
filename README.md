<div align="center">

# 🚀 MTK System Boost
<img width="1774" height="887" alt="mtk" src="https://github.com/user-attachments/assets/04c109e4-353e-4494-97eb-9bee2c00b34b" />

### Advanced Battery, Thermal & Performance Optimizer for MediaTek MT6835 / Dimensity Platforms

<img src="https://img.shields.io/badge/MTK-SystemBoost-blueviolet?style=for-the-badge&logo=android"/>
<br/>
<img src="https://img.shields.io/badge/Chipset-Dimensity%206xx%20%7C%207xx-brightgreen?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Platform-MT6835-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Root-Magisk%20%7C%20KernelSU%20%7C%20APatch-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/WebUI-KSU%20%7C%20MMRL-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Telegram-colorosmodules-229ED9?style=for-the-badge&logo=telegram"/>

<br/>

### Smart tuning engine for MediaTek Dimensity devices

Made with ♥ by **[Ayan (@imnotaino)](https://t.me/imnotaino)**  
Base Module → **AutoSystemBoost by Dima Krylov**

</div>

---

# 📖 About

**MTK System Boost** is an advanced optimization module built specifically for:

- MediaTek MT6835
- Dimensity 6100+
- Dimensity 6xx / 7xx platforms

including devices like:
- Realme Narzo 60x
- Realme 11x
- Realme C67 5G
- other MT6835-based devices

Unlike Snapdragon-focused tuning modules, this project was rewritten specifically for MediaTek architecture.

That means:
- no Qualcomm-only tweaks
- no fake WALT scheduler tuning
- no KGSL GPU configs
- no MSM performance hacks

Instead, the module properly targets:
- EAS schedutil governor
- Mali GPU devfreq
- MTK power policy manager
- MediaTek thermal behavior

Result:
- smoother UI
- lower thermal spikes
- improved battery life
- better sustained performance
- reduced idle drain

without destroying system stability.

---

# ✨ Features

## ⚡ MTK-Specific Architecture Tuning

Optimized specifically for:
```text
6× Cortex-A55 + 2× Cortex-A76/A78
```

CPU topology used in:
- MT6835
- Dimensity 6100+
- Dimensity 6300
- similar MTK SoCs

Includes:
- governor optimization
- scheduler balancing
- thermal scaling improvements
- boost control tuning

---

# 🎮 Mali GPU Optimization

Optimizes:
- Mali G57
- Mali G610

through:
- devfreq tuning
- power policy balancing
- scaling optimizations
- frequency boundary adjustments

Result:
- smoother rendering
- reduced overheating
- more stable gaming sessions

---

# ⚖️ Three Performance Profiles

## ⚖️ Balanced (Default)

Smart scaling with:
- smooth UI
- balanced thermals
- good battery life

Best for:
- daily usage
- multitasking
- social media
- normal gaming

---

## 🔥 Performance

Aggressive tuning:
- maximum CPU clocks
- higher GPU frequencies
- lower scheduling latency

Best for:
- gaming
- emulation
- heavy multitasking

---

## 🔋 Battery

Efficiency-focused tuning:
- strict clock limits
- VM optimization
- reduced thermal output
- improved standby behavior

Best for:
- battery saving
- overnight standby
- low-temperature operation

---

# 🌐 Hybrid Profile Switcher

The module supports:
- WebUI dashboard
- Action button switching
- Shell profile control

---

## 🖥️ WebUI Dashboard

Open the module inside:
- KernelSU Manager
- MMRL

to view:
- CPU temperature
- GPU frequency
- battery status
- active profile

and switch profiles directly.

---

## ▶️ Action Button

Tap:
```text
Action (▶)
```

inside:
- Magisk
- KernelSU
- APatch

to instantly:
- apply WebUI profile
- cycle profiles dynamically

Cycle order:
```text
Balanced ⚖️ → Performance 🔥 → Battery 🔋
```

---

## 💻 Shell / ADB Support

Apply profiles manually:

```bash
su -c "sh /data/adb/modules/MTKSystemBoost/apply_profile.sh performance"
```

---

# 🚫 Logging Suppression

Disables battery-draining MediaTek logging daemons:

```text
mtklogd
mdlogger
```

and other background tracing services.

This helps:
- reduce RAM usage
- lower CPU wakeups
- improve standby battery
- reduce background heat

---

# ⚙️ Configuration System

The module uses:
```text
features.conf
```

for subsystem toggling.

Path:
```text
/data/adb/modules/MTKSystemBoost/features.conf
```

---

# 🛠️ Available Toggles

| Toggle | Default | Description |
|---|---|---|
| CPU=1 | ON | CPU governor & scaling tuning |
| VM=1 | ON | VM swappiness & cache tuning |
| NET=1 | ON | TCP BBR & network optimization |
| WIFI=1 | ON | Wi-Fi power & scan tuning |
| LOG=1 | ON | Disable debug logging |
| KERNEL=1 | ON | Suspend MTK vendor loggers |

---

# 📦 What the module modifies

The module dynamically tunes:
- CPU governors
- scheduler behavior
- VM memory policies
- network stack
- Wi-Fi power policies
- GPU devfreq
- MediaTek vendor services

without:
- kernel patching
- boot image modification
- partition editing

Everything remains:
- system-less
- OTA safe
- fully reversible

---

# 📥 Installation

1. Flash:
```text
MTKSystemBoost-Vx.zip
```

using:
- Magisk
- KernelSU
- APatch

2. Wait for installer completion

3. Reboot device

4. Open WebUI or use Action button to switch profiles

---

# 📱 Compatibility

| Component | Support |
|---|---|
| Platform | MT6835 |
| SoC | Dimensity 6xx / 7xx |
| Root | Magisk / KSU / APatch |
| Android | Android 11+ |

---

# ❓ FAQ

## Q: Is this just a Snapdragon module port?
No.

The module was rewritten specifically for MediaTek architecture.

---

## Q: Does this support Mali GPUs?
Yes.

The module directly targets Mali devfreq behavior.

---

## Q: Will performance increase?
Yes.

Especially:
- UI smoothness
- sustained gaming
- thermal consistency

---

## Q: Will battery improve?
Yes.

Balanced & Battery profiles significantly reduce idle drain and unnecessary boosts.

---

## Q: Can I switch profiles without rebooting?
Yes.

Using:
- WebUI
- Action button
- ADB shell

---

# 👑 Credits

| Role | Name |
|---|---|
| Developer | Ayan (@imnotaino) |
| Base Module | AutoSystemBoost by Dima Krylov |
| Platform | MediaTek MT6835 |

---

# 📢 Community

### 👉 https://t.me/colorosmodules

---

<div align="center">

## ⚡ Built for MediaTek. Tuned for real-world usage.

Made with ♥ by Ayan

</div>
