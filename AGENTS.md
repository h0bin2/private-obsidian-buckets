## Skills
스킬은 `SKILL.md` 파일에 저장된 로컬 작업 지침입니다. 아래 목록은 이 프로젝트에서 사용할 수 있는 스킬입니다.

### Available skills
- write-skill: 작성 목적별 참조 규칙을 적용해 Obsidian 문서를 작성/수정하고, 논문 문서 파일명을 `PAPER_YYYY.MM.DD_제목.md` 형식으로 강제한다. 논문, PRD, 요약, 인수인계, 캔버스(시스템 아키텍처) 작성에 사용한다. (file: C:/docs/hb.ham/.codex/skills/write-skill/SKILL.md)

### How to use skills
- Discovery: 위 목록을 이 프로젝트의 사용 가능 스킬로 간주한다.
- Trigger rules: 사용자가 스킬 이름(`$SkillName` 또는 일반 텍스트)을 명시했거나, 요청이 위 설명과 명확히 일치하면 해당 턴에서 그 스킬을 사용한다.
- Missing/blocked: 명시된 스킬을 읽을 수 없으면 짧게 알리고 가능한 최선의 대체 방식으로 진행한다.
- Progressive disclosure:
  1) 스킬 사용이 결정되면 `SKILL.md`를 열고 필요한 만큼만 읽는다.
  2) 상대 경로는 먼저 해당 스킬 디렉터리 기준으로 해석한다.
  3) 추가 파일은 필요한 경우에만 읽는다.