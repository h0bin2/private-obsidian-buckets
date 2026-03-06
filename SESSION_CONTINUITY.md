# SESSION CONTINUITY

## 1) 세션 목적 (전역)
- 이 저장소는 Obsidian 문서를 AI로 작성/수정/구조화하고, Git으로 이력을 관리하는 운영 세션을 지속한다.
- 특정 프로젝트 하나가 아니라, Obsidian 전체 운영을 일관된 규칙으로 컨트롤한다.

## 2) 항상 유지할 운영 원칙
- 문서 작성/수정은 `write-skill` 목적 라우팅으로 처리한다.
- 논문 문서는 `paper/PAPER_YYYY.MM.DD_제목.md` 규칙을 따른다.
- PRD/아키텍처는 `PROJECT/<순번_프로젝트명>/docs/`에 저장한다.
- 인코딩은 `UTF-8 (BOM 없음)`을 사용한다.
- 커밋 메시지는 `Conventional Commits` + 한글 제목/본문 규칙을 따른다.
- 변경 후 즉시 `commit -> push`를 수행한다.

## 3) 현재 활성 컨텍스트
- 활성 프로젝트: `PROJECT/01_paper-crawling-ai-insights/`
- 핵심 문서:
  - `PROJECT/01_paper-crawling-ai-insights/docs/PRD.md`
  - `PROJECT/01_paper-crawling-ai-insights/docs/Architecture.canvas`
- 프로젝트 상세 연속성: `PROJECT/01_paper-crawling-ai-insights/docs/SESSION_CONTINUITY.md`

## 4) 다음 세션 시작 절차
1. 이 문서를 먼저 읽고 전역 운영 원칙을 확인한다.
2. `AGENTS.md`와 `write-skill` 라우팅 규칙(`.codex/skills/write-skill/SKILL.md`)을 확인한다.
3. 활성 프로젝트 문서 상태(PRD/Architecture/연속성 문서)를 점검한다.
4. 우선순위 1개를 선택해 작업 후 즉시 커밋/푸시한다.

## 5) 세션 종료 전 체크리스트
- 오늘 변경한 정책/경로/규칙이 문서에 반영됐는가?
- 깨진 인코딩/Canvas JSON 문제가 없는가?
- 다음 세션이 바로 시작할 수 있게 현재 상태와 다음 액션을 기록했는가?

## 6) 세션 로그 템플릿
- 날짜:
- 작업 범위:
- 변경 파일:
- 결정 사항:
- 다음 액션: