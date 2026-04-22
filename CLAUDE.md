# CLAUDE.md

This is a BOAT repository. BOAT stands for Blocks of Atomic Thought. Its purpose is to give context and abilities to agentic models like you.

## Core directories

| Directory | Short name | Purpose |
|---|---|---|
| `ways-of-working/` | wow | How to behave. Reusable abilities and working patterns. |
| `context-wayfinding/` | cow | What is known. Orientation, state, and cached data. |
| `efforts/` | — | In-progress work tracking across sessions. |
| `wisps/` | — | Incomplete or speculative thoughts. Read only outside active work. |
| `threads/` | — | Connected chains of reasoning or conversation. |

## File naming

- Lowercase filename — draft or in-progress block.
- Capitalized filename — ready to export to main.
- FULL CAPS subdirectory — phase of critical importance (e.g. CHURN, BURN).

## Each session

Read the `index.md` in any directory before working inside it. It explains the files and how to work there.

### CHURN (active work)

Before executing any non-trivial task:

1. Read `ways-of-working/CHURN/index.md` and its blocks.
2. Check `context-wayfinding/` for relevant existing context or cached data.
3. Open or update an effort file in `efforts/`.
4. Do not read `wisps/` during this phase.

### BURN (after completing work)

After every non-trivial task:

1. Evaluate against the user's goals and any goals listed here or in `goals/`.
2. Route insights: incomplete thought → `wisps/`, solid ability → `ways-of-working/`, context update → `context-wayfinding/`.
3. Read `ways-of-working/BURN/index.md` for the full process.

## Goals

- Build a system that makes agentic models more effective over time through accumulated, validated blocks of thought.
- Keep blocks atomic. One idea per file.
- Let wisps graduate to wows only when the idea is complete enough to act on reliably.
