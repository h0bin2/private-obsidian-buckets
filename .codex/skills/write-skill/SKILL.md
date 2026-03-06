---
name: write-skill
description: Apply writing rules for Obsidian markdown documents by selecting purpose-specific references. Use when writing or revising paper, PRD, summary, handover, or general docs. Always enforce PAPER_YYYY.MM.DD_title.md naming for paper documents.
---

# Write Skill

## Purpose Routing
1. Identify the writing purpose first.
2. Load only the matching reference file from `references/`.
3. Follow that reference strictly while writing or revising.
4. If purpose is `paper`, enforce filename `PAPER_YYYY.MM.DD_title.md`.
5. Run the common checklist before finalizing.

## Reference Selection
- `paper` -> `references/paper.md`
- `prd` -> `references/prd.md`
- `summary` -> `references/summary.md`
- `handover` -> `references/handover.md`
- Unknown or mixed purpose -> `references/general.md`

## Common Rules
- Keep exactly one H1 at the first line.
- Normalize dates to `YYYY.MM.DD`.
- Keep sections explicit and avoid mixing decisions with raw notes.
- Remove forbidden filename characters: `\\ / : * ? " < > |`.

## Paper Filename Rule
- Paper docs must use `PAPER_YYYY.MM.DD_title.md`.
- Use zero-padded month/day (example: `2026.03.06`).
- Keep `title` concise and topic-focused.

## Checklist
- Is the purpose correctly classified?
- Is the correct file from `references/` used?
- If paper, does filename follow `PAPER_YYYY.MM.DD_title.md`?
- Are title, structure, and date format compliant?
