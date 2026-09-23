<a href="https://github.com/limyum-creator/lumen-releases/releases/tag/v0.8.5">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/lumen-cover-dark.png">
    <img src="assets/lumen-cover-light.png" width="100%" alt="光栈 Lumen — 灵感有处安放，创作随时继续。">
  </picture>
</a>

<p align="center">
  <b>让灵感随时延续，让创作秩序井然。✨</b><br>
  为 Mac 上的图像与视频创作者准备的本地图库、项目画布和 AI 工作台。
</p>

<p align="center">
  <a href="https://github.com/limyum-creator/lumen-releases/releases/tag/v0.8.5"><img src="https://img.shields.io/badge/Beta-0.8.5-4088CE?style=flat-square" alt="当前内测版 0.8.5"></a>
  <img src="https://img.shields.io/badge/macOS-14%2B-64748B?style=flat-square&amp;logo=apple&amp;logoColor=white" alt="macOS 14 或更新版本">
  <img src="https://img.shields.io/badge/Chip-Apple%20Silicon-64748B?style=flat-square" alt="仅支持 Apple Silicon">
</p>

<h3 align="center">
  <a href="https://github.com/limyum-creator/lumen-releases/releases/tag/v0.8.5">📦 下载 0.8.5 内测版</a>
</h3>
<p align="center">
  <a href="QUICKSTART.md">⚡ 快速上手</a>
  &nbsp;·&nbsp; <a href="Agent连接指南.txt">🤖 Agent 接入</a>
  &nbsp;·&nbsp; <a href="https://github.com/limyum-creator/lumen-releases/issues">💬 反馈想法</a>
</p>

<br>

## 👋 给灵感一个好找的家

参考图存了一堆，想用的时候找不到；跑出满意的结果，过几天却忘了当时的提示词和参数。再加上 ComfyUI、访达和备忘录来回切换——创作还没开始，先忙着找东西了。

**光栈想把这些零散的小事接起来。** 收好素材，在画布上铺开想法，连接工作流继续创作，再把结果和来龙去脉一起留下。下次打开，不必从头回忆。

> ✨ **0.8.5 已上线** · 这次主要打磨了全局界面、局部动效和画布交互，也修正了多张参数卡加载时误写配置的问题。[更新详情](https://github.com/limyum-creator/lumen-releases/releases/tag/v0.8.5)

<br>

## 🧰 把时间留给创作

### 🖼️ 图库不只是「把图存起来」

图片、视频和音频放在同一个库里，参考与作品各有归处。想找细节？按一下 <kbd>空格</kbd>，先看大图再说。

- **同一作品，多次尝试。** 保留不同版本，挑一张做封面，也可以把两张图放在一起比对。
- **好结果，有迹可循。** 查看版本中记录的提示词、种子与生成参数，不再靠文件名猜。
- **少搬运，多创作。** 把常用目录加入监听，新素材自动收录，来源文件照样保留。

### 🎨 想法还没理顺？先摆到画布上

参考图放左边，提示词写旁边，工作流参数留在手边。把它们连到产出卡上，你能看见一张图是怎么慢慢成形的。

- 参考、提示词、便签、参数与产出卡自由排布，支持拖动、缩放和成组整理。
- 用 **项目 → 单集 → 单元** 组织连续创作，分镜、台词与镜头提示词各有位置。
- 角色、场景等共享素材不用每个单元重新找一遍；已有手动布局不会因为切换而被自动重排。

### ⚡ 本地跑，还是云端跑？都能接着做

你熟悉的工作流不必换掉。光栈连接 **ComfyUI / RunningHub**，让调参数、看结果和整理版本少一点来回跳转。

- 每张产出卡独立选择工作流，常用参数可以展开在画布上。
- 生成结果回收到本地图库，继续挑选、比较，或接着下一轮尝试。
- 喜欢某个版本就固定下来；也能设置项目默认产出、跨单元批量排队。

<sub>生成后端是可选项。模型、节点、账号及云端额度需要自行准备；第三方工作流的兼容范围以实际环境为准。</sub>

### 🤖 让 Agent 当搭档，不只是聊天框

通过内置 **MCP** 接口，让 OpenClaw、Claude Desktop 等具备本地能力的助手读懂你的项目，帮忙整理分镜、梳理素材或润色提示词。

随包提供运行环境和接入说明，**不用为了连接再安装 Python**。[连接你的 Agent →](Agent连接指南.txt)

### 🏡 图库在你选的文件夹里

原图、版本关系和项目资料保存在本地。没连生成后端，也可以浏览与整理；需要云端生成时，再连接相应服务。

想换一台 Mac？先退出应用，把图库目录完整备份，记得带上隐藏的 **`.lumen`** 文件夹——作品之间的关系也住在那里。

<br>

## 🚀 三分钟，开始用

**当前版本：0.8.5（22.7）** · Apple Silicon · macOS 14+ · 免费内测，无需激活码。

**① 下载并安装**

从 [Release 页面](https://github.com/limyum-creator/lumen-releases/releases/tag/v0.8.5) 下载 **[Lumen-0.8.5-arm64.dmg](https://github.com/limyum-creator/lumen-releases/releases/download/v0.8.5/Lumen-0.8.5-arm64.dmg)**，打开后把「光栈.app」拖进「应用程序」。升级前先退出旧版，原图库和设置保留。

**② 给素材安个家**

第一次打开，选择新建图库或打开已有图库。把常用的素材目录加入监听，先从几张喜欢的参考图开始就好。

**③ 按你的节奏继续**

只想整理素材？直接用图库。准备开始创作？新建项目，再按需连接 ComfyUI、RunningHub 或 Agent。不用一次把所有配置填完。

> 🍎 对外安装包目前**尚未经过 Apple 公证**。首次打开若被系统拦截，请在「系统设置 → 隐私与安全性」中确认打开。只从本仓库 Release 下载，并核对校验值。

<details>
<summary>🔎 如何核对下载文件？</summary>

把 [SHA-256 校验文件](https://github.com/limyum-creator/lumen-releases/releases/download/v0.8.5/Lumen-0.8.5-arm64.sha256) 和 DMG 放在同一目录，在该目录运行：

```sh
shasum -a 256 -c Lumen-0.8.5-arm64.sha256
```

显示 `OK` 即表示文件与发布时的校验值一致。

</details>

<details>
<summary>🙋 Intel Mac / Windows 能用吗？仓库里的 Source code 是什么？</summary>

目前仅提供 Apple Silicon（M1 及更新芯片）的 macOS 安装包，暂不支持 Intel Mac 或 Windows。

这里是光栈的**下载与使用资料仓库**，不是客户端源码仓库。GitHub 自动生成的 “Source code” 压缩包不是安装包，请下载 `.dmg`。

</details>

<br>

## 💬 一起把光栈打磨得更顺手

光栈还在内测。哪一步卡手、哪个按钮找不到，或是「要是能这样就好了」——都欢迎[开个 Issue 聊聊](https://github.com/limyum-creator/lumen-releases/issues)。

报问题时，带上版本号、macOS 版本和复现步骤会很有帮助；附图前记得遮住私密素材、提示词和密钥。真实大型工作流、其他设备和触控板手感还需要更多使用反馈，已知验证范围写在[发布记录](https://github.com/limyum-creator/lumen-releases/releases/tag/v0.8.5)里。

如果光栈刚好帮你省下了一点找图、整理的时间，也欢迎点一颗 **Star**，让更多创作者找到它。🌟

<p align="center">
  <a href="QUICKSTART.md">📖 快速上手</a> &nbsp;·&nbsp;
  <a href="光栈快速上手.txt">完整使用指南</a> &nbsp;·&nbsp;
  <a href="Agent连接指南.txt">Agent 连接指南</a>
</p>
<p align="center"><sub>收好每一次灵光一现。下次打开，接着创作。✨</sub></p>
