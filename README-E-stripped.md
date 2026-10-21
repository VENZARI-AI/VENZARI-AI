<div align="center">
  <pre align="center" style="color:#3251fc;background:#0d0d0d;padding:16px;border-radius:8px;font-size:12px">
██╗   ██╗███████╗███╗   ██╗███████╗ █████╗ ██████╗ ██╗
██║   ██║██╔════╝████╗  ██║╚══███╔╝██╔══██╗██╔══██╗██║
██║   ██║█████╗  ██╔██╗ ██║  ███╔╝ ███████║██████╔╝██║
╚██╗ ██╔╝██╔══╝  ██║╚██╗██║ ███╔╝  ██╔══██║██╔══██╗██║
 ╚████╔╝ ███████╗██║ ╚████║███████╗██║  ██║██║  ██║██║
  ╚═══╝  ╚══════╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝
  </pre>

  <h1 style="font-family:'Unbounded',sans-serif;font-size:clamp(3rem,8vw,5rem);font-weight:800;color:#FDFBF9;letter-spacing:-0.02em;margin:1rem 0;">
    VENZARI
  </h1>
  <p style="font-family:'Poppins',sans-serif;font-size:1.25rem;color:rgba(253,251,249,.6);line-height:1.6;max-width:640px;margin:0 auto 2rem;">
    You've been renting your AI. Your engineering OS. Your intelligence layer.<br/>
    <strong style="color:#FDFBF9;">VENZARI sells you the whole exit.</strong>
  </p>

  <p>
    <a href="https://venzari.co/code"><img src="https://img.shields.io/badge/VENZARI%20CODE-Engineering%20OS-A259FF?style=for-the-badge" alt="VENZARI CODE"/></a>
    <a href="https://venzari.co/engine"><img src="https://img.shields.io/badge/VENZARI%20ENGINE-Private%20AI-C1FF00?style=for-the-badge&logoColor=000" alt="VENZARI ENGINE"/></a>
    <a href="https://venzari.co/products/venzari-ai-agent"><img src="https://img.shields.io/badge/VENZARI%20AI%20AGENT-Persistent-3251FC?style=for-the-badge" alt="VENZARI AI AGENT"/></a>
    <a href="https://venzari.co/together"><img src="https://img.shields.io/badge/VENZARI%20TOGETHER-One%20Stack-3251FC?style=for-the-badge" alt="VENZARI TOGETHER"/></a>
    <a href="https://venzari.co/enterprise"><img src="https://img.shields.io/badge/ENTERPRISE-White%20Label-FF38D4?style=for-the-badge" alt="ENTERPRISE"/></a>
  </p>
  <p>
    <a href="https://venzari.co">🌐 Website</a> &nbsp;·&nbsp;
    <a href="https://docs.venzari.co">📚 Docs</a> &nbsp;·&nbsp;
    <a href="https://venzari.co/pricing">💰 Pricing</a> &nbsp;·&nbsp;
    <a href="https://discord.gg/venzari">💬 Discord</a> &nbsp;·&nbsp;
    <a href="https://venzari.co/jobs">💼 Careers</a>
  </p>
</div>

<details>
<summary><kbd>📋 Table of Contents</kbd></summary>

- [The Problem](#the-problem)
- [⚙️ VENZARI CODE — Engineering OS](#️-venzari-code--engineering-os)
- [🛡️ VENZARI ENGINE — Private AI Infrastructure](#️-venzari-engine--private-ai-infrastructure)
- [🤖 VENZARI AI AGENT — Persistent Autonomous Agent](#-venzari-ai-agent--persistent-autonomous-agent)
- [🔗 VENZARI Together](#-venzari-together)
- [Their Way vs VENZARI](#their-way-vs-venzari)
- [The Installer](#the-installer)
- [Get Started](#get-started)

</details>

---

## The Problem

Every company using cloud AI is making two silent bets.

**Bet one:** that a vendor's privacy policy will protect sensitive business data forever — through acquisitions, policy changes, and legal requests. The data is on their server. The promise is in a document.

**Bet two:** that AI coding tools with no governance, no memory, and no evidence trail are acceptable in production engineering environments. Commits ship with no record of what the AI actually did.

**VENZARI doesn't ask you to make either bet.** Three new product categories. The only complete private AI ecosystem.

---

## ⚙️ VENZARI CODE — Engineering OS

> **[venzari.co/code](https://venzari.co/code)** · *The governance layer above AI — not a better coding assistant*

> [!NOTE]
> VENZARI CODE and Copilot are not competitors. They coexist. Copilot is a suggestion tool. CODE is the operating system that governs when and how suggestions are allowed to touch your codebase.

### Why This Is a New Category

AI coding assistants are suggestion machines. No memory between sessions. No enforcement of workflow. No record of what happened. You get a commit — the history says "AI-assisted" and that's all it says.

VENZARI CODE is the **operating system** that sits above AI models. It tells AI what it is permitted to do, in which phase, with what evidence required to complete. 13 operating modes. Each with different tool permissions. Each with different evidence requirements.

### The 13-Mode Lifecycle

| Mode | What the AI may do | What it must prove |
|------|---------------------|-------------------|
| **Discover** | Read only. Write nothing. | Observational report |
| **Plan** | Write a plan document. No code. | Plan document |
| **Implement** | Execute within approved scope only. | Working code |
| **Validate** | Run tests. Produce **actual output** — not a claim. | Real test results |
| **Review** | Read-only analysis + security scan. | Review report |
| **Repair** | Fix the specific failure only. Scope locked. | Fix diff |
| **Commit** | Git operations only. Evidence attached. | Commit + evidence chain |
| **Advisor** | Analysis only. Zero writes. | Analysis document |
| **Handoff** | Structured session summary. | Handoff document |
| **Audit** | Review session evidence. | Audit report |
| **Benchmark** | Performance regression tracking. | Benchmark data |
| **Migration** | Full write + execute for large-scale changes. | Migration plan |
| **Release** | Full access including deploy. | Release evidence chain |

### The Companion System — `.venzari/` in Your Project

```
agents/    configured roles with specific capabilities and constraints
skills/    24 native + 216 vendor task templates
tasks/     structured definitions with opening and closing gates
rules/     project-specific constraints — overrides defaults
memory/    session history, codegraph, architectural decisions
gates/     automated checks that must pass before task completion
```

Return months later. CODE reads the companion and knows exactly where you left off. When you correct the AI, that correction becomes a rule — the system gets better at your specific project over time.

### The Five Governance Components

| Component | What it enforces |
|-----------|-----------------|
| **SSOT Loader** | Reads project rules before every action — AI operates within established patterns |
| **Tool Guard** | Per-mode allowlists at the system call level — not a prompt, a structural constraint |
| **Loop Detector** | 3 identical attempts without progress → stop, escalate to human review |
| **Evidence Collector** | Every tool call logged: input · output · timestamp. Immutable. Follows every commit. |
| **Context Assembler** | Synthetic context under 4,000 chars — most relevant project knowledge, no overflow |

### Ships With Every Install

```
1,508 tests passing · 0 failing · 74 test files
Desktop app (Tauri v2) · JetBrains plugin · Customer dashboard
6 MCP tools · 6 languages · 4-job security CI pipeline
Multi-agent: SubagentPool + SwarmCoordinator + DAG branching
Goal mode: describe objective → autonomous execution, budget-capped
```

---

## 🛡️ VENZARI ENGINE — Private AI Infrastructure

> **[venzari.co/engine](https://venzari.co/engine)** · *Structural privacy. Not policy privacy.*

> [!IMPORTANT]
> **The difference:** Cloud AI privacy is a legal document. It can change. ENGINE's privacy is the architecture — your data physically cannot leave your hardware because there is no mechanism for it to. You can close the internet after installation and the system runs.

### What "Private AI Infrastructure" Means

A complete AI system — conversational AI, voice, automation, dashboard, API, semantic search, custom training — running on a VPS you own. Fixed monthly cost. No per-token billing. No cloud dependency. Offline-capable after installation.

### 7 Features — All Live, All on Your Hardware

| # | Feature | What it delivers |
|---|---------|-----------------|
| 1 | **Conversational AI + permanent memory** | Builds cumulative understanding of your business — every conversation, permanently |
| 2 | **Local voice (TTS + STT)** | Offline synthesis and recognition — voice data never leaves your server |
| 3 | **Workflow automation** | Reports, email, CRM, calendar — all local, no external API calls |
| 4 | **Web dashboard** | Full UI at your domain — chat, memory search, voice, workflows, monitoring |
| 5 | **REST API** | Connect your ERP, CRM, HR systems — locally |
| 6 | **Semantic memory search** | *"What did we discuss about the Acme contract?"* → instant natural language answer |
| 7 | **Custom fine-tuning** *(Growth+)* | Train on your data, run the model locally |

### The 3-Stage Installer — 20 Minutes to a Full Private AI Stack

**Stage 1 — 11 pre-install checks** run in parallel before any wizard question. RAM, disk, required ports, container runtime, internet connectivity, admin access, existing installation detection. Any failure stops with exact fix instructions — no partial states, no mystery errors.

**Stage 2 — 7-question wizard** configures what can't be auto-detected: server identity, license key, AI provider preference (local-only, local + cloud, or cloud-only), model selection with hardware-adaptive recommendations, optional add-ons.

**Stage 3 — 17 hardware-customized steps** generated for your specific machine by the VENZARI installer service. Verified binary download → model pulls → service startup → health checks → SSL setup → ecosystem wiring → MCP registration. 2,301 automated tests back every step. Resumable — the resume-repair command skips completed steps and retries from the failure point.

### Hardware Requirements

| Resource | Minimum | Recommended |
|----------|---------|-------------|
| RAM | 8 GB | 32–64 GB |
| Storage | 60 GB SSD | 200 GB NVMe |
| CPU | 4 cores | 16+ cores |
| GPU | Not required | NVIDIA ≥8 GB VRAM (5–15× faster) |
| OS | Ubuntu 22.04 LTS | Ubuntu 22.04 LTS |

**v1.0.0 · All 33 phases complete · Launched 2026-09-05**

---

## 🤖 VENZARI AI AGENT — Persistent Autonomous Agent

> **[venzari.co/products/venzari-ai-agent](https://venzari.co/products/venzari-ai-agent)** · *Starting at $29/month*

### Why This Is a New Category

Chatbots are stateless. They answer questions and forget you. VENZARI AI AGENT is an always-on autonomous entity — not a conversation interface. It operates across every channel you use simultaneously, remembers every interaction permanently, and becomes more capable every night.

### 6 Live Channels — One Agent, One Memory

`Telegram` · `Slack` · `Discord` · `Email` · `Web chat` · `Webhook`

Start on Telegram. Continue on Slack. Finish via email. Same agent. Same memory. Zero re-explaining.

### 3-Signal Memory — Nothing Falls Through

| Signal | Speed | What it retrieves |
|--------|-------|------------------|
| Vector embeddings | 50ms | Semantic — relevant content even without exact words |
| BM25 full-text | 10ms | Exact — code snippets, names, precise phrases |
| PageRank graph | 5ms | Important — most-referenced facts surface first |

### 2,212 Skills — Invoked Automatically

- **11 S-tier** — flagship capabilities, highest reliability, most maintained
- **522 A-tier** — high quality, broad coverage, the day-to-day backbone
- **1,679 B-tier** — community catalog, wide reach, growing continuously

No manual selection. You describe what you need. The agent finds the skill.

### The Nightly Learning Loop

Every night at 3am: repeated patterns → new skills created · underperforming skills improved · context model updated · old interactions compressed. You go to sleep with an agent. You wake up with a better one.

### 8-Provider Model Router

`Local inference` → `Groq` → `Gemini` → `OpenRouter` → `Cerebras` → `Anthropic` → `OpenAI` → `Bedrock`

Circuit breaker (3 failures → bypass) · Budget monitor (downgrade at 80%) · ENGINE: auto-routes through local AI gateway with zero config

### Everything That Ships With AI AGENT

- `venzari-agent` CLI — 15+ commands: start · stop · doctor · skills · memory · channels · upgrade
- **Native desktop app** (Tauri v2) — 5 tabs: Chat · Skills · Memory · Channels · Settings · system tray
- **9-page dashboard** at agent.venzari.co — including AI Router page (unique in market)
- **12 MCP tools** for Claude Code, Cursor, Kiro, VS Code, Gemini CLI
- 422 tests passing · 0 failing · auto-wires to ENGINE and CODE

---

## 🔗 VENZARI Together

> **[venzari.co/together](https://venzari.co/together)** · *CODE + ENGINE on one machine, zero cloud inference*

Two products. One installer. Fully wired. CODE routes all AI inference through ENGINE's local AI gateway. No cloud calls for development. Offline after installation.

**Requirements:** 8 GB RAM minimum (16 GB recommended) · 20 GB disk · Ubuntu 20.04+

---

## 🏢 VENZARI Enterprise

> **[venzari.co/enterprise](https://venzari.co/enterprise)** · *White-label · SLA · Dedicated infrastructure*

White-label deployment of the complete VENZARI ecosystem under your brand. Custom skill development, managed fleet, dedicated infrastructure, direct team access, full SLA. [Contact us →](https://venzari.co/contact)

---

## Their Way vs. VENZARI

| Question | Cloud AI + Copilot + Chatbot | **VENZARI** |
|----------|------|------|
| Where does the data go? | Vendor's cloud | **Your server** |
| What's the privacy guarantee? | Policy document | **Architecture** |
| What does it cost? | Per-token, no ceiling | **Flat monthly** |
| Does it remember you? | Session only — starts over tomorrow | **Everything. Permanently.** |
| Is AI development governed? | No record, no enforcement | **13 modes, evidence per commit** |
| How long to set up? | API key (minutes) or build-your-own (months) | **20 minutes** |
| What do you own? | Nothing | **The binary, the data, the future** |
| Works offline? | No | **Yes** |

---

## The Installer

**11 checks before a single question is asked.** Every potential problem found and described precisely — not after an installation fails, before it begins.

**7 questions configure everything else.** Server identity, license key, AI provider preference, hardware-adaptive model selection. That's it.

**17 hardware-customized steps execute the plan.** Generated for your specific machine. Each step has retry logic. 2,301 automated tests back every step. Resumable at any point.

The installer is the product. It is what makes private AI infrastructure accessible to companies that could never build it themselves.

---

## Get Started

**→ [venzari.co/pricing](https://venzari.co/pricing)** — pick a product, pick a plan

**→ [docs.venzari.co](https://docs.venzari.co)** — full documentation

**→ [venzari.co/enterprise](https://venzari.co/enterprise)** — for dedicated infrastructure and white-label

**→ [venzari.co/contact](https://venzari.co/contact)** — talk to the team

[venzari.co](https://venzari.co) · [Solutions](https://venzari.co/solutions) · [Jobs](https://venzari.co/jobs) · [Discord](https://discord.gg/venzari)

---

<p align="center">
<strong>VENZARI</strong> &nbsp;·&nbsp; <a href="https://venzari.co">venzari.co</a> &nbsp;·&nbsp; <a href="https://discord.gg/venzari">Discord</a> &nbsp;·&nbsp; <a href="https://venzari.co/jobs">Jobs</a><br/>
<em>Your AI. Your Hardware. Your Future. &nbsp;·&nbsp; © 2026 VENZARI</em>
</p>
