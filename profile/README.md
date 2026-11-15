# ArmadaOS Freedom

**English** · [简体中文](https://github.com/ArmadaOS-Freedom/.github/blob/main/profile/README.zh-CN.md)

**Turn your Android tablet into a portable gaming device—with a Steam Deck-style gaming mode, a full Linux desktop, and optional multi-boot.**

[ArmadaOS Freedom](https://github.com/ArmadaOS-Freedom/armadaos-freedom) is a community-maintained operating system based on [ArmadaOS](https://github.com/armada-os/armada), focused on hardware support and gaming on ARM Android tablets.

We build on ArmadaOS to create a tablet operating system with Steam Gaming Mode, FEX, Proton, KDE Plasma, and more. Our work also includes multi-boot support, hardware drivers, installation and maintenance tools, and gaming controls.

### 🎮 What we work on

- **Gaming and desktop modes**: Steam Gaming Mode and KDE Plasma, with FEX and Proton to run compatible PC games.
- **Optional multi-boot**: Keep Android and Linux side by side with the kShimC launcher, and choose which system to use.
- **Hardware support for more tablets**: Ongoing improvements to displays, touch input, audio, networking, power, USB, and controllers.
- **Easier installation and maintenance**: Companion tools for installation, backup, recovery, and system maintenance.
- **System tools**: Decky plugins for game settings, microSD space allocation, performance settings, and network acceleration.

### 📱 Device support

We are currently adapting the system for the following devices:

| Device | Model | Documentation |
|---|---|---|
| Lenovo Legion Y700 Gen 4 | TB322FC | [Device guide](https://github.com/ArmadaOS-Freedom/armadaos-freedom/blob/main/devices/lenovo-tb322fc/README.md) |
| Lenovo Legion Y700 Gen 5 | TB323FU | [Device guide](https://github.com/ArmadaOS-Freedom/armadaos-freedom/blob/main/devices/lenovo-tb323fu/README.md) |
| Lenovo Xiaoxin Pad Pro GT | TB710FU | [Device guide](https://github.com/ArmadaOS-Freedom/armadaos-freedom/blob/main/devices/lenovo-tb710fu/README.md) |

See each device's documentation for installation requirements, available features, and known issues.

### 🛠️ Main projects

| Project | Description |
|---|---|
| [ArmadaOS Freedom](https://github.com/ArmadaOS-Freedom/armadaos-freedom) | The main system repository, covering tablet hardware support, the kernel and drivers, multi-boot, and documentation. |
| [Freedom Installer](https://github.com/ArmadaOS-Freedom/armadaos-freedom-installer) | Installation and maintenance tools for Windows, including installation, backup, and recovery. The Apple silicon macOS version currently supports installation to internal storage. |
| [Freedom Control](https://github.com/ArmadaOS-Freedom/freedom-control) | A Decky plugin based on Armada Control, offering global and per-game compatibility and performance settings, with ongoing support for tablet hardware. |
| [Smart TF Card Allocator](https://github.com/ArmadaOS-Freedom/smart-tf-allocator) | An Android app for allocating microSD space between Android app storage and a Linux game library. It also moves supported apps. Linux game-library setup is handled by Freedom Controller. |
| [UU Accelerator Plugin](https://github.com/ArmadaOS-Freedom/decky-uu-accelerator) | A third-party Decky plugin for ArmadaOS and Freedom. Install the official core, pair with your phone by scanning a QR code, and view acceleration status. |

### 🤝 Get involved

Contributions are welcome: code, device testing, bug reports, documentation improvements, and sharing your experience.

To report a problem, open an **Issue** in the relevant repository. Include your device model, system version, steps to reproduce the problem, and relevant logs so we can investigate.

### 📬 Community and contact

- **Chinese-speaking community**: Find project updates, tutorials, and demos on [Danyi's Bilibili channel](https://space.bilibili.com/258786).
- **Main QQ fan group**: 487945399
- **Second QQ fan group**: 332038419
- **International contact**: Email [mydanyi@qq.com](mailto:mydanyi@qq.com).

Bug reports and feature requests are also welcome through **GitHub Issues** in the relevant project.

### ❤️ Credits

Thanks to the developers behind [ArmadaOS](https://github.com/armada-os/armada), [kShimC](https://github.com/sunflower2333/kShimC), and the related open-source projects. We also thank everyone contributing tablet support, testing, and feedback.

Each project and component retains its original attribution and is subject to its own license and terms of use.
