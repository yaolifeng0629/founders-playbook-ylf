# Launch Stage

## Goal
Turn early traction into a repeatable, sustainable growth engine. Harden infrastructure while building a company around the product.

## Exit Criteria
1. **Growth is repeatable and channel-driven** — Known CAC, LTV, payback period
2. **Product handles production workloads** — Hardened infra, security/compliance in order
3. **Operations run without founder bottlenecks** — Processes and automation exist

## Challenges & Antidotes

| Challenge | Antidote |
|-----------|----------|
| **Technical debt comes due** | Systematic architectural audit → targeted refactoring → expanded test coverage |
| **Founder becomes the bottleneck** | Audit everything you personally handle; systematize, delegate, or automate |
| **Security/compliance no longer deferrable** | Systematic review **before** production scale; treat findings as required remediation |
| **Expansion before ready** | Protect core PMF before entering new markets |

## Key Exercises

### 1. Architectural audit and remediation
- **Claude Code:** Audit MVP codebase for structural weaknesses, test coverage gaps, refactoring candidates
- **Chat:** Triage and sequence remediation — fix before next release, handle in parallel, or accept as ongoing debt
- Document MVP architectural decisions into CLAUDE.md now

### 2. Founder attention audit
- **Claude Cowork:** Inventory every recurring task, decision, and workflow routed through you
- Categorize:
  - **Automate entirely** — Candidate for Claude Cowork workflows
  - **Needs human but not you** — Delegate to team or contractors
  - **Genuinely requires founder judgment** — Keep on your plate
- Design workflow logic for automation candidates: triggers, decision rules, outputs, destinations

### 3. Security + compliance as product workstream
- **Claude Code:** Surface code-level issues for SOC 2, GDPR, HIPAA (target-market dependent)
- **Chat:** Prioritize remediation, design controls, audit logging, access management
- Build compliance into the dev cycle, not a one-time project
- For enterprise contracts: prepare documentation and controls procurement teams expect

### 4. Lightweight product management OS
Design with Claude:
- Sprint cadence and ceremonies
- Minimum spec template (required before Claude Code builds a feature)
- Bug triage decision tree
- Weekly metrics brief structure

**Claude Cowork** implements recurring elements:
- Scheduling sprint ceremonies
- Routing incoming bug reports
- Compiling weekly metrics from connected data sources
- Maintaining user feedback loop

### 5. Measurement framework in practice
- Track CAC, LTV, payback period by channel
- Monitor activation rate, retention curves, referral rates
- Ask Claude for the **adversarial case** against your traction: what would a skeptic say?
