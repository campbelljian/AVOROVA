# AVOROVA V6.0.1

[简体中文](#简体中文) · [English](#english)

## 简体中文

适用于 Windows x64 上的 Codex 原版，当前验证以 Windows 商店版为准。提供独立主题管理界面、图片与视频主题、动效与玻璃主题、文字和气泡调整，以及顶栏脑洞和额度电池。

**下载：[官网独立下载](https://avorova.app/#download) · [GitHub Releases](https://github.com/campbelljian/AVOROVA/releases/tag/v6.0.1)**

官网安装包由自己的服务器提供，不跳转 GitHub。两个渠道的安装包文件相同；版本和校验值见下方。

1. 下载 `AVOROVA-Setup-V6.0.1.exe`，运行安装程序并按提示完成安装。
2. 使用现有 Codex 账号登录，打开 AVOROVA，选择喜欢的主题。
3. 预览后点击“启动并应用主题”。运行后可暂停动态效果或切换主题。
4. 更多主题可在官网预览。网页应用需要浏览器允许打开 AVOROVA；也可下载主题 ZIP，从应用的“导入”入口选择原文件，无需解压。

内置主题：霓影夜轨 **0.1.0**（默认）、莓紫晶透 **0.1.0**、流光幻境 **1.0.1**。流光幻境可在 AVOROVA 或应用后的 Codex 顶栏调整模式：音乐模式跟随音乐律动，输入模式在发送文字后响应，自然流动模式自由流动。

安装包尚未添加 Windows 发布者签名，安装时可能出现“未知发布者”或信誉提示。[安装提示说明](FAQ.zh-CN.md#安装时出现防护提示怎么办)。

**使用边界：**兼容表记录实际验证过的版本，不是限制使用的名单；新版本 Codex 仍可能影响个别功能。脑洞可保存和复制摘录、返回原窗口，不承诺精确定位任意历史消息。玻璃效果受图形环境影响；动效会使用 CPU/GPU 资源。[兼容性说明](COMPATIBILITY.zh-CN.md)。

主题美化不改写 Codex 原始安装文件，效果在运行时加载。AVOROVA 是独立项目，不隶属于 OpenAI，也未获得其官方背书。本仓库不提供主程序源码。

## English

For original Codex on Windows x64. Current verification covers Windows Store installations. Includes a dedicated theme manager, image/video/motion/glass themes, text and bubble adjustments, Brainstorm, and title-bar quota display.

**Download: [Website](https://avorova.app/#download) · [GitHub Releases](https://github.com/campbelljian/AVOROVA/releases/tag/v6.0.1)**

Website downloads are hosted on our own server and do not redirect to GitHub. Both channels provide the same installer; file details are below.

1. Download `AVOROVA-Setup-V6.0.1.exe`, run it, and follow the installation prompts.
2. Sign in with your existing Codex account, open AVOROVA, and choose a theme.
3. Preview it, then select “Launch & apply theme”. Once running, pause motion or switch themes as needed.
4. Preview more themes on the website. Applying from the web requires allowing your browser to open AVOROVA. Alternatively, download a theme ZIP and select the original file using Import in the app; do not unzip it.

Bundled themes: Neon Nocturne **0.1.0** (default), Berry Glass **0.1.0**, and Luminous Flow **1.0.1**. Choose Luminous Flow modes in AVOROVA or the themed Codex title bar: Music reacts to music, Input reacts after sending text, and Natural Flow moves freely.

The installer has no Windows publisher signature. Windows may show an unknown-publisher or reputation prompt. [Installation notes](FAQ.en.md#what-if-i-see-a-security-warning-during-installation).

**Scope:** the compatibility table records tested versions, not an allowlist. New Codex releases may affect individual features. Brainstorm saves and copies excerpts and returns to the source window; exact historical-message navigation is not guaranteed. Glass effects depend on the graphics environment; motion uses CPU/GPU resources. [Compatibility](COMPATIBILITY.en.md).

Theme effects load at runtime without rewriting Codex’s original installation files. AVOROVA is independent and is not affiliated with or endorsed by OpenAI. This repository does not provide the application source code.

## 文件校验 · File verification

| 项目 / Item | 值 / Value |
| --- | --- |
| 版本 / Version | V6.0.1 |
| 平台 / Platform | Windows x64 |
| 文件 / File | `AVOROVA-Setup-V6.0.1.exe` |
| 大小 / Size | 114,804,736 bytes (109.49 MiB) |
| SHA256 | `97ba6bc335bd5766ac40e788f94ec567d2b0db847c5788fa2cb4d51617afb0ff` |
| Windows 发布者签名 / Publisher signature | 未签名 / NotSigned |

PowerShell（在下载目录运行 / run in the download folder）：

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath .\AVOROVA-Setup-V6.0.1.exe
```

核对下载来源与完整 SHA256。校验值确认文件一致，不代替安全检测。

Check the download source and the entire SHA256 value. A matching hash confirms file identity, not a security assessment.
