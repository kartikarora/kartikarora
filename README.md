# Kartik Arora

Applied AI Engineer & Google Developer Expert (Android) based in Sydney, Australia.

I build systems that bridge foundation models with native runtime environments—specializing in agentic workflows, Model Context Protocol (MCP) tooling, on-device multimodal streaming, and production mobile architectures.

[kartikarora.me](https://kartikarora.me) · [LinkedIn](https://www.linkedin.com/in/arorakartik) · [Medium](https://medium.com/@kartikarora)

---

## Selected Systems & Deployments

### [Previews](https://previews.kartikarora.me) — Cloudflare Edge HTML Hosting & Universal MCP Server
Ephemeral HTML preview infrastructure provisioning isolated subdomains on demand for design and development teams.
- **Architecture**: Cloudflare Workers runtime, D1 relational metadata, R2 asset storage, Google OAuth.
- **AI Agent Integration**: Implements a universal Model Context Protocol (MCP) endpoint supporting local stdio (`npx preview-mcp`) alongside remote SSE and HTTP JSON-RPC transports for tools like Claude Code, Antigravity, and Cursor.
- **Repository / Bridge**: [kartikarora/preview-mcp](https://github.com/kartikarora/preview-mcp)

### [klaat](https://github.com/kartikarora/homebrew-klaat) — Codelabs Authoring & Local Serving Engine
Modern Kotlin CLI reimplementation of Google's archived Codelabs Tools. Parses Google Docs and Markdown into structured, interactive codelab curricula with live-reloading preview servers.
- **Stack**: Kotlin, Ktor HTTP server, Clikt CLI, Google Docs OAuth 2.0 API.
- **Distribution**: Published via custom Homebrew tap (`brew tap kartikarora/klaat && brew install klaat`).

### [ICanHazStream](https://github.com/kartikarora/ICanHazStream) — On-Device Multimodal Gemini Lab
Interactive workshop project demonstrating real-time audio and video frame streaming into the Google Gemini API directly from native Android applications.
- **Stack**: Jetpack Compose Material 3, Kotlin Coroutines & Channels, Gemini Multimodal Live API.

### [Sports Coordinator](https://sports.kartikarora.me) — Social Sports Management Platform
Production server-rendered application streamlining fixture schedules, player attendance, and availability tracking for social sports teams.
- **Stack**: Node.js, Express, Firebase Firestore, Firebase Authentication.

### [rocketflag-kmp-sdk](https://github.com/kartikarora/rocketflag-kmp-sdk) — Feature Flag Engine for Kotlin Multiplatform
Cross-platform configuration and feature toggle SDK supporting Android and iOS targets from a single shared codebase.
- **Distribution**: Published on Maven Central (`me.kartikarora.rocketflag:android`).

### [anylytics](https://github.com/kartikarora/anylytics) — Provider-Agnostic Analytics Abstraction
Modular Android library designed to decouple application business logic from vendor analytics SDKs (Firebase, Mixpanel, Amplitude).
- **Stack**: Kotlin, Android Jetpack, clean modular architecture.

---

## Technical Domain Focus

- **Applied AI & Systems**: Model Context Protocol (MCP) server development, agent tool design, Gemini Multimodal Live API, LLM context engineering.
- **Mobile & Multiplatform**: Kotlin 2.x, Jetpack Compose, Kotlin Multiplatform (KMP), Coroutines & Flow, Gradle build systems.
- **Cloud & Edge Infrastructure**: Cloudflare Workers (D1, R2), Ktor web services, Firebase, Docker, CI/CD with GitHub Actions.

---

## Community & Speaking

- **Google Developer Expert (Android)**: Active speaker at Google Developer Groups (GDG), Droidcon, and community meetups.
- **Mentorship & Writing**: Technical articles on [Medium](https://medium.com/@kartikarora) covering Android engineering and emerging AI developer tooling.
