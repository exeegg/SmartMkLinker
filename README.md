# SmartMkLinker
🚀 基于 mklink 技术的 Windows 11 路径映射软件。通过软件链接方式把实际数据存储路径重定向到其它盘符或磁盘。同时针对 ComfyUI 多环境共用模型的情况，通过目录重定向消除冗余文件，使多个ComfyUI环境共用同一个模型目录，节省大量磁盘空间，省去手动输入命令行的麻烦。
# 🚀 SmartMkLinker (Windows11 链接映射创建软件)

![Platform](https://img.shields.io/badge/Platform-Windows%2011-blue)
![Version](https://img.shields.io/badge/Version-v1.28%20Stable-green)

**告别磁盘红条！让多个 ComfyUI 实例共享百 GB 模型，空间利用率提升。**

## 💡 为什么需要 SmartMkLinker？

在处理 Stable Diffusion 或 ComfyUI 时，每个实例动辄几十 GB 的 `models` 或 `output` 文件夹是磁盘空间的“头号占用”。

**SmartMkLinker** 通过 Windows 底层文件系统重定向技术（mklink），将不同位置的“虚假路径”统一指向同一个“物理存储中心”。
- **不再重复下载**：多套 ComfyUI 只需一份模型数据。
- **跨盘空间优化**：将 C 盘沉重数据一键重定向至大容量机械硬盘或高速 SSD。
- **零学习成本**：将复杂的 `mklink /J` 或 `/D` 命令封装进精致的 Windows 11 原生界面。

---

## ✨ 核心亮点

- **🎨 视觉美学**：深度适配 Windows 11 ，彩色矢量图标，严谨而不失活泼。
- **⚡ 极速映射**：支持三组方案并行配置，批量处理，秒级完成。
- **🛡️ 数据安全**：内置冲突检测，自动提供 `_old` 重命名方案，保护原始数据不丢失。
- **📦 绿色纯净**：由“软件蛋”与 Google AI 联合打造的独立单文件 (.exe)，双击即用，无需安装。

---
## ✨ 不足

- **✨ 还有一些不足的地方 **：如果更新comfyui内核，原来的链接目录则需要重新配置。


## 🤝 致谢

本软件由 **[软件蛋 (Software Egg)](https://exeegg.com)** 与 **Google AI** 跨界合作开发。我们利用 AI 的代码逻辑能力与人类的审美洞察力，共同打造了这款系统级工具。
