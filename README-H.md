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
    The AI platform that learns while you sleep.<br/>
    Three products. One ecosystem. Zero cloud dependency.
  </p>

  <p>
    <a href="https://venzari.co"><img src="https://img.shields.io/badge/venzari.co-Visit%20Website-3251FC?style=for-the-badge" alt="Website"/></a>
    <a href="https://docs.venzari.co"><img src="https://img.shields.io/badge/docs.venzari.co-Documentation-A259FF?style=for-the-badge" alt="Docs"/></a>
    <a href="https://discord.gg/venzari"><img src="https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/></a>
  </p>

  <p>
    <a href="https://venzari.co/code"><img src="https://img.shields.io/badge/VENZARI%20CODE-Engineering%20OS-A259FF?style=for-the-badge" alt="CODE"/></a>
    <a href="https://venzari.co/engine"><img src="https://img.shields.io/badge/VENZARI%20ENGINE-Private%20AI%20Infrastructure-C1FF00?style=for-the-badge&logoColor=000" alt="ENGINE"/></a>
    <a href="https://venzari.co/products/venzari-ai-agent"><img src="https://img.shields.io/badge/VENZARI%20AI%20AGENT-Persistent%20Autonomous-3251FC?style=for-the-badge" alt="AI AGENT"/></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Tests-4%2C231%20Total-00D26A?style=flat-square" alt="Total Tests"/>
    <img src="https://img.shields.io/badge/v1.0.0-Production-00D26A?style=flat-square" alt="Version"/>
    <img src="https://img.shields.io/badge/Install-20%20minutes-3251FC?style=flat-square" alt="Install Time"/>
  </p>
</div>

---

## The Problem We're Actually Solving

You use AI coding assistants. They help. But when you ask **"Why did we choose Redis over Postgres for session storage three months ago?"** — silence. When you ask **"What did the security audit recommend about the auth flow?"** — nothing. The AI that helped you build it has no idea what it built.

Every conversation is a clean slate. Every session starts from zero. You re-explain your architecture. You re-describe your constraints. You paste the same context over and over. The AI is smart. But it has **no memory**.

And when it writes code? No accountability. No evidence trail. No governance. The commit message says "AI-assisted" and that's all it says. You have no record of what rules it followed, what alternatives it considered, or what tests it ran before proposing the change.

**VENZARI is the answer to both problems.**

---

## What VENZARI Actually Is

VENZARI is three products that work as one ecosystem:

1. **VENZARI CODE** — The governance layer above AI coding assistants. 13 operating modes. Each with different tool permissions. Every action logged, timestamped, immutable. The AI can't write to your codebase in Review mode. It can't commit in Implement mode. The rules are structural, not prompt-based. You get evidence per commit, not vibes per PR.

2. **VENZARI ENGINE** — Private AI infrastructure on your hardware. Conversational AI, workflow automation, semantic memory search, local voice (TTS + STT), REST API, custom fine-tuning. Everything runs on your server. You can disconnect the internet after installation and it keeps working. The privacy guarantee is the architecture, not a policy document.

3. **VENZARI AI AGENT** — Persistent autonomous agent across every channel. Telegram, Slack, Discord, email, web chat, webhooks — one agent, one memory. You start a conversation on Telegram. Continue on Slack. Finish via email. Same agent. Same memory. Zero re-explaining. It learns from every interaction. Every night at 3am, it analyzes patterns, creates new skills, improves existing ones, and wakes up more capable than when you went to sleep.

They auto-wire together. ENGINE provides the local AI gateway. CODE routes inference through it. AI AGENT connects to both. **One ecosystem. Zero manual configuration.**

---

## The Story of How CODE Works

> [!NOTE]
> **CODE doesn't replace your AI coding assistant. It governs it.** Copilot, Cursor, Windsurf, Cline, Claude Code — they all keep working. CODE is the operating system that sits above them and enforces rules they cannot enforce themselves.

### Monday Morning

You start a new feature: add pagination to the `/users` API endpoint. You open your editor. You invoke CODE in **Discover mode**.

Discover mode is read-only. The AI can scan your codebase. It can read files. It can analyze patterns. But it **cannot write anything**. Not a single character. The tool guard blocks every write operation at the system call level, not at the prompt level.

Why? Because discovery and implementation are different acts. You want the AI to understand your codebase without worrying it might change something. Discover mode gives you **pure observation**. No side effects. No "I was just looking and accidentally refactored three modules."

The AI scans your codebase. It finds the `/users` endpoint. It identifies the query layer, the route handler, the response schema. It produces a 2-page observational report. No code. Just facts. You read it. It's accurate. You're ready to plan.

### Monday Afternoon

You invoke CODE in **Plan mode**.

Plan mode can write one thing: a plan document. It cannot write code. It cannot modify your routes. It cannot touch your database layer. It can only write to `.venzari/tasks/add-pagination.md`.

The AI writes a plan:
1. Add `limit` and `offset` params to the query layer
2. Update the route handler to accept `page` and `pageSize`
3. Return pagination metadata in the response (`total`, `page`, `pageSize`, `hasMore`)
4. Add tests for edge cases (page 0, negative limit, limit > 1000)

You review the plan. You adjust step 3 — you want `nextCursor` instead of `hasMore` because you're planning to move to cursor-based pagination later. You save the change. Now you're ready to implement.

### Tuesday Morning

You invoke CODE in **Implement mode**.

Implement mode is the **only mode that can write code**. But it's not unbound. It's scoped. The AI can only work within the plan you approved. It can't decide halfway through to refactor your auth middleware. It can't "improve" your error handling while it's there. It does the work described in the plan, and nothing else.

The AI writes the code:
- Updates `getUsersQuery()` to accept `limit` and `offset`
- Updates the route handler to parse `page` and `pageSize` from query params
- Returns pagination metadata with `nextCursor`
- Writes 6 new tests

It finishes. The code is written. But it's not committed. Not yet.

### Tuesday Afternoon

You invoke CODE in **Validate mode**.

Validate mode runs your tests and produces real output. Not "the tests should pass." Not "here's how you would test it." **Actual test execution. Actual results.**

The AI runs `npm test`. Six new tests. All green. It runs the full suite. 342 tests. All green. It runs the linter. Clean. It produces a validation report with the actual test output, not a summary. You can see every assertion that passed.

You're confident. But before you commit, you want a review.

### Wednesday Morning

You invoke CODE in **Review mode**.

Review mode is read-only again. It can scan the changes. It can analyze the diff. It can check against your project rules in `.venzari/rules/`. But it **cannot modify code**. It produces a review report, not a fixed version.

The AI reads your rules:
- "All queries must use parameterized statements" ✓
- "All API responses must include `request_id`" ✗

The review report says: *"The new endpoint does not return `request_id` in the response. This violates the API rule in `.venzari/rules/api.yml`."*

You're glad you checked. This would have been caught in code review, but now you catch it before you even commit.

### Wednesday Afternoon

You invoke CODE in **Repair mode**.

Repair mode can write code, but it's even more constrained than Implement. It can **only fix the issue identified in the review**. It cannot refactor. It cannot "improve" other parts of the code. It adds `request_id` to the response schema. That's all.

You run Validate mode again. All tests pass. The rule check passes. You're ready.

### Thursday

You invoke CODE in **Commit mode**.

Commit mode performs git operations. It stages the changes. It writes a commit message that includes:
1. What was changed
2. What mode was used for each step
3. Links to the Discover report, Plan document, Validation output, and Review report

The commit message looks like this:

```
feat(api): add pagination to /users endpoint

Implementation:
- Added limit/offset to getUsersQuery()
- Updated route handler with page/pageSize params  
- Return pagination metadata with nextCursor
- Added 6 new tests, all passing (342 total green)

Governance:
- Discover: .venzari/sessions/2026-10-20_pagination/discover.md
- Plan: .venzari/tasks/add-pagination.md
- Validate: .venzari/sessions/2026-10-20_pagination/validate.log
- Review: .venzari/sessions/2026-10-20_pagination/review.md
- Repair: Added request_id to response (api.yml compliance)

Evidence: 342 tests passing, 0 failing, linter clean
```

**That's not a commit message. That's a proof.**

Three months from now, when someone asks "Why does the pagination use cursors instead of page numbers?" you don't guess. You open `.venzari/tasks/add-pagination.md` and read the exact reasoning from the day you made the decision.

---

## How CODE Users Experience It

<details>
<summary><strong>Solo developers</strong> — Governance without needing a team</summary>

You're building alone. No team to review your code. No senior engineer to catch your mistakes. But you still want standards. You still want evidence.

CODE gives you the **structure of a team without needing the people**. Your rules in `.venzari/rules/` are your senior engineer. Your validation reports are your QA team. Your review reports are your code reviewer. The AI operates within those boundaries, and every action is logged.

When you come back to the project six months later, you don't wonder what you were thinking. You read the session logs. You see the exact reasoning. You continue from where you left off.

</details>

<details>
<summary><strong>Small teams (2–10 engineers)</strong> — Consistent standards across everyone</summary>

Your team is small. Everyone wears multiple hats. Everyone uses AI assistants. But everyone uses them differently.

One engineer lets the AI refactor liberally. Another asks it to only add features. Another uses it as a search tool. The codebase becomes inconsistent. Styles clash. Conventions drift.

With CODE, **the AI follows the same rules for everyone**. Your `.venzari/rules/` directory is the source of truth. Every engineer's AI reads the same rules. Every session produces the same kind of evidence. The architecture stays coherent.

And when someone leaves? Their session logs stay. The next engineer reads them. They understand the history. The institutional knowledge doesn't walk out the door.

</details>

<details>
<summary><strong>Agencies (10+ clients, different codebases)</strong> — Audit trails per client</summary>

You work on twelve client codebases. Each has different rules. Different frameworks. Different compliance requirements. You use AI to move faster. But clients ask: "How do I know the AI didn't introduce a security issue?"

CODE gives you **evidence per client**. Client A's `.venzari/rules/` enforce PCI compliance. Client B's enforce HIPAA. Client C's enforce FedRAMP. The AI respects each client's rules structurally. Every validation report is timestamped and immutable.

When the client's auditor asks "How was this code validated?" you send them the `.venzari/sessions/` directory. They see the Discover report. They see the Plan. They see the test output. They see the review. **The evidence is the deliverable.**

</details>

<details>
<summary><strong>Enterprises (100+ engineers)</strong> — Regulatory compliance at scale</summary>

You have 200 engineers. Half use AI assistants. The other half don't trust them. Legal is worried. Compliance is worried. You need a governance model that works at scale.

CODE is **structural governance**. Not training. Not guidelines. Not hoping engineers read the wiki. The rules are enforced at runtime. Tool permissions are mode-based. Evidence is automatic.

Your compliance team defines the rules once in `.venzari/rules/`. Every engineer's AI reads them. Every commit produces evidence. The audit trail is built-in, not bolted on.

And when regulators ask "How do you govern AI-generated code?" you show them CODE. The modes. The tool guard. The evidence chain. **The system is the answer.**

</details>

<details>
<summary><strong>Open source maintainers</strong> — Evidence for AI contributions</summary>

Your project accepts contributions. Someone submits a PR. The description says "AI-assisted." You don't know what that means. Did they write it and the AI cleaned it up? Did the AI write it and they reviewed it? How thoroughly?

CODE contributions come with **session logs**. You see the Discover report. You see the Plan the AI worked from. You see the Validation output with actual test results. You see the Review report.

You're not guessing whether the contributor understood the change. You're reading the exact analysis the AI performed and the exact tests it ran. **The PR includes the proof.**

</details>

---

## The Story of How ENGINE Works

> [!IMPORTANT]
> **Structural privacy means your data physically cannot leave your hardware.** Not because someone promised it won't. Because there is no architecture by which it could. You can disconnect the internet after installation and the system keeps running. The privacy guarantee is not a document. It is the design.

### Why ENGINE Exists

Cloud AI is convenient. Until it isn't.

You're in healthcare. You want an AI assistant that understands your patient workflows. But HIPAA says patient data cannot leave your infrastructure. Cloud AI says patient data must leave your infrastructure. You're stuck.

You're in legal. You want an AI that can search your case files and draft motions. But attorney-client privilege means those files cannot be transmitted to a vendor. Cloud AI requires transmission. You're stuck.

You're in finance. You want an AI that can analyze transactions and detect anomalies. But regulatory requirements say transaction data must remain in your datacenter. Cloud AI cannot run in your datacenter. You're stuck.

**ENGINE is the unstuck.**

### What ENGINE Actually Includes

ENGINE is seven features, all running on your hardware:

1. **Conversational AI + Permanent Memory** — Every conversation, forever. Semantic search: *"What did we discuss about the Acme contract?"* → instant, sourced answer. Not "I don't remember." Not "Let me search my logs." The memory is built-in.

2. **Local Voice (TTS + STT)** — Voice synthesis and recognition, offline. Piper for text-to-speech. Whisper for speech-to-text. Voice data never leaves your server. No cloud audio processing. No transcripts sent anywhere.

3. **Workflow Automation** — Reports, email, CRM updates, calendar, ticketing. All local. No external API calls required. Scheduled tasks, triggered workflows, manual invocation. You describe the workflow in natural language. ENGINE builds it.

4. **Web Dashboard** — Full UI served at your domain. Chat interface, memory search, voice playground, workflow designer, system monitoring, model router status. Your team accesses it like any internal tool.

5. **REST API** — Connect your ERP, CRM, HR systems, ticketing platforms — all locally. No data leaves your network. OpenAPI spec included. Swagger UI at `/api/docs`. Your internal tools talk to ENGINE the same way they talk to your database.

6. **Semantic Memory Search** — Natural language queries over your entire memory store. Vector embeddings + BM25 full-text + PageRank importance ranking. Three-signal retrieval, sub-second response. *"What decisions did we make about the vendor RFP?"* → ranked results with context.

7. **Custom Fine-Tuning** (Growth+ plans) — Train models on your proprietary data. Run them locally. Never send training data to a vendor. LoRA adapters for Llama, Mistral, Qwen families. Your legal brief templates. Your financial report formats. Your customer support patterns. ENGINE learns them. Locally.

### The 3-Stage Installer

You've installed software before. You know the pain. Hours of troubleshooting. Cryptic errors. Half-configured states. Dependencies that conflict. Services that don't start. You give up. You go back to the cloud.

**ENGINE's installer is different.**

**Stage 1: 11 Pre-Install Checks** (parallel, before any wizard question)

The installer checks **everything** before asking you **anything**. RAM. Disk. CPU. OS version. Container runtime. Port availability. Internet connectivity. Sudo access. Existing installs. GPU detection. Python version.

Any failure stops immediately with **exact fix instructions**. Not "insufficient resources." Not "port conflict." You see: *"Port 443 is in use by nginx (PID 1234). Run `sudo systemctl stop nginx` to free it, or choose a different HTTPS port in the wizard."*

No partial states. No "it mostly worked." Either all 11 checks pass, or you don't proceed.

**Stage 2: 7-Question Wizard** (configures what can't be auto-detected)

The installer asks seven questions. Not twenty. Not "press Enter to continue" twelve times. Seven questions that matter:

1. Server identity (domain or IP)
2. License key (validates tier + seats)
3. AI provider preference (local-only | local+cloud | cloud-only)
4. Model selection (hardware-adaptive recommendations based on your RAM/GPU)
5. SSL mode (auto Let's Encrypt | manual cert | HTTP only)
6. Telemetry (anonymous install success ping yes/no)
7. Optional add-ons (voice, custom training, workflows)

Everything else is auto-detected. Your hardware profile is measured in Stage 1. Your network topology is inferred from routing tables. Your container runtime is already confirmed working.

**Stage 3: 17-Step Hardware-Customized Plan** (from VENZARI installer service)

The installer sends your hardware profile + license to the VENZARI installer service. The service returns a **17-step plan customized for your machine**.

8 GB RAM? You get small models (Qwen 1.5B, Llama 3.2 3B). 64 GB RAM? You get large models (Qwen 72B, Llama 3.1 70B). NVIDIA GPU detected? You get GPU-accelerated inference. No GPU? You get CPU-optimized models.

The 17 steps execute in order:
1. Download verified binary
2. Download verified models (matched to your hardware)
3. Configure container runtime
4. Start database (Postgres)
5. Start cache (Redis)
6. Start vector store (Chroma)
7. Start inference engine
8. Start API gateway
9. Start workflow scheduler
10. Start memory indexer
11. Health check: all services responding
12. Initialize database schema
13. Seed default skills
14. Configure SSL (if selected)
15. Wire inter-service connections
16. Final health check: end-to-end test
17. Generate access credentials

**If any step fails, the installer is resumable.** Step 9 fails? You run the resume-repair command. It skips steps 1–8 (already complete), retries step 9, continues from there.

2,301 automated tests back every step. Not "should work." **Proven to work.**

Twenty minutes later, you have a URL. You open it. The dashboard loads. You're in.

### How ENGINE Users Experience It

<details>
<summary><strong>Healthcare organizations</strong> — HIPAA compliance by design</summary>

You're a hospital system. You want AI to help with clinical workflows. Symptom analysis. Treatment recommendations. Medical literature search. But HIPAA says: **Protected Health Information (PHI) cannot leave your infrastructure without patient consent.**

Cloud AI says: **Your data must leave your infrastructure.** Structurally. The model runs in the vendor's datacenter. Your query goes to them. Their response comes back. Your PHI crossed the boundary. You're non-compliant.

ENGINE runs in your datacenter. The model runs on your hardware. The data never leaves. Not because of a contract. Not because the vendor promised. **Because there is no network path by which it could leave.** The architecture guarantees compliance. The contract just describes what already exists.

Your auditor asks: "How do you ensure PHI doesn't leave your environment?" You show them the network diagram. You show them the firewall logs. You show them that ENGINE's inference service has **no outbound network routes**. It cannot send data out even if it wanted to. **The audit answer is: it is physically impossible.**

</details>

<details>
<summary><strong>Legal firms</strong> — Attorney-client privilege protection</summary>

You're a law firm. You want AI to search case files, draft motions, analyze precedents. But attorney-client privilege means **case details cannot be disclosed to a third party**.

Cloud AI is a third party. The moment your case file goes to their API, privilege is waived. You've disclosed to them. They're now a potential witness. You've created a liability.

ENGINE runs on your server. No third party sees the data. No vendor processes your queries. The privilege boundary is preserved **architecturally**. Your clients' files stay within your infrastructure, under your control, protected by the same physical and logical security that protects your file servers.

Your malpractice insurer asks: "Do you use AI tools?" You say yes. They ask: "How do you protect privilege?" You show them ENGINE. Local deployment. No external API calls. The insurer nods. **The risk is contained.**

</details>

<details>
<summary><strong>Financial institutions</strong> — Regulatory requirements met structurally</summary>

You're a bank. You want AI for fraud detection, transaction analysis, customer support. But regulatory requirements (SOX, PCI-DSS, GLBA) say **transaction data must remain in controlled environments with full audit trails**.

Cloud AI says: "We're SOC 2 compliant." That's policy compliance. You need **structural compliance**. You need to prove to regulators that transaction data never left your datacenter. A policy document doesn't prove that. Network logs prove that.

ENGINE gives you **provable data residency**. The models run on your hardware. The transactions never leave. Your network monitoring shows: zero outbound API calls from the ENGINE service. Your audit logs show: every query, every response, every timestamp, all local.

Your regulator asks: "How do you govern AI access to transaction data?" You show them ENGINE's access control system. Role-based permissions. Audit trails. Data residency proof. **The system is the compliance artifact.**

</details>

<details>
<summary><strong>Government agencies</strong> — Air-gapped environments</summary>

You're a government agency. You work in a classified environment. Air-gapped. No internet. No cloud. No external services. You still want AI. You've been told: "AI requires cloud." You've been told wrong.

ENGINE installs in **three phases** (described above). Phase 1 and Phase 2 require internet — for downloading the binary and models. Phase 3 does not. Once installed, **disconnect the network**. ENGINE keeps running.

Your queries stay local. Your models stay local. Your memory stays local. The system functions fully offline. Updates are delivered via USB or internal network. Security patches are tested in your staging environment before deployment.

You have AI. You have air-gap. You have both. **The constraint is satisfied architecturally.**

</details>

<details>
<summary><strong>Enterprises with 500+ employees</strong> — Cost predictability</summary>

You're a Fortune 500 company. You piloted AI assistants. Usage exploded. Ten people used it. Then a hundred. Then a thousand. Your bill went from $2,000/month to $80,000/month. Finance is asking questions. Procurement is asking questions. You're asked to "control AI spend." You don't know how.

Cloud AI is **per-token pricing**. More usage = more cost. Viral adoption = budget explosion. You can't predict it. You can't cap it. You can only watch the bill grow.

ENGINE is **flat monthly pricing**. Foundation: $349/month. Growth: $899/month. Enterprise: $2,499/month. Unlimited inference. Unlimited memory. Unlimited users. The bill in January is the same as the bill in December. You can forecast. You can budget. You can scale.

Your CFO asks: "What's our annual AI spend?" With cloud AI, you guess. With ENGINE, you say: **$29,988**. Twelve months times $2,499. No surprises. No overages. **Cost is predictable because the architecture is local.**

</details>

<details>
<summary><strong>Privacy-first companies</strong> — Competitive advantage</summary>

You're a startup. Your competitors use cloud AI. They're fast. They're impressive. But you've read their privacy policies. You know where the data goes. You've chosen a different path.

Your marketing says: **"We never send your data to third-party AI providers."** Your competitors cannot say that. They use cloud AI. The data goes. They can't claim otherwise.

ENGINE lets you **make privacy a feature, not a tradeoff**. Your customers get AI-powered features. Their data stays with you. You're not slower. You're not less capable. You're structurally private. That's differentiation.

Your enterprise customers ask: "Where does our data go?" Your competitors hedge. You say: **"Your hardware. Period."** You win the deal. **Privacy is the moat.**

</details>

---

## The Nightly Learning Loop — A Monday Through Friday Story

> [!TIP]
> **VENZARI AI AGENT is the only persistent AI agent that learns from you and becomes more capable every night without you training it.** You don't configure skills. You don't write rules. You just use it. And every morning, it's better than yesterday.

### Monday

You wake up. You open Telegram. You message your VENZARI AI AGENT: *"What's on my calendar today?"*

It responds instantly. Three meetings. One deadline. Two follow-ups from last week that you forgot about.

You say: *"Remind me to call Sarah before the 3pm meeting."* The agent confirms. You close Telegram.

Later, you're on your laptop. You open Slack. You type: *"Pull the Q3 revenue numbers from the finance drive."* Same agent. Same memory. It doesn't ask "Which drive?" or "What's your email again?" It already knows. It remembers Monday morning's conversation even though that was on Telegram and this is Slack.

The numbers arrive in 8 seconds. Formatted. Sourced. Time-stamped. You drop them into your report.

You close Slack. You go to a meeting. Your phone buzzes. It's 2:47pm. *"Reminder: call Sarah before 3pm."* You smile. You call Sarah.

That night at 3am — while you sleep — the agent runs its **nightly learning loop**.

It analyzes Monday's patterns:
- You asked for calendar data three times today (once per channel)
- You asked for finance data twice (similar phrasing both times)
- You set a reminder tied to a calendar event (not just a time)

The learning loop creates **two new skills**:
1. `fetch_calendar_next_24h` — optimized query, caches the result, returns instantly
2. `remind_before_event` — ties reminders to calendar events, not just timestamps

These skills go live. Tomorrow, you'll get faster calendar responses. And your reminders will be context-aware.

You sleep. The agent learns.

### Tuesday

You wake up. You message the agent on Discord (because you were already in Discord): *"What's on my calendar today?"*

Response time: 0.6 seconds. Yesterday it was 2.4 seconds. You don't notice. The agent does.

You say: *"Pull the Q3 revenue numbers again, but just October."* The agent refines the query. You get October only. Formatted the same way as yesterday. Consistent.

You say: *"Actually, pull Q2 and Q3 side by side."* The agent restructures the data. Two columns. Labeled. You paste it into your slide deck.

You say: *"Thanks."* The agent says: *"You're welcome. I saved your data formatting preference (two-column comparison) for future revenue queries."*

That night at 3am, the learning loop runs again.

It analyzes Tuesday's patterns:
- You pulled the same financial data twice, with refinements
- You asked for a side-by-side comparison (new request type)
- You thanked the agent (positive feedback signal)

The learning loop **improves an existing skill**:
- `fetch_finance_data` now remembers your preference for two-column comparisons when you ask for multi-period data

And it creates **one new skill**:
- `format_for_slides` — recognizes when data is for a presentation, auto-formats with headers and alignment optimized for paste-into-PowerPoint

You sleep. The agent learns.

### Wednesday

You wake up. You open your email. You forward an email to your agent's email address with the note: *"Summarize this thread and tell me if I need to respond."*

The agent reads the thread. Six people. Twelve messages. It produces a three-sentence summary: *"The vendor is asking for a revised timeline. Legal approved the contract. You're waiting on finance to confirm budget. No response needed yet — finance is expected to reply by Thursday."*

You don't respond. You move on.

Later, you're in a meeting. Someone asks: *"What did we decide about the vendor timeline?"* You don't remember. You pull out your phone. You message the agent on Telegram: *"What did the vendor email thread say about timeline?"*

The agent recalls the thread you forwarded this morning (even though that was via email, and this is Telegram). It replies: *"The vendor is asking for a revised timeline. You haven't committed to one yet."*

You answer the question in the meeting. You look prepared. The agent made you prepared.

That night at 3am, the learning loop runs again.

It analyzes Wednesday's patterns:
- You forwarded an email thread for summarization (first time)
- You later queried the same thread from a different channel (cross-channel memory retrieval worked)
- You asked "what did we decide" about something that hasn't been decided yet (the agent correctly identified: no decision made)

The learning loop creates **one new skill**:
- `summarize_email_thread` — optimized for multi-party email chains, extracts action items, flags decisions vs. pending questions

And it improves **memory retrieval logic**:
- When you ask "what did we decide," the agent now checks whether a decision was actually made, and responds differently if it's still pending

You sleep. The agent learns.

### Thursday

You wake up. You message the agent on Slack: *"Did finance respond about the vendor budget?"*

The agent says: *"Not yet. The thread is still active. I'm monitoring it. I'll notify you when they respond."*

You didn't ask it to monitor. It inferred that from Wednesday's conversation. You said "finance is expected to reply by Thursday." It's Thursday. The agent assumed you want to know when they reply. It was right.

At 2:14pm, you get a Slack notification from the agent: *"Finance replied to the vendor email thread. Budget is approved. You can confirm the timeline now."*

You open the email. Finance replied 4 minutes ago. The agent saw it in real-time. You reply to the vendor. Done.

That night at 3am, the learning loop runs again.

It analyzes Thursday's patterns:
- You asked if someone responded (checking for updates)
- The agent proactively monitored the thread without being asked (inferred intent, positive outcome)
- You acted on the notification immediately (confirmation that the proactive monitoring was useful)

The learning loop creates **one new skill**:
- `monitor_thread_until_reply` — when you ask about an expected reply, the agent auto-monitors the thread and notifies you when the reply arrives

And it improves **notification logic**:
- The agent now distinguishes between threads you're passively aware of vs. threads you're actively waiting on, and only sends real-time notifications for the latter

You sleep. The agent learns.

### Friday

You wake up. You message the agent on Telegram: *"Summarize my week."*

The agent produces a six-point summary:
1. Three calendar-heavy days (Monday, Wednesday, Friday)
2. Two finance data pulls (Q3 revenue)
3. One vendor email thread (now resolved, timeline confirmed)
4. One proactive notification (finance approval)
5. Four reminders set, four reminders delivered on time
6. Cross-channel usage: Telegram 8 times, Slack 6 times, Discord 2 times, Email 1 time

You say: *"That's perfect. Do this every Friday at 8am."*

The agent says: *"Scheduled. You'll receive a weekly summary every Friday at 8am, starting next week."*

That night at 3am, the learning loop runs again.

It analyzes Friday's patterns:
- You asked for a week summary (first time, but well-received)
- You scheduled it as a recurring task (strong positive feedback)
- The summary included cross-channel stats (you didn't ask for that, but you didn't object, so it's kept)

The learning loop creates **one new skill**:
- `weekly_summary` — runs every Friday at 8am, produces the six-point format you saw today

And it improves **scheduling logic**:
- When you say "do this every [time]," the agent now confirms the exact recurrence pattern and asks if you want reminders/notifications tied to it

You sleep. The agent learns.

---

### The Difference

**Monday's agent**: Reactive. Fast. Accurate. But no initiative. You ask, it answers. That's all.

**Friday's agent**: Proactive. Contextual. Predictive. It knows your patterns. It monitors threads you care about. It formats data the way you like. It reminds you with context. It learns from every interaction.

**You didn't train it. You didn't configure skills. You didn't write rules. You just used it. And it became yours.**

That's the learning loop. That's what makes VENZARI AI AGENT different from every chatbot you've used.

---

## How AI AGENT Users Experience It

<details>
<summary><strong>Solo founders</strong> — Always-on assistant without hiring anyone</summary>

You're building a startup alone. You're the CEO, the CTO, the CMO, the support team. You need help. But you can't afford to hire yet.

VENZARI AI AGENT is your **first employee**. It's on Slack when you're at your desk. It's on Telegram when you're mobile. It's on email when customers write in. It's on webhooks when your monitoring service alerts. Same agent. Same memory. It knows your business because it's been with you since day one.

You say: *"Draft a response to this support email."* It drafts it. You say: *"Monitor the server logs for errors."* It monitors. You say: *"Remind me to invoice Client X on the 1st."* It reminds.

Every night, it learns your patterns. It learns what you care about. It learns what you ignore. **It becomes your assistant, shaped by you, without you managing it.**

</details>

<details>
<summary><strong>Remote teams</strong> — One agent for the whole team, all channels</summary>

Your team is distributed. Some people use Slack. Some use Discord. Some prefer email. Some are always on Telegram. You've tried to centralize on one tool. It didn't stick.

VENZARI AI AGENT works **across every channel**. Your team doesn't have to change their habits. They ask the agent questions wherever they already are. Same agent. Same memory. Same knowledge.

Your designer asks on Slack: *"What's the brand color hex code?"* The agent replies. Your developer asks on Discord: *"What API rate limit did we agree on?"* The agent replies. Your PM asks via email: *"What did we decide about the pricing tier names?"* The agent replies.

One source of truth. Six access points. **Your team stays in their tools. The agent meets them there.**

</details>

<details>
<summary><strong>Support teams</strong> — 24/7 coverage without 24/7 staff</summary>

You run a support team. You have customers in twelve time zones. You can't afford to staff 24/7. Overnight tickets sit until morning. Customers get frustrated.

VENZARI AI AGENT handles **tier-1 support overnight**. Common questions. Password resets. Status checks. Billing inquiries. It responds instantly. It pulls from your knowledge base. It escalates to your team when it can't resolve.

Your support lead says: *"What questions did the agent handle overnight?"* The agent produces a summary: 14 tickets. 11 resolved. 3 escalated. Average response time: 4 seconds.

Your team arrives in the morning. Three escalated tickets in the queue. Not seventeen. **The agent handled the routine. Your team handles the complex.**

</details>

<details>
<summary><strong>Sales teams</strong> — Auto-CRM updates without manual data entry</summary>

You're in sales. You hate data entry. Every call ends with: "Now I have to log this in the CRM." You don't. It piles up. Your manager asks: "Is the CRM up to date?" It's not.

VENZARI AI AGENT listens to your conversations (with permission). After every call, it asks: *"Would you like me to log this?"* You say yes. It writes the summary, logs the next action, updates the deal stage, tags the stakeholders.

You didn't type anything. You didn't open the CRM. **The CRM is current because the agent made it current.**

Your manager asks: "Is the Acme deal moving forward?" You say: "Check the CRM." It's accurate. Because the agent kept it accurate.

</details>

<details>
<summary><strong>VENZARI CODE + ENGINE users</strong> — Natural language interface to your entire system</summary>

You use VENZARI CODE. You use VENZARI ENGINE. You have rules in `.venzari/rules/`. You have memory in ENGINE. You have workflows in ENGINE. You have models in ENGINE.

VENZARI AI AGENT **wires to both**. You say: *"What rules do we have about database queries?"* The agent reads `.venzari/rules/database.yml` and replies. You say: *"What did we decide about the auth refactor?"* The agent queries ENGINE's memory and replies. You say: *"Run the weekly report workflow."* The agent invokes ENGINE's workflow scheduler.

You're not switching between three tools. You're talking to one agent. The agent talks to the three tools. **Your interface is natural language. The agent handles the plumbing.**

</details>

---

## The Provider Comparison Table

VENZARI AI AGENT uses **8 AI providers** in a router with automatic failover, circuit breakers, and budget monitoring:

| Provider | When Used | Strength | Speed | Cost |
|----------|-----------|----------|-------|------|
| **Local** (via ENGINE) | Primary — always tried first | Privacy, zero cost | Medium | Free |
| **Groq** | Fallback when local unavailable | Fast GPU inference | Very Fast | Low |
| **Gemini** | Secondary cloud fallback | Free tier, good quality | Fast | Free tier available |
| **OpenRouter** | Specific model needed | Broad model variety | Medium | Medium |
| **Cerebras** | Speed-critical tasks | Ultra-fast (1800 tok/s) | Fastest | Medium |
| **Anthropic** | Claude-specific reasoning | Best reasoning quality | Medium | High |
| **OpenAI** | GPT-4/structured output | Structured responses | Medium | High |
| **Bedrock** | Already on AWS | Enterprise compliance | Medium | Medium |

**Routing logic:**
1. Try local (if ENGINE installed)
2. Fallback to Groq (fast + cheap)
3. Fallback to Gemini (free tier)
4. Route to specialized provider if needed (OpenRouter for variety, Cerebras for speed, Anthropic for reasoning, OpenAI for structured output, Bedrock for AWS-native)

**Circuit breaker:** 3 consecutive failures → bypass provider for 5 minutes, auto-probe for recovery

**Budget monitor:** Approaching monthly limit → downgrade to cheaper model tier, alert user

---

## VENZARI Together — The Auto-Wired Ecosystem

**CODE + ENGINE on one machine. Zero manual configuration.**

When you install ENGINE, it exposes a local AI gateway. When you install CODE on the same machine, CODE auto-detects ENGINE's gateway and routes all inference through it. No config file edits. No environment variables. No manual wiring.

**What this means:**
- CODE's Implement mode uses local models (via ENGINE)
- CODE's Review mode uses local models (via ENGINE)
- Your development workflow produces **zero cloud API calls**
- You can work offline after ENGINE + CODE are installed
- Your code never leaves your machine during development

**Hardware requirements:**
- 8 GB RAM minimum (16 GB recommended)
- 20 GB disk space
- Ubuntu 20.04+ (22.04 recommended)
- Container runtime (Docker/Podman) installed and running

**What auto-wires:**
- CODE CLI → ENGINE gateway
- CODE Desktop app → ENGINE gateway
- CODE MCP tools → ENGINE gateway
- AI AGENT (if installed) → ENGINE gateway + CODE session logs + ENGINE memory

**One ecosystem. Zero config. Three products working as one.**

**[→ venzari.co/together](https://venzari.co/together)** — Installation guide

---

## VENZARI Enterprise — White-Label + Managed

You want VENZARI under your brand. You want custom skills developed for your workflows. You want a managed fleet across 50 locations. You want an SLA. You want direct access to the VENZARI team.

**VENZARI ENTERPRISE includes:**

| Feature | Enterprise Platforms | VENZARI ENTERPRISE |
|---------|---------------------|---------------------|
| **White-label** | Not offered | Your brand, your domain, your logo |
| **Custom skills** | None or expensive | Included — we build skills for your workflows |
| **Managed fleet** | Self-managed | We manage deployments, updates, monitoring |
| **Dedicated support** | Ticket-based | Direct Slack channel with VENZARI team |
| **SLA** | None or basic | 99.9% uptime, <4hr critical response |
| **Training** | Documentation only | Live onboarding + ongoing training sessions |
| **Price** | $100,000–$500,000/year | **$5,988/year ($499/month)** |
| **Setup time** | 3–6 months | **20 minutes (same installer)** |

**Who needs Enterprise:**
- **Agencies** — White-label for clients
- **Enterprises 500+** — Managed fleet across regions
- **Government** — SLA + compliance requirements
- **Healthcare systems** — HIPAA + custom clinical workflows
- **Financial institutions** — Regulatory compliance + audit support

**[→ venzari.co/enterprise](https://venzari.co/enterprise)** — Schedule a call

---

## Pricing Summary

<table>
<thead>
<tr>
<th>Product</th>
<th>Tier</th>
<th>Monthly</th>
<th>What's Included</th>
</tr>
</thead>
<tbody>

<tr>
<td rowspan="3"><strong>CODE</strong></td>
<td>Solo</td>
<td>$49</td>
<td>1 user · All modes · Desktop + CLI + MCP tools</td>
</tr>
<tr>
<td>Team</td>
<td>$199</td>
<td>5 users · Shared rules · Session logs</td>
</tr>
<tr>
<td>Enterprise</td>
<td>$599</td>
<td>Unlimited users · SSO · Audit exports</td>
</tr>

<tr>
<td rowspan="3"><strong>ENGINE</strong></td>
<td>Foundation</td>
<td>$349</td>
<td>1 admin · All features · Self-hosted</td>
</tr>
<tr>
<td>Growth</td>
<td>$899</td>
<td>5 admins · Custom fine-tuning · Priority support</td>
</tr>
<tr>
<td>Enterprise</td>
<td>$2,499</td>
<td>Unlimited admins · SLA · Managed deployment</td>
</tr>

<tr>
<td rowspan="3"><strong>AI AGENT</strong></td>
<td>Starter</td>
<td>$29</td>
<td>1 channel · 1,000 skills · Basic memory</td>
</tr>
<tr>
<td>Pro</td>
<td>$99</td>
<td>6 channels · 2,212 skills · Full memory · Learning loop</td>
</tr>
<tr>
<td>Team</td>
<td>$299</td>
<td>Unlimited channels · Custom skills · Team memory</td>
</tr>

<tr>
<td><strong>Together</strong></td>
<td>—</td>
<td><em>CODE + ENGINE pricing</em></td>
<td>Auto-wired ecosystem · Offline dev workflow</td>
</tr>

<tr>
<td><strong>Enterprise</strong></td>
<td>—</td>
<td>$499</td>
<td>White-label · Custom skills · Managed · SLA</td>
</tr>

</tbody>
</table>

**[→ venzari.co/pricing](https://venzari.co/pricing)** — Compare all plans

---

## What You Actually Get

When you buy VENZARI, here's what you own:

**1. The software itself** — Not a license to use someone else's software. The binary. The source (on request). The models. The data. It's yours. You can run it forever. You can modify it. You can deploy it to 500 servers. We don't control it after you install it.

**2. The data and memory** — Every conversation. Every session log. Every decision record. Every workflow. All stored on your hardware, under your control. We never see it. We cannot access it. It's not in "your account on our servers." It's in your database on your server.

**3. The future** — Updates are included. New features are included. Security patches are included. You're not on a treadmill where each new capability is an upsell. You bought the platform. You get the platform's evolution.

**4. The architecture** — The governance model in CODE. The structural privacy in ENGINE. The learning loop in AI AGENT. These are not configuration settings we can revoke. They're the design. You own the design.

**What you don't get:**
- Cloud hosting (it's self-hosted by design)
- Vendor lock-in (you can export everything)
- Per-token billing (it's flat monthly)
- The need to ask permission to use your own data (it never left your server)

---

## The Manifesto

We believe AI should be **owned, not rented**.

We believe privacy is **architectural, not contractual**.

We believe governance is **structural, not policy-based**.

We believe memory should be **permanent, not session-limited**.

We believe AI agents should **learn from you, not from everyone**.

We believe software should **work offline, not require constant connectivity**.

We believe evidence should be **immutable, not editable narratives**.

We believe the future should be **yours, not controlled by a platform you don't own**.

That's why we built VENZARI.

Not because cloud AI doesn't work. Because **you shouldn't have to depend on it**.

Not because AI coding assistants are bad. Because **they need governance they cannot provide themselves**.

Not because chatbots aren't useful. Because **stateless tools cannot build institutional knowledge**.

VENZARI is the platform for people who want **control, privacy, and ownership**. For organizations that need **compliance, predictability, and evidence**. For teams that value **memory, learning, and persistence**.

If that's you, we built this for you.

---

## Get Started

**→ [venzari.co/pricing](https://venzari.co/pricing)** — All products, all tiers
**→ [docs.venzari.co](https://docs.venzari.co)** — Full documentation
**→ [venzari.co/together](https://venzari.co/together)** — Install the ecosystem
**→ [venzari.co/enterprise](https://venzari.co/enterprise)** — White-label and managed
**→ [venzari.co/contact](https://venzari.co/contact)** — Talk to the team
**→ [discord.gg/venzari](https://discord.gg/venzari)** — Join the community
**→ [venzari.co/jobs](https://venzari.co/jobs)** — We're hiring

---

<p align="center">
<strong>VENZARI</strong> &nbsp;·&nbsp; <a href="https://venzari.co">venzari.co</a> &nbsp;·&nbsp; <a href="https://docs.venzari.co">Docs</a> &nbsp;·&nbsp; <a href="https://venzari.co/pricing">Pricing</a> &nbsp;·&nbsp; <a href="https://discord.gg/venzari">Discord</a> &nbsp;·&nbsp; <a href="https://venzari.co/jobs">Jobs</a><br/>
<em>Your AI. Your Hardware. Your Future. &nbsp;·&nbsp; © 2026 VENZARI</em>
</p>
