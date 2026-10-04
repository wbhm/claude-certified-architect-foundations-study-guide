# Exam overview

## What the credential tests

The exam tests whether you can **choose the right architecture for a production Claude system**, not whether you can recite API field names. Almost every question is a scenario: something is failing in production; four fixes are offered; three look reasonable.

You are expected to have roughly six months of hands-on work with Claude APIs, the Agent SDK, Claude Code, and MCP.

## Format

Source: the official Exam Guide v1.0 (July 2026) — download it from the certification page on the Anthropic Partner Academy. It is the authoritative reference.

- Exam code **CCAR-F**
- 60 items, 120 minutes (~2 minutes per item)
- **Multiple-choice and multiple-response items** — each item states how many responses to select. Read the stem for "select TWO" before answering
- Distractors are options a candidate with incomplete knowledge would choose
- Closed book, no AI assistance; proctored online or at a Pearson VUE test centre
- 4 of 6 production scenarios selected at random for your sitting
- Scaled score 100–1,000; pass at **720**. The score report adds percent-correct by domain (informational only — pass/fail is the total scaled score)
- Unanswered questions score as incorrect — guess rather than skip
- Fee **$125 USD** (partner-tier discounts apply at checkout). Cancel or reschedule up to 24 hours before; later changes forfeit the fee
- Retakes: wait 14 days after the first fail, 30 after the second, 90 after the third; at most 4 attempts in a rolling 12 months
- Credential valid **12 months**. On-time renewal is a free, non-proctored assessment on the Partner Academy; a lapsed credential means retaking the full exam

## The six scenarios

Questions are framed inside these production contexts. Details in [scenarios.md](scenarios.md).

1. Customer Support Resolution Agent
2. Code Generation with Claude Code
3. Multi-Agent Research System
4. Developer Productivity with Claude
5. Claude Code for CI/CD
6. Structured Data Extraction

Domain 1 appears most heavily in **1, 3, and 4**.

## In scope vs out of scope

**In scope:** agentic loops, hub-and-spoke, hooks, CLAUDE.md, MCP, tool descriptions, structured errors, plan mode, CI `-p` mode, few-shot, `tool_use` + JSON Schema, Message Batches API, case-facts blocks, escalation, provenance.

**Out of scope** (the guide's explicit list): fine-tuning or training custom models; API authentication, billing, account management; detailed language/framework implementation; deploying or hosting MCP servers; Claude's internal architecture or training; Constitutional AI, RLHF, safety training; embedding models and vector-database internals; **computer use**; **vision / image analysis**; **streaming** and server-sent events; rate limits, quotas, pricing calculations; OAuth, key rotation, auth protocols; **cloud-provider configuration** (AWS, GCP, Azure); benchmarking and model comparisons; **prompt caching implementation** (beyond knowing it exists); token counting and tokenization.

Consequence for the Academy courses: the Bedrock and Google Cloud courses, and course C's computer-use, vision, streaming and caching lessons, feed nothing on this exam.

## Core technologies named on the blueprint

Claude Agent SDK · MCP · Claude Code · Messages API · Message Batches API · JSON Schema · Pydantic · CLAUDE.md · built-in tools (Read, Write, Edit, Bash, Grep, Glob)
