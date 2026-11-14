# ArmadaOS Freedom

[English](https://github.com/ArmadaOS-Freedom) · **简体中文**

**让 ARM 平板拥有 Steam 游戏模式、Linux 桌面与多系统启动体验。**

[ArmadaOS Freedom](https://github.com/ArmadaOS-Freedom/armadaos-freedom) 是基于 [ArmadaOS](https://github.com/armada-os/armada) 的社区维护项目，专注于 ARM 平板的硬件适配与游戏体验。

我们保留 ArmadaOS 的系统基础，将 Steam 游戏模式、FEX、Proton 和 KDE Plasma 桌面带到平板上，并围绕多系统引导、硬件驱动、安装维护和游戏控制开发配套工具。

### 🎮 我们在做什么

- **游戏与桌面**：提供 Steam 游戏模式与 KDE Plasma 桌面，通过 FEX 和 Proton 运行兼容的 PC 游戏。
- **多系统启动**：基于 kShimC 提供启动菜单，让 Android 与 Linux 共存，按需选择使用。
- **平板硬件适配**：持续完善显示、触摸、音频、网络、电源、USB 和手柄等功能。
- **安装与维护**：提供配套安装助手、备份恢复及系统维护工具。
- **游戏配套工具**：通过 Decky 插件管理游戏设置、性能配置和网络加速。

### 📱 当前适配设备

目前围绕以下设备开展适配：

| 设备 | 型号 | 文档 |
|---|---|---|
| 联想拯救者 Y700 四代 | TB322FC | [适配说明](https://github.com/ArmadaOS-Freedom/armadaos-freedom/blob/main/devices/lenovo-tb322fc/README.md) |
| 联想拯救者 Y700 五代 | TB323FU | [适配说明](https://github.com/ArmadaOS-Freedom/armadaos-freedom/blob/main/devices/lenovo-tb323fu/README.md) |
| 联想小新 Pad Pro GT | TB710FU | [适配说明](https://github.com/ArmadaOS-Freedom/armadaos-freedom/blob/main/devices/lenovo-tb710fu/README.md) |

各设备的安装条件、可用功能与已知问题，请以对应机型文档为准。

### 🛠️ 主要项目

| 项目 | 介绍 |
|---|---|
| [ArmadaOS Freedom](https://github.com/ArmadaOS-Freedom/armadaos-freedom) | 系统主仓库，维护平板适配、内核与驱动、多系统引导及相关文档。 |
| [Freedom 安装助手](https://github.com/ArmadaOS-Freedom/armadaos-freedom-installer) | Windows 安装与维护工具，提供安装、备份和恢复等功能；另有 Apple 芯片 macOS 版，目前提供内部存储安装。 |
| [Freedom Control](https://github.com/ArmadaOS-Freedom/freedom-control) | 基于 Armada Control 的 Decky 控制插件，提供全局与逐游戏的兼容性、性能设置，并持续完善平板平台适配。 |
| [UU 加速器插件](https://github.com/ArmadaOS-Freedom/decky-uu-accelerator) | 面向 ArmadaOS 与 Freedom 的第三方 Decky 插件，整合官方核心安装、手机扫码绑定和加速状态查看。 |

### 🤝 参与项目

欢迎参与代码开发、设备测试、问题反馈、文档完善和使用经验分享。

反馈问题时，请到对应仓库的 **Issues**，附上设备型号、系统版本、复现步骤及相关日志，帮助我们定位和解决问题。

### 📬 交流与联系

- **中文交流**：欢迎前往[单翼的哔哩哔哩](https://space.bilibili.com/258786)，查看项目动态、使用教程与演示。
- **QQ 粉丝大群**：487945399
- **QQ 粉丝二群**：332038419
- **海外联系 / International contact**：欢迎通过邮箱联系 / Feel free to email [mydanyi@qq.com](mailto:mydanyi@qq.com)。

问题反馈与功能建议，也欢迎提交到对应项目的 **GitHub Issues**。

### ❤️ 致谢

感谢 [ArmadaOS](https://github.com/armada-os/armada)、[kShimC](https://github.com/sunflower2333/kShimC) 及相关开源项目的开发者，也感谢参与适配、测试与反馈的每一位贡献者。

各项目与组件保留其原作者署名，并遵循各自的开源许可证及使用条款。
