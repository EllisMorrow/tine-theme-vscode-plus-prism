<div align="center">

# VS Code Plus · Prism

**A white page opens like morning; charcoal gathers the last light. Blue marks the way between ideas.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-007ACC?labelColor=1E1E1E)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-007ACC?labelColor=1E1E1E)
[![License: MIT](https://img.shields.io/badge/license-MIT-007ACC?labelColor=1E1E1E)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-vscode-plus-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-vscode-plus-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-vscode-plus-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

The familiar Light+ and Dark+ palettes pair bright paper-white with a quiet charcoal canvas, linked by VS Code’s classic blue accent.

Explore the full [Prism theme gallery](https://github.com/martinkoutecky/tine/discussions/786) to compare all 29 themes in light and dark modes.

### Dark mode

![VS Code Plus · Prism in Tine dark mode](docs/vscode-plus-dark.png)

### Light mode

![VS Code Plus · Prism in Tine light mode](docs/vscode-plus-light.png)

*Actual Windows Tine screenshots supplied after testing. Both palettes are included in this package.*

## Install

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-vscode-plus-prism/releases/latest/download/theme.json).
2. In Tine, open **Settings → Appearance → Theme packages → Select theme.json** and select the downloaded file.
3. Choose **Use colors**, then select **Light**, **Dark** or **System** mode.

Requires Tine Theme API **0.2** support. Existing `logseq/custom.css` and device accent settings may affect the result. This package supplies colors only; typography, layout, task markers and other roles outside the theme API remain host-controlled.

## Palette

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#FFFFFF` | `#1E1E1E` |
| Sidebar | `#F3F3F3` | `#252526` |
| Body | `#000000` | `#D4D4D4` |
| Heading | `#000000` | `#D4D4D4` |
| Accent | `#007ACC` | `#007ACC` |
| Links | `#006AB1` | `#4FC1FF` |
| Tags | `#800080` | `#C586C0` |
| Mark background | `#FFF2CC` | `#51472f` |

## Tested in Tine

The manifest passed the official theme checker. A Chromium fixture checked both complete token sets, mode switching and specified contrast pairs. The user supplied the real Windows light/dark screenshots above using Tine's public welcome graph. The visible headings, body, outlines, links, tags, inline code and reference panels are shown; mark highlights, selection behavior, Settings and other platforms are not established by these images. See [screenshot notes](docs/screenshots.md).

## Source and scope

Based on [Visual Studio Code Light+ / Dark+](https://github.com/microsoft/vscode) at `4bda7217fc83e8e838b1edd9ebaf21bb9b498c7e`, under MIT; see [LICENSE](LICENSE). Based on Microsoft VS Code built-in Light+ and Dark+ themes at fixed revision 4bda7217fc83e8e838b1edd9ebaf21bb9b498c7e; both are in the official repository under MIT. Tine role mappings are independent adaptations.

Independent community adaptation by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`). No Codex program code, logo or bundled assets are included. No affiliation or endorsement is claimed.

Only the 21 supported literal color roles per mode are packaged. It does not claim pixel-for-pixel reproduction of Codex, or that all Tine-derived and opacity-dimmed text meets a contrast target. Check results and actual application coverage are recorded in [adaptation notes](docs/adaptation.md).

## Feedback

[Open an issue](https://github.com/EllisMorrow/tine-theme-vscode-plus-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content. The download badge counts GitHub Release asset downloads, not installations or unique users.
