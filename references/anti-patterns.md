# Anti-Patterns Summary

Common mistakes at each stage and how to avoid them.

| Anti-Pattern | Stage | Fix |
|--------------|-------|-----|
| **Building before validating** | Idea | Conversations are evidence; prototypes are props. A working prototype proves you can build, not that anyone wants it. |
| **Confirmation bias with AI** | Idea | Ask AI to argue **against** your idea and find disconfirming evidence. AI will validate what you believe; you must actively seek counterarguments. |
| **No architecture docs** | MVP | Write CLAUDE.md before first line of code. Without guardrails, each AI session re-derives foundations from scratch and decisions drift. |
| **No scope boundaries** | MVP | Written scope: what it does, what it doesn't do, and the specific user evidence needed to justify additions. |
| **Skipping security review** | MVP/Launch | Review auth, data exposure, input validation, dependency vulnerabilities before any user touches the product. |
| **Tracking metrics post-launch** | Launch | Define framework, benchmarks, and false positive definitions **before** launch. Otherwise you optimize for flattering noise. |
| **Founder as bottleneck** | Launch/Scale | Audit everything you personally handle. Categorize: automate, delegate, or keep. Build systems that replace founder attention. |
| **Expanding too early** | Launch | Protect core PMF before entering new markets. New markets introduce new variables and you lose data interpretability. |
| **Organic growth ceiling** | Scale | Build dedicated GTM function before flattening curves. Founder-led selling has a ceiling. |
| **Handing off too fast** | Scale | Codify institutional knowledge before delegating. Critical decisions made without founder context create invisible failure modes. |
