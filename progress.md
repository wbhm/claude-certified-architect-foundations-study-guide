# Progress tracker

> **Blank template.** Starting your own journey? Copy this file over the tracker: `cp progress.template.md progress.md` — then tick as you go. Full instructions in [docs/getting-started.md](docs/getting-started.md).

Follow **[docs/roadmap.md](docs/roadmap.md)** for what to do next; it maps onto the numbered steps in **[docs/study-steps.md](docs/study-steps.md)**. Tick here as you complete each step.

## Phase 0 — Orientation

- [x] 1. Register on Anthropic Academy
- [x] 2. Read `docs/exam-overview.md`
- [x] 3. Read `docs/exam-strategy.md`
- [x] 4. Read `docs/scenarios.md`
- [x] 5. Read `cheatsheets/decision-rules.md`

Official practice exam score: n/a — no official practice exam exists (retired at the 30 Jun 2026 Pearson move; the exam guide PDF has sample questions instead)  
Mock exam (60 items, 4 random scenarios, untimed): **55 / 60 (92%)** — 4 Oct 2026. D1 14/16 · D2 9/11 · D3 11/12 · D4 12/12 · D5 9/9; 8/8 select-TWO. Misses (Q4 1.2, Q21 1.7, Q23 2.1, Q32 3.1, Q42 2.5) logged OPEN in `progress/weak-spots.md`  
Exam date: 9 Oct 2026

## Official Academy courses

Source: Anthropic Academy → Prepare for this exam. Details: [docs/academy-courses.md](docs/academy-courses.md).

- [x] A. AI Fluency: Framework & Foundations (100) — optional if already fluent
- [x] B. Claude 101 (100)
- [x] C. Building with the Claude API (100–200) — start alongside Phase 1
- [x] D. Claude with Amazon Bedrock (100–200) — only if you use Bedrock
- [x] E. Claude on Google Cloud (100–200) — only if you use GCP
- [x] F. Introduction to Model Context Protocol (200)
- [x] G. Claude Code in Action (200)
- [x] Claude Platform 101 — not in the original A–G list; completed
- [x] Claude Code 101 — not in the original A–G list; completed
- [x] Introduction to agent skills — not in the original A–G list; completed 14 Aug 2026 (partner portal)
- [x] Model Context Protocol: Advanced Topics — not in the original A–G list; completed 20 Sep 2026 (partner portal)

## Phase 1 — Domain 1 (27%)

- [x] 6. 1.1 Agentic loops + premature-stop answers — 25 Sep 2026
- [x] 7. 1.2 Multi-agent orchestration — 25 Sep 2026
- [x] 8. 1.3 Subagent invocation — 25 Sep 2026
- [x] 9. 1.4 Workflow enforcement — 25 Sep 2026
- [x] 10. 1.5 SDK hooks — 25 Sep 2026
- [x] 11. 1.6 Task decomposition — 25 Sep 2026
- [x] 12. 1.7 Session state — 25 Sep 2026
- [x] 13. Domain 1 practice: 9 / 10 (target 8+) — 26 Sep 2026
- [x] 14. Exercise 1 — support agent with real loop (`docs/exercises.md`) — 26 Sep 2026

## Phase 2 — Domain 2 then Domain 5

- [x] 15. Domain 2 files 2.1–2.5 — 26 Sep 2026
- [x] 16. Domain 2 practice: 6 / 7 (target 6+) — 26 Sep 2026, then exercise 5 (`docs/exercises.md`) — 26 Sep 2026
- [x] 17. Domain 5 files 5.1–5.6 — 26 Sep 2026
- [x] 18. Domain 5 practice: 6 / 6 (target 5+) — 26 Sep 2026
- [x] 19. Exercise 1 hardened (structured errors, gate, handoff) **or** exercise 4 started — 26 Sep 2026 (exercise 1 hardened; exercise 4 started)

## Phase 3 — Domain 3 then Domain 4

- [x] 20. Domain 3 files 3.1–3.6 — 27 Sep 2026
- [x] 21. Domain 3 practice: 8 / 8 (target 7+) — 27 Sep 2026
- [x] 22. Exercise 2 — Claude Code team workflow (`docs/exercises.md`) — 27 Sep 2026 (guided audit of the repo's artefacts, 5 / 6 audit questions; `-p` hang proved live: no `-p` + TTY → exit 124 after 20 s, `-p` → exit 0)
- [x] 23. Domain 4 files 4.1–4.6 — 27 Sep 2026
- [x] 24. Domain 4 practice: 8 / 8 (target 7+) — 27 Sep 2026
- [x] 25. Exercise 3 — extraction pipeline (`docs/exercises.md`) — 27 Sep 2026 (built in `../exercises/ex3-extraction-pipeline/`: prompt-only JSON 10/10 parse failures vs 0/20 with `tool_use`; required `po_number` → string `'null'` 3/3; absent PO stops at needs_human; few-shot 73/80 → 73/80 (layout) → 80/80 (boundary examples); field-level retry run live via injected failure. Batches (optional) not done)

## Phase 4 — Lock together

- [x] 26. Exercise 4 finished (research pipeline) — 26 Sep 2026
- [x] 27. Decision rules from memory — 27–28 Sep 2026 (multiple-choice drill, one item per row: 73 / 75; misses 4.10 interacting fixes → one message, 4.19 `--continue` for last session — both in weak-spots)
- [x] 28. Mixed set: 12 / 12 (target 10+) — 29 Sep 2026
- [x] 29. Official Academy practice exam — N/A, confirmed 4 Oct 2026: none exists. Substitute: sample questions in the official Exam Guide PDF (anthropic-partners.skilljar.com CCA-F page)
- [x] 30. Re-read missed task files only — 4 Oct 2026: 3 / 3 VERIFY rows passed cold (1.7, 3.3, 3.5); ledger fully CLOSED, no re-reads needed. — driven by your `progress/weak-spots.md` ledger (local, gitignored — create it from [progress/weak-spots-template.md](progress/weak-spots-template.md)): every OPEN/QUEUED/VERIFY row gets one cold item; a fail sends you to the task file named in the row

## Scenario check (after phase 4, or as you hit them)

- [ ] Customer support agent
- [ ] Code generation with Claude Code
- [ ] Multi-agent research
- [ ] Developer productivity
- [ ] CI/CD
- [ ] Structured extraction
