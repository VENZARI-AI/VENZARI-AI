# VENZARI — Engineering OS | Private AI | Multi-Channel Agent

<div align="center">

  <pre align="center" style="color:#3251fc;background:#0d0d0d;padding:16px;border-radius:8px;font-size:12px">
██╗   ██╗███████╗███╗   ██╗███████╗ █████╗ ██████╗ ██╗
██║   ██║██╔════╝████╗  ██║╚══███╔╝██╔══██╗██╔══██╗██║
██║   ██║█████╗  ██╔██╗ ██║  ███╔╝ ███████║██████╔╝██║
╚██╗ ██╔╝██╔══╝  ██║╚██╗██║ ███╔╝  ██╔══██║██╔══██╗██║
 ╚████╔╝ ███████╗██║ ╚████║███████╗██║  ██║██║  ██║██║
  ╚═══╝  ╚══════╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝
  </pre>

  <!-- Main Title -->
  <h1 style="font-family:'Unbounded',sans-serif;font-size:clamp(3rem,8vw,5rem);font-weight:800;color:#FDFBF9;letter-spacing:-0.02em;margin:1rem 0;">
    VENZARI
  </h1>
  <p style="font-family:'Poppins',sans-serif;font-size:1.25rem;color:rgba(253,251,249,.6);line-height:1.6;max-width:600px;margin:0 auto 2rem;">
    You've been renting your engineering OS and intelligence layer without noticing. VENZARI changes that. 
    We don't sell you access — we sell you the whole exit. 
    <a href="https://venzari.co/pricing" style="color:#3251fc;font-weight:600;">Pick your product. Pick your plan. Own your stack.</a>
  </p>

  <!-- Hero Badges -->
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

## 🛠️ VENZARI CODE — The Engineering OS That Governs AI

> **Not a coding assistant. The governance substrate on which AI-assisted development runs.**

### The Problem It Solves

Engineering teams that adopt AI coding tools quickly run into the same walls:

1. **Hallucination**: The AI confidently writes code that doesn't work, libraries that don't exist, or approaches that contradict the codebase architecture.
2. **Loop behavior**: The AI gets stuck in a loop trying to fix something, making it worse with each attempt.
3. **No accountability**: You can't audit what the AI did. There's no record. The commit history just shows "AI-generated code."
4. **Context loss**: Every new session starts from zero. The AI knows nothing about your codebase, your conventions, your past decisions.
5. **Tool promiscuity**: AI with filesystem access and shell execution can do unexpected things when not constrained.
6. **No governance**: In regulated environments, you cannot use tools that have no audit trail, no access controls, and no evidence of what they did.

VENZARI CODE addresses all six:

1. **Evidence requirements** prove the AI's output actually works
2. **Loop detection** breaks runaway sessions at 3 strikes
3. **Every tool call is logged** to an immutable evidence record
4. **Persistent memory** maintains context across sessions
5. **Per-mode tool guards** restrict what the AI can do at each stage
6. **Formal mode lifecycle** creates an auditable record of every action

### The Mode Lifecycle — 13 Operating Modes

```
Discover → Plan → Implement → Validate → Review → Repair → Commit
Advisor | Handoff | Audit | Benchmark | Migration | Release
```

Each mode has distinct capabilities and different risk tolerances. Treating them all the same is what causes problems.

**Discover Mode** — The AI scans the environment. Reads project structure, dependencies, existing tests, architectural decisions, previous session memory. Writes nothing. Executes nothing. Purely observational.

**Plan Mode** — The AI writes a plan — specific files to change, specific steps to take, specific tests to add. The plan is a document, not code. Can be reviewed and approved before execution begins.

**Implement Mode** — The AI executes the plan within the approved scope. Only tools allowed in Implement mode can be used (no git operations, no network requests outside the plan, no filesystem access outside the task scope).

**Validate Mode** — Tests must pass. The AI cannot move to Review until it produces evidence that the implementation works. Evidence = actual test output, not the AI's claim that tests pass.

**Review Mode** — Static analysis, code quality checks, security scanning. Read-only. The AI produces a review report. Humans can inspect before commit.

**Repair Mode** — Targeted fix-only mode. Task scope is locked to the specific failure identified in Validate or Review. Prevents scope creep during fixes.

**Commit Mode** — The only mode in which git operations are allowed. Writes a structured commit message with evidence references. One commit per completed task.

**Other Modes** — Advisor: High-level analysis only, no writes, no execution. Handoff: Produces a structured handoff document at session end. Audit: Reviews session evidence records, mode transitions, security events. Benchmark: Controlled test execution for performance regression tracking. Migration: Full write + execute access for large-scale codebase changes. Release: Full access including deploy operations — evidence-gated.

> **No more hallucination loops. No more unreviewed code. No more context loss between sessions.**

<details>
<summary>All 13 Modes at a Glance</summary>

| Mode | What It Does | What It Prevents |
|------|-------------|------------------|
| **Discover** | Scans environment, reads project structure | Jumping into implementation without understanding |
| **Plan** | Writes specific plan — files to change, steps to take | Unplanned implementation that doesn't match architecture |
| **Implement** | Executes approved plan within scope | AI doing unexpected things "while it's at it" |
| **Validate** | Tests must pass — produces actual test output, not AI's claim | Shipping broken code with AI's assurance |
| **Review** | Static analysis, code quality, security — read-only | Unreviewed AI code going directly to production |
| **Repair** | Targeted fix-only mode — scope locked to specific failure | Scope creep during fixes |
| **Commit** | Only mode allowing git operations — structured commit message with evidence references | Partial work, uncommitted changes, messy history |
| **Advisor** | High-level analysis only, no writes, no execution | — |
| **Handoff** | Produces structured handoff document at session end | — |
| **Audit** | Reviews session evidence records, mode transitions, security events | — |
| **Benchmark** | Controlled test execution for performance regression tracking | — |
| **Migration** | Full write + execute access for large-scale changes | — |
| **Release** | Full access including deploy operations — evidence-gated | — |

</details>

<details>
<summary>Evidence Schema — What Gets Logged</summary>

| Call Type | Input Recorded | Output Recorded | Timestamp | Immutable? |
|-----------|---------------|-----------------|-----------|------------|
| Tool call | Arguments given | Returned data | Yes | Yes — follows the commit |
| Mode transition | Previous mode | New mode | Yes | Yes — attached to commit |
| Loop attempt | Action attempted | Progress metric | Yes | Yes — 3-strike escalation |
| Evidence produced | Test command | Pass/fail output | Yes | Yes — never the AI's claim |

</details>

<blockquote>
<p style="color:#5EE7FF;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  ⚡ <strong>Current Status:</strong> Distribution [LIVE] — curl install | Version [LIVE] — 1.0.0 | Automated tests [LIVE] — 1,508 passing, 0 failing (74 test files)
</p>
</blockquote>

<blockquote>
<p style="color:#C1FF00;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  📦 <strong>Pre-install Checker:</strong> 6 checks: RAM/Disk/git/Runtime/ExistingInstall/Internet (CODE-A). Fail if RAM <8 GB, warn if <16 GB; fail if disk <60 GB free, warn if <40 GB.
</p>
</blockquote>

<blockquote>
<p style="color:#A259FF;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  🔄 <strong>Self-Update:</strong> `venzari-code upgrade` — R2/Keygen, atomic replace. Mode lifecycle [LIVE] — 13 modes enforced.
</p>
</blockquote>

**[vzari.co/code →](https://venzari.co/code)**

---

## ⚙️ VENZARI ENGINE — Private AI Infrastructure You Actually Own

> **A single CLI command installs a complete private AI system on your hardware.**

### What the Installed System Provides

| Feature | Status | Description |
|---------|--------|-------------|
| **Conversational AI with Persistent Memory** | 🟢 Live | Remembers everything — every conversation, decision, piece of company knowledge — indefinitely and privately. This is not a stateless chatbot. |
| **Local Voice Synthesis & Recognition** | 🟢 Offline | Text-to-speech and speech-to-text with no cloud latency and no third-party audio processing. The company's voice interactions never leave their server. |
| **Business Workflow Automation** | 🟢 Live | Pre-built and custom workflows for: scheduled reports, email drafting, CRM queries, database lookups, API integrations, calendar management. ENGINE is designed for business-layer actions only — HTTP, email, SQL, CRM, calendar. It does not edit code repositories. |
| **Web Dashboard** | 🟢 Live | Full web UI accessible at the company's domain (e.g., ai.acme.com) providing: AI chat interface, memory search, voice controls, workflow management, system monitoring, and user management. |
| **REST API** | 🟢 Live | Local REST API that connects ENGINE to any existing business system — ERP, CRM, ticketing systems, HR platforms. All locally. |
| **Semantic Memory Search** | 🟢 Live | Search everything the system has ever learned — conversations, documents, decisions — using natural language queries. "What did we discuss about the Acme contract in March?" returns the relevant context instantly. |
| **Custom Fine-Tuning Pipeline** | 🟢 Growth+ | Train a custom AI model on the company's own conversations and domain knowledge. The trained model runs locally — the company's data never leaves to a training provider. Export conversations, generate a training config, launch training on available GPU, import the resulting model back into the stack. |

### Why Ownership Matters (Structural Privacy)

> **"We don't just say your data is private. Your data physically cannot leave your hardware."**

With cloud AI, a vendor's privacy policy is a legal document that can change, expire, be superseded by acquisition, or be overridden by a legal request to the vendor. The data leaves your control the moment you send it.

With VENZARI ENGINE, data never leaves the customer's hardware by design. There is no architecture by which VENZARI can access it. The privacy guarantee is **structural, not contractual**.

This matters for:
- Companies with trade secret concerns
- Companies in regulated industries (healthcare, legal, finance)
- Companies in countries with data sovereignty requirements
- Companies whose clients contractually prohibit data sharing with third parties

### The Installer — Your Personal CTO

> **The most incredible thing is the way our VENZARI INSTALLER handles all the hard setup and config — like you have hired your own VENZARI CTO to get it done and working all on its own, stiff like that it should be written in the style of the ad creator \GARY BRIGGS.**

The VENZARI INSTALLER handles:

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

- Pre-install verification
- Binary download
- AI model pulls (fast + reasoning + embedding)
- the service orchestrator write and service startup
- Health checks for each service
- Gateway configuration (probes all configured AI providers)
- SSL and nginx configuration
- Ecosystem wiring (detects co-installed CODE/AI AGENT)
- MCP registration
- Anonymous install count ping

Each step has retry logic. The install is **resumable at any point** with `the resume-repair command` — it skips completed steps and retries from the failure point.

> **2,301 automated tests** cover every step, every retry, every ecosystem wiring.

> **You close your internet connection after installation and the system continues to function.** No per-token billing. No cloud dependency. Fixed monthly pricing.

</details>

<blockquote>
<p style="color:#5EE7FF;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  ⚡ <strong>Current Status:</strong> ALL 33 PHASES COMPLETE — v1.0.0 launched 2026-09-05
</p>
</p>
</p>
</blockquote>

<blockquote>
<p style="color:#C1FF00;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  💰 <strong>Pricing Tiers:</strong> Foundation $349/mo | Growth $899/mo | Enterprise $2,499/mo | Founder-Guided Setup $2,499 one-time
</p>
</p>
</blockquote>

<blockquote>
<p style="color:#A259FF;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  📦 <strong>Hardware Requirements:</strong> CPU 4 cores (16+ recommended) | RAM 8 GB warn / 16 GB comfortable | Storage 60 GB SSD (200+ GB NVMe recommended) | GPU NVIDIA ≥8 GB VRAM (CUDA optional) | OS Ubuntu 22.04 LTS
</p>
</p>
</blockquote>

<blockquote>
<p style="color:#FDFBF9;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  🛡️ <strong>Licensing:</strong> License key gates the real binary download. All valuable commands require a valid license. 24-hour offline grace period. No phone-home required after activation — the system works even if VENZARI ceases to exist.
</p>
</p>
</blockquote>

**[vzari.co/engine →](https://venzari.co/engine)**

---

## 🤖 VENZARI AI AGENT — One Agent, Every Channel, Forever

> **Persistent autonomous agent that learns from every interaction and works across 6 live messaging channels simultaneously — without any technical setup.**

### What It Does — Multi-Channel Presence

One VENZARI AI AGENT instance operates simultaneously across all connected channels. Start a conversation on Telegram, pick it up on Slack, continue via email. The agent maintains context across all channels — same identity, same memory, regardless of channel.

**Live channels (Phase 26):** Telegram · Slack · Discord · Email (Mailgun/Acelle) · Web chat widget · Webhook

### Persistent Memory — Three-Signal Retrieval

Three-signal memory retrieval (Phase 25+):

| Signal | Method | Speed | What It Finds |
|--------|--------|-------|---------------|
| **Vector embeddings** | Semantic search | 50ms | "What did we discuss about billing?" — semantic meaning |
| **BM25 full-text** | Exact phrase search | 10ms | Code snippets, exact phrases |
| **PageRank graph** | Most important/referenced memories | 5ms | Key facts, highly-referenced context |

### 2,212 Real Skills — Tier Breakdown

Skills are tiered by quality and tested (Phase 25):

| Tier | Count | Quality |
|------|-------|---------|
| **S-tier** | 11 | Highest quality, most reliable, flagship capabilities |
| **A-tier** | 522 | High quality, broad coverage |
| **B-tier** | 1,679 | Community catalog, broad reach |

Total: **2,212 real skills** invoked automatically based on what you ask. No explicit skill selection needed.

<details>
<summary>Skill Usage Examples</summary>


</details>

<details>
<summary>8-Provider Model Router</summary>

| Provider | Speed | Config | When Used |
|----------|-------|--------|-----------|
| **Local local inference** | Free, private, zero-config | Fast prompts ≤1,200 tokens | Primary path — always tried first |
| **Groq** | Fast inference | External provider, free API tier | Fallback when local fails or times out |
| **Gemini** | External provider | Free API tier available | Secondary cloud fallback |
| **OpenRouter** | Broad model access | Multiple model providers | When specific model needed |
| **Cerebras** | Ultra-fast inference | Specialized hardware | Speed-critical prompts |
| **Anthropic** | Claude models | External provider | Claude-specific requirements |
| **OpenAI** | GPT models | External provider | When GPT-4/Turbo needed |
| **Bedrock** | AWS enterprise | Enterprise pricing | Company already on AWS |

**Circuit breaker:** 3 failures → provider bypassed, auto-recovery after cooldown. **Budget monitor:** auto-downgrades model tier at 80% of session budget.

> **One agent. Every channel. Never forgets. Gets smarter every day.**

### Pricing Tiers

| Tier | Price | What You Get |
|------|-------|-------------|
| **Starter** | $29/mo | Full agent, all 2,212 skills, 5 channels, unlimited memory |
| **Professional** | $99/mo | Multi-agent support, all 6 channels, dashboard, team sharing |
| **Enterprise** | $499/mo | Managed fleet, custom skills, SLA, dedicated instance, API access |

> **Note:** There is no free tier. All tiers require an active paid subscription.

> **Who Uses It:** Individuals (Personal tier), Small teams (Professional tier), Enterprises (Enterprise tier), VENZARI ecosystem customers who want the AI AGENT as the natural language interface to their entire private AI stack.

**[vzari.co/products/venzari-ai-agent →](https://venzari.co/products/venzari-ai-agent)**

---

## 🚀 VENZARI TOGETHER — The Complete Stack, One Command

> **CODE + ENGINE + AI AGENT working as one system — one command, one license, one owner.**

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

> **No cloud calls for inference when Together is active.** CODE never touches `ai.venzari.xyz` when Together is active. CODE routes all AI inference through the local ENGINE stack — eliminating cloud AI dependency for development.

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

## 🏢 VENZARI ENTERPRISE — Custom Deployment, SLA, Dedicated Infrastructure

> **Custom deployment, SLA support, dedicated infrastructure, and direct access to the VENZARI team.**

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

> **Everyone else sells you a piece. VENZARI sells you the whole exit.**

<blockquote>
<p style="color:#FF38D4;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  💼 <strong>Contact for Enterprise:</strong> <a href="mailto:venzariai@gmail.com">venzariai@gmail.com</a>
</p>
</blockquote>

---

## 📊 The Four Products — Category Design Comparison

> **VENZARI doesn't compete in existing categories. We create new ones.**

<details>
<summary>vs. Cloud AI APIs (OpenAI, Anthropic, Google AI)</summary>

| Dimension | Cloud AI APIs | VENZARI ENGINE |
|-----------|--------------|----------------|
| Data location | Vendor's cloud | Your server |
| Pricing | Per-token | Flat monthly |
| Privacy guarantee | Policy | Architecture |
| Memory | Session-only | Permanent, private |
| Setup time | Minutes (API key) | 20 minutes (full stack) |

</details>

<details>
<summary>vs. AI Coding Assistants (GitHub Copilot, Cursor, Claude Code, Codeium)</summary>

| Dimension | AI Coding Assistants | VENZARI CODE |
|-----------|---------------------|--------------|
| Category | Tool | Operating System |
| Memory | Session-only | Permanent, project-scoped |
| Governance | None | 13-mode lifecycle + tool guards |
| Evidence | None | Required for every completion |
| Loop detection | None | 3-strike escalation |

</details>

<details>
<summary>vs. Cloud Chatbots (ChatGPT, Claude, Gemini)</summary>

| Dimension | Cloud Chatbots | VENZARI AI AGENT |
|-----------|---------------|------------------|
| Memory | Session-only | Permanent, cross-channel (3-signal) |
| Channels | 1 (their app) | 6 live simultaneously |
| Learning loop | None | Nightly skill creation |
| Skills | Implicit | 2,212 curated + auto-generated |
| CLI binary | ❌ | ✅ `venzari-agent` — 15+ commands |
| Desktop app | ❌ | ✅ Tauri v2, 5 tabs, system tray |
| MCP server | ❌ | ✅ 12 tools for any AI editor |
| Model router | ❌ | ✅ 8 providers, circuit breaker, budget monitor |
| Ecosystem | ❌ | ✅ Auto-wires to ENGINE + CODE |

</details>

<details>
<summary>vs. Enterprise AI Platforms (ServiceNow AI, Salesforce Einstein)</summary>

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

</details>

---

## 🎯 The Installer — Your Personal CTO (The Wow Factor)

> **The most incredible thing is the way our VENZARI INSTALLER handles all the hard setup and config — like you have hired your own VENZARI CTO to get it done and working all on its own, stiff like that it should be written in the style of the ad creator \GARY BRIGGS.**

<details>
<summary>VENZARI INSTALLER — Three Stages</summary>

**Stage 1 — Pre-install checks (automatic, before any wizard questions):** 11 parallel checks enforce RAM (≥8 GB warn, <8 GB fail), disk (≥60 GB warn, <60 GB fail), ports 4001/11434/5432/6379 free, the container runtime installed + running, internet connectivity to the VENZARI installer service, sudo access, existing install detection. Any failure stops the process and tells you exactly what to fix.

**Stage 2 — The setup wizard (7 questions):** Server identity (domain/IP, company name, admin email), license key validation, AI provider preference (local-only, local + cloud fallback with 13 supported providers, or cloud-only), hardware-adaptive model recommendations, optional add-ons (Growth+ only), and final confirmation.

**Stage 3 — Worker-driven install plan (17 steps executed locally):** After the wizard, the installer sends your hardware profile to the VENZARI Installer Worker at `the VENZARI installer service`. The Worker returns a 17-step plan customized for your hardware tier and license. Each step has retry logic. The install is **resumable at any point** with `the resume-repair command` — it skips completed steps and retries from the failure point.

> **2,301 automated tests** cover every step, every retry, every ecosystem wiring.

> **You close your internet connection after installation and the system continues to function.** No per-token billing. No cloud dependency. Fixed monthly pricing.

</summary>

</details>

<blockquote>
<p style="color:#5EE7FF;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  ⚡ <strong>Installer Status:</strong> Distribution [LIVE] — All 33 phases complete. v1.0.0 launched 2026-09-05
</p>
</blockquote>

<blockquote>
<p style="color:#C1FF00;font-weight:700;font-size:1.1rem;margin:1rem 0;">
  ⚙️ <strong>Installer Features:</strong> 11 pre-install checks | 7-question wizard | 17-step worker plan | Resumable repair mode | 2,301 automated tests
</p>
</blockquote>

---

## 🏆 Why VENZARI? The Complete Picture

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

<script>
  // Font preload for proper rendering
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

---

## 📦 Quick Start Reference


> 1,508 CODE tests · 2,301 ENGINE automated steps · 422 AI AGENT pass · 13 governance modes · 8 model providers · 6 live channels · 2,212 skills · 2,301 installer tests
