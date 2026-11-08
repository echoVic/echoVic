# Hi, I'm echoVic (青雲) 👋

📍 **Guangzhou** | 🤖 **Agent Developer** | 🏢 **ByteDance**

![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Electron](https://img.shields.io/badge/-Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)

> I build coding agents and the tools around them, then write down what breaks.

## 🔭 Now

- **[Orca](https://orcaagent.dev)** — a DeepSeek-native coding agent for the terminal. Rust, MIT, `npm i -g @blade-ai/orca`.
- **[Pilion Browser](https://github.com/echoVic/pilion-browser)** — a desktop browser that pairs web pages with local or remote agents over the [Agent Client Protocol](https://agentclientprotocol.com). Listed in the official [ACP clients directory](https://agentclientprotocol.com/get-started/clients).
- **Native Mac apps on [MyGo](https://github.com/egoist/mygo)** — Cleanzo, Clipnest, 留白 and 小海底 are Go apps with native windows; 14 PRs of framework fixes and docs are merged upstream.
- **[dsh-usage-stats](https://github.com/echoVic/dsh-usage-stats)** — turns the session log into token, cost and tool-time accounting for the DeepSeek Harness web shell.
- Writing agent internals on [echovic.com](https://echovic.com): source-code handbooks for [Codex](https://www.echovic.com/handbook/codex-internals), [pi](https://www.echovic.com/handbook/pi-internals) and [DeepSeek Harness](https://www.echovic.com/handbook/deepseek-harness-internals), plus postmortems like the Orca result-protocol fix.

## 🚀 Featured

| Project | What it is |
|---------|------------|
| [orca-agent](https://github.com/echoVic/orca-agent) | DeepSeek-native terminal coding agent. TUI for interactive work, `orca exec` for scripts and CI, persistent goal and workflow mode, prefix-cache-friendly prompts. Docs in 7 languages · [orcaagent.dev](https://orcaagent.dev) |
| [boss-skill](https://github.com/echoVic/boss-skill) | Expert-squad pipeline for coding agents: PM, Architect, UI, Tech Lead, Scrum, FE, BE, QA and DevOps, with hard quality contracts, replayable `.boss/` artifacts and an auto-continuation chain. Works with Claude Code, Codex, OpenClaw, Antigravity and Hermes |
| [pilion-browser](https://github.com/echoVic/pilion-browser) | Desktop browser for ACP agents: tabs and history on the left, the page in the middle, your agent on the right. macOS, Windows and Linux builds |
| [教员 · jiaoyuan.app](https://jiaoyuan.app) | 遇事不决问教员：基于教员全部作品的经典语录卡片与 AI 对话，用辩证方法论帮你理清职场、人生与重大决策中的实际困惑。内置账号、积分与内容审核，运行在 Cloudflare Workers 上 |
| [图文工厂 · tietulab.com](https://tietulab.com) | AI image-and-text generator for 小红书 / 微信 / 抖音 creators: one sentence in; topic, 3:4 cards, title, tags and post copy out |
| [Markdown2X](https://markdown2x.com) | Preview, format and publish long-form X Articles from Markdown ([x-article-md](https://github.com/echoVic/x-article-md)) |

*Full project list, with stars and recent commit activity: [echovic.com/projects](https://echovic.com/projects).*

## 🗡️ Blade

The TypeScript side of the same work: [blade-code](https://github.com/echoVic/blade-code), a CLI + Web + headless coding agent (`npm i -g blade-code`), and [blade-agent-sdk](https://github.com/echoVic/blade-agent-sdk), a session-first agent SDK for Node.js (`@blade-ai/agent-sdk`).

## 🍃 Mac apps

Small native apps written in Go on [MyGo](https://github.com/egoist/mygo). Downloads are on each repo's Releases page.

- **[Cleanzo](https://github.com/echoVic/cleanzo)** — a safety-first macOS cleaner: rule-based junk cleanup, disk space analysis, large files, similar photos, an app uninstaller, and app updates as of 0.4. About 8 MB.
- **[Clipnest](https://github.com/echoVic/clipnest)** — keyboard-first clipboard history (⌘⇧V): 1–9 / arrows / scroll to pick, SQLite-backed search across text, code, links and images, snippets and per-app exclusions. macOS and Windows.
- **[留白 · Liubai](https://github.com/echoVic/liubai)** — 极简的 Markdown 写作桌：11 套主题、表格与图片、公式和图表、双链与全文搜索，导出 PDF / Word / HTML；免费开源，Windows 内测中。
- **[小海底 · Little Reef](https://github.com/echoVic/little-reef)** — 用专注时间养出一片小海底：番茄钟、会慢慢长大的水族馆、偶尔来访的鱼，还有 20 种公共领域的实录背景音。

The ecosystem around them: **[awesome-mygo-apps](https://github.com/echoVic/awesome-mygo-apps)** — 33 apps and UI libraries, each verified against its `go.mod`.

## ✍️ Latest posts

<!-- BLOG-POST-LIST:START -->
- [Cleanzo 0.5.0：本地模型、agent 会话和缓存，分开算清楚](https://www.echovic.com/blog/ai/cleanzo-050-ai-space) · 2026-11-07
- [Agent 共用一个浏览器时，怎么隔离标签 ACL：Pilion Agent Spaces](https://www.echovic.com/blog/ai/pilion-agent-spaces) · 2026-11-06
- [agent-desktop 深度解析：不截图，也能让 Agent 操控桌面](https://www.echovic.com/blog/ai/agent-desktop-deep-dive) · 2026-11-04
- [写入全部失败，Agent 却返回成功：Orca 的一次结果协议修复](https://www.echovic.com/blog/ai/orca-exec-blocked-outcome) · 2026-11-02
- [Cleanzo 0.3.0 开发复盘：从「有点慢、会闪」到原生菜单栏面板](https://www.echovic.com/blog/ai/cleanzo-030-native-menubar-retrospective) · 2026-10-31<!-- BLOG-POST-LIST:END -->

More on [echovic.com](https://echovic.com) · [RSS](https://echovic.com/rss.xml)

📖 Long-form: **[给 Vibe Coder 的设计模式](https://github.com/echoVic/design-patterns-for-vibe-coders)** — 17 chapters + 2 appendices on telling which abstractions in AI-written code are worth keeping (HTML / PDF / Markdown).

## 🌍 Upstream contributions

- **[OpenClaw](https://github.com/openclaw/openclaw)** — 18 merged PRs: Feishu/Lark tools and error handling, systemd update safety, Telegram DM policy docs, AGENTS.md template fixes
- **[MyGo](https://github.com/egoist/mygo)** — 14 merged PRs: Windows clipboard formats, named Tester click validation, UI docs and CLI delta baseline fixes
- **[agent-client-protocol](https://github.com/agentclientprotocol/agent-client-protocol)** — Pilion Browser added to the clients directory
- **[Qwen Code](https://github.com/QwenLM/qwen-code)** — MCP `readOnlyHint` annotation support in plan mode
- **[Mastra](https://github.com/mastra-ai/mastra)** — unique `runId` per parallel workflow tool call
- Orca listed in **[awesome-agents](https://github.com/kyrolabs/awesome-agents)**

## Connect

[![Website](https://img.shields.io/badge/-echovic.com-000000?style=flat-square&logo=safari&logoColor=white)](https://echovic.com)
[![X/Twitter](https://img.shields.io/badge/-X/Twitter-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/echo_vic)

---

*"世界无限宽广，我才刚刚启程。"*

<!-- Profile README -->
