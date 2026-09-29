# Fork notes

This is a fork of **[karpathy/llm-council](https://github.com/karpathy/llm-council)**. The idea, the three-stage design (first opinions, anonymized peer review, chairman synthesis) and all original code are Andrej Karpathy's. Upstream has not published a license, so this fork adds none and is kept for reference and personal experimentation only.

## Why I keep this fork

A council-of-models pattern is directly useful for GTM research tasks where a single model's answer is not enough (ICP definition, messaging critique). I use it as a reference implementation for anonymized cross-review.

## What is different from upstream

| Change | Type | Why |
|---|---|---|
| `.env.example` added | Small improvement | The README tells you to hand-create `.env` with `OPENROUTER_API_KEY`; a checked-in example makes setup copy-paste and documents the only required variable |
| `FORK_NOTES.md` + README pointer | Docs | Attribution |

No changes to backend, frontend or council logic.

## Upstream

- Repo: https://github.com/karpathy/llm-council
