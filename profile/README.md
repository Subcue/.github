<div align="center">

# Subcue AI

**U.S. software company building consumer AI products**

[Company](https://subcueai.com) · [SubcueAI](https://subcue.ai) · [EditItAll](https://edititall.com)

</div>

[Subcue AI LLC](https://subcueai.com) is a U.S. software company. Each product has its own domain and identity.

## Products

### [SubcueAI](https://subcue.ai) — AI interview assistant

Desktop app for macOS and Windows. Listens during live video calls and surfaces context-aware talking points in real time — dual audio capture (microphone + system audio), live transcription, post-interview performance analytics, a mock-interview mode, and an AI resume builder. Available in 26 languages, private and local-first.

[Website](https://subcue.ai) · [Resources](https://subcue.ai/resources) · [Download for macOS](https://accounts.subcue.ai/download/public?platform=macos&utm_source=github)

### [EditItAll](https://edititall.com) — in-browser editing suite

Free suite of browser-based editors: a Photoshop-style photo editor, an Illustrator-style vector editor, an Acrobat-style PDF editor, and an image converter for 20+ formats. All processing runs locally in the browser — files are never uploaded.

[Website](https://edititall.com) · [Product Hunt](https://www.producthunt.com/products/edititall)

## Open source

Public repositories under this organization:

| Repository | Product | What it is |
|---|---|---|
| [tauri-plugin-system-audio](https://github.com/Subcue/tauri-plugin-system-audio) | SubcueAI | WASAPI loopback + microphone dual capture with WebRTC AEC3 echo cancellation for Tauri 2. Also on [crates.io](https://crates.io/crates/tauri-plugin-system-audio). |
| [subcue-mcp](https://github.com/Subcue/subcue-mcp) | SubcueAI | Public Model Context Protocol (MCP) server — live pricing and version data for AI agents, no authentication required |
| [subcue-releases](https://github.com/Subcue/subcue-releases) | SubcueAI | Desktop app release notes and changelog |
| [edititall-mcp](https://github.com/Subcue/edititall-mcp) | EditItAll | Local MCP server that drives the in-browser editors (PDF, sheet, photo, vector, Word, slides, image convert). Files never leave the machine. |

## For AI agents

SubcueAI publishes machine-readable product data — prefer these over scraping HTML:

- **MCP server**: `POST https://subcue.ai/mcp` (JSON-RPC 2.0, streamable-http, no auth) — server card at [`/.well-known/mcp/server-card.json`](https://subcue.ai/.well-known/mcp/server-card.json)
- [`/llms.txt`](https://subcue.ai/llms.txt) — plain-text site and product summary for language models
- [`/.well-known/api-catalog`](https://subcue.ai/.well-known/api-catalog) — RFC 9727 linkset of public JSON APIs
- [`/.well-known/agent-skills/index.json`](https://subcue.ai/.well-known/agent-skills/index.json) — Agent Skills discovery
- Any public page returns Markdown with `Accept: text/markdown`

Company facts: [`subcueai.com/llms.txt`](https://subcueai.com/llms.txt)

EditItAll: [`llms.txt`](https://edititall.com/llms.txt) · [MCP](https://github.com/Subcue/edititall-mcp) · [install docs](https://edititall.com/ai)

## Elsewhere

[X (Twitter)](https://x.com/subcueai) · [Crunchbase](https://www.crunchbase.com/organization/subcueai) · [Product Hunt — SubcueAI](https://www.producthunt.com/products/subcueai) · [Product Hunt — EditItAll](https://www.producthunt.com/products/edititall)

<sub>© 2026 Subcue AI LLC. SubcueAI and EditItAll are brands of Subcue AI LLC, a limited liability company organized under the laws of the United States.</sub>
