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
  <p style="font-family:'Poppins',sans-serif;font-size:1.5rem;color:#FDFBF9;line-height:1.6;max-width:640px;margin:0 auto 2rem;font-weight:700;">
    Stop renting. Start owning.
  </p>

  <p>
    <a href="https://venzari.co"><img src="https://img.shields.io/badge/venzari.co-Visit-3251FC?style=for-the-badge" alt="Website"/></a>
    <a href="https://docs.venzari.co"><img src="https://img.shields.io/badge/docs.venzari.co-Read-A259FF?style=for-the-badge" alt="Docs"/></a>
    <a href="https://venzari.co/pricing"><img src="https://img.shields.io/badge/Pricing-From%20$29-C1FF00?style=for-the-badge&logoColor=000" alt="Pricing"/></a>
    <a href="https://discord.gg/venzari"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/></a>
  </p>

  <p>
    <a href="https://venzari.co/code"><img src="https://img.shields.io/badge/CODE-Engineering%20OS-A259FF?style=for-the-badge" alt="CODE"/></a>
    <a href="https://venzari.co/engine"><img src="https://img.shields.io/badge/ENGINE-Private%20AI%20Infrastructure-C1FF00?style=for-the-badge&logoColor=000" alt="ENGINE"/></a>
    <a href="https://venzari.co/products/venzari-ai-agent"><img src="https://img.shields.io/badge/AI%20AGENT-Persistent%20Autonomous-3251FC?style=for-the-badge" alt="AI AGENT"/></a>
  </p>
</div>

---

> [!IMPORTANT]
> VENZARI creates three new product categories — not three better versions of existing tools. **Private AI Infrastructure** (ENGINE). **Engineering OS** (CODE). **Persistent Autonomous Agent** (AI AGENT). The comparison frame that matters is not "better vs worse" — it is "different kind of product."

---

<br/>

You have been renting your AI.

Every query to a cloud API. Every token generated on someone else's GPU. Every conversation with a chatbot that forgets you the moment you close the tab. Every commit with an "AI-assisted" label and no record of what the AI actually did. Every month, the invoice goes up. Every quarter, the vendor's privacy policy gets another update. And at the end of it all, you own nothing.

You have been renting your engineering intelligence.

AI coding assistants that suggest code with no governance. No memory between sessions. No enforcement of workflow. No evidence that the code was validated before it shipped. Powerful tools. Completely ungoverned. In production engineering environments where every commit matters, where every bug costs money, where every security vulnerability is a liability.

You have been renting your autonomous agent.

Chatbots that answer one question and forget you were there. Stateless. Session-bound. One channel. No memory that builds. No skills that compound. No agent that knows you better on day 100 than it did on day 1. Just an API you pay for monthly that starts over every time you open it.

**VENZARI sells you the exit.**

Three products. Three new categories. One ecosystem that runs on your hardware, under your rules, at a flat monthly cost, with permanent memory, governed AI development, and a 20-minute installer backed by 2,301 automated tests.

<br/>

---

## The Three Products

### ⚙️ VENZARI CODE — Engineering OS

*[venzari.co/code](https://venzari.co/code)* · **The governance layer above AI — not a better coding assistant.**

> [!NOTE]
> **CODE and Copilot are not competitors. They coexist.** Copilot is a suggestion tool. CODE is the operating system that governs when suggestions are allowed to touch your codebase. Copilot generates. CODE enforces what happens next.

<br/>

AI coding assistants are suggestion machines. No memory. No governance. No evidence trail. You get a commit — the history says "AI-assisted" and that's all it says.

VENZARI CODE is the **operating system** above AI models. It doesn't replace your coding assistant. It tells AI what it is permitted to do, in which phase, with what evidence required to complete.

**13 operating modes.** Discover. Plan. Implement. Validate. Review. Repair. Commit. Advisor. Handoff. Audit. Benchmark. Migration. Release. Each with different tool permissions. Each with different evidence requirements. Every action logged, timestamped, immutable.

**The companion system.** `.venzari/` in your project — agents, skills, task definitions with gates, project rules, permanent memory. Return months later and CODE knows exactly where it left off. When you correct the AI, that correction becomes a rule. The system gets better at your specific project over time. It learns your patterns. It enforces your standards.

**Five governance components:**

- **SSOT Loader** — project rules loaded before every action
- **Tool Guard** — per-mode allowlists at the system call level, structural constraints not prompt instructions
- **Loop Detector** — 3 identical attempts without progress → stop, escalate
- **Evidence Collector** — every tool call logged: input, output, timestamp. Immutable. Follows every commit.
- **Context Assembler** — synthetic context under 4,000 chars, most relevant knowledge, no overflow

<details>
<summary><strong>How the modes work in practice</strong></summary>

<br/>

**Discover** before planning — AI reads everything, writes nothing, understands before changing. The Discover report documents what exists, what the constraints are, what the AI learned. No code changes permitted.

**Plan** before implementing — AI writes a document that can be reviewed before a line of code changes. The plan is structured: objective, approach, files affected, tests required, rollback strategy. A human reviews and approves the plan. Only then does Implement mode unlock.

**Implement** within scope only — AI writes code, but only within the scope defined in the approved plan. Structural constraints, not prompt instructions. The Tool Guard enforces allowlists at the system call level. AI cannot call `rm`, cannot access files outside scope, cannot modify `.git/` directly.

**Validate** with real evidence — AI runs tests and produces **actual test output**, not claims. "The tests pass" is not evidence. The test runner's stdout showing GREEN is evidence. The Evidence Collector logs the full output. It follows the commit.

**Review** before committing — AI enters read-only mode, performs static analysis, runs security scanners, produces a review report. The review includes: code quality signals, security findings, test coverage delta, complexity metrics. A human reviews the report.

**Commit** with evidence — the only mode where git operations are allowed. AI stages specific files, writes a structured commit message, attaches the full evidence chain (Discover report, Plan document, Validate output, Review report). The commit is traceable. Six months later, you know exactly what the AI did and why.

The loop detector monitors for repeated failures. Three identical attempts without progress → CODE stops, escalates to human review, logs the loop. No infinite burn.

</details>

**1,508 tests passing. 0 failing. 74 test files.** Multi-agent orchestration (SubagentPool, SwarmCoordinator, DAG branching). Goal mode: describe the objective, CODE runs it autonomously with budget caps and parallel limits. Desktop app, JetBrains plugin, 6 MCP tools, and a customer dashboard ship with every install.

<br/>

---

### 🛡️ VENZARI ENGINE — Private AI Infrastructure

*[venzari.co/engine](https://venzari.co/engine)* · **Structural privacy. Not policy privacy.**

> [!IMPORTANT]
> **Structural privacy means your data physically cannot leave your hardware.** Not because someone promised it won't. Because there is no architecture by which it could. You can disconnect the internet after installation and the system keeps running. The privacy guarantee is not a document — it is the design.

<br/>

A complete AI system — conversational AI, voice, automation, dashboard, API, semantic search, custom training — running on a VPS you own. Fixed monthly cost. No per-token billing. No cloud dependency. No vendor access. Offline-capable after installation.

This is not "self-hosted ChatGPT." This is the full stack: inference, memory, voice, workflows, monitoring, API. Seven features. All live. All on your hardware.

**7 features, all on your hardware:**

1. **Conversational AI + permanent memory** — builds cumulative understanding of your business. Every conversation, permanently. Returns to context from months ago. Semantic search: *"What did we discuss about the Acme contract?"* → instant, sourced answer.

2. **Local voice (TTS + STT)** — offline synthesis and recognition. Voice data never leaves your server. No cloud audio processing. Piper (TTS) and Whisper (STT) models run locally.

3. **Workflow automation** — reports, email, CRM updates, calendar, ticketing. All local. No external API calls required. Scheduled tasks, triggered workflows, manual invocation.

4. **Web dashboard** — full UI served at your domain. Chat interface. Memory search. Voice playground. Workflow designer. System monitoring. Model router status.

5. **REST API** — connect your ERP, CRM, HR systems, ticketing platforms — all locally. No data leaves your network. OpenAPI spec included. Swagger UI at `/api/docs`.

6. **Semantic memory search** — natural language queries over your entire memory store. Vector embeddings + BM25 full-text + PageRank importance ranking. Three-signal retrieval, sub-second response.

7. **Custom fine-tuning** *(Growth+ plans)* — train models on your proprietary data. Run them locally. Never send training data to a vendor. LoRA adapters for Llama, Mistral, Qwen families.

**The installer is the product.** Before a single wizard question, 11 parallel checks confirm your server is ready. Any failure stops with exact fix instructions. Seven questions configure what can't be auto-detected. Then the VENZARI installer returns a 17-step plan customized for your hardware — your CPU, your RAM, your GPU, your disk. Verified binary download. Model pulls. Health checks. SSL. Ecosystem wiring. MCP registration.

<details>
<summary><strong>The 3-stage installer — why it matters</strong></summary>

<br/>

**Stage 1 — 11 pre-install checks** run in parallel before any wizard question. RAM (fail <8GB), Disk (fail <60GB), CPU (warn <4 cores), OS (Ubuntu 22.04/24.04 only), container runtime (installed + running), ports (80, 443, 3000, 5432, 6379 available), internet (required for install), sudo access, existing install detection, GPU detection (optional), Python 3.10+.

Any failure stops with exact fix instructions. No partial states. No mystery errors halfway through.

**Stage 2 — 7-question wizard** configures what can't be auto-detected: server identity (domain or IP), license key (validates tier + seats), AI provider preference (local-only | local+cloud | cloud-only), model selection (hardware-adaptive recommendations), SSL mode (auto Let's Encrypt | manual cert | HTTP only), telemetry (anonymous install success ping yes/no), optional add-ons (voice, custom training, workflow automation).

Everything else is auto-detected.

**Stage 3 — 17-step hardware-customized plan** from the VENZARI installer service. Your hardware profile + license sent to the installer service. Returns 17-step plan customized for your CPU, RAM, GPU, disk, license tier. Binary (verified download) → models → service startup → health checks → SSL → ecosystem wiring → MCP registration → tier features.

**Resumable:** Step 9 fails? Run the resume-repair command. It skips steps 1–8 (complete) and retries from 9.

**2,301 automated tests** cover every step, every retry, every hardware config from 8GB RAM / 2-core to 256GB RAM / 64-core + A100.

</details>

**Hardware requirements:** 8 GB RAM minimum (16–32 GB recommended), 60 GB SSD (200 GB NVMe recommended), 4 cores (16+ recommended), GPU optional (NVIDIA ≥8 GB VRAM for 5–15× faster inference), Ubuntu 22.04 LTS.

> **You close your internet connection after installation and the system continues to function.** No per-token billing. No cloud dependency. Fixed monthly pricing.

**Pricing:** Foundation $349/mo | Growth $899/mo | Enterprise $2,499/mo

**v1.0.0 · All 33 phases complete · Launched 2026-09-05**

<br/>

---

### 🤖 VENZARI AI AGENT — Persistent Autonomous Agent

*[venzari.co/products/venzari-ai-agent](https://venzari.co/products/venzari-ai-agent)* · **Starting at $29/month**

<br/>

Chatbots are stateless. They answer questions and forget you. VENZARI AI AGENT is an always-on autonomous entity — not a conversation interface. It operates across every channel you use simultaneously, remembers every interaction permanently, and becomes more capable every night.

This is not "better ChatGPT." This is a different product category: **Persistent Autonomous Agent**.

**6 channels, one memory.** Telegram. Slack. Discord. Email. Web chat. Webhook. Start on Telegram. Continue on Slack. Finish via email. Same agent. Same memory. Zero re-explaining.

**3-signal memory.** Vector embeddings (50ms — semantic, relevant content without exact words). BM25 full-text (10ms — exact, code snippets, names, precise phrases). PageRank graph (5ms — important, most-referenced facts surface first). Nothing falls through.

**2,212 skills.** 11 S-tier (flagship, highest reliability). 522 A-tier (day-to-day backbone). 1,679 B-tier (community catalog, growing). No manual selection. You describe what you need. The agent finds the skill.

**The nightly learning loop.** Every night at 3am: repeated patterns become new skills. Underperforming skills are improved. The context model is updated. Old interactions are compressed. You go to sleep with an agent. You wake up with a better one.

<details>
<summary><strong>How the nightly loop works</strong></summary>

<br/>

**Monday:** You ask *"Pull the latest sales numbers from the CRM, calculate growth vs last month, format as a table, email to the leadership team."*

The agent does it using 4 existing skills: `crm_query`, `calculate_growth`, `format_table`, `send_email`.

**Tuesday, Wednesday, Thursday:** You ask the same thing, slightly differently worded each time.

**Friday morning:** The nightly loop has detected the pattern. It creates a new skill: `weekly_sales_report`. One command. Four steps automated.

**Friday afternoon:** You say *"Send the weekly sales report."* The agent uses the new skill. One invocation. Done.

**You didn't train it. You didn't configure a workflow. You just kept asking. The agent learned.**

</details>

**8-provider model router.** Local → Groq → Gemini → OpenRouter → Cerebras → Anthropic → OpenAI → Bedrock. Circuit breaker (3 failures → bypass + auto-recovery). Budget monitor (downgrade at 80%). ENGINE installed? All calls route through the local AI gateway with zero configuration.

**Everything included:** `venzari-agent` CLI with 15+ commands. Native desktop app (Tauri v2, 5 tabs, system tray). 9-page dashboard including the AI Router page. 12 MCP tools for Claude Code, Cursor, Kiro, Windsurf, VS Code, Gemini CLI. 422 tests passing, 0 failing. Auto-wires to ENGINE and CODE.

**Pricing:** Starter $29/mo (1 channel, 1K skills) | Pro $99/mo (6 channels, 2.2K skills, priority support) | Team $299/mo (unlimited channels, custom skills, dedicated infrastructure)

<br/>

---

## 🔗 VENZARI Together + Enterprise

**Together** — [venzari.co/together](https://venzari.co/together)

CODE + ENGINE on one machine, fully wired. CODE routes all AI inference through ENGINE's local AI gateway. No cloud calls for development. Offline after install. 8 GB RAM minimum, 16 GB recommended. 20 GB disk. Ubuntu 20.04+.

**Enterprise** — [venzari.co/enterprise](https://venzari.co/enterprise)

White-label deployment of the complete VENZARI ecosystem under your brand. Custom skill development. Managed fleet. Dedicated infrastructure. Direct team access. Full SLA.

**[→ venzari.co/contact](https://venzari.co/contact)** — Schedule a call

<br/>

---

## The Numbers

| Product | Tests | What It Replaces |
|---------|-------|------------------|
| **VENZARI CODE** | 1,508 passing, 0 failing | Ungoverned AI coding tools |
| **VENZARI ENGINE** | 2,301 installer tests | Cloud AI APIs + DIY stacks + enterprise platforms |
| **VENZARI AI AGENT** | 422 passing, 0 failing | Stateless chatbots |
| **Together** | Full stack on one machine | Multi-vendor AI development setup |

---

## Their Way vs VENZARI

| | Before VENZARI | After VENZARI |
|---|---|---|
| **Your data** | Vendor's servers — policy-protected | Your server — architecture-protected |
| **Your cost** | Per-token, no ceiling | Flat monthly, no surprise |
| **Your memory** | Session-only, starts over tomorrow | Permanent, cumulative, cross-channel |
| **Your dev AI** | Suggestions, no governance, no record | 13 modes, evidence per action, audit trail |
| **Your agent** | Forgets you every session | Knows you better every day |
| **Your setup** | API key in minutes or 3–6 months | 20 minutes |
| **What you own** | Nothing | The binary, the data, the future |

---

## Get Started

**→ [venzari.co/pricing](https://venzari.co/pricing)** — All products, all tiers

**→ [docs.venzari.co](https://docs.venzari.co)** — Full documentation

**→ [venzari.co/enterprise](https://venzari.co/enterprise)** — White-label and dedicated

**→ [venzari.co/contact](https://venzari.co/contact)** — Talk to the team

**→ [discord.gg/venzari](https://discord.gg/venzari)** — Join the community

**→ [venzari.co/jobs](https://venzari.co/jobs)** — We're hiring. Build the future of AI infrastructure with us.

---

<p align="center">
<strong>VENZARI</strong> &nbsp;·&nbsp; <a href="https://venzari.co">venzari.co</a> &nbsp;·&nbsp; <a href="https://docs.venzari.co">Docs</a> &nbsp;·&nbsp; <a href="https://venzari.co/pricing">Pricing</a> &nbsp;·&nbsp; <a href="https://discord.gg/venzari">Discord</a> &nbsp;·&nbsp; <a href="https://venzari.co/jobs">Jobs</a><br/>
<em>Your AI. Your Hardware. Your Future. &nbsp;·&nbsp; © 2026 VENZARI</em>
</p>
