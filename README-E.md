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
  <p style="font-family:'Poppins',sans-serif;font-size:1.25rem;color:rgba(253,251,249,.6);line-height:1.6;max-width:600px;margin:0 auto 2rem;">
    You've been renting your AI. Your engineering OS. Your intelligence layer.<br/>
    VENZARI sells you the whole exit.
  </p>

  <p>
    <a href="https://venzari.co/code"><img src="https://img.shields.io/badge/VENZARI%20CODE-Engineering%20OS-A259FF?style=for-the-badge" alt="VENZARI CODE"/></a>
    <a href="https://venzari.co/engine"><img src="https://img.shields.io/badge/VENZARI%20ENGINE-Private%20AI-C1FF00?style=for-the-badge&logoColor=000" alt="VENZARI ENGINE"/></a>
    <a href="https://venzari.co/products/venzari-ai-agent"><img src="https://img.shields.io/badge/VENZARI%20AI%20AGENT-Persistent-3251FC?style=for-the-badge" alt="VENZARI AI AGENT"/></a>
    <a href="https://venzari.co/together"><img src="https://img.shields.io/badge/VENZARI%20TOGETHER-One%20Stack-3251FC?style=for-the-badge" alt="VENZARI TOGETHER"/></a>
    <a href="https://venzari.co/enterprise"><img src="https://img.shields.io/badge/VENZARI%20ENTERPRISE-White%20Label-FF38D4?style=for-the-badge" alt="VENZARI ENTERPRISE"/></a>
  </p>
  <p>
    <a href="https://venzari.co"><img src="https://img.shields.io/badge/venzari.co-3251fc?style=for-the-badge" alt="Website"/></a>
    <a href="https://install.venzari.xyz"><img src="https://img.shields.io/badge/install-3251fc?style=for-the-badge" alt="Install"/></a>
    <a href="https://docs.venzari.co"><img src="https://img.shields.io/badge/docs-5EE7FF?style=for-the-badge" alt="Docs"/></a>
    <a href="https://venzari.co/pricing"><img src="https://img.shields.io/badge/pricing-3251fc?style=for-the-badge" alt="Pricing"/></a>
    <a href="https://discord.gg/venzari"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/></a>
  </p>
</div>

---

## The Problem

Every day, companies do two things they don't talk about.

They send their most sensitive business conversations to a server they don't own, run by a vendor whose terms of service they haven't read, stored in a way they cannot audit, under a privacy policy that can change tomorrow.

And they watch their engineers work with AI tools that have no memory of what was decided last week, no record of what the AI actually did, and no governance layer between a junior developer's prompt and a production codebase.

These are not edge cases. These are the daily operating conditions of AI in business today.

**VENZARI solves both.** Not with a better API. Not with a fancier chatbot. With three new product categories that didn't exist before — and the only complete private AI ecosystem in the world.

---

## VENZARI CODE — The Engineering OS

> **Not an AI coding assistant. The operating system that governs how AI touches your code.**

[venzari.co/code](https://venzari.co/code) · `curl -fsSL https://install.venzari.xyz | bash && venzari-code install`

The difference between an AI coding assistant and an Engineering OS is the difference between a suggestion and a system. Copilot suggests. CODE governs. Copilot answers. CODE enforces. Copilot forgets everything. CODE builds a permanent understanding of your codebase and gets smarter with every correction you make.

### 13 Operating Modes — Each With Different Permissions

Software development has distinct phases. Treating them the same is what causes runaway AI behavior. CODE enforces 13 modes:

| Mode | What the AI can do | What it proves |
|------|-------------------|----------------|
| **Discover** | Read only. Scan codebase. Write nothing. | Observational report |
| **Plan** | Write a plan document. No code, no execution. | Plan document |
| **Implement** | Execute within the approved scope only. | Working code |
| **Validate** | Run tests. Must produce **actual test output** — not a claim. | Real test results |
| **Review** | Read-only. Static analysis, security scanning. | Review report |
| **Repair** | Fix only the specific failure. Scope is locked. | Fix diff |
| **Commit** | Git operations only. Every commit carries evidence. | Commit + evidence chain |
| **Advisor** | Analysis only. No writes, no execution. | Analysis document |
| **Handoff** | Structured session summary. | Handoff document |
| **Audit** | Reviews session evidence records. | Audit report |
| **Benchmark** | Performance regression tracking. | Benchmark data |
| **Migration** | Full write + execute for large-scale changes. | Migration plan |
| **Release** | Full access including deploy operations. | Release evidence |

### The Companion System — Your Project's Brain

`venzari-code install` creates `.venzari/` in your project. This directory is the permanent intelligence layer for every session:

```
.venzari/
├── agents/    # configured roles with specific constraints
├── skills/    # 24 native + 216 vendor task templates
├── tasks/     # structured definitions with opening/closing gates
├── rules/     # project-specific constraint overrides
├── memory/    # session history, codegraph, architectural decisions
└── gates/     # automated checks that must pass before task completion
```

Return months later. CODE reads the companion and knows exactly where you left off. When you correct the AI, that correction becomes a rule — it cannot make the same mistake twice.

### Five Governance Components Between Your Request and the AI's Action

**SSOT Loader** reads project rules before every action — the AI operates within established patterns, not just prompt instructions.

**Tool Guard** enforces per-mode allowlists at the system call level. This is not a prompt instruction. It is a structural constraint.

**Loop Detector** tracks action patterns. Three identical attempts without progress → escalate to human review, stop the session.

**Evidence Collector** logs every tool call: what was called, what input was given, what output was returned, at what timestamp. The record is immutable and follows every commit.

**Context Assembler** constructs a synthetic context window under 4,000 characters — the most relevant project knowledge for the current task, without context overflow.

### VENZARI CODE Also Ships With

- **1,508 automated tests passing, 0 failing** across 74 test files
- **6 pre-install checks**: RAM, disk, git, runtime, existing install, internet
- **Tauri v2 desktop app** — .AppImage/.deb/.rpm, ships with every install
- **JetBrains plugin** — v0.2.2, 1.6 MB, ships with every install
- **Customer dashboard** — Laravel app in every product tarball
- **6 MCP tools**: `venzari_doctor`, `venzari_list_tasks`, `venzari_get_logs`, `venzari_get_context`, `venzari_get_mode`, `code_run_automation`
- **6 languages**: English, Spanish, French, German, Japanese, Portuguese
- **Multi-agent orchestration**: SubagentPool, SwarmCoordinator, DAG branching — parallel workers, no file conflicts
- **Goal mode**: `venzari-code goal "<objective>"` with budget caps and parallel limits — autonomous from description to commit

---

## VENZARI ENGINE — Private AI Infrastructure

> **The only AI system where data privacy is architecture, not policy.**

[venzari.co/engine](https://venzari.co/engine) · `curl -fsSL https://install.venzari.xyz/engine | sh`

Here is how cloud AI privacy works: you send your data to a vendor's server. They promise to protect it. Their promise is a legal document. Legal documents can change. They can be overridden by a court order. They can be rendered meaningless when the company is acquired. The data is on their server the entire time, because that is how their product works.

Here is how VENZARI ENGINE privacy works: your data is on your server. There is no mechanism for VENZARI to access it. You can unplug the internet after installation and the system runs perfectly. The privacy guarantee is not a promise — it is the architecture.

### 7 Features, All Live, All On Your Hardware

**Conversational AI with Permanent Memory** — builds a cumulative understanding of your business across thousands of interactions. Every conversation, every decision, indefinitely and privately. This is not a stateless chatbot with a longer memory — it is a system that learns your organization.

**Local Voice Synthesis and Recognition** — offline text-to-speech and speech-to-text with no cloud latency and no third-party audio processing. Your voice data never leaves your server.

**Business Workflow Automation** — pre-built and custom workflows for scheduled reports, email drafting, CRM queries, database lookups, API integrations, calendar management. ENGINE is designed for business-layer actions only: HTTP, email, SQL, CRM, calendar. It does not edit code repositories.

**Web Dashboard** — a full web UI accessible at your domain (ai.yourcompany.com): AI chat, memory search, voice controls, workflow management, system monitoring, user management. You deploy it once and your whole company uses it.

**REST API** — connects ENGINE to any existing business system locally. ERP, CRM, ticketing, HR platforms. All data stays local.

**Semantic Memory Search** — search everything the system has ever learned using natural language queries. "What did we discuss about the Acme contract in March?" returns the relevant context instantly. The answer has always been in there. Now you can find it.

**Custom Fine-tuning Pipeline** *(Growth tier)* — train a custom AI model on your company's own conversations and domain knowledge. The trained model runs locally. Your training data never goes to a training provider.

### The Installer: 20 Minutes. From Zero to Full Private AI Stack.

Most companies that want private AI infrastructure face a genuine problem: it takes 3 to 6 months and a dedicated AI engineering team to build. VENZARI ENGINE's installer does it in 20 minutes with someone who knows SSH.

**Stage 1 — 11 Pre-Install Checks (automatic, parallel, before a single wizard question):**

| Check | Warn at | Fail at |
|-------|---------|---------|
| RAM | < 16 GB | < 8 GB |
| Disk space | < 40 GB free | < 60 GB free |
| Port 4001 | — | Occupied |
| Port 11434 | — | Occupied |
| Port 5432 | — | Occupied |
| Port 6379 | — | Occupied |
| Docker | Not running | Not installed |
| Internet | — | No connectivity to installer.venzari.xyz |
| Sudo access | — | Not available |
| Existing install | — | Detected (prompts choice) |
| Architecture | — | Unsupported CPU |

Any failure stops immediately and tells the operator exactly what to fix before continuing. No partial installs. No mystery errors.

**Stage 2 — 7-Question Wizard:**
Server identity (domain, company name, admin email) → License key validation → AI provider preference (local-only / local + cloud / cloud-only) → Model selection (hardware-adaptive recommendations displayed) → Optional add-ons (Growth+ features) → Final review → Confirmation.

**Stage 3 — 17-Step Worker-Driven Install Plan:**
Your hardware profile is sent to `installer.venzari.xyz`. The Worker returns a 17-step plan customized for your hardware tier and license. Steps: pre-install verification → binary download (SHA256 verified) → AI model pull (fast) → AI model pull (reasoning) → embedding model pull → docker-compose write → service startup → health checks × 4 → gateway configuration → SSL configuration → nginx setup → ecosystem wiring (auto-detects CODE and AI AGENT) → MCP registration → anonymous install count ping → final verification.

**2,301 automated tests back every step. Resumable at any point: `venzari-engine install --repair`**

### Hardware Requirements

| Resource | Minimum | Comfortable | Recommended |
|----------|---------|------------|-------------|
| CPU | 4 cores | 8 cores | 16+ cores |
| RAM | 8 GB | 16 GB | 32–64 GB |
| Storage | 60 GB SSD | 100 GB | 200+ GB NVMe |
| GPU | Not required | Not required | NVIDIA ≥8 GB VRAM (5-15× faster inference) |
| OS | Ubuntu 22.04 LTS | Ubuntu 22.04 LTS | Ubuntu 22.04 LTS |

### Status: All 33 Phases Complete. v1.0.0 Launched 2026-09-05.

| Phase range | What was built |
|-------------|---------------|
| 0–15 | Core AI stack, wizard, smart installer, LiteLLM config, SSL, security, observability, launch prep |
| 8 | Resumable state machine: `--repair`, `--reset` |
| 10 | nginx, certbot, Caddy fallback, keepwarm |
| 12 | Custom training pipeline (export → train → import) |
| 13 | Security hardening, Authelia (Enterprise), backup, secret rotation |
| 14 | Prometheus + Grafana observability dashboards (Growth+) |
| 15 | Self-update: `venzari-engine upgrade` with checksum-verified binary swap |
| 18 | Email lifecycle triggers: 6 events × 6 locales |
| 19 | Clean uninstall: `venzari-engine uninstall [--keep-data] [--yes]` |
| 21 | CLI i18n: 6 languages, 21 keys, `--locale` flag |
| 22 | Security CI: 0 vulns, 0 secrets, 0 GPL/AGPL, CycloneDX SBOM |
| 23 | Ecosystem integration: auto-detect CODE + AI AGENT, `ecosystem status|wire` |
| 24 | 17-check pre-publish CI gate before every release |
| 26 | Privacy-safe install ping telemetry (no PII) |
| 28 | 11-check pre-install environment checker |
| 29 | ENGINE-specific step handlers: nginx SSL, gateway config, Gigapipe, sudo-prefix |
| 30 | MCP server: 16 tools |
| 32 | E2E smoke test: 15/15 full checks (CLI, security, package, bun test, Worker plan, MCP) |
| 33 | v1.0.0 public launch: R2 artifacts, install.venzari.xyz deployed, GitHub Release |

---

## VENZARI AI AGENT — Persistent Autonomous Agent

> **Not a chatbot. The first agent that remembers everything, works everywhere, and gets smarter every night.**

[venzari.co/products/venzari-ai-agent](https://venzari.co/products/venzari-ai-agent) · `curl -fsSL https://install.venzari.xyz/agent | sh`

You have used AI assistants. You have noticed what happens when you close the tab. Tomorrow, you open a new conversation and the AI has no idea who you are. You explain your project again. You re-establish your context. You do the same twenty minutes of setup you did yesterday.

VENZARI AI AGENT does not work this way. It is an always-on entity — not a conversation interface — that operates simultaneously across every channel you use, remembers every interaction permanently, and runs a learning loop every night that makes it more capable than it was the day before.

### 6 Live Channels — One Agent, One Memory

| Channel | Status |
|---------|--------|
| Telegram | ✅ Live |
| Slack | ✅ Live |
| Discord | ✅ Live |
| Email (Mailgun / Acelle) | ✅ Live |
| Web chat widget | ✅ Live |
| Webhook | ✅ Live |

Start on Telegram in the morning. Continue on Slack at lunch. Finish via email in the evening. Same agent. Same memory. Same context. The agent never asks you to re-explain anything.

### 3-Signal Memory Retrieval — Fast and Comprehensive

| Signal | Method | Speed | Best for |
|--------|--------|-------|---------|
| Vector embeddings | Semantic search | 50ms | "What did we discuss about billing?" |
| BM25 full-text | Exact phrase matching | 10ms | Code snippets, exact keywords |
| PageRank graph | Importance-weighted retrieval | 5ms | Most frequently referenced facts |

Three signals means nothing falls through the cracks — semantically similar content surfaces even when you don't use the exact words, exact phrases match when you do, and the most important facts surface first because the graph knows what matters most.

### 2,212 Skills — Tiered by Quality, Invoked Automatically

| Tier | Count | What it means |
|------|-------|---------------|
| S-tier | 11 | Flagship capabilities. The highest reliability, most tested, most maintained. |
| A-tier | 522 | High quality, broad coverage. The backbone of day-to-day capability. |
| B-tier | 1,679 | Community catalog. Wide reach, growing continuously. |

Skills are invoked automatically based on context. You do not select a skill. You describe what you want, and the agent finds the skill that handles it.

```bash
venzari-agent skills list             # browse all 2,212
venzari-agent skills search "email"   # search by keyword
venzari-agent skills run <id>         # run directly from CLI
```

### The Nightly Learning Loop — It Gets Smarter While You Sleep

Every night at 3am (configurable), the agent automatically:

1. **Creates new skills** — identifies repeated task patterns and builds new capabilities for them
2. **Improves existing skills** — rates skill performance based on usage signals, fixes underperformers
3. **Updates your context model** — learns new preferences, adjusts understanding of who you are
4. **Compresses memory** — retains key facts from old interactions, removes redundant data

This is not a marketing claim. It is a scheduled job that runs on your server. You wake up to an agent that is measurably more capable than yesterday.

### 8-Provider Model Router — Intelligence Is Never a Bottleneck

| Provider | Type | When it activates |
|----------|------|------------------|
| Local Ollama | Local | Default — free, private, zero-config |
| Groq | External | Fast inference, free API tier |
| Gemini | External | Free API tier available |
| OpenRouter | External | Broad model access |
| Cerebras | External | Ultra-fast inference |
| Anthropic | External | Claude models |
| OpenAI | External | GPT models |
| Bedrock | External | AWS enterprise |

**Circuit breaker:** 3 failures → provider bypassed automatically, recovery after cooldown.
**Budget monitor:** auto-downgrades model tier at 80% of session budget.
**ENGINE integration:** if VENZARI ENGINE is installed, all calls route through ENGINE's LiteLLM at :4001 — zero configuration required.

### Everything Else VENZARI AI AGENT Ships With

- **`venzari-agent` CLI binary** with 15+ commands: `start`, `stop`, `doctor`, `skills list`, `skills search`, `skills run`, `memory search`, `channels status`, `code status`, `upgrade`
- **Native desktop app** (Tauri v2 + SolidJS): 5 tabs (Chat · Skills · Memory · Channels · Settings), system tray, minimize-to-tray, full VENZARI branding
- **9-page web dashboard** at agent.venzari.co: Overview · Chat · Skills · Memory · Tasks · Channels · Training · Evolution · AI Router. The AI Router page is unique in the market — shows current provider, model tier, cost today, budget bar, ENGINE probe status.
- **12 MCP tools** for any AI editor (Claude Code, Cursor, Kiro, VS Code, Gemini CLI): `agent_status`, `agent_router_status`, `agent_send_message`, `agent_get_conversation`, `agent_memory_search`, `agent_memory_get`, `agent_memory_add`, `agent_skills_list`, `agent_skills_search`, `agent_skills_run`, `agent_evolution_status`, `agent_channel_list`
- **422 tests passing, 0 failing**
- **Ecosystem integration**: auto-detects VENZARI ENGINE and CODE, wires to both automatically

---

## VENZARI Together — The Complete Stack

> **CODE + ENGINE on one machine. Zero cloud inference. Works offline.**

[venzari.co/together](https://venzari.co/together) · `curl -fsSL https://install.venzari.xyz/together | sh`

One installer. Two products. Fully wired. VENZARI CODE routes all AI inference through ENGINE's local LiteLLM gateway. No cloud calls for development. No external API costs. No data leaving the machine.

```
Your Machine
  ├── venzari-code CLI
  │       │  routes to
  │       ▼
  ├── LiteLLM :4001   ← ENGINE provides this
  │       │  routes to
  │       ▼
  ├── Ollama :11434   ← local models (qwen, llama, and more)
  ├── ENGINE Dashboard :3000
  └── ~/.venzari-together/   ← Together config
```

The 22-step hardware-aware install plan detects your machine's CPU, GPU, RAM, and disk before selecting models and configuring services. `venzari-together doctor` confirms everything is healthy. `venzari-together status` shows the combined state of both products.

**Requirements:** 8 GB RAM minimum (16 GB recommended) · 20 GB disk minimum · Ubuntu 20.04+ · GPU optional but significantly faster

---

## VENZARI ENTERPRISE

> **White-label. Dedicated infrastructure. Your brand. Full SLA.**

[venzari.co/enterprise](https://venzari.co/enterprise)

The complete VENZARI ecosystem under your brand. Custom skill development, managed fleet, dedicated infrastructure, direct access to the VENZARI team, and full service level agreements.

For organizations that need everything VENZARI offers and want it deployed and maintained as their own product. [Contact us](https://venzari.co/contact) to discuss your requirements.

---

## Why VENZARI — Their Way vs. Our Way

| Question | Their way | VENZARI way |
|----------|-----------|-------------|
| Where does the data go? | Vendor's cloud. Their terms. | Your server. Full stop. |
| What does it cost? | Per token. No ceiling. | Flat monthly fee. |
| What's the privacy guarantee? | A policy document. | The architecture itself. |
| Does it remember you? | Session only. Start over tomorrow. | Everything. Permanently. |
| How long to set up? | API key in minutes. Or 3-6 months. | 20 minutes for the full stack. |
| What do you own? | Nothing. You rent access. | Binary, data, and future. |
| What if VENZARI disappears? | Nothing left. | Your system keeps running. |

---

## The Installer Is the Product

Most private AI tools require either a developer to set up an API key (and you get nothing durable) or a 3-6 month engineering project (and most companies don't finish). VENZARI's installer is the third option: 20 minutes, SSH access, and you have a complete system.

**11 pre-flight checks.** Every problem is caught before installation begins. No partial states.
**7 wizard questions.** Server identity, license, AI provider choice, model selection. That's it.
**17 worker-driven steps.** Hardware-customized. Resumable. Backed by 2,301 tests.

`venzari-engine install --repair` skips completed steps and retries from the failure point. The install is not a one-shot script — it is a resumable state machine.

---

## Start Now

```bash
# VENZARI CODE — Engineering OS
curl -fsSL https://install.venzari.xyz | bash && venzari-code install

# VENZARI ENGINE — Private AI Infrastructure
curl -fsSL https://install.venzari.xyz/engine | sh

# VENZARI AI AGENT — Persistent Autonomous Agent
curl -fsSL https://install.venzari.xyz/agent | sh

# VENZARI Together — CODE + ENGINE, one machine
curl -fsSL https://install.venzari.xyz/together | sh
```

**Starting at $29/month.** No per-token billing. No cloud dependency. No data leaving your hardware.

[venzari.co/pricing](https://venzari.co/pricing) · [docs.venzari.co](https://docs.venzari.co) · [install.venzari.xyz](https://install.venzari.xyz)

---

## All Links

[Website](https://venzari.co) · [CODE](https://venzari.co/code) · [ENGINE](https://venzari.co/engine) · [AI AGENT](https://venzari.co/products/venzari-ai-agent) · [Together](https://venzari.co/together) · [Enterprise](https://venzari.co/enterprise) · [Pricing](https://venzari.co/pricing) · [Docs](https://docs.venzari.co) · [Install](https://install.venzari.xyz) · [Solutions](https://venzari.co/solutions) · [Jobs](https://venzari.co/jobs) · [Contact](https://venzari.co/contact) · [Discord](https://discord.gg/venzari)

---

<div style="margin-top:3rem;padding-top:2rem;border-top:1px solid rgba(255,255,255,.08);color:rgba(253,251,249,.6);font-size:.85rem;line-height:1.6;">
  © 2026 VENZARI<br/>
  <em>Your AI. Your Hardware. Your Future.</em>
</div>

<script>
  (function() {
    var html = document.documentElement;
    html.style.fontFamily = "'Poppins','Unbounded',system-ui,sans-serif";
    var heads = document.getElementsByTagName('head');
    if (heads.length > 0) {
      var link = document.createElement('link');
      link.rel = 'preconnect'; link.href = 'https://fonts.googleapis.com';
      heads[0].appendChild(link);
      var unbounded = document.createElement('link');
      unbounded.rel = 'stylesheet';
      unbounded.href = 'https://fonts.googleapis.com/css2?family=Unbounded&display=swap';
      heads[0].appendChild(unbounded);
    }
  })();
</script>
