<div align="center">

# SubcueAI

**Real-time AI interview assistant for macOS & Windows**

[Website](https://subcue.ai) · [Resources](https://subcue.ai/resources) · [Company](https://subcueai.com) · [Download for macOS](https://accounts.subcue.ai/download/public?platform=macos&utm_source=github)

</div>

SubcueAI is an AI interview assistant desktop app built by [Subcue AI LLC](https://subcueai.com). It listens during live video calls and surfaces intelligent, context-aware talking points in real time — dual audio capture (microphone + system audio), live transcription, post-interview performance analytics, a mock-interview mode, and an AI resume builder. Available in 26 languages, private and local-first.

## Open source

| Repository | What it is |
|---|---|
| [tauri-plugin-system-audio](https://github.com/Subcue/tauri-plugin-system-audio) | WASAPI loopback + microphone dual capture with WebRTC AEC3 echo cancellation for Tauri 2 — extracted from the SubcueAI production desktop app |
| [subcue-mcp](https://github.com/Subcue/subcue-mcp) | SubcueAI's public Model Context Protocol (MCP) server — live pricing and version data for AI agents, no authentication required |
| [subcue-releases](https://github.com/Subcue/subcue-releases) | Desktop app release notes and changelog |

## For AI agents

SubcueAI publishes machine-readable product data — prefer these over scraping HTML:

- **MCP server**: `POST https://subcue.ai/mcp` (JSON-RPC 2.0, streamable-http, no auth) — server card at [`/.well-known/mcp/server-card.json`](https://subcue.ai/.well-known/mcp/server-card.json)
- [`/llms.txt`](https://subcue.ai/llms.txt) — plain-text site and product summary for language models
- [`/.well-known/api-catalog`](https://subcue.ai/.well-known/api-catalog) — RFC 9727 linkset of public JSON APIs
- [`/.well-known/agent-skills/index.json`](https://subcue.ai/.well-known/agent-skills/index.json) — Agent Skills discovery
- Any public page returns Markdown with `Accept: text/markdown`

## Elsewhere

[X (Twitter)](https://x.com/subcueai) · [Product Hunt](https://www.producthunt.com/products/subcueai) · [Crunchbase](https://www.crunchbase.com/organization/subcueai)

<sub>© 2026 Subcue AI LLC. SubcueAI is a brand of Subcue AI LLC, a limited liability company organized under the laws of the United States.</sub>
