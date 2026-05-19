# Idea Stage

## Goal
Research-oriented validation: assemble solid evidence that a real problem exists (and your solution addresses it) before writing production code.

## Exit Criteria
Answer **YES** to all three:
1. Is the problem real and specific? (who, how often, how severely, current workaround)
2. Does your solution address the **actual** problem validation revealed?
3. Do you have enough qualitative evidence from real conversations to justify building?

## Challenges & Antidotes

| Challenge | Antidote |
|-----------|----------|
| **Mistaking building for validating** | Prototype is a prop for conversations; conversations are the evidence |
| **Premature scaling** | Keep sense-making ahead of building |
| **Loss of objectivity** (confirmation bias) | Ask Claude to argue **against** your idea and find disconfirming evidence |

## Key Exercises

### 1. Sharpen the hypothesis
Transform vague observations into testable statements.

- **Weak:** "Contract review takes too long"
- **Strong:** "In-house legal teams at mid-market companies spend 3+ days per contract review cycle because redlines are managed across email threads rather than a single version-controlled document"

### 2. Devil's advocate analysis
- Ask Claude: "Make the most compelling argument for why a competitor would succeed while I do not"
- Map competitive landscape by tier: direct, indirect, potential acquirers, adjacent players
- For each tier, ask Claude to argue why they pose a genuine threat

### 3. Customer discovery
- Define precise target profiles: job titles, company types, team structures, seniority levels
- Ask **past-facing** questions: "Tell me about the last time you dealt with this problem"
- Avoid future-facing questions: "Would you use something like this?"
- Audit interview questions with Claude: flag leading, future-facing, or overly broad questions
- Design different question sets for each persona

### 4. Post-interview analysis
- After each conversation: feed notes to Claude, identify what confirmed, challenged, or surprised
- After every 5 interviews: synthesize into two lists — supporting evidence vs. challenging evidence
- If supporting list is significantly longer, ask Claude whether that reflects reality or confirmation bias

### 5. Market research
- Build TAM/SAM/SOM models from public data; pressure-test assumptions
- Synthesize competitor reviews to identify unresolved complaints
- Identify 3 external trends (regulatory, technological, demographic) and assess tailwind vs. headwind

### 6. Solution concept validation
- Present solution to Claude; ask it to identify the 3 assumptions your design depends on most heavily
- Ask what would have to be true for each assumption to hold, and consequences if it doesn't
- Build a lightweight prototype with Claude Code — define the **single core interaction** and build only that
