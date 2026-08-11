# Marvell AI

**A personal AI desktop assistant for Windows** — chat, voice, and a huge set of built-in agents for everyday tasks, backed by a local LLM (via [Ollama](https://ollama.com)) with optional Google Gemini fallback for when you want more power.

Built by **Venom**.

> This repository ships the packaged Windows application only. Source code is not published here.

## Download

Grab the latest release from the [**Releases**](../../releases) page, download the `.zip`, extract it anywhere, and run `Marvell_AI.exe` from inside the extracted folder.

No installer, no admin rights needed — it's a portable app. On first run, Windows SmartScreen may warn about an unrecognized publisher (normal for apps not code-signed by a commercial certificate) — click "More info" → "Run anyway."

## What it does

Marvell is a always-on assistant that lives in your system tray and understands both typed and spoken commands. Highlights:

- **Chat & Voice** — type or talk to it; wake-word and push-to-talk support; an "Immersive Voice" mode with a live audio-reactive 3D visualization for hands-free conversation.
- **Local-first AI** — runs on a local Ollama model by default (private, no internet needed for basic chat), with an in-app model downloader and an optional Gemini fallback for tougher questions.
- **A large agent library** covering things like:
  - Messaging: WhatsApp, Telegram, Slack, Discord
  - Productivity: reminders, calendar, email, notes, habit tracking, journaling
  - Files & media: file creation, image generation, video/audio tools, screen recording
  - Dev tools: code generation, git helpers, a sandboxed scripting console
  - Smart home, shopping/price tracking, market prices, and more
  - A "computer use" mode that can look at your screen and carry out a task via mouse/keyboard, with narration and a hard step limit for safety
- **Automation** — recurring rules, conditional triggers, and a focus/Pomodoro mode that blocks distracting sites in its built-in browser while you work.
- **Privacy controls** — dry-run mode (preview actions before they happen), guest mode (hard-blocks anything that sends/writes/controls something), and a clipboard history you opt into rather than one that's on by default.
- **Local API** — an optional local REST endpoint (off by default, token-protected) for scripting Marvell from other tools, plus a browser extension for sending page content or a right-click selection straight to it.

## System requirements

- Windows 10/11 (64-bit)
- For local AI: [Ollama](https://ollama.com/download) installed, with at least one model pulled — Marvell will detect this and help you download a model on first run
- A microphone, if you want to use voice features

## License

See [LICENSE](LICENSE) for usage terms.

## Feedback

Found a bug or have a feature request? Open an [issue](../../issues).
