# ArmadaOS Freedom

**English** · [简体中文](https://github.com/ArmadaOS-Freedom/.github/blob/main/profile/README.zh-CN.md)

**Bringing Steam Gaming Mode, a Linux desktop, and multi-boot to ARM tablets.**

[ArmadaOS Freedom](https://github.com/ArmadaOS-Freedom/armadaos-freedom) is a community-maintained project based on [ArmadaOS](https://github.com/armada-os/armada), focused on hardware support and gaming on ARM tablets.

We build on the ArmadaOS foundation to bring Steam Gaming Mode, FEX, Proton, and KDE Plasma to tablets. We also develop tools for multi-boot, hardware support, installation and maintenance, and gaming controls.

### 🎮 What we work on

- **Gaming and desktop**: Steam Gaming Mode and KDE Plasma, with FEX and Proton for running compatible PC games.
- **Multi-boot**: A kShimC boot menu that lets Android and Linux coexist, so you can choose which system to use.
- **Tablet hardware support**: Ongoing work on displays, touch input, audio, networking, power, USB, and controllers.
- **Installation and maintenance**: Companion tools for installation, backup, recovery, and system maintenance.
- **Gaming tools**: Decky plugins for game settings, performance configuration, and network acceleration.

### 📱 Current device work

Our current adaptation work covers the following devices:

| Device | Model | Documentation |
|---|---|---|
| Lenovo Legion Y700 Gen 4 | TB322FC | [Device guide](https://github.com/ArmadaOS-Freedom/armadaos-freedom/blob/main/devices/lenovo-tb322fc/README.md) |
| Lenovo Legion Y700 Gen 5 | TB323FU | [Device guide](https://github.com/ArmadaOS-Freedom/armadaos-freedom/blob/main/devices/lenovo-tb323fu/README.md) |
| Lenovo Xiaoxin Pad Pro GT | TB710FU | [Device guide](https://github.com/ArmadaOS-Freedom/armadaos-freedom/blob/main/devices/lenovo-tb710fu/README.md) |

See each device's documentation for installation requirements, available features, and known issues.

### 🛠️ Main projects

| Project | Description |
|---|---|
| [ArmadaOS Freedom](https://github.com/ArmadaOS-Freedom/armadaos-freedom) | The main system repository, maintaining tablet support, the kernel and drivers, multi-boot, and related documentation. |
| [Freedom Installer](https://github.com/ArmadaOS-Freedom/armadaos-freedom-installer) | Windows installation and maintenance tools, including installation, backup, and recovery. An Apple silicon macOS version is also available and currently provides installation to internal storage. |
| [Freedom Control](https://github.com/ArmadaOS-Freedom/freedom-control) | A Decky control plugin derived from Armada Control, providing global and per-game compatibility and performance settings, with ongoing tablet platform support. |
| [Smart TF Card Allocator](https://github.com/ArmadaOS-Freedom/smart-tf-allocator) | An Android app for splitting a microSD card between Android adopted storage and a Linux game library, and moving supported apps. Linux game-library setup is completed with Freedom Controller. |
| [UU Accelerator Plugin](https://github.com/ArmadaOS-Freedom/decky-uu-accelerator) | A third-party Decky plugin for ArmadaOS and Freedom that integrates official core installation, phone pairing via QR code, and acceleration status monitoring. |

### 🤝 Get involved

Contributions are welcome: code, device testing, bug reports, documentation, and sharing your experience.

To report a problem, open an **Issue** in the relevant repository and include your device model, system version, reproduction steps, and relevant logs to help us investigate.

### 📬 Community and contact

- **Chinese-speaking community**: Visit [Danyi on Bilibili](https://space.bilibili.com/258786) for project updates, tutorials, and demonstrations.
- **Main QQ fan group**: 487945399
- **Second QQ fan group**: 332038419
- **International contact**: Feel free to email [mydanyi@qq.com](mailto:mydanyi@qq.com).

Bug reports and feature requests are also welcome through **GitHub Issues** in the relevant project.

### ❤️ Credits

Thanks to the developers of [ArmadaOS](https://github.com/armada-os/armada), [kShimC](https://github.com/sunflower2333/kShimC), and the related open-source projects, and to everyone contributing hardware support, testing, and feedback.

All projects and components retain their original attribution and follow their respective licenses and terms of use.
