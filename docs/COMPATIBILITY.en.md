# Codex compatibility and verification history

[Back to the overview](../README.en.md) · [简体中文](COMPATIBILITY.zh-CN.md)

**Your version is not listed? That does not mean it is incompatible.** Codex has updated frequently during development, and AVOROVA has undergone multiple rounds of compatibility work. This is a record of versions and features actually tested, not a compatibility allowlist. Unlisted versions may work too.

As of October 30, 2026, existing records cover runtime tests on at least **17 Codex Windows Store package versions**. These include targeted automated tests and hands-on user validation, with different coverage for each version. Historical results refer to the AVOROVA build used at the time; the current build has not been fully retested against every older package.

## Current hands-on test baseline

| Product or identifier | Version |
| --- | --- |
| AVOROVA | 4.0.0.10 |
| Codex application version | **26.1027.30824** |
| Corresponding Windows Store package version | **26.1027.3384.0** |

The two Codex numbers identify the same installation using different numbering conventions. They are not counted as two separate compatibility targets.

The current baseline has been validated for themed launch, video playback and pause, composer surroundings, retained Brainstorm notes, saving excerpts from user and assistant messages, copying excerpts, returning to the source window, brand icons, and terminal display/input. True glass transparency was validated on the host computer. The test virtual machine still showed a black background with the cause unresolved, so identical glass behavior is not promised across all graphics environments.

“Return to source window” does not guarantee exact navigation to any historical message. Exact navigation still needs further adaptation. New Codex releases may affect individual features; we continue to follow these changes. Report issues with your versions and reproduction steps to [8849412@qq.com](mailto:8849412@qq.com).

## Historical verification record

All Codex identifiers below are **complete Windows Store package versions**. The 17-version count excludes packages that were merely downloaded or inspected, and experiments performed only on isolated application copies.

| Codex Store package | Recorded date | AVOROVA stage at the time | Main verified scope |
| --- | --- | --- | --- |
| 26.818.5229.0 | Aug 24–25, 2026 | Early prototype | Targeted static, image, animated WebP, and silent-video runtime tests; some motion behavior also confirmed by a user |
| 26.818.8289.0 | Aug 25, 2026 | Early desktop interface | Apply-button, video playback, and in-place Codex restoration lifecycle tests |
| 26.825.6671.0 | Aug 31–Sep 1, 2026 | w0.3 runtime | Unified launch, theme switching, pause/resume, restore/exit; later five-theme and tray tests |
| 26.831.2377.0 | Sep 2–3, 2026 | w0.3.6 development | Launch, terminal, composer, file panel, and foreground text-color tests |
| 26.901.1978.0 | Sep 3–4, 2026 | w0.3.6.9 | Hands-on launch, single-window behavior, glass theme, and terminal validation |
| 26.901.2854.0 | Sep 4–5, 2026 | V1 | Launch, branching, terminal, themes, transparent settings, restoration, tray, and a second cold start |
| 26.901.6511.0 | Sep 9, 2026 | V2 | Launch and theme application/switching; coexistence with Codex++ 1.2.56 at that time |
| 26.908.9136.0 | Sep 26, 2026 | V3 | Conversation bubbles, colors/opacity, per-theme preferences, persistence, and restoration cleanup |
| 26.924.2738.0 | Sep 29, 2026 | V3 | Launch, glass transparency, colored frame, and external image opening; split-screen still awaited a fix then |
| 26.928.1915.0 | Runtime records Oct 25–30, 2026 | V4, later 4.0.0.9 | Host Brainstorm saving/reopening and glass transparency; application version 26.928.20755 |
| 26.928.2636.0 | Sep 30, 2026 | V3 | Themes, quota battery, existing chats, terminal, Windows split-screen, exit and restart |
| 26.928.4866.0 | Oct 2 and 8, 2026 | V3→V4 | Updated Store installation paths, full theme runtime, and controlled compatibility fallback |
| 26.1002.7124.0 | Oct 8, 2026 | V4 | New window/terminal layouts, themes, battery, terminal commands, and announcements; exit leftovers handled separately |
| 26.1007.2314.0 | Oct 15, 2026 | V4 | Glass, split-screen restoration, video pause/resume, battery, and two exit paths |
| 26.1013.4894.0 | Oct 17, 2026 | V4 | Targeted video, battery, glass, terminal, image opening, split-screen, composer, and exit validation |
| 26.1021.3705.0 | Oct 24–25, 2026 | V4 | Theme video, assistant-message capture, complete Brainstorm saving/reopening; historical navigation remained limited |
| 26.1027.3384.0 | Oct 30, 2026 | 4.0.0.10 | Agreed test scope on two machines; see the current baseline above |

A historical result does not automatically carry over to every later Codex or AVOROVA release. Themes, glass rendering, and returning to message sources can also have different compatibility behavior.

## Why not decide only by version number?

AVOROVA's themed-launch path checks actual modules and window structure instead of allowing only the version numbers in this table. Codex internals can change, however, and some features need separate adaptation. You can try an unlisted version; reports about any affected feature help us extend the verification record.

Historical Codex++ coexistence tests are not a blanket guarantee for every Codex++ version or relay service. Service and model availability depend on your configuration and provider. AVOROVA does not display third-party API relay balances yet.
