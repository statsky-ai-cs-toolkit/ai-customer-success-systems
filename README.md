# AI-Powered Churn Detection System

This is a practical, LLM-driven churn detection system designed for Customer Success teams operating at scale.

This is not a traditional health score.

It is a signal-based system that uses AI to:
- analyze customer behavior
- identify risk patterns
- classify accounts by churn likelihood
- prioritize where teams should focus

---

## The Problem

Traditional churn detection relies on:
- static health scores
- lagging indicators
- manual review

This leads to:
- late detection
- reactive workflows
- missed opportunities to intervene early

---

## The Approach

This system is built on four components:

1. Signals (inputs)
2. Context (account understanding)
3. AI classification
4. Output (prioritized risk)

---

## How It Works

1. Collect account-level signals
2. Format them into structured input
3. Pass them into an LLM (ChatGPT or Claude)
4. Use a structured prompt to classify risk
5. Output prioritized accounts + reasoning

---

## Who This Is For

- Customer Success teams
- Lifecycle / Growth teams
- RevOps teams
- Anyone managing large customer bases

---

## What This Is Not

- Not production code
- Not tied to any specific company
- Not using proprietary data

This is a reusable system design that can be adapted to any environment.

---

## Files in This System

- signals.md → defines inputs
- sample-prompts.md → ready-to-use prompts
- example-input.json → sample account data
- example-output.md → expected output format
