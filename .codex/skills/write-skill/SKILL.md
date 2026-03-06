---
name: write-skill
description: 작성 목적에 맞는 참조 문서를 선택해 Obsidian Markdown 문서 작성 규칙을 적용한다. 논문, PRD, 요약, 인수인계, 일반 문서 작성/수정 시 사용하며 논문 문서는 PAPER_YYYY.MM.DD_제목.md 파일명을 강제한다.
---

# Write Skill

## 목적 라우팅
1. 먼저 문서 작성 목적을 분류한다.
2. `references/`에서 목적에 맞는 파일 하나만 읽는다.
3. 해당 참조 규칙대로 문서를 작성 또는 수정한다.
4. 목적이 `paper`이면 파일명을 `PAPER_YYYY.MM.DD_제목.md`로 강제한다.
5. 최종 저장 전에 공통 체크리스트를 점검한다.

## 참조 선택
- `paper` -> `references/paper.md`
- `prd` -> `references/prd.md`
- `summary` -> `references/summary.md`
- `handover` -> `references/handover.md`
- 목적이 불명확하거나 혼합됨 -> `references/general.md`

## 공통 규칙
- 첫 줄에 H1 제목을 1개만 둔다.
- 날짜 표기는 `YYYY.MM.DD`로 통일한다.
- 결정사항과 메모/초안을 혼합하지 않는다.
- 파일명 금지 문자 `\\ / : * ? " < > |` 는 제거한다.

## 논문 파일명 규칙
- 논문 문서는 반드시 `PAPER_YYYY.MM.DD_제목.md`를 사용한다.
- 월/일은 2자리 0패딩을 사용한다. (예: `2026.03.06`)
- `제목`은 핵심 키워드 중심으로 짧고 명확하게 작성한다.

## 체크리스트
- 작성 목적 분류가 정확한가?
- 목적에 맞는 `references/*.md`를 선택했는가?
- 논문 문서면 `PAPER_YYYY.MM.DD_제목.md` 형식을 지켰는가?
- 제목, 섹션 구조, 날짜 표기가 규칙에 맞는가?