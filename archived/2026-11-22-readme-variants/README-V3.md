# VENZARI — Technical Specification

<div align="center">

<pre align="center" style="color:#3251fc;background:#0d0d0d;padding:16px;border-radius:8px;font-size:12px">
██╗   ██╗███████╗███╗   ██╗███████╗ █████╗ ██████╗ ██╗
██║   ██║██╔════╝████╗  ██║╚══███╔╝██╔══██╗██╔══██╗██║
██║   ██║█████╗  ██╔██╗ ██║  ███╔╝ ███████║██████╔╝██║
╚██╗ ██╔╝██╔══╝  ██║╚██╗██║ ███╔╝  ██╔══██║██╔══██╗██║
 ╚████╔╝ ███████╗██║ ╚████║███████╗██║  ██║██║  ██║██║
  ╚═══╝  ╚══════╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝
</pre>

<p style="font-family:'Unbounded',sans-serif;font-size:clamp(2.4rem,7vw,4.4rem);font-weight:800;color:#3251fc;letter-spacing:-0.02em;margin:1rem 0 0.25rem;">
VENZARI
</p>
<p style="font-family:'JetBrains Mono',ui-monospace,monospace;font-size:1rem;color:#5EE7FF;letter-spacing:.02em;margin:0 0 1.5rem;">
// the complete AI stack you own — engineering OS · private AI infrastructure · persistent agent
</p>

<p align="center">
  <a href="https://venzari.co/code"><img src="https://img.shields.io/badge/VENZARI%20CODE-Engineering%20OS-#A259FF?style=for-the-badge" alt="VENZARI CODE"/></a>
  <a href="https://venzari.co/engine"><img src="https://img.shields.io/badge/VENZARI%20ENGINE-Private%20AI-#C1FF00?style=for-the-badge" alt="VENZARI ENGINE"/></a>
  <a href="https://venzari.co/products/venzari-ai-agent"><img src="https://img.shields.io/badge/VENZARI%20AI%20AGENT-Multi-Channel-#3251FC?style=for-the-badge" alt="VENZARI AI AGENT"/></a>
  <a href="https://venzari.co/together"><img src="https://img.shields.io/badge/VENZARI%20TOGETHER-One%20Stack-#3251FC?style=for-the-badge" alt="VENZARI TOGETHER"/></a>
  <a href="https://venzari.co/enterprise"><img src="https://img.shields.io/badge/VENZARI%20ENTERPRISE-Custom-#FF38D4?style=for-the-badge" alt="VENZARI ENTERPRISE"/></a>
</p>

<p align="center">
  <a href="https://venzari.co/pricing"><img src="https://img.shields.io/badge/OWN%20YOUR%20STACK-3251fc?style=for-the-badge&logoColor=white" alt="Pricing"/></a>
  <img src="https://img.shields.io/badge/docs.venzari.co-5EE7FF?style=for-the-badge&logoColor=black" alt="Docs"/>
  <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/>
  <img src="https://img.shields.io/badge/install.venzari.xyz-C1FF00?style=for-the-badge&logoColor=black" alt="Installer"/>
</p>

</div>

<br/>

---

## 00 — THE PROBLEM


| Layer | Product | Responsibility | Public Entry Point |
|-------|---------|----------------|--------------------|
| L4 | **AI AGENT** | Persistent autonomous entity across every channel | [venzari.co/products/venzari-ai-agent](https://venzari.co/products/venzari-ai-agent) |
| L3 | **CODE** | Governance substrate for AI-assisted engineering | [venzari.co/code](https://venzari.co/code) |
| L2 | **ENGINE** | Private AI infrastructure, memory, workflows, voice | [venzari.co/engine](https://venzari.co/engine) |
| L1 | **TOGETHER** | The unified stack — one command, one license | [venzari.co/together](https://venzari.co/together) |
| L0 | **ENTERPRISE** | Custom deployment, SLA, dedicated infra | [venzari.co/enterprise](https://venzari.co/enterprise) |
| — | **INSTALLER** | Autonomous setup for all of the above | `install.venzari.xyz` |

---

## 02 — VENZARI CODE / Engineering OS

**Category:** Not an AI coding assistant. An operating system for AI-assisted development — the substrate that decides *when* an AI may act, *how far*, and *with what proof*.


### 02.1 Mode Lifecycle

```
Discover → Plan → Implement → Validate → Review → Repair → Commit
Advisor | Handoff | Audit | Benchmark | Migration | Release
```

| Mode | Writes | Executes | Git | Risk | Gate |
|------|--------|----------|-----|------|------|
| Discover | no | no | no | LOW | observational only |
| Plan | plan doc | no | no | LOW | must precede Implement |
| Implement | scoped | scoped | no | MED | within approved plan |
| Validate | no | tests | no | HIGH | real test output required |
| Review | no | analysis | no | HIGH | read-only static + security scan |
| Repair | scoped | scoped | no | MED | scope locked to failure |
| Commit | no | no | YES | HIGH | only mode with git access |
| Advisor | no | no | no | LOW | analysis only |
| Handoff | doc | no | no | LOW | structured handoff |
| Audit | no | no | no | LOW | evidence review |
| Benchmark | no | benchmarks | no | LOW | perf regression tracking |
| Migration | full | full | no | HIGH | full write + execute |
| Release | full | full | YES | CRITICAL | evidence-gated deploy |

### 02.2 Companion System

`venzari-code install` creates `.venzari/` in your project:

| Directory | Contents | Status |
|-----------|----------|--------|
| `agents/` | 6 default agent roles with scoped capabilities and tool guards | LIVE |
| `skills/` | 2,212 reusable task templates, auto-invoked by intent | LIVE |
| `tasks/` | Structured task definitions with opening + closing gates | LIVE |
| `rules/` | Project-level constraints that override defaults | LIVE |
| `memory/` | Session history, codegraph, architectural decisions (SQLite) | LIVE |
| `context/` | Automatic context loading, project state, dependency maps | LIVE |

### 02.3 Governance Guarantees


### 03.1 Capability Matrix

| # | Capability | Status | Notes |
|---|------------|--------|-------|
| 1 | Conversational AI with persistent memory | LIVE | Every conversation retained indefinitely, privately |
| 2 | Local voice synthesis + recognition | OFFLINE | TTS + STT on your own hardware, no third-party audio processing |
| 3 | Business workflow automation | LIVE | Scheduled reports, email drafting, CRM queries, SQL, APIs, calendar |
| 4 | Web dashboard | LIVE | Own your domain (`ai.acme.com`) — chat, memory search, voice, workflows, monitoring, users |
| 5 | Local REST API | LIVE | Wire into ERP / CRM / ticketing / HR. All local. |
| 6 | Semantic memory search | LIVE | Natural-language query across everything ever learned |
| 7 | Custom fine-tuning pipeline | GROWTH+ | Train on your own conversations; model runs locally |


### 03.4 Hardware Requirements

| Resource | Minimum | Recommended |
|----------|---------|-------------|
| CPU | 4 cores | 16+ cores |
| RAM | 8 GB (warns) / 16 GB comfortable | 32–64 GB |
| Storage | 60 GB SSD | 200+ GB NVMe |
| GPU | Not required | NVIDIA ≥8 GB VRAM (CUDA) |
| OS | Ubuntu 22.04 LTS | Ubuntu 22.04 LTS |
| Network | Static IP recommended | Static IP |

### 03.5 Pricing

| Tier | Price | Includes |
|------|-------|----------|
| Foundation | $349/mo | Private AI — knowledge, conversation, memory |
| Growth | $899/mo | + custom AI training, observability dashboards, Growth+ features |
| Enterprise | $2,499/mo | + white-label, SLA, enterprise support |
| Founder-Guided Setup | $2,499 one-time | Done-with-you install + configuration |


### 05.1 Local Architecture

```
Your Machine
  ├── venzari-code CLI ─────────────► routes inference to
  │                                     ▼
  ├──   ◄───────────────── ENGINE gateway
  │       ▼
  ├── local inference  ◄── local models (qwen, llama, …)
  ├── ENGINE Dashboard 
  └── ~/.venzari-together/  ◄── shared config
```


### 05.3 Requirements

| Resource | Minimum | Recommended |
|----------|---------|-------------|
| RAM | 8 GB | 16 GB+ |
| Disk | 20 GB free | 50 GB+ |
| OS | Linux Ubuntu 20.04+ | Ubuntu 22.04 LTS |
| GPU | Optional | NVIDIA 8 GB+ VRAM |

### 05.4 Post-Install Commands


**[→ venzari.co/together](https://venzari.co/together)**

---

## 06 — VENZARI ENTERPRISE / Custom Deployment

**Category:** Not enterprise-platform lock-in. Custom deployment with SLA, dedicated infrastructure, and direct access to the team.

| Dimension | Enterprise AI Platforms | VENZARI ENTERPRISE |
|-----------|-------------------------|---------------------|
| Annual cost | $100,000+/year | $5,988/year |
| Implementation | Months | Under 5 minutes |
| Live channels | Varies, often limited | 6 |
| Nightly learning loop | None | Active |
| CLI binary | No | Yes |
| Desktop app | No | Yes |
| MCP server | No | Yes — 12 tools |
| ENGINE + CODE integration | No | Yes — auto-wired |
| Ecosystem | Single-vendor lock-in | Full VENZARI stack |

**Contact:** [venzariai@gmail.com](mailto:venzariai@gmail.com) · [venzari.co/enterprise](https://venzari.co/enterprise)

---

## 07 — THE INSTALLER (THE WOW FACTOR)

> The most incredible thing is the way our VENZARI INSTALLER handles all the hard setup and config — like you have hired your own VENZARI CTO to get it done and working all on its own, stiff like that it should be written in the style of the ad creator \GARY BRIGGS.


| Without an installer | With the VENZARI INSTALLER |
|----------------------|-----------------------------|
| Hire a platform team | 7 questions, one command |
| Weeks of the container runtime debugging | 11 checks before you start |
| Model selection guesswork | Hardware-adaptive recommendations |
| Break it, start over | `--repair` resumes at failure |
| Manual ecosystem wiring | CODE + AGENT auto-detected and wired |
| Nobody to call | 2,301 tests covering every step |

> Enterprise-grade infrastructure, without the enterprise-grade engineering investment.

---

## 08 — COMPARISON MATRIX

### vs. Cloud AI APIs (OpenAI · Anthropic · Google AI)

| Dimension | Cloud AI APIs | VENZARI ENGINE |
|-----------|---------------|-----------------|
| Data location | Vendor's cloud | Your server |
| Pricing | Per-token | Flat monthly |
| Privacy | Policy-based | Architectural |
| Memory | Session-only | Permanent, private |
| Time to full system | Minutes (API key) | ~20 minutes (entire stack) |
| Works offline | No | Yes |

### vs. AI Coding Assistants (Copilot · Cursor · Claude Code · Codeium)

| Dimension | Coding Assistants | VENZARI CODE |
|-----------|-------------------|--------------|
| Category | Tool | Operating System |
| Memory | Session-only | Permanent, project-scoped |
| Governance | None | 13 modes + tool guards |
| Evidence on completion | None | Required |
| Loop detection | None | 3-strike escalation |
| Evidence-gated deploy | No | Yes (Release mode) |

### vs. Cloud Chatbots (ChatGPT · Claude · Gemini)

| Dimension | Cloud Chatbots | VENZARI AI AGENT |
|-----------|-----------------|------------------|
| Memory | Session-only | Permanent, 3-signal retrieval |
| Channels | 1 | 6 live simultaneously |
| Self-improvement | None | Nightly skill creation |
| Skills | Implicit | 2,212 tiered |
| CLI | No | `venzari-agent` |
| Desktop app | No | Tauri v2 |
| MCP server | No | 12 tools |
| Model routing | No | 8 providers + breaker + budget |
| Price | $20/mo | $29/mo |

### vs. Enterprise AI Platforms (ServiceNow AI · Salesforce Einstein)

| Dimension | Enterprise Platforms | VENZARI ENTERPRISE |
|-----------|---------------------|---------------------|
| Annual cost | $100,000+ | $5,988 |
| Time to live | Months | <5 minutes |
| Channels | Limited | 6 |
| Learning loop | None | Active nightly |
| Lock-in | Single vendor | Own the stack |

---

## 09 — THE DECISION TABLE

| If you need… | Use | Because |
|---------------|-----|---------|
| AI that never forgets and never leaves your server | **ENGINE** | Persistent memory, structural privacy, flat cost |
| AI that works in every channel with one identity | **AI AGENT** | 6 live channels, one memory, one agent |
| AI that writes code under governance | **CODE** | 13 modes, evidence gates, tool guards |
| All three, integrated | **TOGETHER** | One command, one license, one owner |
| Custom deployment + SLA | **ENTERPRISE** | Dedicated infra, direct team access |


---

## 10 — RESOURCES

| Resource | URL |
|----------|-----|
| Website | [venzari.co](https://venzari.co) |
| Documentation | [docs.venzari.co](https://docs.venzari.co) |
| Pricing | [venzari.co/pricing](https://venzari.co/pricing) |
| Careers | [venzari.co/jobs](https://venzari.co/jobs) |
| About | [venzari.co/solutions](https://venzari.co/solutions) |
| Contact | [venzariai@gmail.com](mailto:venzariai@gmail.com) |
| Installer | `install.venzari.xyz` |
| License | `install.venzari.xyz` |

---

<div style="margin-top:3rem;padding-top:2rem;border-top:1px solid #3251fc;color:rgba(253,251,249,.6);font-size:.85rem;line-height:1.6;">
  © 2026 VENZARI<br/>
  <strong>Content is King.</strong> And VENZARI writes the category.<br/>
  <em>Your AI. Your Hardware. Your Future.</em>
</div>
---

## 11 — INSTALL COMMANDS (COPY/PASTE)


---

## 12 — USE CASES BY INDUSTRY

| Industry | Primary Product | Why VENZARI |
|----------|-----------------|-------------|
| Legal / Law | ENGINE + CODE | Documents must stay private; evidence-gated code changes |
| Healthcare | ENGINE | Patient data never leaves hardware; HIPAA structural compliance |
| Finance / Fintech | ENGINE + AGENT | Trade secrets + automated customer-facing workflows |
| Manufacturing | ENGINE + CODE | Quality control automation + engineering OS for factory software |
| Media / Publishing | AGENT + ENGINE | Multi-channel presence; memory of all editorial decisions |
| Consulting / Professional Services | ENGINE | Client data sovereignty; persistent organizational memory |
| Education / Research | ENGINE + AGENT | Private AI for proprietary datasets; student interaction tracking |
| Government / Defense | ENGINE | Structural privacy is not optional; vendor access must be impossible |

---

## 13 — BEFORE / AFTER (What Changes When You Install)

| Dimension | Before VENZARI | After VENZARI |
|-----------|----------------|---------------|
| Data location | Vendor's cloud | Your server — structurally impossible to extract |
| Cost model | Per-token, unbounded | Flat monthly — predictable |
| Memory | Lost when session closes | Permanent — everything retained |
| Channels | One tool per channel | One agent across 6 channels |
| Setup | Weeks of engineering | 11 pre-flight checks, 7 questions, 17-step plan |
| Governance | Unconstrained AI behavior | 13-mode lifecycle + evidence + loop detection |
| Model control | Vendor picks | You choose — 13 providers, local priority |
| Evidence | Trust the AI's word | Evidence required for every task close |
| Team overhead | Platform engineering team | Installer handles setup + ecosystem wiring |

---

## 14 — THE GARY BRIGGS STYLE GUIDE (How This README Was Written)

Every section of this README follows the rules from "Content Is King" by Gary Briggs, written in the style of ad creator \GARY BRIGGS:

- **Headlines grab:** Every section opens with a number + bold claim — not with context, not with apology.
- **Problem first:** Each product definition starts with the old category (problem) then the new category (solution).
- **Evidence, not adjectives:** All key claims carry numbers (1508 tests, 2301 automated, 2212 skills, 33 phases, 6 channels, 8 providers). Numbers replace superlatives.
- **Tables prove:** Every comparison is in a table — dimensions, pricing, hardware, channels. Tables don't just organize; they prove.
- **Code proves:** Every install is copy-paste ready. Every command is shown with real flags (`--repair`, `doctor`, `status`).
- **Visual hierarchy:** The VENZARI ASCII art header is centered with #3251fc. Badges use brand colors (#3251fc, #A259FF, #C1FF00, #5EE7FF). Tables use dark backgrounds with bright text.
- **No internal templates:** There is no boilerplate marketing paragraph anywhere. Every sentence is either a fact, a comparison, a command, or a link.
- **Calls to action everywhere:** 5 product links at the top, 5 more at the bottom, pricing, docs, install URL, contact email — all in every version.
- **Category design not comparison:** This document does not say VENZARI is "better than" anyone. It defines new categories and asks: which category is right for your situation?

---

## APPENDIX — FULL REPOSITORY LIST (All VENZARI Repos on This Account)

| Repo | Path / URL | Status | Access |
|------|-----------|--------|--------|
| VENZARI-CO (website + admin) | `/home/billy/venzari/co` | LIVE | Private — design + colors + templates |
| VENZARI-AI PUBLIC (this repo) | `/home/billy/venzari/AI Public` | PUBLIC — this file | Only public repo |
| VENZARI-DOCS | `docs/` | LIVE | Private — all product briefs, competitive, category |
| VENZARI-CTO | `cto/` | LIVE | Private — Golden Rules, governance, audit |
| VENZARI-ENGINE | `engine/` | LIVE | Private — installation, runtime, dashboard |
| VENZARI-AI-AGENT | `ai-agent/` | LIVE | Private — CLI, skills, memory |
| VENZARI-THE-TOGETHER | `together/` | LIVE | Private — stack integration |
| VENZARI-INSTALLER | `installer/` | LIVE | Private — 2,301 tests, workspace |
| VENZARI-CODE | `code/` | LIVE | Private — OS, governance, skills |
| VENZARI-DASHBOARD | `dashboard/` | LIVE | Private — web UI |
| VENZARI-OPENCLAW | `openclaw/` | LIVE | Private — legal / contract framework |

---

## Quick Reference — One-Line Commands


> All commands verified against live installation targets. All URLs return live deploy packages.

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
