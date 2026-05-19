---
name: founders-playbook
version: 1.0.0
description: |
  AI-native startup founder playbook — tactical guide for building startups with Claude as core infrastructure.
  Covers the four-stage lifecycle (Idea, MVP, Launch, Scale) with stage-specific goals, exit criteria, challenges, exercises, and anti-patterns.
  Based on Anthropic's The Founder's Playbook (2026).

  Use when asked about startup building, founder strategy, product-market fit, MVP scope,
  go-to-market, fundraising, technical debt, scope creep, CLAUDE.md best practices, or any
  stage of the AI-native startup journey.

  Proactively suggest when the user is:
  - Validating a business idea or exploring a new market
  - Building an MVP and needs architecture or scope guidance
  - Preparing for launch and needs measurement frameworks
  - Scaling operations and facing founder bottleneck issues
  - Writing pitch decks, investor memos, or competitive analyses

triggers:
  - founder
  - startup
  - idea stage
  - MVP stage
  - launch stage
  - scale stage
  - product-market fit
  - PMF
  - business plan
  - pitch deck
  - customer discovery
  - competitive analysis
  - go-to-market
  - fundraising
  - technical debt
  - scope creep
  - founder bottleneck
  - workflow automation
  - agentic coding
  - CLAUDE.md
  - startup playbook
  - AI native startup
  - lean startup
  - startup lifecycle
---

# AI-Native Startup Founder Playbook

> **Core thesis:** AI compresses quarters into weeks. The founder's role shifts from individual contributor to orchestrator of agents. A good idea gets founders further than ever — but validation discipline matters more than ever.

---

## Quick Navigation

| Stage | Core Question | Exit Criteria | Primary Claude Tool | Details |
|-------|--------------|---------------|---------------------|---------|
| **Idea** | Is this worth building? | Problem-solution fit validated | Chat + Cowork | [Read](references/idea-stage.md) |
| **MVP** | What should we build first? | Evidence of PMF (retention/revenue/referral) | Code + Cowork | [Read](references/mvp-stage.md) |
| **Launch** | Can this grow repeatably? | Repeatable growth, production-ready, founder-free ops | All three | [Read](references/launch-stage.md) |
| **Scale** | Can this survive without me? | Sustainable profitability / IPO / acquisition | All three | [Read](references/scale-stage.md) |

---

## Claude Surface Selection

Match the tool to the task:

| Task | Tool | Why |
|------|------|-----|
| Quick question, rewrite, brainstorm | **Chat** | Fast, conversational, no setup |
| Research, analysis, finished docs/decks | **Claude Cowork** | Folder access, connectors, skills, scheduled runs |
| Write, test, ship software | **Claude Code** | Codebase access, diffs, git, Plan Mode |

The three share the same Claude model; what changes is the workspace around it.

---

## Stage Overview

### Idea Stage

**Goal:** Research-oriented validation before writing production code.

**Three exit criteria** (must all be YES):
1. Problem is real and specific (who, how often, how severely, current workaround)
2. Solution addresses the **actual** problem validation revealed
3. Enough qualitative evidence from real conversations to justify building

**Top challenges:**
- Mistaking building for validating (prototype ≠ evidence; conversations = evidence)
- Premature scaling (keep sense-making ahead of building)
- Confirmation bias (ask Claude to argue **against** your idea)

**Read the full Idea Stage guide:** [references/idea-stage.md](references/idea-stage.md)

---

### MVP Stage

**Goal:** Smallest focused product that generates PMF evidence.

**Secondary goal:** Move fast without accruing compounding technical debt. Invest in persistent context (CLAUDE.md, specs, architecture) from day one.

**Top challenges:**
- **Agentic technical debt** — Write CLAUDE.md before building; update after each session
- **False PMF** — Define measurement framework **before** launch
- **Zero-friction scope creep** — Written scope: what it does, what it doesn't, evidence needed to add
- **Insecure by inexperience** — Security review before any user touches the product

**Key practices:**
- **CLAUDE.md** as persistent architectural memory
- **Session template:** Revisit scope → Provide CLAUDE.md → Execute → Document decisions
- **Sean Ellis test:** >40% "very disappointed" = meaningful PMF indicator
- **Effort test:** Pre-PMF you push; post-PMF product pulls

**Read the full MVP Stage guide:** [references/mvp-stage.md](references/mvp-stage.md)

---

### Launch Stage

**Goal:** Turn early traction into repeatable, sustainable growth.

**Three exit criteria:**
1. Growth is repeatable and channel-driven (known CAC, LTV, payback)
2. Product handles production workloads (hardened infra, security/compliance)
3. Operations run without founder bottlenecks

**Top challenges:**
- Technical debt comes due (audit → refactor → expand test coverage)
- Founder becomes the bottleneck (audit, categorize, automate/delegate)
- Security/compliance no longer deferrable (review before production scale)
- Expansion before ready (protect core PMF first)

**Read the full Launch Stage guide:** [references/launch-stage.md](references/launch-stage.md)

---

### Scale Stage

**Goal:** Systematic growth sustained by mature operations. Build a defensible moat.

**Exit forms:** Sustainable profitability, IPO-readiness, or acquisition readiness.

**Top challenges:**
- Delegating the operational layer (codify institutional knowledge first)
- Scaling technical operations (docs, SLAs, monitoring, incident response)
- Building a GTM function (AI bootstraps: segmentation, messaging, sales playbooks)
- Organic growth ceiling (build dedicated GTM before flattening curves)

**Read the full Scale Stage guide:** [references/scale-stage.md](references/scale-stage.md)

---

## Anti-Patterns at a Glance

| Anti-Pattern | Stage | Fix |
|--------------|-------|-----|
| Building before validating | Idea | Conversations are evidence; prototypes are props |
| Confirmation bias with AI | Idea | Ask AI to argue **against** your idea |
| No architecture docs | MVP | Write CLAUDE.md before first line of code |
| No scope boundaries | MVP | Written scope: in-scope, out-of-scope, amendment criteria |
| Skipping security review | MVP/Launch | Review auth, data exposure, input validation, dependencies |
| Tracking metrics post-launch | Launch | Define framework, benchmarks, false positives **before** launch |
| Founder as bottleneck | Launch/Scale | Audit, categorize, automate/delegate |
| Expanding too early | Launch | Protect core PMF before new markets |
| Organic growth ceiling | Scale | Build dedicated GTM function |

**Read the full Anti-Patterns guide:** [references/anti-patterns.md](references/anti-patterns.md)

---

## Checklists

Stage-specific checklists for tracking progress:

- **Idea Stage checklist:** [references/checklists.md](references/checklists.md#idea-stage)
- **MVP Stage checklist:** [references/checklists.md](references/checklists.md#mvp-stage)
- **Launch Stage checklist:** [references/checklists.md](references/checklists.md#launch-stage)
- **Scale Stage checklist:** [references/checklists.md](references/checklists.md#scale-stage)

---

## Resources

Reference materials including Claude tooling guides, AI-native startup case studies, and support programs:

**Read:** [references/resources.md](references/resources.md)

---

## When to Read Each Reference

| When the user asks about... | Read this reference |
|-----------------------------|---------------------|
| Idea validation, customer discovery, competitive analysis, market sizing | [references/idea-stage.md](references/idea-stage.md) |
| MVP scope, architecture, CLAUDE.md, security review, PMF measurement | [references/mvp-stage.md](references/mvp-stage.md) |
| Launch readiness, growth channels, founder bottleneck, compliance | [references/launch-stage.md](references/launch-stage.md) |
| Scaling operations, GTM, enterprise sales, moat building | [references/scale-stage.md](references/scale-stage.md) |
| Common mistakes and how to avoid them | [references/anti-patterns.md](references/anti-patterns.md) |
| Progress tracking by stage | [references/checklists.md](references/checklists.md) |
| Claude tooling, startup stories, support programs | [references/resources.md](references/resources.md) |
