**Münster, Germany** | currently doing my M.Sc. in Information Systems @ FH Münster

Building Python libraries and developer tools for typed APIs, generated
clients, and working with coding agents.

Currently focused on FastAPI streaming, TypeScript/Python SDKs, and checks
that keep contracts and architecture in sync.

| Area | Tools |
| --- | --- |
| Languages | [![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/mathisarends?tab=repositories&language=python) [![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)](https://github.com/mathisarends?tab=repositories&language=go) [![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/mathisarends?tab=repositories&language=typescript) |
| Frameworks | [![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Lit](https://img.shields.io/badge/-Lit-324FFF?style=flat-square&logo=lit&logoColor=white)](https://lit.dev/) [![Angular](https://img.shields.io/badge/-Angular-DD0031?style=flat-square&logo=angular&logoColor=white)](https://angular.dev/) |
| Coding agents | [![Codex](assets/badges/codex.svg)](https://openai.com/codex/) [![Claude](https://img.shields.io/badge/-Claude-D97757?style=flat-square&logo=claude&logoColor=white)](https://claude.ai/) |

## APIs, Codegen & Developer Tooling

- 🌊 [fastapi-streams](https://github.com/mathisarends/fastapi-streams) - Decorate FastAPI SSE endpoints, generate typed TypeScript and Python clients, and catch contract drift in CI
- 🔌 [pyrpckit](https://github.com/mathisarends/pyrpckit) - Define typed Python RPC protocols with schema export and generated clients
- 🧩 [lit-query-codegen](https://github.com/mathisarends/lit-query-codegen) - Generate typed TypeScript clients and TanStack Lit Query options from OpenAPI
- 🐍 [httpxgen](https://github.com/mathisarends/httpxgen) - Generate typed async HTTPX clients from OpenAPI
- ⚒️ [smelt](https://github.com/mathisarends/smelt) - Architecture guardrails for Python: import boundaries, test mirroring, and change-aware checks for reviewing agent changes

## AI / LLM Infrastructure

- 🤖 [callm](https://github.com/mathisarends/callm) - Type-safe Python library for OpenAI, Azure OpenAI and Codex
- 🔍 [retrieverkit](https://github.com/mathisarends/retrieverkit) - Provider-agnostic RAG building blocks for Python - chunking, dense/lexical retrieval, and rank fusion behind small abstract ports, zero core dependencies
- 🧰 [agenttoolkit](https://github.com/mathisarends/agenttoolkit) - One provider-neutral definition for tools exposed to LLM agents - schema, availability, metadata, and execution logic in one place
- 💰 [tokenary](https://github.com/mathisarends/tokenary) - LLM API cost calculation based on the LiteLLM model catalog

## Browser Automation

- 🌐 [browsertunnel](https://github.com/mathisarends/browsertunnel) - Mirrors a real Chromium tab into a web page over a single WebSocket - CDP-driven screencast, full clipboard/tab sync, and imitated input, built on cdpify and pyrpckit
- 🪐 [browserplane](https://github.com/mathisarends/browserplane) - Browser provisioning platform inspired by Browserbase: lease and remotely control real Chromium sessions in a web UI
- 🧬 [cdpify](https://github.com/mathisarends/cdpify) - Type-safe Chrome DevTools Protocol client with Pydantic models, including a codegen tool that generates the client straight from the CDP specification

## Voice & Realtime Agents

- 🧠 [cara](https://github.com/mathisarends/cara) - Voice/CLI conversational agent with a JSON-RPC gateway and pluggable agent runtime
- 🗣️ [rtvoice](https://github.com/mathisarends/rtvoice) - Framework for real-time voice agents on OpenAI's Realtime API
- 🎤 [vocalbin](https://github.com/mathisarends/vocalbin) - Typed async adapters for speech-to-text, text-to-speech, realtime transcription, and translation
- 👂 [wakewordkit](https://github.com/mathisarends/wakewordkit) - Wake word detection built on openWakeWord, with a pluggable audio input API

## Smart Home

- 🔊 [sonosify](https://github.com/mathisarends/sonosify) - Sonos control over UPnP and the S2 API, with a Cloud Integration (playback, queue, groups, events)
- 💡 [hueify](https://github.com/mathisarends/hueify) - Typed async Python client for Philips Hue CLIP v2, with one API for lights, rooms, zones, scenes, and events
- 🌅 [huerise](https://github.com/mathisarends/huerise) - Philips Hue sunrise alarm with audio, REST API, and an agent-friendly CLI

## CLI Tools

- 📚 [arxcli](https://github.com/mathisarends/arxcli) - Fast, minimal, script-friendly CLI for researching papers on arXiv, with human-readable tables and JSON/JSONL for agents
- 🎧 [spoti](https://github.com/mathisarends/spoti) - Go CLI for Spotify, backed by the official Web API via OAuth PKCE, no cookie scraping - agent-friendly JSON output
- 📊 [go-withings](https://github.com/mathisarends/go-withings) - Script-friendly CLI for the Withings API - OAuth, weight & body composition, human-readable or JSON output
- ⌚ [fitbitctl](https://github.com/mathisarends/fitbitctl) - Read-first Go CLI for Fitbit/Pixel Watch health data via Google Health API v4, OAuth 2.0 + PKCE, JSON output
- 🔉 [elevenfx](https://github.com/mathisarends/elevenfx) - Go CLI for generating sound effects with the ElevenLabs API
- 💡 [huego](https://github.com/mathisarends/huego) - Go CLI for Philips Hue bridges, talking directly to the local CLIP v2 REST API

## Integrations

- 📝 [notionary](https://github.com/mathisarends/notionary) - Markdown → Notion, built for Python developers and AI automation
- 🖼️ [unsplash-wrapper](https://github.com/mathisarends/unsplash-wrapper) - Simplified interface for the Unsplash API

## Music & Games

- 🎴 [prompster-cli](https://github.com/mathisarends/prompster-cli) - Generate Hitster-style card decks from natural language prompts and Spotify
- 🎮 [prompster-frontend](https://github.com/mathisarends/prompster-frontend) - Web app for playing with self-made Hitster cards
- 🎵 [spotifyify](https://github.com/mathisarends/spotifyify) - Typed async Spotify client for Python

## Presentations

- 🎬 [fh-muenster-slidev-starter](https://github.com/mathisarends/fh-muenster-slidev-starter) - Slidev starter for FH Münster presentations with a component library and style guide in FH corporate design

---

<sub>[GitHub](https://github.com/mathisarends)</sub>
