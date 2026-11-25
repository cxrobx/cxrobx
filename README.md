# Christopher Robinson

**Enterprise AI strategy & delivery · Systems builder shipping native macOS apps, MCP servers, and multi-agent software.**

I build **local-first desktop software that plugs straight into your AI** — Rust/Tauri and Swift/SwiftUI apps, Model Context Protocol (MCP) infrastructure, and production advisor platforms that turn expensive expertise into software.

[cxventures.io](https://cxventures.io) · [CX Tools Suite](https://cxventures.io/products) · [LinkedIn](https://www.linkedin.com/in/crob1) · Atlanta, GA

---

## Featured Builds

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/cxrobx/cxmail">
        <img src="https://raw.githubusercontent.com/cxrobx/cxmail/main/docs/media/cxmail-demo.gif" alt="CXMail demo" width="100%" />
      </a>
      <br />
      <strong><a href="https://github.com/cxrobx/cxmail">CXMail</a></strong> · <code>Rust · Tauri 2 · React 19 · MCP</code>
      <br />
      Native macOS IMAP/SMTP email client with sandboxed HTML rendering and a built-in MCP server so Claude searches, triages, and drafts in your voice locally. <a href="https://cxventures.io/products/cxmail">Overview →</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/cxrobx/cxtasks">
        <img src="https://raw.githubusercontent.com/cxrobx/cxtasks/main/docs/media/cxtasks-demo.gif" alt="CXTasks demo" width="100%" />
      </a>
      <br />
      <strong><a href="https://github.com/cxrobx/cxtasks">CXTasks</a></strong> · <code>Rust · Tauri 2 · SQLite/FTS5 · MCP</code>
      <br />
      Agentic macOS task manager with MCP capture, script/agent condition tripwires, and bounded background dispatch (Inspect / Run / Build) to Claude Code or Codex. <a href="https://cxventures.io/products/cxtasks">Overview →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/cxrobx/quickask">
        <img src="https://raw.githubusercontent.com/cxrobx/quickask/main/docs/media/quickask-demo.gif" alt="QuickAsk demo" width="100%" />
      </a>
      <br />
      <strong><a href="https://github.com/cxrobx/quickask">QuickAsk</a></strong> · <code>Swift · SwiftUI · Accessibility</code>
      <br />
      <code>⌥Space</code> macOS popup assistant that answers about what is on screen and controls apps in the background using your existing Claude or Codex CLI logins. <a href="https://cxventures.io/products/quickask">Overview →</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/cxrobx/onyx">
        <img src="https://raw.githubusercontent.com/cxrobx/onyx/main/docs/media/onyx-demo.gif" alt="Onyx demo" width="100%" />
      </a>
      <br />
      <strong><a href="https://github.com/cxrobx/onyx">Onyx</a></strong> · <code>Python · macOS · Local-First</code>
      <br />
      Highlight-to-ask reading workspace for HTML, Markdown, and PDF — right-click any passage for <em>ELI5</em>, <em>Prove it</em>, or <em>Ask</em> with verified citations from your own files. <a href="https://cxventures.io/products/onyx">Overview →</a>
    </td>
  </tr>
</table>

---

## Native macOS Software

Source-available and open-source tools built to stay fast, local-first, and composable with coding agents ([full collection](https://cxventures.io/products)):

| Project | Stack | What it does |
|---|---|---|
| **[cxmail](https://github.com/cxrobx/cxmail)** | Rust · Tauri 2 · React 19 · MCP | Direct IMAP/SMTP client with sandboxed rendering, voice-matched drafting, and `cxmail-mcp` |
| **[cxtasks](https://github.com/cxrobx/cxtasks)** | Rust · Tauri 2 · React 19 · SQLite | Multi-crate task workspace with MCP capture, repo tripwires, and snapshot-backed agent runs |
| **[quickask](https://github.com/cxrobx/quickask)** | Swift · SwiftUI · AppKit | Native `⌥Space` screen-aware assistant and background macOS app controller |
| **[onyx](https://github.com/cxrobx/onyx)** | Python · macOS | Local reading companion with streaming answers grounded in a chosen evidence folder |
| **[cxnotes](https://github.com/cxrobx/cxnotes)** | Electron · Whisper · MCP | Dual-track menu-bar meeting recorder, local transcription, and speaker-aware Obsidian filing |
| **[Margin](https://github.com/cxrobx/Margin)** | Electron · Markdown · Alfred · MCP | Signed & notarized screen-edge notebook with live Markdown, Alfred capture, and MCP tools |
| **[DiskSight](https://github.com/cxrobx/DiskSight)** | Swift · SwiftUI · GRDB · MCP | Treemap, sunburst, and icicle disk visualizer with content-hashed duplicate & cache detection |
| **[txt](https://github.com/cxrobx/txt)** | Rust · Tauri 2 · Alfred · MCP | Instant tabbed note windows over plain `.md`/`.txt` files with optional local semantic search |
| **[frosty](https://github.com/cxrobx/frosty)** | Swift · AppKit · SwiftUI · MIT | Open-source macOS Dock replacement that organizes open apps into tidy groups |

---

## MCP Servers & Agent Infrastructure

Systems that connect coding agents to real browsers, local knowledge vaults, enterprise platforms, live meetings, and physical hardware:

| Project | Stack | What it does |
|---|---|---|
| **[zen-mcp](https://github.com/cxrobx/zen-mcp)** | TypeScript · MV3 WebExtension | Drive your daily, already-signed-in Zen/Firefox browser from Claude Code — zero launch flags, zero restarts, container-scoped sessions (20+ tools) |
| **[vault-mcp](https://github.com/cxrobx/vault-mcp)** | Python · Ollama · SQLite FTS5 | Hybrid semantic (768-dim local embeddings) + BM25 search MCP server over local Markdown/Obsidian vaults at zero API cost |
| **[powerapp-mcp](https://github.com/cxrobx/powerapp-mcp)** | Python · FastMCP · Pydantic | 17-tool stateful MCP server that compiles natural language into importable Microsoft Power Apps `.msapp` packages with HTML previews |
| **[meeting-copilot](https://github.com/cxrobx/meeting-copilot)** | SwiftUI · Core Audio · TypeScript | Real-time macOS meeting copilot with local transcription, live coaching, and approval-gated AI workers (Research, Summary, Analysis, Mockup) |
| **[cxdeck](https://github.com/cxrobx/cxdeck)** | TypeScript · Stream Deck SDK | Elgato Stream Deck plugin surfacing blocked or finished Claude Code and agent sessions with one-tap jump-to-focus |
| **[guide-skill](https://github.com/cxrobx/guide-skill)** | Python · Claude Code Skill | Single-file narrated, diagram-first HTML explainers with pure-CSS altitude toggles (ELI5 / ELI14 / ELII), inline SVGs, and Kokoro/Speechify TTS |

---

## Full-Stack & Live Products

- **[Artist Advisory](https://artistadvisory.io)** — AI career intelligence for independent artists: 15 specialized agents over Spotify and social analytics.
- **[PocketBuddy](https://pocketbuddy.org)** — AI personal-finance advisor with 6 domain agents, bank connectivity, and a native iOS companion.
- **[BuildersBuddy](https://buildersbuddy.org)** — Deal analysis and underwriting for home builders and property investors.
- **[telly](https://github.com/cxrobx/telly)** (`Python · FastAPI · Next.js · MCP`) — Multi-user Plex watch intelligence with episode/renewal alerts, upcoming timeline, AI-ranked picks, and per-caller HMAC-authenticated MCP access.
- **[essaybuddy](https://github.com/cxrobx/essaybuddy)** (`TypeScript · Next.js · FastAPI`) — Local-first essay development platform that learns your authentic voice from writing samples.

---

## How I Build

- **Local-first by default.** SQLite/FTS5, on-device Whisper & Ollama embeddings, and direct protocol clients (IMAP/SMTP, Core Audio, Accessibility) — bring your own model or CLI login with no vendor lock-in.
- **MCP-native composability.** Every desktop tool exposes clean, bounded tools so coding agents can read context, capture follow-ups, and draft work without brittle UI scraping.
- **Real native engineering.** Signed & notarized Apple Silicon releases, OS-agnostic Rust workspace boundaries (`cxtasks-core`), snapshot-and-rollback safety envelopes for unattended agents, and automated test suites.

**Core Stack:** `Rust` · `Swift / SwiftUI` · `TypeScript` · `Python` · `Tauri 2` · `React 19` · `Next.js` · `FastAPI` · `SQLite / FTS5` · `PostgreSQL` · `MCP` · `Claude API & Agent SDK`
