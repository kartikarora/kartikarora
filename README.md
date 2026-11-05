# Kartik Arora

**Applied AI Engineer** · **Google Developer Expert (Android)** · Sydney, Australia  
[kartikarora.me](https://kartikarora.me) · [LinkedIn](https://www.linkedin.com/in/arorakartik) · [Medium](https://medium.com/@kartikarora)

---

I bridge foundation models with native runtime environments—building agentic workflows, Model Context Protocol (MCP) systems, and production mobile architectures.

```
$ kartik --status
● Role:           Applied AI Engineer & GDE (Android)
● Current Focus:  Agentic Orchestration, MCP Tooling, Multimodal Streaming
● Edge & Cloud:   Cloudflare Workers (D1, R2), Ktor, Firebase, Docker
● Native Mobile:  Kotlin 2.x, Jetpack Compose, KMP, Coroutines & Flow
● Beyond Code:    Polyrhythmic drumming 🥁 & Formula 1 🏎️
```

---

### 🕹️ Interactive CLI & Quick Start

<details>
<summary><b><code>$ npx preview-mcp --help</code></b> — Universal MCP Server for AI Coding Environments</summary>
<br>

Connect AI coding agents (Claude Code, Antigravity, Cursor) directly to live edge previews via stdio, SSE, or JSON-RPC:

```bash
# Test locally via stdio
npx preview-mcp

# Claude Code / Antigravity config:
{
  "mcpServers": {
    "preview": {
      "command": "npx",
      "args": ["-y", "preview-mcp"]
    }
  }
}
```
Public CLI bridge for the Cloudflare edge platform [`previews.kartikarora.me`](https://previews.kartikarora.me).  
Repository: [kartikarora/preview-mcp](https://github.com/kartikarora/preview-mcp)
</details>

<details>
<summary><b><code>$ brew install kartikarora/klaat/klaat</code></b> — Interactive Codelabs CLI & Server</summary>
<br>

Modern Kotlin reimplementation of Google's Codelabs tools for authoring, parsing, and serving interactive documentation:

```bash
brew tap kartikarora/klaat
brew install klaat

# Serve Markdown/Google Doc codelabs locally with live reload:
klaat serve .
```
Includes Homebrew taps [`homebrew-klaat`](https://github.com/kartikarora/homebrew-klaat) & snapshots.
</details>

<details>
<summary><b><code>$ git clone ICanHazStream</code></b> — Real-Time Gemini Multimodal Streaming</summary>
<br>

Hands-on workshop project integrating live audio/video frame streaming into Google Gemini with Jetpack Compose:

```bash
git clone https://github.com/kartikarora/ICanHazStream.git
cd ICanHazStream
```
Repository: [kartikarora/ICanHazStream](https://github.com/kartikarora/ICanHazStream)
</details>

<details>
<summary><b><code>$ gradle add rocketflag-kmp-sdk</code></b> — Feature Flags for Kotlin Multiplatform</summary>
<br>

Type-safe, cross-platform configuration and feature flags on Maven Central:

```kotlin
// build.gradle.kts
dependencies {
    implementation("me.kartikarora.rocketflag:android:latest.version")
}
```
Repository: [kartikarora/rocketflag-kmp-sdk](https://github.com/kartikarora/rocketflag-kmp-sdk)
</details>

<details>
<summary><b><code>$ curl https://sports.kartikarora.me</code></b> — Social Sports Coordinator</summary>
<br>

Live web platform streamlining scheduling, team availability, and match coordination:

- Production App: [sports.kartikarora.me](https://sports.kartikarora.me)
- Stack: Node.js, Express, Firebase Firestore & Authentication
</details>

<details>
<summary><b><code>$ kartik --easter-egg</code></b> — Trivia & Offline Interests</summary>
<br>

- 🥁 Drummer obsessed with polyrhythms, ghost notes, and odd time signatures.
- 🏎️ F1 calendar is always marked off.
- 🇦🇺 Based in Sydney, actively speaking at GDG and mobile developer conferences.
</details>

---

### 🔨 Live & Active Projects (Updated Past Year)

| Project | Access / Stack | Description & Live URL |
| :--- | :--- | :--- |
| [**Previews**](https://previews.kartikarora.me) | 🚀 `Live App` · `Cloudflare Edge` | Ephemeral HTML preview hosting with per-project subdomains, Google OAuth, and D1/R2 storage. |
| [**preview-mcp**](https://github.com/kartikarora/preview-mcp) | 🌐 `Open Source` · `MCP` · `Node` | Universal Model Context Protocol server (stdio, SSE, HTTP JSON-RPC) for AI coding environments. |
| [**klaat**](https://github.com/kartikarora/homebrew-klaat) | 📦 `CLI Tool` · `Kotlin` · `Homebrew` | Modern Kotlin CLI authoring & serving tool for interactive codelabs (Google Codelabs reimplementation). |
| [**ICanHazStream**](https://github.com/kartikarora/ICanHazStream) | 🌐 `Open Source` · `Kotlin` · `Gemini` | Real-time multimodal streaming and on-device intelligent Android workshop lab. |
| [**Sports Coordinator**](https://sports.kartikarora.me) | 🚀 `Live App` · `Node` · `Firebase` | Social sports team management and fixture coordination app deployed in production. |
| [**What Dog Should I Get?**](https://kartikarora.me) | 🤖 `AI App` · `Kotlin` · `Ktor` | Intelligent lifestyle matcher powered by Google Gemini API recommendations. |
| [**rocketflag-kmp-sdk**](https://github.com/kartikarora/rocketflag-kmp-sdk) | 🌐 `Open Source` · `KMP` · `Maven` | Multiplatform feature flagging SDK for Android & iOS published on Maven Central. |
| [**anylytics**](https://github.com/kartikarora/anylytics) | 🌐 `Open Source` · `Kotlin` · `Android` | Modular, provider-agnostic analytics abstraction library for Android apps. |
