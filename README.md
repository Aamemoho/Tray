# tray

> A sandbox where ideas don't need permission to exist.

**tray** is an open-source AI hub that orchestrates multiple agents, learns how you think, and turns the flow of your thoughts into executable work — all from a single interface.

---

## Why tray exists

Every productivity tool assumes you think the same way every day.

You don't. No one does.

Some days you're designing systems, thinking in structures. Other days ideas are rushing in faster than you can catch them. Sometimes you need to execute fast. Sometimes you need to slow down and feel your way through.

Most tools fight this. tray doesn't.

tray watches how you write, detects where you are, and shifts with you. The layout changes. The language changes. The way agents respond to you changes. You stop adapting to the tool — the tool adapts to you.

And when you want to experiment, break things, or let ideas run wild? tray is built to contain it. Like a sandbox, but for thinking.

---

## Core Ideas

### 🔄 Adaptive Mode System
tray reads the cognitive signal in how you write. Four modes — each with its own layout, color language, and agent behavior. Switch manually in seconds, or let tray suggest it based on what it notices.

| Mode | State | Experience |
|------|-------|------------|
| 🏗️ **Architect** | Analytical, structural | Canvas-first, dense, technical |
| 🌊 **Explorer** | Ideative, connective | Flow-first, minimal, narrative |
| ⚡ **Executor** | Decisive, completion-driven | Kanban-first, brief, direct |
| 🌱 **Nurturer** | Gentle, one-thing focus | List-first, quiet, supportive |

### 🧠 Input Preprocessor
You talk. tray structures. Stream-of-consciousness input gets sorted automatically into three buckets:

- `TASK` — actionable now, ready for agents
- `IDEA` — worth keeping, not yet ready
- `VISION` — directional, long-term

You confirm. Agents execute. Nothing gets lost.

### 🤖 Multi-Agent Orchestrator
Different models for different strengths. tray routes your work to the right model and brings the results back into one place.

### 🔌 The Hub
One interface. Every conversation, checklist, architecture canvas, and agent session. Designed to grow — new agents, new integrations, new modes — without breaking what already works.

---

## How it feels

```
You think out loud
        ↓
tray listens and structures
        ↓
You confirm (or adjust)
        ↓
Agents execute in parallel
        ↓
Results come back into your flow
```

No context switching. No copy-pasting between tools. No losing an idea because you couldn't act on it fast enough.

---

## Tech Stack

- **Electron** — desktop-first, local-first
- **React** — component architecture
- **Docker** — agent environment isolation
- **Zustand** — state management
- **Anthropic / OpenAI / Google APIs** — model routing

---

## Project Status

> 🚧 Active development. Core architecture stable. Building fast.

**Done**
- [x] Multi-agent orchestrator foundation
- [x] IdeaHub routing
- [x] Kanban checklist layout
- [x] Docker integration

**In Progress**
- [ ] Adaptive Mode System
- [ ] Input Preprocessor
- [ ] Architecture canvas save/load

**Planned**
- [ ] Plugin architecture
- [ ] Mode history & cognitive pattern report
- [ ] Worldbuilding / visual design canvas
- [ ] Mobile-aware layout

---

## Getting Started

```bash
git clone https://github.com/Aamemoho/Tray.git
cd Tray
npm install
npm run dev
```

Docker required for agent execution:

```bash
docker-compose up -d
```

---

## Contributing

tray is built on one belief: one person with the right system can do what used to take a team.

But the right system gets better with more people.

If any of this resonates — AI orchestration, adaptive interfaces, local-first tools, closing the gap between thinking and making — you're welcome here.

Open an issue. Start a discussion. The architecture is modular by design. You can contribute a new mode, a new agent adapter, or a layout without touching the core.

No contribution is too small.

---

## Philosophy

The line between thinking and making is disappearing.

What used to require a team — designer, developer, researcher, writer — is concentrating into a single person with the right environment. Not because those roles matter less, but because the tools are finally catching up to how creative people actually work.

tray is that environment. For people who generate ideas faster than they can execute them. For people who think in bursts, not schedules. For people who want a tool that gets out of the way.

---

## License

MIT — use it, fork it, build on it.

---

<p align="center">
  <sub>Built in the open. Thinking out loud.</sub>
</p>
