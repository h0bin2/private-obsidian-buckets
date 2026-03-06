## Skills
A skill is a set of local instructions to follow that is stored in a `SKILL.md` file. Below is the list of skills that can be used.

### Available skills
- write-skill: Apply Obsidian writing rules for this project and enforce paper filenames in `PAPER_YYYY.MM.DD_title.md` format. Use for writing, editing, renaming, and standardizing markdown documents. (file: C:/docs/hb.ham/.codex/skills/write-skill/SKILL.md)

### How to use skills
- Discovery: Use the list above as the available skills in this project.
- Trigger rules: If the user names a skill (with `$SkillName` or plain text) OR the task clearly matches a skill description above, use that skill for that turn.
- Missing/blocked: If a named skill cannot be read, state that briefly and continue with the best fallback.
- Progressive disclosure:
  1) Open the skill `SKILL.md` and read only what is needed.
  2) Resolve relative paths from the skill directory first.
  3) Load extra files only when needed.
