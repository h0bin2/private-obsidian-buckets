## Skills
A skill is a set of local instructions to follow that is stored in a `SKILL.md` file. Below is the list of skills that can be used.

### Available skills
- write-skill: 작성 목적별 참조 규칙을 적용해 Obsidian 문서를 작성/수정하고, 논문 문서 파일명을 `PAPER_YYYY.MM.DD_제목.md` 형식으로 강제한다. (file: C:/docs/hb.ham/.codex/skills/write-skill/SKILL.md)

### How to use skills
- Discovery: Use the list above as the available skills in this project.
- Trigger rules: If the user names a skill (with `$SkillName` or plain text) OR the task clearly matches a skill description above, use that skill for that turn.
- Missing/blocked: If a named skill cannot be read, state that briefly and continue with the best fallback.
- Progressive disclosure:
  1) Open the skill `SKILL.md` and read only what is needed.
  2) Resolve relative paths from the skill directory first.
  3) Load extra files only when needed.