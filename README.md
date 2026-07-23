<h1 align="center">Fayez Bast</h1>

<h3 align="center">Software engineer building efficient AI systems and dependable backend products.</h3>

<p align="center">
  I turn noisy context and repetitive workflows into practical agents, APIs, and automation.
</p>

<p align="center">
  <a href="mailto:fayezbast15@gmail.com">Email</a> ·
  <a href="https://linkedin.com/in/fayez-bast">LinkedIn</a> ·
  <a href="https://github.com/FayezBast?tab=repositories">Projects</a>
</p>

---

```text
focus      agent infrastructure · backend systems · workflow automation
building   B-eats · Basira
proof      OpenAI Agents SDK · 17 World Monitor PRs · PPSSPP
approach   prototype → evaluate → harden → ship → improve
```

## Selected work

### [B-eats](https://github.com/FayezBast/Uber-Eats-Clone) — full-stack delivery platform

An actively developed delivery system split across three applications: a Next.js experience for customers, drivers, and restaurant owners; a React operations dashboard; and a Go API for authentication, delivery lifecycle management, notifications, analytics, and simulated live tracking.

`Go` · `Gin` · `Next.js` · `PostgreSQL` · `Redis`

### Basira — voice-first assistive AI

A voice-first mobile assistant for blind users in Lebanon.

`Swift` · `SwiftUI` · `ARKit` · `FastAPI` · `Groq` · `Azure TTS`

### [Jarvis 2.0](https://github.com/FayezBast/Jarvis-2.0) — tool-using development agent

A Python agent that executes tools locally for sandboxed file operations, shell and Git workflows, and persistent memory. Gemini is its current model backend.

`Python` · `Agents` · `Tool use` · `Gemini`

## Open-source impact

### [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) — voice streaming reliability

Fixed a speech-to-text bug where streamed float32 samples were sent as raw IEEE-754 bytes to a realtime transcription endpoint expecting PCM16. Added a shared, non-mutating conversion path and regression coverage for clipping, exact bytes, int16 pass-through, and buffer immutability.

[View merged PR #3916 →](https://github.com/openai/openai-agents-python/pull/3916)

### [World Monitor](https://github.com/koala73/worldmonitor) — 17 merged pull requests

I contribute to a real-time global intelligence dashboard across data pipelines, cache correctness, map localization, polling infrastructure, panel UX, and desktop reliability.

- [Localized MapLibre basemap labels](https://github.com/koala73/worldmonitor/pull/1032) across 20 languages, including RTL support.
- [Isolated request caches by query variant](https://github.com/koala73/worldmonitor/pull/3158) and added focused regression coverage.
- [Shipped an ocean-and-ice data pipeline](https://github.com/koala73/worldmonitor/pull/2652) from ingestion through RPC, cache health, and MCP freshness.

[View all merged contributions →](https://github.com/koala73/worldmonitor/pulls?q=is%3Apr+author%3AFayezBast+is%3Amerged)

### [PPSSPP](https://github.com/hrydgard/ppsspp) — Arabic localization

Completed the emulator's Arabic UI translation by translating roughly 380 remaining strings, repairing four broken placeholder substitutions, and adding eight missing locale keys. The change brought the Arabic key set in sync with the English source.

[View merged PR #21913 →](https://github.com/hrydgard/ppsspp/pull/21913)

## What I work with

- **Applied AI** — agents, retrieval, context engineering, evaluation, and model serving.
- **Backend systems** — Go services, FastAPI, REST APIs, PostgreSQL, caching, and background jobs.
- **Product engineering** — TypeScript, React, Next.js, Docker, automation, and practical observability.

## More work

- **[Pulse AI](https://github.com/FayezBast/Pulse-Ai---Hackathon)** — a hospital workflow prototype that turns spoken notes into text and helps automate DXCare form entry.

## Let's build

I am open to collaborating on applied AI products, automation-heavy tooling, and backend platforms.

[Email me](mailto:fayezbast15@gmail.com) or [connect with me on LinkedIn](https://linkedin.com/in/fayez-bast).
