# Context Vault

Context Vault is a minimal set of Markdown files that give AI coding agents stable context and clear boundaries.
It reduces repeated prompts, scope creep, random refactors, and misaligned changes.
Use it in any software project where you want AI to act with focus and precision.
The files are small, explicit, and meant to be filled with real project facts.

## Files

- `PROJECT_CONTEXT.md` — what the project is and what the AI must understand.
- `AI_RULES.md` — how the AI should work.
- `ROADMAP.md` — what is in scope right now.

## Usage

Ask your AI coding agent:

> Read `PROJECT_CONTEXT.md`, `AI_RULES.md`, and `ROADMAP.md` before coding. Then summarize the project in 5 bullets. Do not edit files yet.
