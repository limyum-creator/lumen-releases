# 光栈 Lumen

<p align="center">
  <b>让灵感随时延续，让创作秩序井然。</b><br>
  专为 Apple Silicon Mac 打造的 AI 视觉创作与资产管理工作台。
</p>

<p align="center">
  <a href="https://github.com/limyum-creator/lumen-releases/releases/latest"><img src="https://img.shields.io/badge/Release-v0.8.0-orange?style=flat-square" alt="Release"></a>
  <img src="https://img.shields.io/badge/Platform-macOS%2014%2B%20(Apple%20Silicon)-blue?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/Engine-ComfyUI%20%7C%20RunningHub-green?style=flat-square" alt="Engine">
  <img src="https://img.shields.io/badge/Extension-MCP%20Agent-purple?style=flat-square" alt="MCP">
</p>

<p align="center">
  <a href="https://github.com/limyum-creator/lumen-releases/releases/latest">📦 立即下载 DMG</a> · 
  <a href="QUICKSTART.md">⚡ 3 分钟快速上手</a> · 
  <a href="Agent连接指南.txt">🤖 AI / Agent 接入指南</a> · 
  <a href="https://github.com/limyum-creator/lumen-releases/issues">💬 问题与反馈</a>
</p>

---

## 为什么需要光栈？

做 AI 图像与视频创作时，你是否也经常遇到这些烦恼：

- **灵感四散**：收集的参考图存了一堆，真正想用时却翻遍桌面和访达；
- **版本丢失**：跑出了一张惊艳的结果，隔几天想微调，却再也找不到当时的 Prompt、Seed 和工作流参数；
- **窗口割裂**：浏览器开着 ComfyUI，备忘录记着提示词，访达堆满各版本的测试图，来回切换极其低效。

**光栈（Lumen）把创作的全链路收拢在一个优雅顺手的 Mac 本地工作台里：**  
从**灵感收集**、**无限画布推演**，到**直连工作流生成**与**版本溯源**——下一次打开，随时接着上一次的想法继续探索。

---

## 核心亮点

### 🖼️ 原生极速图库 · 找回每一张图的“来龙去脉”
- **全格式混排与空格预览**：图片原比例呈现，视频、音频同库流畅播放；按空格键即刻全屏沉浸预览。
- **参数全生命周期还原**：随时调取该版本的正负提示词、种子、模型及采样参数。英文提示词内置中文双语对照，原样复制绝不串味。
- **多版本平铺与同屏对比**：同一个作品允许容纳多次尝试迭代。把最满意的设为封面，其他版本完整保留，支持两张图并排放大比对细节。
- **智能监听文件夹**：只需把输出目录或灵感文件夹加入监听，新素材自动同步收录进库，保留完整来源。

### 🎨 无限创作画布 · 像导演一样摆开你的分镜
- **白板级自由排布**：参考图、提示词卡、工作流参数、便签、音视频均可自由拖拽、缩放、成组整理。
- **结构化叙事组织**：专为连续创作设计的架构：**项目 → 单集 → 单元**。公共角色与场景常驻共享层，各单元独立维护分镜、镜头时长、台词与镜头提示词。
- **所见即所得的节点关联**：将参考图与提示词直接连线接入产出卡，直观查看每一张图由哪些元素孕育而来。

### ⚡ 双引擎驱动 · 直连 ComfyUI 与 RunningHub
- **本地 ComfyUI 协同**：无缝连接本地 ComfyUI 服务，独立配置产出卡的工作流与模型参数。常调参数可单独展开悬挂在手边。
- **RunningHub 云端无缝生成**：粘贴工作流链接或 ID 即可直接调用云端算力；生成完毕自动将图片/视频回收至本地图库，支持 ZIP 结果包自动解压归档。
- **版本固定与受控执行**：产出卡可跟随最新跑图，也可一键“固定此版本”。每次生成均记录真实 Seed，复现不抓瞎。

### 🤖 现代 Agent 协作 · 原生支持 MCP 协议
- 内置 MCP（Model Context Protocol）服务，无需繁琐配置 Python 环境。
- 导出接入文档，即可让 OpenClaw、Claude Desktop 等具备本地能力的 AI 助手读取你的项目资产、帮你整理单集分镜、推敲润色提示词。

### 🔒 100% 本地优先 · 隐私与数据全掌控
- **目录即图库**：所有媒体资产、版本关联与项目数据全部存放在你指定的本地目录中。无需联网也能随心浏览和整理。
- **凭据安全隔离**：云端 API 凭证均安全托管于 macOS 原生钥匙串（Keychain）。

---

## 快速下载与安装

### 系统要求
- **硬件**：配备 Apple Silicon 芯片的 Mac（M1 / M2 / M3 / M4 系列）
- **系统**：macOS 14 (Sonoma) 或更高版本

### 安装步骤
1. 前往 **[Releases 页面](https://github.com/limyum-creator/lumen-releases/releases/latest)** 下载最新的 `.dmg` 安装包；
2. 打开安装包，将 **光栈.app** 拖入 **应用程序（Applications）** 目录；
3. 首次启动若提示“无法打开，因为无法验证开发者”，前往 **系统设置 → 隐私与安全性**，点击 **仍要打开** 即可。

> 💡 更多图文指引与使用秘诀，请参阅 **[3 分钟快速上手指南](QUICKSTART.md)**。

---

## 创作生态与规划说明

- **算力与环境**：光栈专注于提供一流的工作台体验，ComfyUI 依赖的本地模型/节点环境，或 RunningHub 账号额度请按需自行准备。
- **数据备份**：如需备份或迁移图库，只需完整复制你的图库文件夹（请确保保留其中的隐藏目录 `.lumen`，这里记录了所有版本关联与项目元数据）。
- **持续进化中**：我们正高频迭代分镜体验、节点交互与资产流转。有任何想法或遇到 Bug，欢迎在 [Issues](https://github.com/limyum-creator/lumen-releases/issues) 随时交流！
