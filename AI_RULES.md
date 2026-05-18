# AI Rules

## Purpose

These rules keep AI work precise, safe, and within scope.

## Core Rules

- Read the relevant files before editing.
- Make small, focused changes.
- Do not modify unrelated files.
- Do not add dependencies unless clearly necessary.
- Do not rewrite working code without a strong reason.
- Preserve existing architecture and patterns.
- Ask for clarification only when the task is ambiguous.

## Before Coding

1. Read `PROJECT_CONTEXT.md` and `ROADMAP.md`.
2. Inspect the relevant source files.
3. Identify which files need to change.
4. Explain the plan briefly.
5. Mention risks if the task touches architecture, database, auth, API logic, build config, security, or performance.

## After Coding

Summarize:

1. What changed.
2. Why it changed.
3. Which files were modified.
4. How to test.
5. Risks, limitations, or tradeoffs.

## Forbidden Unless Requested

- Restructure the entire project.
- Rewrite large parts of the codebase.
- Add new libraries.
- Change frameworks or databases.
- Add authentication.
- Change build configuration.
- Introduce global state management.
- Redesign major UI flows.

## Dependency Rule

Before adding a dependency, explain why it is needed, alternatives, and tradeoffs. If the benefit is small, do not add it.