# tray

> The app adapts to you. You don't adapt to the app.

**tray** is an open-source AI hub that orchestrates multiple agents, learns your cognitive mode, and converts the flow of your thoughts into executable work — all from a single interface.

---

## Why tray exists

Every productivity app assumes you think the same way every day.

You don't. No one does.

Some days you're in architect mode — designing systems, thinking in structures. Other days you're in explorer mode — ideas rushing in faster than you can catch them. Sometimes you just need to execute. Sometimes you need to slow down.

tray detects where you are and shifts with you. The layout changes. The language changes. The way agents respond to you changes. You stop fighting the tool and start thinking.

---

## Core Ideas

**Adaptive Mode System**
tray watches how you write and speak. Short, decisive sentences signal execution mode. Long, wandering thoughts signal exploration mode. Four modes — Architect, Explorer, Executor, Nurturer — each with its own layout, color system, and agent behavior. You can switch manually in 3 seconds, or let tray suggest it.

**Input Preprocessor**
You talk. tray listens and structures. Stream-of-consciousness input gets parsed into three buckets automatically — `TASK` (actionable now), `IDEA` (worth keeping), `VISION` (directional). You confirm. Agents execute.

**Multi-Agent Orchestrator**
Different models for different strengths. Gemini for creative expansion. GPT-4 for structured analysis. Claude for implementation. tray routes your tasks to the right model and coordinates the results into a single workflow.

**The Hub**
One place. Every conversation, checklist, architecture canvas, and agent session. Built to be extended — plugins, integrations, new agents — without rebuilding from scratch.

---

## Modes

| Mode | Personality | Default View | Agent Voice |
|------|------------|-------------|-------------|
| 🏗️ Architect | NT — analytical, structural | Canvas | Structured |
| 🌊 Explorer | NF — ideative, connective | Flow | Narrative |
| ⚡ Executor | ST — decisive, completion-focused | Kanban | Brief |
| 🌱 Nurturer | SF — gentle, one-thing-at-a-time | List | Gentle |

Mode detection runs on every input. No extra cost. No separate step.

---

## How it works

```
Your raw input (any form, any topic, any length)
        │
        ▼
┌───────────────────┐
│  Input Processor  │  ← Classifies TASK / IDEA / VISION
│  Mode Detector    │  ← Reads cognitive signal from text pattern
└───────────────────┘
        │
        ▼
   You confirm
        │
    ┌───┴────────────────────┐
    ▼                        ▼
 Tasks → Kanban          Ideas → IdeaHub
    │                        │
    ▼                        ▼
Agents execute          Backlog preserved
```

---

## Tech Stack

- **Electron** — desktop-first, local-first
- **React** — component architecture
- **Docker** — agent environment isolation
- **Zustand** — lightweight state management
- **Anthropic / OpenAI / Google APIs** — model routing

---

## Project Status

> 🚧 Active development. Core architecture is stable. Adaptive Mode System and Input Preprocessor are being implemented now.

**Done**
- [x] Multi-agent orchestrator foundation
- [x] IdeaHub routing
- [x] Kanban checklist layout
- [x] Docker integration

**In Progress**
- [ ] Adaptive Mode System (4 modes, auto-detection)
- [ ] Input Preprocessor (TASK / IDEA / VISION classification)
- [ ] Architecture canvas save/load

**Planned**
- [ ] Plugin architecture
- [ ] Mode history & personality report
- [ ] Mobile-aware responsive layout
- [ ] Worldbuilding / visual design canvas

---

## Getting Started

```bash
git clone https://github.com/YOUR_USERNAME/tray.git
cd tray
npm install
npm run dev
```

Docker required for agent execution:

```bash
docker-compose up -d
```

---

## Contributing

tray is built on the idea that one person with the right tools can do what used to take a team.

But the right tools get better with more people.

If you care about any of these things, this project is for you:

- AI agent orchestration
- Adaptive interfaces
- Local-first tools
- Reducing the gap between thinking and making

**How to contribute:**
Open an issue. Start a discussion. Pick something from the roadmap. The architecture is designed to be modular — you can add a new mode, a new agent adapter, or a new layout without touching the core.

No contribution is too small. Typo fixes welcome.

---

## Philosophy

The boundary between designer and developer is not disappearing. It's concentrating. What used to require five people now fits inside one person with the right system.

tray is that system — for people who generate ideas faster than they can execute them, and want a tool that closes that gap.

---

## License

MIT — use it, fork it, build on it.

---

<p align="center">
  <sub>Built in the open. Thinking out loud.</sub>
</p>

