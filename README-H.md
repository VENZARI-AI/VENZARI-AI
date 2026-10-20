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
    Everyone else sells you a piece.<br/>
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
    <a href="https://venzari.co"><img src="https://img.shields.io/badge/venzari.co-3251fc?style=for-the-badge" alt="Website"/></a>
    <a href="https://docs.venzari.co"><img src="https://img.shields.io/badge/docs-5EE7FF?style=for-the-badge" alt="Docs"/></a>
    <a href="https://venzari.co/pricing"><img src="https://img.shields.io/badge/pricing-3251fc?style=for-the-badge" alt="Pricing"/></a>
    <a href="https://discord.gg/venzari"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/></a>
  </p>
</div>

---

> [!IMPORTANT]
> VENZARI creates three new product categories — not three better versions of existing tools. **Private AI Infrastructure** (ENGINE). **Engineering OS** (CODE). **Persistent Autonomous Agent** (AI AGENT). The comparison frame that matters is not "better vs worse" — it is "different kind of product."


<br/>

You have been renting your AI.

Every API call you make to a cloud AI service is a rental transaction. You send your data to someone else's server. You pay by the token — no ceiling, no ownership. The AI answers, then forgets you. Tomorrow you explain everything again.

And in your codebase, AI tools write code with no memory of last week's decisions, no governance layer between a developer's prompt and production, no record of what happened. You ship a commit and have no idea what the AI did to produce it.

VENZARI is built for the companies that have already noticed this, and the ones about to.

---

<br/>

## ⚙️ VENZARI CODE

> **The governance substrate on which AI-assisted development runs.**

[venzari.co/code](https://venzari.co/code) · `see docs.venzari.co`

AI coding tools are suggestion machines. They suggest well. But suggestion is not governance. There is no record of what they did. No enforcement of a workflow. No evidence that the code they produced was actually tested. You commit, and the history shows "AI-assisted" — and that's all it shows.

VENZARI CODE is different in kind, not degree. It is not a more powerful coding assistant. It is the **operating system** that sits above coding assistants and decides what they are permitted to do. Copilot is a tool. CODE is the OS that tools run under.

Thirteen operating modes enforce the phases that engineering actually has. **Discover** first — read everything, write nothing, understand the codebase before touching it. **Plan** next — write the approach as a document, review it before a single line changes. **Implement** within the approved scope only, not what the AI decides is adjacent. **Validate** with real test output — not the AI's word that tests pass. **Review** read-only before commit. **Repair** scoped to the specific failure. **Commit** as the only mode where git operations are allowed, with the evidence chain attached.

Six more modes for specialized work: Advisor (analysis only), Handoff (session summary), Audit (evidence review), Benchmark (performance regression), Migration (large-scale changes), Release (full access including deploy).

Between every request and every action sit five governance components. The **SSOT Loader** reads your project's rules before anything happens. The **Tool Guard** enforces per-mode allowlists at the system call level — not a prompt instruction, a structural constraint. The **Loop Detector** stops sessions that are stuck in a repair cycle at three identical attempts. The **Evidence Collector** logs every tool call — what was called, what went in, what came out, when — immutably, attached to every commit. The **Context Assembler** constructs a synthetic context window under 4,000 characters with the most relevant project knowledge for the current task.

Your project gets a `.venzari/` companion directory: 24 native skills, 216 vendor task templates, configured agents, task definitions with opening and closing gates, project-specific rules, and persistent memory that accumulates across sessions. Come back months later. CODE reads the companion and knows exactly where you left off.

When you correct the AI, that correction becomes a rule. Every correction makes CODE better at working on your specific project. The governance substrate improves over time.

**1,508 tests. 74 test files. 0 failing.** Multi-agent orchestration (SubagentPool, SwarmCoordinator, DAG branching). Goal mode: describe the objective, CODE runs it autonomously with budget caps and parallel limits. Desktop app, JetBrains plugin, 6 MCP tools, and a customer dashboard ship with every install.

---

## 🛡️ VENZARI ENGINE

> **The only AI system where data privacy is architecture, not policy.**

[venzari.co/engine](https://venzari.co/engine) · `see docs.venzari.co`

There are two kinds of privacy.

Policy privacy is a legal document. It says your data is protected. The vendor means it. They also cannot guarantee that their policy won't change, that an acquirer won't rewrite it, or that a legal request won't override it. The data is on their server — because that is how their product fundamentally works.

Structural privacy means your data physically cannot leave your hardware. Not because someone promised it won't. Because there is no architecture by which it could. You can disconnect the internet after installation and the system keeps running. The privacy guarantee is not a document — it is the design.

VENZARI ENGINE delivers a complete AI stack on a Linux VPS you own: **conversational AI that builds permanent memory** of your business across thousands of interactions; **local voice synthesis and recognition** that runs entirely offline; **business workflow automation** for reports, email, CRM, and calendar — all local API calls; a **full web dashboard** at your domain; a **REST API** that connects ENGINE to your existing business systems locally; **semantic memory search** that finds anything the system has ever learned from a natural language query; and a **custom fine-tuning pipeline** for Growth and Enterprise customers that trains models on your data, locally.

Seven features, all live, all on your hardware.

The installer is the product. Before a single wizard question, 11 parallel checks confirm your server is ready. Any failure stops with exact fix instructions. Seven questions configure what can't be auto-detected. Then `installer.venzari.xyz` returns a 17-step plan customized for your hardware — your CPU, your RAM, your GPU, your disk. Binary download (SHA256 verified). Model pulls. Docker-compose. Health checks. SSL. Ecosystem wiring. MCP registration.

2,301 automated tests. Resumable at any point: `venzari-engine install --repair`. Offline after install.

The company that needs private AI is not the five-person startup and not the Fortune 500 with a dedicated AI team. It is the 200-person company that has real business problems AI could solve, sensitive data that cannot leave the building, and no 3-to-6-month engineering project available to build this themselves. For that company, VENZARI ENGINE is the only option that doesn't require a compromise.

**33 phases complete. v1.0.0 launched September 5, 2026. Every feature live.**

---

## 🤖 VENZARI AI AGENT

> **The first agent that earns loyalty through memory.**

[venzari.co/products/venzari-ai-agent](https://venzari.co/products/venzari-ai-agent) · `see docs.venzari.co`

The fundamental problem with AI assistants is not intelligence. It is memory. Every time you open a new conversation, the AI is meeting you for the first time. You spend twenty minutes re-establishing context — your project, your preferences, your decisions. The AI is capable. It knows nothing about you. You do the same twenty minutes tomorrow.

VENZARI AI AGENT is an always-on autonomous entity — not a conversation interface. It operates simultaneously across six channels: Telegram, Slack, Discord, email, web chat, and webhook. Start a conversation on Telegram in the morning. Continue on Slack at lunch. The agent carries the full context. It never asks you to re-explain.

It remembers through three parallel retrieval signals: vector embeddings (semantic search in 50ms — finds relevant content even when you don't use the exact words), BM25 full-text (exact phrase matching in 10ms — code snippets, names, precise terms), and PageRank graph (importance-weighted retrieval in 5ms — most-referenced facts surface first). Three signals because different questions require different retrieval strategies, and because nothing should fall through the cracks.

2,212 skills across three quality tiers: 11 S-tier flagship capabilities at the highest reliability, 522 A-tier high-quality skills forming the day-to-day backbone, and 1,679 B-tier community catalog skills growing continuously. Invoked automatically from context. You describe what you need; the agent finds the skill.

Every night at 3am, the agent runs a learning loop: identifying repeated patterns and creating new skills for them, rating existing skills by performance signals and improving underperformers, updating its model of who you are and what you care about, and compressing old interactions to retain key facts while removing noise. You go to sleep with an agent. You wake up with a smarter one. This compounds.

The model router connects to eight providers — local Ollama for privacy and zero cost as the default, Groq and Gemini for speed and free tiers, OpenRouter for broad model access, Cerebras for ultra-fast inference, Anthropic, OpenAI, and Bedrock for enterprise models. Circuit breaker bypasses failed providers automatically. Budget monitor downgrades model tier at 80% of session budget. If VENZARI ENGINE is installed, all calls route through ENGINE's local LiteLLM at :4001 — zero configuration.

A CLI binary with 15+ commands. A native Tauri v2 desktop app with five tabs and system tray. A nine-page web dashboard including an AI Router page unique in the market — showing current provider, model tier, today's cost, and ENGINE probe status. Twelve MCP tools for any AI editor.

**Starting at $29/month. 422 tests passing. 0 failing. 2,212 skills. 2,301 installer tests backing the stack.**

---

## 🔗 VENZARI Together

> **One command. Both products. Fully wired. Zero cloud inference.**

[venzari.co/together](https://venzari.co/together) · `see docs.venzari.co`

CODE and ENGINE on the same machine. One installer. Both products. CODE routes all AI inference through ENGINE's local LiteLLM gateway at :4001. No cloud calls for development. Offline after install.

```
venzari-code CLI → LiteLLM :4001 → Ollama :11434 → your local models
                        ↑ ENGINE
venzari-together doctor   # health check
venzari-together status   # combined view
```

The 22-step hardware-aware install plan detects your machine before selecting models. 8 GB RAM minimum, 16 GB recommended. 20 GB disk. GPU optional.

---

## Before and After

| | Before VENZARI | After VENZARI |
|---|---|---|
| Your data | On a vendor's server | On your server — structurally inaccessible |
| Your cost | Per token, no ceiling | Flat monthly, no surprise |
| Your memory | Resets with every session | Permanent, cumulative, cross-channel |
| Your development | AI with no governance, no record | 13 modes, evidence per action, audit trail per commit |
| Your agent | Starts fresh every conversation | Knows you better every day |
| Your setup | API key or 3–6 months | 20 minutes |
| Your ownership | Nothing | The binary, the data, the future |

---

## Start


[venzari.co](https://venzari.co) · [Pricing](https://venzari.co/pricing) · [Docs](https://docs.venzari.co) · [Enterprise](https://venzari.co/enterprise) · [Solutions](https://venzari.co/solutions) · [Jobs](https://venzari.co/jobs) · [Contact](https://venzari.co/contact) · [Discord](https://discord.gg/venzari)

---

---

<p align="center">
<strong>VENZARI</strong> &nbsp;·&nbsp; <a href="https://venzari.co">venzari.co</a> &nbsp;·&nbsp; <a href="https://discord.gg/venzari">Discord</a> &nbsp;·&nbsp; <a href="https://venzari.co/jobs">Jobs</a><br/>
<em>Your AI. Your Hardware. Your Future. &nbsp;·&nbsp; © 2026 VENZARI</em>
</p>
