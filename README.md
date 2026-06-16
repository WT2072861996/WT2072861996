<p align="center">
  <img src="./avatar.png" width="180" height="180" alt="三清科技 - Hackintosh EFI 专家" style="border-radius: 50%; box-shadow: 0 4px 20px rgba(0,0,0,0.1);" />
</p>

<h1 align="center">🍎 三清科技</h1>

<p align="center">
  <b>OpenCore Hackintosh EFI · ACPI SSDT · macOS 系统优化</b><br/>
  <em>为全球 Hackintosh 爱好者提供专业的硬件解决方案</em>
</p>

<p align="center">
  <a href="#核心仓库"><img src="https://img.shields.io/badge/Projects-12%2B-FF6B6B?style=flat-square" alt="Projects" /></a>
  <a href="https://github.com/WT2072861996?tab=repositories"><img src="https://img.shields.io/badge/Repositories-Active-blue?style=flat-square" alt="Repositories" /></a>
  <a href="https://github.com/WT2072861996"><img src="https://img.shields.io/badge/Focus-Hackintosh-9cf?style=flat-square" alt="Focus" /></a>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License" />
</p>

---

## 📌 核心仓库

### 🎓 教学与指南
| 项目 | 描述 | 难度 |
|:-----|:-----|:----:|
| **[Hackintosh-Installation-Guide](https://github.com/WT2072861996/Hackintosh-Installation-Guide)** | 🔧 完整的 OpenCore 安装指南、硬件兼容性矩阵、BIOS 设置、故障排除 | ⭐⭐ |
| **[Introduction-to-SSDT](https://github.com/WT2072861996/Introduction-to-SSDT)** | 📘 ACPI SSDT 从入门到精通 - 常见表格、创建工具、实战案例 | ⭐⭐⭐ |
| **[CPUFriend-Usage-Tutorial](https://github.com/WT2072861996/CPUFriend-Usage-Tutorial)** | ⚡ CPU 电源管理优化 - 生成自定义 CPUFriendDataProvider.kext | ⭐ |
| **[RX6950XT-RX6650XT-Black-Apple-video-card-driver-tutorial-and-method](https://github.com/WT2072861996/RX6950XT-RX6650XT-Black-Apple-video-card-driver-tutorial-and-method)** | 🎮 AMD Navi GPU 驱动教程 - SSDT 仿冒方案 | ⭐⭐⭐ |

---

### 💻 硬件 EFI 配置

#### 🖥️ 台式机
| 主板 | CPU | GPU | 状态 | 链接 |
|:----:|:---:|:---:|:----:|:----:|
| ASUS PRIME Z890M-PLUS WIFI | Intel Core Ultra 7 265K | 核显 | ✅ | [配置](https://github.com/WT2072861996/EFI-ASUS-PRIME-Z890M-PLUS-WIFI-CORE-ULTRA-7-265K-open-core1.04) |
| MSI Creator TRX40 | AMD Ryzen Threadripper 3960X | RX 6950 XT | ✅ | [配置](https://github.com/WT2072861996/EFI-MSI-Creator-TRX40-Ryzen-Threadripper-3960X-OpenCore1.07) |
| DELL Optiplex 7070 | Intel Core i7-9700T | UHD 630 | ✅ | [配置](https://github.com/WT2072861996/DELL-OptiPlex-7070-OpenCore1.0) |
| DELL Optiplex 7060 | Intel Core i5-8500T | UHD 630 | ✅ | [配置](https://github.com/WT2072861996/DELL-Optiplex-7060-OpenCore1.0) |
| Lenovo ThinkCentre M6600q | Intel Core i3-6100 | HD 620 | ✅ | [配置](https://github.com/WT2072861996/Lenovo-ThinkCentre-M6600q-N000-Open-Core1.0) |
| Mini PC | Intel Core i7-8565U | UHD 620 | ✅ | [配置](https://github.com/WT2072861996/Mini-PC-i7-8565U-OpenCore) |

#### 💼 笔记本电脑
| 品牌型号 | CPU | GPU | 状态 | 链接 |
|:-------:|:---:|:---:|:----:|:----:|
| HP EliteBook 840 G3 | Intel Core i5-6300U | Iris 540 | ✅ | [配置](https://github.com/WT2072861996/EFI-HP-EliteBook-840-G3-Hackintosh) |
| 机械革命 S1 Pro | Intel Core i5-8265U | UHD 620 | ✅ | [配置](https://github.com/WT2072861996/MMECHREVO-S1-Pro-OpenCore1.0) |
| RedmiBook Pro 14S | AMD Ryzen 7 5700U | Radeon | ✅ | [配置](https://github.com/WT2072861996/TIMI-RedmiBook-Pro-14S-open-core-1.06) |

---

## 🎯 特性亮点

### ✅ 完整的驱动支持
- 🖥️ **核显/独显** - Intel HD/UHD、AMD Radeon、NVIDIA 驱动支持
- 🔊 **音频系统** - Realtek/Conexant 高精度音频
- 🌐 **网络连接** - 有线/Wi-Fi/蓝牙 全面支持
- 🔌 **USB 映射** - 优化的端口分配，完美睡眠唤醒
- ⚡ **电源管理** - CPU 频率调节、睡眠省电配置
- 🎮 **3D 加速** - Metal 加速，游戏/专业应用支持

### 📊 技术栈
```
OpenCore 1.0x +  ·  macOS Sequoia/Sonoma/Ventura  ·  Intel/AMD CPU
ACPI SSDT  ·  BIOS 优化  ·  EFI 分区配置
```

---

## 🚀 快速开始

### 1️⃣ 选择你的硬件
浏览上方 [硬件 EFI 配置](#-硬件-efi-配置) 表，找到对应的配置

### 2️⃣ 阅读安装指南
前往 **[Hackintosh 完整安装指南](https://github.com/WT2072861996/Hackintosh-Installation-Guide)** 获取详细步骤

### 3️⃣ 学习 ACPI SSDT（可选但推荐）
查阅 **[SSDT 从入门到精通](https://github.com/WT2072861996/Introduction-to-SSDT)** 了解深度优化

### 4️⃣ 获取支持
- 📖 本仓库的 [Issues](https://github.com/WT2072861996/WT2072861996/issues)
- 💬 在特定硬件配置仓库提问
- 🌐 [r/Hackintosh](https://reddit.com/r/hackintosh)

---

## 📈 仓库统计

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=WT2072861996&show_icons=true&theme=dark&hide_title=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=WT2072861996&layout=compact&theme=dark&hide_title=true)

</div>

---

## 🏆 社区贡献

✨ 感谢所有为 Hackintosh 社区做出贡献的开发者和用户

- **OpenCore 团队** - 现代化引导程序
- **Dortania** - 详尽的安装指南
- **acidanthera** - 高质量的 Kext 驱动
- **中文 Hackintosh 社区** - 本地支持与反馈

---

## 📞 联系方式

<p align="center">
  <a href="https://github.com/WT2072861996"><img src="https://img.shields.io/badge/GitHub-@WT2072861996-black?style=social" /></a>
  <a href="https://github.com/WT2072861996/WT2072861996/issues"><img src="https://img.shields.io/badge/Issues-Questions-blue?style=social" /></a>
</p>

---

## 📄 许可证

所有项目均采用 **MIT License** 发布。

> ⚠️ **免责声明**：在非 Apple 硬件上安装 macOS 可能违反 Apple EULA。本项目仅供学习和研究使用。

---

<p align="center">
  Built with ❤️ for the Hackintosh Community · © 三清科技<br/>
  <sub>Last Updated: 2026 · OpenCore 1.0x Series</sub>
</p>
