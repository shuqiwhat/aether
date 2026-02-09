<p align="center">
  <img src="docs/images/editor.webp
" width="800" alt="Aether" />
</p>

<h3 align="center">
  AI 驱动的 Markdown 编辑器，内置幽灵写作 (Ghost Writing)。<br/>
  写作 · 心流 · 创造 — 享受智能辅助的写作体验。
</h3>

<p align="center">
  <a href="./README.md">English</a> | <strong>中文</strong>
</p>

<p align="center">
  <a href="https://github.com/shuqiwhat/aether/releases">下载</a> ·
  <a href="https://www.shuqihere.top/archive/open-source/aether">文档</a> ·
  <a href="#快速开始">快速开始</a>
</p>

<p align="center">
  <a href="https://github.com/shuqiwhat/aether/stargazers"><img src="https://img.shields.io/github/stars/shuqiwhat/aether?style=social" alt="Stars" /></a>
</p>

---

---

Aether 是一款开源的 Markdown 编辑器，内置 AI 辅助写作功能。目标是提供一个专注、流畅的写作环境。

> ⚠️ **注意**：本项目目前仍处于 **早期开发阶段**，可能会存在 Bug 或不完善之处。欢迎尝鲜，但请注意数据备份。

<p align="center">
  <a href="https://github.com/shuqiwhat/aether/releases"><strong>👉 下载最新版本</strong></a>
</p>

## 功能特性

- ✍️ **幽灵写作** — 实时 AI 补全，在你停顿时自动出现，按 Tab 键接受建议 ([详细介绍](docs/ai-features_zh-CN.md))
- 📝 **所见即所得** — 基于 Tiptap 的真·所见即所得 Markdown 编辑，随时切换源码模式
- 🎨 **精美主题** — 内置明亮/暗黑主题，支持自定义 CSS
- 🔄 **Git 同步** — 简单的 Git 集成，支持定时自动备份和打开时自动拉取
- 📁 **工作区模式** — 文件树侧边栏，模糊搜索，Git 状态指示
- 🔍 **强大搜索** — 全局全文搜索
- 📊 **Mermaid 图表** — 在代码块中渲染流程图、时序图等
- 📤 **多格式导出** — 支持导出 PDF, HTML, DOCX, EPUB, LaTeX (基于 Pandoc)
- ⌨️ **键盘优先** — Vim 风格理念，丰富的快捷键支持 ([快捷键列表](docs/shortcuts_zh-CN.md))
- 🌐 **跨平台** — macOS, Windows, Linux (Electron)

## 截图展示

<table>
  <tr>
    <td align="center"><img src="docs/images/editor.webp" width="400" /><br/><sub>幽灵写作演示</sub></td>
    <td align="center"><img src="docs/images/workspace.webp" width="400" /><br/><sub>带文件树的工作区</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="docs/images/themes.webp" width="400" /><br/><sub>主题选择</sub></td>
    <td align="center"><img src="docs/images/source.webp" width="400" /><br/><sub>源码模式</sub></td>
  </tr>
</table>

## 快速开始

### 下载安装包

从 [Releases](https://github.com/shuqiwhat/aether/releases) 页面下载最新的 `.dmg` (macOS) 或 `.exe` (Windows) 安装包。

## 幽灵写作设置

1. 打开 **设置 (Settings) → 幽灵写作 (Ghost Writer)**
2. 选择提供商：OpenAI, Claude, 或 Ollama (本地模型)
3. 输入 API Key (如果是云端提供商)
4. 开始打字 — 建议会在你停顿时出现

## 常用快捷键

| 动作         | macOS | Windows/Linux |
| ------------ | ----- | ------------- |
| 保存         | `⌘S`  | `Ctrl+S`      |
| 切换侧边栏   | `⌘\`  | `Ctrl+\`      |
| 命令面板     | `⌘P`  | `Ctrl+P`      |
| 切换源码模式 | `⌘/`  | `Ctrl+/`      |
| 接受 AI 建议 | `Tab` | `Tab`         |
| 忽略 AI 建议 | `Esc` | `Esc`         |

## 反馈与联系

本项目目前由个人（Shuqi Wang）维护，精力有限。

- **Bug 反馈 / 功能建议**：非常欢迎提交 [Issue](https://github.com/shuqiwhat/aether/issues) 或 Pull Request。
- **邮件联系**：如有其他问题，可以通过邮件联系我：`shuqiwhat@gmail.com`。

感谢你的关注和试用！

## Star 历史

<a href="https://star-history.com/#shuqiwhat/aether&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=shuqiwhat/aether&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=shuqiwhat/aether&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=shuqiwhat/aether&type=Date" />
 </picture>
</a>

## 许可协议

Copyright © 2026 Shuqi Wang. All rights reserved.

---

<p align="center">
  Built with ❤️ by <a href="https://github.com/shuqiwhat">@shuqiwhat</a>
</p>
