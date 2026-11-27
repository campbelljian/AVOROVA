# AVOROVA V6.0.2 · Windows x64

[简体中文](#简体中文) · [English](#english) · [V6.0.3 软件内更新 / In-app update](RELEASE-V6.0.3.md)

## 简体中文

**独立安装包下载：[GitHub](https://github.com/campbelljian/AVOROVA/releases/download/v6.0.2/AVOROVA-Setup-V6.0.2.exe) · [官网](https://avorova.app/#download)**

GitHub 和官网提供同一份已验收安装包。当前程序 V6.0.3 通过软件内更新提供：新用户先安装 V6.0.2，再在 AVO 中检查更新。

- 保留主题管理、动态主题、文字与气泡调整、剩余额度电池和官方公告显示。
- 已取消脑洞界面、划词采集、摘录和来源跳转；旧本地记录不删除。
- 内置霓影夜轨（默认）、莓紫晶透和流光幻境。

安装步骤：

1. 下载 `AVOROVA-Setup-V6.0.2.exe`，退出正在运行的 AVO，按安装程序提示完成安装。
2. 打开 AVO，在设置中检查并下载 V6.0.3 更新，按提示正常退出、重新打开。[更新步骤](RELEASE-V6.0.3.md)。
3. 选择主题，预览后点击“启动并应用主题”。现有 Codex 账号继续使用；无需手动替换程序文件。

安装包尚未添加 Windows 发布者签名。文件身份见下表；[安装提示说明](FAQ.zh-CN.md#安装时出现防护提示怎么办)。

## English

**Standalone installer: [GitHub](https://github.com/campbelljian/AVOROVA/releases/download/v6.0.2/AVOROVA-Setup-V6.0.2.exe) · [Website](https://avorova.app/#download)**

GitHub and the website provide the same verified installer. The current V6.0.3 app is delivered through in-app updates: install V6.0.2 first, then check for updates inside AVO.

- Retains theme management, motion themes, text and bubble customization, the remaining-quota battery, and official announcement display.
- Removes the Brainstorm interface, text capture, excerpts, and source navigation. Existing local records are retained.
- Includes Neon Nocturne (default), Berry Glass, and Luminous Flow.

Setup:

1. Download `AVOROVA-Setup-V6.0.2.exe`, exit any running AVO instance, and follow the installer prompts.
2. Open AVO, check for V6.0.3 in settings, download it, then exit and reopen as prompted. [Update steps](RELEASE-V6.0.3.md#english).
3. Choose and preview a theme, then select “Launch & apply theme”. Continue using your existing Codex sign-in.

The installer has no Windows publisher signature. Verify its identity below; see the [installation notes](FAQ.en.md#what-if-i-see-a-security-warning-during-installation).

## 文件校验 · File verification

| 项目 / Item | 值 / Value |
| --- | --- |
| 安装器版本 / Installer version | V6.0.2 / 6.0.2.0 |
| 平台 / Platform | Windows x64 |
| 文件 / File | `AVOROVA-Setup-V6.0.2.exe` |
| 大小 / Size | 114,717,184 bytes |
| SHA256 | `e128db093427c74f39f1c24f16cd51d6d2619d5c323e4ce64587da7f339f2e6d` |
| Windows 发布者签名 / Publisher signature | 未签名 / NotSigned |

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath .\AVOROVA-Setup-V6.0.2.exe
```

本仓库提供产品介绍和发行资料，不公开主程序源码。AVOROVA 是独立项目，与 OpenAI 无隶属关系或官方背书。

This repository contains product information and release materials, not the application source code. AVOROVA is independent and is not affiliated with or endorsed by OpenAI.
