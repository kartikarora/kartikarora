# Kartik Arora

**Applied AI Engineer** · **Google Developer Expert (Android)** · Sydney, Australia  
[kartikarora.me](https://kartikarora.me) · [LinkedIn](https://www.linkedin.com/in/arorakartik) · [Medium](https://medium.com/@kartikarora)

---

I bridge foundation models and native runtime environments—building agentic workflows, Model Context Protocol (MCP) tooling, and production mobile systems.

```
$ kartik --status
● Current Focus:  Agentic AI Orchestration & Tool Calling
● Native Stack:   Kotlin 2.x, Jetpack Compose, KMP, Coroutines
● Edge & AI:      MCP (stdio/SSE/JSON-RPC), Google Gemini, Cloudflare Workers
● Drumming:       Polyrhythms & odd time signatures 🥁
```

---

### 🕹️ Interactive Terminal & Cheat Sheet

<details>
<summary><b><code>$ npx preview-mcp --help</code></b> — Try my Universal MCP Server</summary>
<br>

Connect your AI coding assistants (Claude Code, Cursor, Antigravity) to preview edge environments via standard stdio, SSE, or JSON-RPC:

```bash
# Run locally via stdio
npx preview-mcp

# Or add to your Claude Code / Antigravity MCP config:
{
  "mcpServers": {
    "preview": {
      "command": "npx",
      "args": ["-y", "preview-mcp"]
    }
  }
}
```
Repository: [kartikarora/preview-mcp](https://github.com/kartikarora/preview-mcp)
</details>

<details>
<summary><b><code>$ git clone ICanHazStream</code></b> — Real-Time Gemini Multimodal Lab</summary>
<br>

A hands-on workshop application exploring streaming audio/video frames into Gemini with Jetpack Compose:

```bash
git clone https://github.com/kartikarora/ICanHazStream.git
cd ICanHazStream
# Built with modern Compose Material 3 & on-device streaming
```
Repository: [kartikarora/ICanHazStream](https://github.com/kartikarora/ICanHazStream)
</details>

<details>
<summary><b><code>$ gradle add rocketflag-kmp-sdk</code></b> — Feature Flags for Kotlin Multiplatform</summary>
<br>

Lightweight, type-safe feature flagging across Android & iOS:

```kotlin
// build.gradle.kts
dependencies {
    implementation("me.kartikarora.rocketflag:android:latest.version")
}
```
Repository: [kartikarora/rocketflag-kmp-sdk](https://github.com/kartikarora/rocketflag-kmp-sdk)
</details>

<details>
<summary><b><code>$ kartik --easter-egg</code></b> — Random facts & trivia</summary>
<br>

- 🥁 When not architecting agentic systems, I'm behind a drum kit playing syncopated beats.
- 🏎️ Weekend calendar is strictly blocked out for Formula 1 race weekends.
- 🇦🇺 Based out of Sydney, organizing local Android & AI community tech talks.
</details>

---

### 🔨 Active Projects (Updated Past Year)

| Project | Stack | What It Does |
| :--- | :--- | :--- |
| [**preview-mcp**](https://github.com/kartikarora/preview-mcp) | `TypeScript` · `MCP` · `Workers` | Universal Model Context Protocol server (stdio, SSE, JSON-RPC) for AI coding environments. |
| [**ICanHazStream**](https://github.com/kartikarora/ICanHazStream) | `Kotlin` · `Gemini` · `Compose` | Real-time multimodal streaming and on-device intelligent Android workshop lab. |
| [**rocketflag-kmp-sdk**](https://github.com/kartikarora/rocketflag-kmp-sdk) | `Kotlin` · `KMP` · `Maven` | Multiplatform feature flagging SDK for Android & iOS published on Maven Central. |
| [**anylytics**](https://github.com/kartikarora/anylytics) | `Kotlin` · `Architecture` | Modular, provider-agnostic analytics abstraction library for Android apps. |
| [**codelabs**](https://github.com/kartikarora/codelabs) | `Android` · `Curriculum` | Technical codelabs and workshop guides on modern Android and AI development. |
