---
name: write-skill
description: 작성 목적을 분류하고 목적별 참조 문서를 선택해 Obsidian Markdown 문서 작성 규칙을 적용한다. 논문, PRD, 요약, 인수인계, 캔버스(시스템 아키텍처), 일반 문서 작성/수정 작업에서 사용한다.
---

# Write Skill

## 역할
- 이 파일은 목적 라우팅만 담당한다.
- 실제 작성 규칙은 `references/*.md`에서만 읽는다.

## 목적 라우팅
1. 문서 작성 목적을 분류한다.
2. 아래 매핑에서 참조 파일 1개를 선택한다.
3. 선택한 참조 파일 규칙으로 문서를 작성 또는 수정한다.

## 참조 매핑
- `paper` -> `references/paper.md`
- `prd` -> `references/prd.md`
- `summary` -> `references/summary.md`
- `handover` -> `references/handover.md`
- `canvas` -> `references/canvas.md`
- 목적이 불명확하거나 혼합됨 -> `references/general.md`

## 공통 저장 경로 규칙
- `prd` 또는 `canvas` 목적 문서는 아래 경로에 저장한다.
- 경로 형식: `PROJECT/<순번_프로젝트명>/docs/`

## 공통 체크
- 목적 분류가 정확한가?
- 참조 파일을 1개만 선택했는가?
- 목적이 `prd`/`canvas`라면 `PROJECT/<순번_프로젝트명>/docs/` 경로를 지켰는가?
- 날짜 표기가 `YYYY.MM.DD`로 통일되었는가?