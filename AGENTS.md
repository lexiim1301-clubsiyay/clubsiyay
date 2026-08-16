# AGENTS.md

## Purpose
This file defines the default working rules for AI coding agents operating in this repository.

## General rules
- Read the repository structure and existing documentation before making changes.
- Keep changes focused on the requested task; avoid unrelated refactors.
- Preserve existing conventions, architecture, naming, and formatting unless the task explicitly requires changing them.
- Prefer small, reviewable changes over broad rewrites.
- Do not delete or overwrite user work without a clear reason.
- Do not introduce secrets, credentials, tokens, or private data into the repository.

## Before editing
- Inspect relevant files and identify the smallest set of files that needs to change.
- Check for local instructions in nested `AGENTS.md` files; more specific instructions take precedence for their subtree.
- Identify available tests, linters, formatters, and build commands before changing code.

## Implementation
- Write clear, maintainable code.
- Follow the project's established style and dependency choices.
- Avoid adding dependencies unless they are necessary for the task.
- Keep public APIs backward compatible unless a breaking change is explicitly requested.
- Add or update comments only where they explain non-obvious behavior.

## Validation
- Run the most relevant tests after making changes.
- Run formatting, linting, and type checks when the repository provides them.
- If validation cannot be run, state exactly what was not run and why.
- Never claim tests passed unless they were actually executed successfully.

## Git hygiene
- Keep commits scoped and descriptive.
- Do not rewrite shared history or force-push unless explicitly requested.
- Do not commit generated files, build outputs, caches, or local environment files unless the project intentionally tracks them.

## Communication
When reporting completed work, summarize:
1. what changed;
2. which files changed;
3. what validation was run;
4. any remaining risks, assumptions, or follow-up work.
