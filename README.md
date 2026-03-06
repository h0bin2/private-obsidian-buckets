# private-obsidian-buckets

논문 수집/요약/정리 워크플로우를 Obsidian + GitHub로 관리하는 개인 지식 운영 저장소입니다.

## 프로젝트 목적
- arXiv 등에서 논문 메타데이터를 수집한다.
- AI로 핵심 내용을 요약하고 근거를 정리한다.
- 규칙 기반 문서(`write-skill`)로 일관된 포맷을 유지한다.
- 모든 변경 이력을 Git으로 추적하고 즉시 원격 백업한다.

## 현재 진행 중인 프로젝트
- `PROJECT/01_paper-crawling-ai-insights/`

핵심 문서:
- `PROJECT/01_paper-crawling-ai-insights/docs/PRD.md`
- `PROJECT/01_paper-crawling-ai-insights/docs/Architecture.canvas`

## 문서 저장 규칙
- 논문 문서: `paper/PAPER_YYYY.MM.DD_제목.md`
- PRD/아키텍처: `PROJECT/<순번_프로젝트명>/docs/`
- 프로젝트 폴더: `PROJECT/<순번_프로젝트명>/` (예: `01_paper-crawling-ai-insights`)

## 스킬 운영 규칙
- 기본 스킬: `write-skill`
- 목적별 참조 문서(`references/*.md`)를 선택해 작성
  - `projects`, `paper`, `prd`, `canvas`, `summary`, `handover`, `general`

## 작업 루프
1. 수집: 논문 후보 수집 및 중복 제거
2. 요약: AI 요약 + 핵심 근거 정리
3. 문서화: `write-skill` 규칙으로 문서 생성/수정
4. 검토: 구조/근거/인코딩(UTF-8, BOM 없음) 점검
5. 반영: 커밋 후 즉시 푸시

## 커밋 메시지 규칙
- 국제 표준 `Conventional Commits`
- 형식: `<type>(<scope>): <subject>`
- 제목/본문은 한글 작성 (type/scope는 영문)
- 예시:
  - `feat(project): 신규 프로젝트 기본 문서 생성`
  - `docs(write-skill): references 규칙 업데이트`

## 인코딩 규칙
- `*.md`, `*.canvas`, `*.yaml`은 UTF-8(BOM 없음) 사용
- Canvas는 유효한 JSON 형식 유지

## 다음 세션 시작 위치`n- `SESSION_CONTINUITY.md` (전역 운영 세션 기준)`n- `PROJECT/01_paper-crawling-ai-insights/docs/SESSION_CONTINUITY.md` (프로젝트 상세 기준)`n