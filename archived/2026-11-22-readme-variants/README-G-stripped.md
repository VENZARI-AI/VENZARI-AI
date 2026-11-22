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
    One ecosystem. Three products. Zero cloud dependency.<br/>
    <strong style="color:#FDFBF9;">The architecture is the product.</strong>
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

---

> [!NOTE]
> All three products auto-wire together. ENGINE provides the local AI gateway. CODE routes inference through it. AI AGENT connects to both. One ecosystem — zero manual configuration.

## The Ecosystem

```
┌─────────────────────────────────────────────────────────┐
│                    VENZARI TOGETHER                      │
│         CODE + ENGINE on one machine, fully wired        │
│         Zero cloud inference · Offline after install     │
├─────────────┬───────────────────────┬────────────────────┤
│             │                       │                    │
│  VENZARI    │    VENZARI ENGINE     │   VENZARI AI AGENT  │
│  CODE       │                       │                    │
│             │  Private AI Infra     │  Persistent Agent   │
│  Eng OS     │                       │                    │
│             │  Your hardware        │  Your memory        │
│  Your rules │  Your data            │  Your channels      │
│  Your modes │  Your models          │  Your skills        │
│  Your proof │  Your cost            │  Your learning loop │
│             │                       │                    │
│  1,508 test │  2,301 tests         │  422 tests         │
│  13 modes   │  7 features           │  2,212 skills      │
│  6 gov comp │  33 phases            │  6 channels        │
│             │                       │                    │
├─────────────┴───────────────────────┴────────────────────┤
│                                                         │
│              VENZARI ENTERPRISE                          │
│     White-label · SLA · Dedicated infrastructure         │
│         Custom skills · Managed fleet                    │
└─────────────────────────────────────────────────────────┘
```

---

## ⚙️ VENZARI CODE

> [venzari.co/code](https://venzari.co/code) · *The governance layer above AI*

### What It Is

AI coding assistants are suggestion machines. No memory. No governance. No evidence trail. You get a commit that says "AI-assisted" and that's all it says.

VENZARI CODE is the **operating system** above AI models. 13 operating modes. Each with different tool permissions. Each with different evidence requirements. Every action logged, timestamped, immutable.

> [!TIP]
> CODE and Copilot coexist. Copilot is a suggestion tool. CODE is the OS that governs when suggestions interact with your codebase.

### The 13-Mode Lifecycle

```
Discover → Plan → Implement → Validate → Review → Repair → Commit
                                                    ↗
Advisor · Handoff · Audit · Benchmark · Migration · Release
```

| Mode | Tools Allowed | Evidence Required |
|------|--------------|------------------|
| Discover | Read only | Observational report |
| Plan | Write plan only | Plan document |
| Implement | Code within scope | Working code |
| Validate | Run tests | **Real test output** |
| Review | Read + scan | Review report |
| Repair | Fix failure only | Fix diff |
| Commit | Git operations | Commit + evidence chain |
| Advisor | Read only | Analysis document |
| Handoff | Summary only | Handoff document |
| Audit | Read evidence | Audit report |
| Benchmark | Run perf | Benchmark data |
| Migration | Full write | Migration plan |
| Release | Full access | Release evidence chain |

### The Companion System

```
.venzari/
  agents/     → configured roles with specific capabilities
  skills/     → 24 native + 216 vendor templates
  tasks/      → structured definitions with opening/closing gates
  rules/      → project-specific constraints (overrides defaults)
  memory/     → session history, codegraph, architecture decisions
  gates/      → automated checks before task completion
```

Return months later. CODE reads the companion and knows where you left off. When you correct the AI, that correction becomes a rule — the system improves at your specific project over time.

### Five Governance Components

| Component | Enforcement |
|-----------|------------|
| **SSOT Loader** | Project rules loaded before every action |
| **Tool Guard** | Per-mode allowlists at system-call level — structural, not prompt-based |
| **Loop Detector** | 3 identical attempts without progress → stop, escalate to human |
| **Evidence Collector** | Every tool call logged: input · output · timestamp. Immutable. Follows every commit. |
| **Context Assembler** | Synthetic context under 4,000 chars — most relevant knowledge, no overflow |

### Ships With Every Install

```
✅ 1,508 tests passing · 0 failing · 74 test files
✅ Desktop app (Tauri v2) — cross-platform
✅ JetBrains plugin
✅ Customer dashboard
✅ 6 MCP tools
✅ 6 languages · 4-job security CI pipeline
✅ Multi-agent: SubagentPool + SwarmCoordinator + DAG branching
✅ Goal mode: describe objective → autonomous execution, budget-capped
```

---

## 🛡️ VENZARI ENGINE

> [venzari.co/engine](https://venzari.co/engine) · *Structural privacy. Not policy privacy.*

> [!IMPORTANT]
> Cloud AI privacy is a legal document. It can change. ENGINE's privacy is the architecture — there is no mechanism for data to leave your hardware. You can disconnect the internet after installation and the system keeps running.

### 7 Features — All Live, All on Your Hardware

```
┌──────────────────────────────────────────────┐
│           VENZARI ENGINE v1.0.0              │
│        33 phases complete · Launched         │
│              2026-09-05                      │
├──────────────────────────────────────────────┤
│                                              │
│  🧠 Conversational AI + Permanent Memory    │
│  🎙️ Local Voice (TTS + STT)                 │
│  ⚙️ Workflow Automation                     │
│  🌐 Web Dashboard at your domain             │
│  🔌 REST API — connect your systems          │
│  🔎 Semantic Memory Search                   │
│  🎓 Custom Fine-Tuning (Growth+)             │
│                                              │
│  Installer: 11 checks · 7 questions          │
│  17 steps · 2,301 tests · Resumable         │
│                                              │
└──────────────────────────────────────────────┘
```

### Hardware Requirements

| Resource | Minimum | Recommended |
|----------|---------|-------------|
| RAM | 8 GB | 32–64 GB |
| Storage | 60 GB SSD | 200 GB NVMe |
| CPU | 4 cores | 16+ cores |
| GPU | Not required | NVIDIA ≥8 GB VRAM (5–15× faster) |
| OS | Ubuntu 22.04 LTS | Ubuntu 22.04 LTS |

### The 3-Stage Install — 20 Minutes

**Stage 1** — 11 parallel pre-install checks. RAM, disk, ports, runtime, internet, admin. Any failure stops with exact fix instructions.

**Stage 2** — 7-question wizard. Server identity, license, AI provider preference, model selection with hardware-adaptive recommendations, optional add-ons.

**Stage 3** — 17 hardware-customized steps from the VENZARI installer service. Verified binary download → model pulls → service startup → health checks → SSL → ecosystem wiring → MCP registration. Resumable at any point.

---

## 🤖 VENZARI AI AGENT

> [venzari.co/products/venzari-ai-agent](https://venzari.co/products/venzari-ai-agent) · *Starting at $29/month*

### Why It's Different

Chatbots are stateless. They answer questions and forget you. VENZARI AI AGENT is an always-on autonomous entity — operates across every channel simultaneously, remembers every interaction permanently, becomes more capable every night.

### 6 Channels — One Agent, One Memory

```
Telegram ─┐
Slack ────┤
Discord ──┤
Email ────┼──→ VENZARI AI AGENT ──→ Permanent Memory (3-signal)
Web chat ─┤         │
Webhook ──┘         ▼
              2,212 Skills
              (auto-invoked)
                   │
                   ▼
              Nightly Learning Loop
              (new skills · improvements · compression)
```

### 3-Signal Memory

| Signal | Speed | Retrieves |
|--------|-------|-----------|
| Vector embeddings | 50ms | Semantic — relevant content without exact words |
| BM25 full-text | 10ms | Exact — code snippets, names, precise phrases |
| PageRank graph | 5ms | Important — most-referenced facts surface first |

### 2,212 Skills — Auto-Invoked

- **11 S-tier** — flagship, highest reliability
- **522 A-tier** — high quality, day-to-day backbone
- **1,679 B-tier** — community catalog, growing

### 8-Provider Model Router

```
Local → Groq → Gemini → OpenRouter → Cerebras → Anthropic → OpenAI → Bedrock
  │
  ├── Circuit breaker: 3 failures → bypass + auto-recovery
  ├── Budget monitor: downgrade at 80% session budget
  └── ENGINE installed? → routes through local gateway, zero config
```

### Everything Included

- `venzari-agent` CLI — 15+ commands: start · stop · doctor · skills · memory · channels · upgrade
- **Native desktop app** (Tauri v2) — 5 tabs, system tray
- **9-page dashboard** at agent.venzari.co — including AI Router page (unique in market)
- **12 MCP tools** for Claude Code, Cursor, Kiro, VS Code, Gemini CLI
- 422 tests passing · 0 failing

---

## 🔗 VENZARI Together + Enterprise

**Together** — [venzari.co/together](https://venzari.co/together)
CODE + ENGINE on one machine. Fully wired. CODE routes all inference through ENGINE's local AI gateway. No cloud calls for development. Offline after install.

**Enterprise** — [venzari.co/enterprise](https://venzari.co/enterprise)
White-label deployment under your brand. Dedicated infrastructure. Custom skill development. Managed fleet. Full SLA. [Contact →](https://venzari.co/contact)

---

## Their Way vs VENZARI

| Question | Cloud AI + Copilot + Chatbot | **VENZARI** |
|----------|------|------|
| Where does data go? | Vendor cloud | **Your server** |
| Privacy guarantee? | Policy (can change) | **Architecture (cannot)** |
| Cost model? | Per-token, no ceiling | **Flat monthly** |
| Remembers you? | Session only | **Everything. Permanently.** |
| AI dev governed? | No record, no enforcement | **13 modes, evidence per commit** |
| Setup time? | API key or 3–6 months | **20 minutes** |
| What do you own? | Nothing | **Binary, data, future** |
| Works offline? | No | **Yes** |

---

## Get Started

**→ [venzari.co/pricing](https://venzari.co/pricing)** — all products, all tiers
**→ [docs.venzari.co](https://docs.venzari.co)** — full documentation
**→ [venzari.co/enterprise](https://venzari.co/enterprise)** — white-label and dedicated
**→ [venzari.co/contact](https://venzari.co/contact)** — talk to the team

[venzari.co](https://venzari.co) · [Solutions](https://venzari.co/solutions) · [Jobs](https://venzari.co/jobs) · [Discord](https://discord.gg/venzari)

---

<p align="center">
<strong>VENZARI</strong> &nbsp;·&nbsp; <a href="https://venzari.co">venzari.co</a> &nbsp;·&nbsp; <a href="https://discord.gg/venzari">Discord</a> &nbsp;·&nbsp; <a href="https://venzari.co/jobs">Jobs</a><br/>
<em>Your AI. Your Hardware. Your Future. &nbsp;·&nbsp; © 2026 VENZARI</em>
</p>
