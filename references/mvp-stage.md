# MVP Stage

## Goal
Translate validated problem into the smallest, most focused working product that generates evidence of product-market fit.

## Secondary Goal
Move fast without accruing compounding technical debt. Invest in persistent context (CLAUDE.md, specs, architecture decisions) from day one.

## Exit Criteria
Genuine evidence of PMF: users find it valuable enough to **return** (retention), **pay** (revenue), or **tell others** (referral).

## Challenges & Antidotes

| Challenge | Antidote |
|-----------|----------|
| **Agentic technical debt** | Write architecture docs and CLAUDE.md before building; update after each session |
| **False product-market fit** | Define measurement framework **before** launch |
| **Zero-friction scope creep** | Written scope: what it does, what it does **not** do, evidence needed to add |
| **Insecure by inexperience** | Security review before any user touches the product |

## Key Exercises

### 1. Define architecture before building
Before opening Claude Code, use Chat to define:
- Core problem and users
- Expected scale in next 6 months
- Architectural principles and patterns
- Dependencies to avoid
- Tradeoffs being consciously accepted

Save output as **CLAUDE.md** — persistent memory for every subsequent session.

### 2. Session template for Claude Code
```
1. Revisit scope document
2. Provide CLAUDE.md architectural context
3. Execute specific task with defined constraints
4. End session: update CLAUDE.md with decisions made and assumptions introduced
```
> Five minutes of documentation per session is cheap insurance against architectural drift.

### 3. Define and enforce MVP scope
Create a scope document describing:
- What the product does
- What it deliberately does **not** do
- Feature amendment criteria: what specific user evidence justifies additions

When new ideas surface, use Claude to pressure-test: genuine user signal or founder enthusiasm?

### 4. Security review checklist (pre-launch)
- [ ] Authentication and session handling
- [ ] Data exposure in API responses
- [ ] Input validation and injection risks
- [ ] Dependencies with known vulnerabilities
- [ ] Human review for anything touching auth, secrets, or data handling

### 5. Measure before launch
- Define metrics that matter, benchmarks, and what constitutes genuine PMF vs. flattering noise
- Set retention benchmarks, activation criteria, Day 7/30 targets
- Define **false positives**: signups without activation, revenue without retention, initial enthusiasm without repeat usage

### 6. Sean Ellis PMF test
Ask active users: "How would you feel if you could no longer use this product?"
If **>40%** answer "very disappointed," that's a meaningful indicator.

### 7. Effort test
- **Pre-PMF:** Retention requires constant intervention (pushing)
- **Post-PMF:** Product starts doing the work on its own (pulling)
- When things begin **pulling instead of pushing**, that's a clear signal

### 8. Pivot diagnostic
If 3+ iteration cycles without PMF, feed Claude:
- Retention data
- User feedback
- Original hypothesis

Ask:
1. Is there a segment responding differently than the rest?
2. Is the gap a **positioning** problem or a **product** problem?
3. What would have to be true for the current product to find genuine PMF, and is that realistic?
