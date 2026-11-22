# VENZARI — Category Creation, Not Competition

<div align="center">

  <pre align="center" style="color:#3251fc;background:#0d0d0d;padding:16px;border-radius:8px;font-size:12px">
██╗   ██╗██████6║██████6║██████6║███████╗ █████╗ ██████╗ ██╗
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
    You're comparing VENZARI to ChatGPT, Copilot, Claude, or OpenCode? You're asking the wrong question. VENZARI isn't "better" — it's a different kind of product for different needs.
    <br/><br/>
    <a href="https://venzari.co/pricing" style="color:#3251fc;font-weight:600;">Own Your Stack →</a>
  </p>

  <div style="display:flex;flex-wrap:wrap;gap:0.75rem;justify-content:center;margin:1.5rem 0;">
    <a href="https://venzari.co/code">
      <img src="https://img.shields.io/badge/VENZARI%20CODE-Engineering%20OS-#A259FF?style=for-the-badge" alt="VENZARI CODE"/>
    </a>
    <a href="https://venzari.co/engine">
      <img src="https://img.shields.io/badge/VENZARI%20ENGINE-Private%20AI-#C1FF00?style=for-the-badge" alt="VENZARI ENGINE"/>
    </a>
    <a href="https://venzari.co/products/venzari-ai-agent">
      <img src="https://img.shields.io/badge/VENZARI%20AI%20AGENT-Multi-Channel-#3251FC?style=for-the-badge" alt="VENZARI AI AGENT"/>
    </a>
    <a href="https://venzari.co/together">
      <img src="https://img.shields.io/badge/VENZARI%20TOGETHER-One%20Stack-#3251FC?style=for-the-badge" alt="VENZARI TOGETHER"/>
    </a>
    <a href="https://venzari.co/enterprise">
      <img src="https://img.shields.io/badge/VENZARI%20ENTERPRISE-Custom-#FF38D4?style=for-the-badge" alt="VENZARI ENTERPRISE"/>
    </a>
  </div>

</div>

<br/>

---


## 🏛️ The Three New Categories — Category Design

> **Category design** is the practice of creating a new market category rather than competing in an existing one. This document defines the new categories VENZARI is creating and how to evangelize them.

VENZARI's actual competitive differentiation is not "better AI" — it is:

1. **The ownership position:** No cloud vendor can offer what ENGINE offers. Private AI infrastructure is structurally incompatible with the cloud AI business model.
2. **The governance position:** No AI coding assistant currently offers what CODE offers. Governance, mode lifecycle, and evidence requirements require building a product specifically for that purpose — not adding features to an assistant.
3. **The integrated ecosystem:** The combination of ENGINE + CODE + AI AGENT is unique. No other vendor operates at all three layers.

> **Positioning principle:** Never position as "better than" — always position as "different category" where possible. The goal is not to win a comparison — it is to make comparison irrelevant by defining the category correctly.

---

## 🛠️ VENZARI CODE — Engineering OS (Not a Coding Assistant)

### Why It's a New Category

> **The old category:** AI coding assistant — a tool that responds to developer prompts.
> **The new category:** Engineering OS — the governance substrate on which AI-assisted development runs.

AI coding assistants are tools. An OS is the environment in which tools operate — managing resources, enforcing constraints, maintaining state, providing the system calls that everything else depends on. VENZARI CODE is not a better Copilot. It is the layer that decides when Copilot (or any AI) is allowed to do what, with what evidence, in which phase.

### The 13-Mode Governance Lifecycle

```
Discover → Plan → Implement → Validate → Review → Repair → Commit
Advisor | Handoff | Audit | Benchmark | Migration | Release
```

Each mode has different capabilities and different risk tolerances. Treating them all the same — as AI assistants do — is what causes problems.

| Mode | Capability | Risk Tolerance | What It Prevents |
|------|------------|----------------|------------------|
| **Discover** | Scans environment, reads project structure, writes nothing, executes nothing | Low — observational only | Jumping into implementation without understanding |
| **Plan** | Writes plan — specific files to change, specific steps to take, specific tests to add | Low — document, not code | Unplanned implementation that doesn't match architecture |
| **Implement** | Executes plan within approved scope | Medium — constrained tools | AI doing unexpected things "while it's at it" |
| **Validate** | Tests must pass — produces actual test output, not AI's claim | High — gates Review | Shipping broken code with AI's assurance |
| **Review** | Static analysis, code quality checks, security scanning — read-only | High — report only | Unreviewed AI code going directly to production |
| **Repair** | Targeted fix-only mode — task scope locked to specific failure | Medium — limited scope | Scope creep during fixes |
| **Commit** | Only mode allowing git operations — structured commit message with evidence references | High — git gated | Partial work, uncommitted changes, messy history |

**Other modes:** Advisor (high-level analysis only), Handoff (structured handoff document), Audit (reviews session evidence records), Benchmark (performance regression tracking), Migration (full write + execute access), Release (full deploy access — evidence-gated).

### Companion System

`venzari-code install` creates a `.venzari/` directory in your project containing:

| Component | Purpose | Current Status |
|-----------|---------|----------------|
| **Agents** | Configured agent roles with specific capabilities and constraints | [LIVE] — 6 default agents |
| **Skills** | Reusable task templates for common operations | [LIVE] — 2,212 built-in skills |
| **Tasks** | Structured task definitions with opening and closing gates | [LIVE] — 13-mode lifecycle gates |
| **Rules** | Project-specific constraints that override defaults | [LIVE] — per-project rules |
| **Memory** | Session history, codegraph, architectural decisions | [LIVE] — persistent SQLite database |
| **Closing gates** | Automated checks that must pass before task completion | [LIVE] — evidence-gated |

> **Current Status:** Distribution [LIVE] — curl install. Version [LIVE] — 1.0.0. Automated tests [LIVE] — 1,508 passing, 0 failing (74 test files). Pre-install checker [LIVE] — 6 checks (CODE-A). Mode lifecycle [LIVE] — 13 modes enforced.

**[vzari.co/code →](https://venzari.co/code)**

---

## ⚙️ VENZARI ENGINE — Private AI Infrastructure (Not a Cloud AI Service)

### Why It's a New Category

> **The old category:** Cloud AI API — you pay a vendor for access to AI on their servers.
> **The new category:** Private AI infrastructure — a complete AI system running on your VPS, at flat cost, with structural privacy (not just policy).

The cloud AI market is not the right competitive frame for ENGINE. ENGINE is not a better ChatGPT. It is a different kind of product that requires no ongoing vendor relationship, stores no data externally, and creates no per-token cost. The comparison to cloud AI is like comparing buying a generator to paying for electricity — they solve the same problem in fundamentally different ways.

### What the Installed System Provides

| # | Feature | Status | What It Delivers |
|---|---------|--------|------------------|
| 1 | **Conversational AI with Persistent Memory** | 🟢 Live | Remembers everything — every conversation, decision, piece of company knowledge — indefinitely and privately. This is not a stateless chatbot. |
| 2 | **Local Voice Synthesis & Recognition** | 🟢 Offline | Text-to-speech and speech-to-text with no cloud latency, no third-party audio processing. The company's voice interactions never leave their server. |
| 3 | **Business Workflow Automation** | 🟢 Live | Pre-built and custom workflows for: scheduled reports, email drafting, CRM queries, database lookups, API integrations, calendar management. ENGINE is designed for business-layer actions only — HTTP, email, SQL, CRM, calendar. It does not edit code repositories. |
| 4 | **Web Dashboard** | 🟢 Live | Full UI accessible at the company's domain (e.g., ai.acme.com): AI chat interface, memory search, voice controls, workflow management, system monitoring, and user management. |
| 5 | **REST API** | 🟢 Live | Local REST API that connects ENGINE to any existing business system — ERP, CRM, ticketing systems, HR platforms. All locally. |
| 6 | **Semantic Memory Search** | 🟢 Live | Search everything the system has ever learned — conversations, documents, decisions — using natural language queries. "What did we discuss about the Acme contract in March?" returns the relevant context instantly. |
| 7 | **Custom Fine-Tuning Pipeline** | 🟢 Growth+ | Train a custom AI model on the company's own conversations and domain knowledge. The trained model runs locally — the company's data never leaves to a training provider. Export conversations, generate a training config, launch training on available GPU, import the resulting model back into the stack. |

### Structural Privacy

> **"We don't just say your data is private. Your data physically cannot leave your hardware."**

With cloud AI, a vendor's privacy policy is a legal document that can change, expire, be superseded by acquisition, or be overridden by a legal request to the vendor. The data leaves your control the moment you send it.

With VENZARI ENGINE, data never leaves the customer's hardware by design. There is no architecture by which VENZARI can access it. The privacy guarantee is **structural, not contractual**.

This matters for:
- Companies with trade secret concerns
- Companies in regulated industries (healthcare, legal, finance)
- Companies in countries with data sovereignty requirements
- Companies whose clients contractually prohibit data sharing with third parties

### The Installer Architecture — Three Stages

<details>
<summary>Stage 1 — Pre-install checks (automatic, before any wizard questions)</summary>

11 parallel checks enforce: RAM (≥8 GB warn, <8 GB fail), disk (≥60 GB warn, <60 GB fail), ports 4001/11434/5432/6379 free, the container runtime installed + running, internet connectivity to the VENZARI installer service, sudo access, existing install detection. Any failure stops the process and tells you exactly what to fix.

</details>

<details>
<summary>Stage 2 — The setup wizard (7 questions)</summary>

Server identity (domain/IP, company name, admin email), license key validation, AI provider preference (local-only, local + cloud fallback with 13 supported providers, or cloud-only), hardware-adaptive model recommendations, optional add-ons (Growth+ only), and final confirmation.

</details>

<details>
<summary>Stage 3 — Worker-driven install plan (17 steps executed locally)</summary>

After the wizard, the installer sends your hardware profile to the VENZARI Installer Worker at `the VENZARI installer service`. The Worker returns a 17-step plan customized for your hardware tier and license. Steps include:

1. Pre-install verification
2. Binary download
3. AI model pulls (fast + reasoning + embedding)
3. the service orchestrator write and service startup
4. Health checks for each service
5. Gateway configuration (probes all configured AI providers)
6. SSL and nginx configuration
7. Ecosystem wiring (detects co-installed CODE/AI AGENT)
8. MCP registration
9. Anonymous install count ping
10. Step retry logic (each step has it)
11. Resumable at any point with `the resume-repair command`
12. 2,301 automated tests coverage
12. Offline operation after installation

> **2,301 automated tests** cover every step, every retry, every ecosystem wiring.

> **You close your internet connection after installation and the system continues to function.** No per-token billing. No cloud dependency. Fixed monthly pricing.

</details>

### Hardware Requirements

| Resource | Minimum | Recommended |
|----------|---------|-------------|
| **CPU** | 4 cores | 16+ cores |
| **RAM** | 8 GB (warns), 16 GB (comfortable) | 32–64 GB |
| **Storage** | 60 GB SSD | 200+ GB NVMe |
| **GPU** | Not required | NVIDIA ≥8 GB VRAM (CUDA) |
| **OS** | Ubuntu 22.04 LTS | Ubuntu 22.04 LTS |
| **Network** | Static IP recommended | Static IP |

### Pricing Tiers

| Tier | Price | Who It's For |
|------|-------|--------------|
| **Foundation** | $349/mo | Companies that want private AI for knowledge, conversation, and memory |
| **Growth** | $899/mo | Companies that want custom AI training, observability dashboards, and Growth+ features |
| **Enterprise** | $2,499/mo | Companies that need white-label, SLA, and enterprise support |
| **Founder-Guided Setup** | $2,499 one-time | Done-with-you installation and configuration session |

> **Licensing model:** License key gates the real binary download. All valuable commands require a valid license. 24-hour offline grace period. No phone-home required after activation — the system works even if VENZARI ceases to exist.

> **Current Status:** ALL 33 PHASES COMPLETE — v1.0.0 launched 2026-09-05

**[vzari.co/engine →](https://venzari.co/engine)**

---

## 🤖 VENZARI AI AGENT — Persistent Autonomous Agent (Not a Chatbot)

### Why It's a New Category

> **The old category:** AI chatbot — a stateless question-answerer that forgets you the moment you close the tab.
> **The new category:** Persistent autonomous agent — an always-on entity that works across all your channels, learns permanently, and acts independently.

Chatbots are stateless question-answerers. Autonomous agents have memory, take actions, improve over time, and operate proactively. The difference is not one of degree — it is one of kind. A chatbot waits to be asked. An autonomous agent can anticipate, create capabilities from experience, and operate across every platform you use simultaneously.

### What It Does — Multi-Channel Presence

One VENZARI AI AGENT instance operates simultaneously across all connected channels. Start a conversation on Telegram, pick it up on Slack, continue via email. The agent maintains context across all channels — same identity, same memory, regardless of channel.

**Live channels (Phase 26):** Telegram · Slack · Discord · Email (Mailgun/Acelle) · Web chat widget · Webhook

### Persistent Memory — Three-Signal Retrieval

| Signal | Method | Speed | What It Finds |
|--------|--------|-------|---------------|
| **Vector embeddings** | Semantic search ("what did we discuss about billing?") | 50ms | Semantic meaning of past conversations |
| **BM25 full-text** | Exact phrase search, code snippets | 10ms | Code snippets, exact phrases |
| **PageRank graph** | Most important/referenced memories | 5ms | Key facts, highly-referenced context |

### 2,212 Real Skills — Tier Breakdown

Skills are tiered by quality and tested (Phase 25):

| Tier | Count | Quality |
|------|-------|---------|
| **S-tier** | 11 | Highest quality, most reliable, flagship capabilities |
| **A-tier** | 522 | High quality, broad coverage |
| **B-tier** | 1,679 | Community catalog, broad reach |

Total: **2,212 real skills** invoked automatically based on what you ask. No explicit skill selection needed.

### 8-Provider Model Router

| Provider | Speed | Config | Purpose |
|----------|-------|--------|---------|
| **Local local inference** | Free, private, zero-config | Fast prompts ≤1,200 tokens | Primary path — always tried first |
| **Groq** | Fast inference | External provider, free API tier | Fallback chain |
| **Gemini** | External provider | Free API tier available | Secondary cloud fallback |
| **OpenRouter** | Broad model access | Multiple model providers | Model diversity |
| **Cerebras** | Ultra-fast inference | Specialized hardware | Speed-critical prompts |
| **Anthropic** | Claude models | External provider | Claude-specific requirements |
| **OpenAI** | GPT models | External provider | When GPT-4/Turbo needed |
| **Bedrock** | AWS enterprise | Enterprise pricing | Company already on AWS |

**Circuit breaker:** 3 failures → provider bypassed, auto-recovery after cooldown. **Budget monitor:** auto-downgrades model tier at 80% of session budget.

### Pricing Tiers

| Tier | Price | What You Get |
|------|-------|-------------|
| **Starter** | $29/mo | Full agent, all 2,212 skills, 5 channels, unlimited memory |
| **Professional** | $99/mo | Multi-agent support, all 6 channels, dashboard, team sharing |
| **Enterprise** | $499/mo | Managed fleet, custom skills, SLA, dedicated instance, API access |

> **Note:** There is no free tier. All tiers require an active paid subscription.

> **Current Status:** Tests [LIVE] — 422 pass, 0 fail

**[vzari.co/products/venzari-ai-agent →](https://venzari.co/products/venzari-ai-agent)**

---

## 🚀 VENZARI TOGETHER — The Complete Stack (Not Three Vendors)

### Why It's a New Category

> **The old category:** Separate products, separate licenses, separate installs, separate integrations.
> **The new category:** The complete stack — CODE + ENGINE + AI AGENT working as one system — one command, one license, one owner: you.

### Architecture

```
Your Machine
  ├── venzari-code CLI → routes to
  │       ▼
  ├──  ← ENGINE gateway
  │       ▼
  ├── local inference  ← local models (qwen, llama, etc.)
  ├── ENGINE Dashboard 
  └── ~/.venzari-together/ ← Together config dir
```

> **No cloud calls for inference when Together is active.** CODE never touches `ai.venzari.xyz` when Together is active.

### Requirements

| Resource | Minimum | Recommended |
|----------|---------|-------------|
| **RAM** | 8 GB | 16 GB+ |
| **Disk** | 20 GB free | 50 GB+ |
| **OS** | Linux Ubuntu 20.04+ | Ubuntu 22.04 LTS |
| **GPU** | Optional | NVIDIA 8 GB+ VRAM |

### After Install


**[vzari.co/together →](https://venzari.co/together)**

---

## 🏢 VENZARI ENTERPRISE — Custom Deployment (Not Single-Vendor Lock-in)

### Why It's a New Category

> **The old category:** Enterprise AI platforms — $100,000+/year, months of implementation, single-vendor lock-in.
> **The new category:** Enterprise VENZARI — custom deployment, SLA support, dedicated infrastructure, direct team access.

| Dimension | Enterprise Platforms | VENZARI ENTERPRISE |
|-----------|---------------------|---------------------|
| **Price** | $100,000+/year | $5,988/year |
| **Implementation** | Months | Under 5 minutes |
| **Channels** | Varies (often limited) | 6 live |
| **Learning loop** | None | Active nightly loop |
| **CLI binary** | ❌ | ✅ |
| **Desktop app** | ❌ | ✅ |
| **MCP server** | ❌ | ✅ 12 tools |
| **ENGINE/CODE integration** | ❌ | ✅ Auto-wired |
| **Ecosystem** | Single-vendor lock-in | VENZARI full stack |

> **Contact for Enterprise:** <a href="mailto:venzariai@gmail.com">venzariai@gmail.com</a>

---

## 📊 Competitive Positioning Tables

### vs. Cloud AI APIs (OpenAI, Anthropic, Google AI)

| Dimension | Cloud AI APIs | VENZARI ENGINE |
|-----------|--------------|----------------|
| Data location | Vendor's cloud | Your server |
| Pricing | Per-token | Flat monthly |
| Privacy guarantee | Policy | Architecture |
| Memory | Session-only | Permanent, private |
| Setup time | Minutes (API key) | 20 minutes (full stack) |

**Positioning statement:** "Cloud AI APIs are development tools. VENZARI ENGINE is infrastructure. They're for different purposes. You use an API key to experiment; you use ENGINE when the work is serious and the data is sensitive."

### vs. AI Coding Assistants (GitHub Copilot, Cursor, Claude Code, Codeium)

| Dimension | AI Coding Assistants | VENZARI CODE |
|-----------|---------------------|--------------|
| Category | Tool | Operating System |
| Memory | Session-only | Permanent, project-scoped |
| Governance | None | 13-mode lifecycle + tool guards |
| Evidence | None | Required for every completion |
| Loop detection | None | 3-strike escalation |

**Positioning statement:** "If you have the AI engineering team and 6 months, building your own stack makes sense. ENGINE is for companies that want the outcome — working private AI — without the engineering investment."

### vs. Cloud Chatbots (ChatGPT, Claude, Gemini)

| Dimension | Cloud Chatbots | VENZARI AI AGENT |
|-----------|---------------|------------------|
| Memory | Session-only (or limited) | Permanent, cross-session, cross-channel (3-signal) |
| Channels | 1 (their app) | 6 live simultaneously |
| Learning loop | None | Nightly skill creation |
| Skills | Implicit | 2,212 curated (11 S-tier + 522 A + 1,679 B) |
| CLI binary | ❌ | ✅ `venzari-agent` — 15+ commands |
| Desktop app | ❌ | ✅ Tauri v2, 5 tabs, system tray |
| MCP server | ❌ | ✅ 12 tools for any AI editor |
| Model router | ❌ | ✅ 8 providers, circuit breaker, budget monitor |
| Ecosystem | ❌ | ✅ Auto-wires to ENGINE + CODE |
| Price | $20/mo (Pro) | $29/mo (full agent) |

**Positioning statement:** "ChatGPT is a chat interface. VENZARI AI AGENT is an autonomous agent. ChatGPT answers questions and forgets you. The Agent takes actions, remembers everything, improves over time, has a CLI, a desktop app, an MCP server, and wires to your entire private AI stack."

### vs. Enterprise AI Platforms (ServiceNow AI, Salesforce Einstein)

| Dimension | Enterprise Platforms | VENZARI AI AGENT (Enterprise) |
|-----------|---------------------|------------------------------|
| Price | $100,000+/year | $5,988/year |
| Implementation | Months | Under 5 minutes |
| Channels | Varies (often limited) | 6 live |
| Learning loop | None | Active nightly loop |
| CLI binary | ❌ | ✅ |
| Desktop app | ❌ | ✅ |
| MCP server | ❌ | ✅ 12 tools |
| ENGINE/CODE integration | ❌ | ✅ Auto-wired |
| Ecosystem | Single-vendor lock-in | VENZARI full stack |

**Positioning statement:** "Enterprise AI platforms are priced for Fortune 500 budgets with 6-month implementations. VENZARI AI AGENT Enterprise is for mid-market and growth-stage companies that need enterprise capability at reasonable cost — with a CLI, desktop app, and full VENZARI ecosystem integration that no enterprise platform offers."

---

## 🎯 The Installer — Your Personal CTO (The Wow Factor)

> **The most incredible thing is the way our VENZARI INSTALLER handles all the hard setup and config — like you have hired your own VENZARI CTO to get it done and working all on its own, stiff like that it should be written in the style of the ad creator \GARY BRIGGS.**

| Feature | What It Means |
|---------|---------------|
| **11 parallel pre-install checks** | RAM, disk, ports, the container runtime, connectivity, sudo, existing install — any failure stops and tells you exactly what to fix |
| **7-question setup wizard** | Server identity, license key, AI provider preference, hardware-adaptive models, optional add-ons, confirmation |
| **17-step worker-driven install plan** | Hardware profile sent to VENZARI Installer Worker at `the VENZARI installer service` — customized for your tier |
| **Resumable repair mode** | `the resume-repair command` skips completed steps, retries from failure point |
| **2,301 automated tests** | Every step, every retry, every ecosystem wiring covered |
| **Offline after install** | Close your internet connection — system continues to function |

> **The installer is the product.** It makes enterprise-grade AI infrastructure available to companies that could never build it themselves.

<blockquote>
<p style="color:#5EE7FF;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  ⚡ <strong>Installer Status:</strong> Distribution [LIVE] — All 33 phases complete. v1.0.0 launched 2026-09-05
</p>
</blockquote>

---

## 🏆 Why VENZARI? Category Design Summary

> **Everyone else sells you a piece. VENZARI sells you the whole exit.**

| What You Get | VENZARI | Everyone Else |
|--------------|---------|---------------|
| **Ownership** | You own the binary, the data, the future | They own it; you rent access |
| **Pricing** | Flat monthly fee — no per-token surprise | Per-token billing — costs spiral |
| **Data Privacy** | Your data never leaves your hardware — structurally | Policy-based; can change, expire, be overridden |
| **Memory** | Learns continuously — doesn't forget between sessions | Session-only; forgets you completely |
| **Channels** | Every channel, one agent — Telegram, Slack, Discord, Email, Webhook | Single channel per tool |
| **Setup** | Installs itself — like you hired your own CTO | Days to months of engineering work |
| **Governance** | 13-mode lifecycle + evidence + loop detection | None — unconstrained AI behavior |

---

## 📦 Start Your Journey

<div style="display:flex;flex-wrap:wrap;gap:1rem;justify-content:center;margin:2rem 0;">
  <a href="https://venzari.co/code" style="background:linear-gradient(90deg,#3251fc,#A259FF);color:#04111f;padding:12px 24px;border-radius:8px;font-weight:800;font-family:'Poppins',sans-serif;text-decoration:none;">
    🛠️ VENZARI CODE
  </a>
  <a href="https://venzari.co/engine" style="background:linear-gradient(90deg,#0A102F,#5EE7FF);color:#04111f;padding:12px 24px;border-radius:8px;font-weight:800;font-family:'Poppins',sans-serif;text-decoration:none;">
    ⚙️ VENZARI ENGINE
  </a>
  <a href="https://venzari.co/products/venzari-ai-agent" style="background:linear-gradient(90deg,#3251fc,#C1FF00);color:#04111f;padding:12px 24px;border-radius:8px;font-weight:800;font-family:'Poppins',sans-serif;text-decoration:none;">
    🤖 VENZARI AI AGENT
  </a>
  <a href="https://venzari.co/together" style="background:linear-gradient(90deg,#3251fc,#3251fc);color:#04111f;padding:12px 24px;border-radius:8px;font-weight:800;font-family:'Poppins',sans-serif;text-decoration:none;">
    🚀 VENZARI TOGETHER
  </a>
  <a href="https://venzari.co/enterprise" style="background:linear-gradient(90deg,#FF38D4,#FF38D4);color:#04111f;padding:12px 24px;border-radius:8px;font-weight:800;font-family:'Poppins',sans-serif;text-decoration:none;">
    🏢 VENZARI ENTERPRISE
  </a>
</div>

<br/>

---

<p align="center">
<strong>VENZARI</strong> &nbsp;·&nbsp; <a href="https://venzari.co">venzari.co</a> &nbsp;·&nbsp; <a href="https://discord.gg/venzari">Discord</a> &nbsp;·&nbsp; <a href="https://venzari.co/jobs">Jobs</a><br/>
<em>Your AI. Your Hardware. Your Future. &nbsp;·&nbsp; © 2026 VENZARI</em>
</p>

---

## 📚 Full Suite Reference — All Products, All Links

### Company & Brand

| Resource | URL | Type |
|----------|-----|------|
| Official Website | [venzari.co](https://venzari.co) | Company homepage |
| Documentation Portal | [docs.venzari.co](https://docs.venzari.co) | Full docs |
| Career Opportunities | [venzari.co/jobs](https://venzari.co/jobs) | Job listings |
| About & Solutions | [venzari.co/solutions](https://venzari.co/solutions) | Company story |
| Contact | [venzariai@gmail.com](mailto:venzariai@gmail.com) | Direct email |

### Products — All Five

| Product | Product URL | Installation URL | Category Definition |
|---------|-------------|-------------------|---------------------|
| VENZARI CODE | [venzari.co/code](https://venzari.co/code) | `curl -FsSL install.venzari.xyz (customers only) | bash` | Engineering OS — governance substrate |
| VENZARI ENGINE | [venzari.co/engine](https://venzari.co/engine) | `curl -FsSL install.venzari.xyz (customers only) | Private AI infrastructure |
| VENZARI AI AGENT | [venzari.co/products/venzari-ai-agent](https://venzari.co/products/venzari-ai-agent) | `curl -FsSL install.venzari.xyz (customers only) | Persistent autonomous agent |
| VENZARI TOGETHER | [venzari.co/together](https://venzari.co/together) | `curl -FsSL install.venzari.xyz (customers only) | Full stack — one license |
| VENZARI ENTERPRISE | [venzari.co/enterprise](https://venzari.co/enterprise) | Contact for custom deployment | Enterprise deployment + SLA |

---

## 🔒 Golden Rules for AI (VENZARI Governance Principles)

> **These rules apply to all VENZARI products. Non-negotiable.**

1. **Every AI agent must follow Golden Rules.** No exceptions.
2. **Every change includes changed content + task evidence.**
3. **Every session has documented handoff with blocker tracking.**
4. **No hidden conflicts allowed.**
5. **No partial evidence — proof shown, not stated.**
6. **No evidence fabrication — URLs, SHAs, line numbers must be real.**
7. **Verification reproducible — commands work when re-run.**
8. **Evidence tracking consistent — supersede references for updates.**
9. **Task tracking complete — full lifecycle visible.**
10. **Every evidence record has source reference.**
11. **Each version references previous version.**
12. **No hidden manual steps — everything in checklist.**
13. **No hidden deletions — everything in removal record.**
14. **Agent reads rules before action. Every session starts with verification.**
15. **Every commit references evidence.**
16. **Evidence updates include full updated evidence.**
17. **No hidden blockers — tracked in blocker record with root cause.**

---

## 🧭 Category Evangelism Strategy

Don't fall back into comparison:

- Don't say "ENGINE is like OpenAI but private." → Say "ENGINE creates private AI infrastructure — different category from cloud APIs."
- Don't say "CODE is better than Copilot." → Say "CODE is an engineering OS — different category. Copilot writes code; CODE decides when code is allowed."
- Don't say "AGENT is like ChatGPT with features." → Say "AGENT is a persistent autonomous agent — acts independently, remembers permanently, improves over time."
- Don't say "VENZARI is cheaper/faster." → Say "VENZARI creates new category: complete AI stack you own."

The insight: when you define the category, you control evaluation. When customers compare VENZARI to ChatGPT, ChatGPT's framework wins. When customers see VENZARI as creating categories — private AI infrastructure, engineering OS, autonomous agent — comparison is irrelevant.

---

## 📝 Content Philosophy — "Content Is King" by Gary Briggs

This README follows Gary Briggs "Content Is King" principles, written in style of ad creator \GARY BRIGGS:

- **Headline-first:** Every section starts with what matters.
- **Problem-solution framing:** Old category (problem) → new category (solution).
- **Evidence over claims:** 1,508 tests, 2,212 skills, 13 modes, 33 phases, 2,301 automated tests — all verifiable.
- **Social proof through structure:** Comparison tables, badges, version numbers.
- **Visual hierarchy:** ASCII art header, gradient buttons, colored tables.
- **Clear call to action:** Direct links for each product.

---

## 📂 Related Resources

| Resource | URL | What It Is |
|----------|-----|------------|
| VENZARI.md | [docs/living-docs/](docs/living-docs/agent/explanation/PRODUCT-BRIEF.md) | Agent brief |
| CODE Brief | [docs/living-docs/code/](docs/living-docs/code/explanation/PRODUCT-BRIEF.md) | CODE spec |
| ENGINE Brief | [docs/living-docs/engine/](docs/living-docs/engine/explanation/PRODUCT-BRIEF.md) | ENGINE spec |
| AGENT Brief | [docs/living-docs/agent/](docs/living-docs/agent/explanation/PRODUCT-BRIEF.md) | AGENT spec |
| TOGETHER Brief | [docs/living-docs/together/](docs/living-docs/together/explanation/PRODUCT-BRIEF.md) | TOGETHER spec |
| Competitive | [docs/living-docs/positioning/COMPETITIVE-POSITIONING.md](COMPETITIVE-POSITIONING.md) | Positioning framework |
| Category Design | [docs/living-docs/positioning/CATEGORY-DESIGN.md](CATEGORY-DESIGN.md) | Evangelism strategy |
| Golden Rules | [cto/GOLDEN_RULES.md](cto/GOLDEN_RULES.md) | Governance rules |
<script>
  (function() {
    var html = document.documentElement;
    html.style.fontFamily = "'Poppins','Unbounded',system-ui,sans-serif";
    var heads = document.getElementsByTagName('head');
    if (heads.length > 0) {
      var link = document.createElement('link');
      link.rel = 'preconnect';
      link.href = 'https://fonts.googleapis.com';
      heads[0].appendChild(link);
      var unbounded = document.createElement('link');
      unbounded.rel = 'stylesheet';
      unbounded.href = 'https://fonts.googleapis.com/css2?family=Unbounded&display=swap';
      heads[0].appendChild(unbounded);
    }
  })();
</script>
