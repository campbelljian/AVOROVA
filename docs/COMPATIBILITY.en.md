# Codex compatibility

[Back to the overview](../README.en.md) · [简体中文](COMPATIBILITY.zh-CN.md)

**Your version is not listed? That does not mean it is incompatible.** Codex has updated frequently during AVOROVA's development, and we have made multiple rounds of compatibility improvements. These are versions actually tested, not a list of the only supported versions. Unlisted versions may work too.

As of November 1, 2026, records cover at least **18 Codex Windows Store package versions**. The features tested vary by version. Historical results refer to the AVOROVA version available at the time; the current version has not been fully retested against every older package.

V6.0.1 is designed for **original Codex on Windows x64**. These records cover Windows Store installations. Other installation sources or launch entry points require separate verification; application names or filenames alone do not establish compatibility. [V6.0.1 release notes](RELEASE-V6.0.1.md#english).

## Most recently verified Codex version

| Version identifier | Version |
| --- | --- |
| Windows Store package version | **26.1027.6604.0** |

On November 1, 2026, the author tested this version and confirmed that it works with AVOROVA.

Historically verified features include themed launch, video playback and pause, composer display, retained Brainstorm notes, saving excerpts from user and assistant messages, copying excerpts, returning to the source window, and terminal display/input. Glass transparency can vary by graphics environment; some environments may show a black background.

V6.0.1 completed scoped post-install checks for original Codex launch, video playback controls, Luminous Flow mode selection, title-bar quota and Brainstorm, saving and copying excerpts, returning to the source window, and Chinese/English UI. Those release checks used a fresh installation; migration of older notes was not tested. Historical results do not mean the current build was fully retested against every older version.

“Return to source window” does not guarantee exact navigation to any historical message. New Codex releases may also affect individual features, and we continue to follow these changes. Report issues with your versions and reproduction steps to [8849412@qq.com](mailto:8849412@qq.com).

## Verified version history

The table uses **complete Windows Store package versions** and lists the main features verified for each.

| Codex Store package | Verification date | Main verified features |
| --- | --- | --- |
| 26.818.5229.0 | 2026-08-24–25 | Image, animated WebP, and silent-video themes |
| 26.818.8289.0 | 2026-08-25 | Applying themes, video playback, and restoring Codex |
| 26.825.6671.0 | 2026-08-31–09-01 | Launch, theme switching, pause/resume, restore/exit, and tray controls |
| 26.831.2377.0 | 2026-09-02–03 | Launch, terminal, composer, file panel, and text colors |
| 26.901.1978.0 | 2026-09-03–04 | Launch, single-window display, glass themes, and terminal |
| 26.901.2854.0 | 2026-09-04–05 | Launch, branching, terminal, themes, transparent settings, restore, and tray controls |
| 26.901.6511.0 | 2026-09-09 | Launch and applying/switching themes |
| 26.908.9136.0 | 2026-09-26 | Conversation bubbles, colors/opacity, per-theme preferences, and saved settings |
| 26.924.2738.0 | 2026-09-29 | Launch, glass transparency, colored frame, and external image opening; split-screen had issues at the time |
| 26.928.1915.0 | 2026-10-25–30 | Saving/reopening Brainstorm notes and glass transparency; application version 26.928.20755 |
| 26.928.2636.0 | 2026-09-30 | Themes, quota battery, existing chats, terminal, split-screen, exit/restart |
| 26.928.4866.0 | 2026-10-02, 08 | Detecting the updated Store installation and running themes |
| 26.1002.7124.0 | 2026-10-08 | Window/terminal layouts, themes, battery, terminal commands, and announcements; exit cleanup was fixed later |
| 26.1007.2314.0 | 2026-10-15 | Glass, split-screen restoration, video pause/resume, quota battery, and exit |
| 26.1013.4894.0 | 2026-10-17 | Video, battery, glass, terminal, image opening, split-screen, composer, and exit |
| 26.1021.3705.0 | 2026-10-24–25 | Theme video, capturing assistant messages, and saving/reopening Brainstorm notes; exact historical navigation was limited |
| 26.1027.3384.0 | 2026-10-30 | Themed launch, video pause/resume, Brainstorm capture/copy, returning to the source window, and terminal; application version 26.1027.30824 |
| 26.1027.6604.0 | 2026-11-01 | Tested by the author; compatibility confirmed after the Codex update |

Historical results do not automatically carry over to every later release. Themes, glass rendering, and returning to message sources can also have different compatibility behavior.

## Can I use an unlisted version?

You can try it. AVOROVA checks the application's actual structure rather than allowing only the versions in this table. As Codex continues to change, some features may need further compatibility work. Reports about your experience help us improve support.
