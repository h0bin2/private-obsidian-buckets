# SESSION CONTINUITY - paper-crawling-ai-insights

## 1) 현재 상태 요약
- 프로젝트명: `paper-crawling-ai-insights`
- 목적: 논문 수집 -> AI 요약 -> 규칙 기반 문서화 파이프라인 구축
- 활성 스킬: `write-skill` (projects/paper/prd/canvas 등 목적 라우팅)

## 2) 현재 구조
- 프로젝트 루트: `PROJECT/01_paper-crawling-ai-insights/`
- 문서 폴더: `PROJECT/01_paper-crawling-ai-insights/docs/`
- 핵심 파일:
  - `PRD.md`
  - `Architecture.canvas`
- 논문 폴더: `paper/`

## 3) 완료된 작업
- 프로젝트 초기 PRD 작성
- 아키텍처 캔버스(Obsidian Canvas JSON) 작성
- `write-skill`에 projects 목적 및 인코딩 안전 규칙 반영
- 저장 경로/파일명 규칙 정립

## 4) 다음 세션 우선 작업
1. arXiv 수집 스펙 확정
- 검색 조건(카테고리/기간/정렬) 정의
- 중복 제거 키(title+year+source) 확정

2. 수집 결과 문서화 자동화 초안
- 수집 결과를 `paper/PAPER_YYYY.MM.DD_제목.md`로 생성하는 흐름 정의
- 필수 섹션(요약/핵심 근거/적용 메모) 채우기 기준 확정

3. 품질 게이트 정의
- 근거 링크 누락 여부 체크
- 한글 깨짐/인코딩 체크(UTF-8, BOM 없음)
- Canvas JSON 유효성 체크

## 5) 운영 체크리스트
- 문서 저장 경로가 규칙에 맞는가?
- 파일명이 규칙에 맞는가?
- 날짜 표기가 `YYYY.MM.DD`인가?
- 커밋 메시지가 `Conventional Commits` + 한글 규칙을 따르는가?
- 커밋 후 즉시 `git push` 했는가?

## 6) 의사결정 로그 템플릿
- 날짜:
- 이슈:
- 선택안:
- 결정 이유:
- 후속 작업:

## 7) 세션 종료 시 기록 규칙
- 이 문서에 "완료/진행중/다음 액션"을 업데이트한다.
- 주요 정책 변경 시 `README.md`, `write-skill references`를 함께 갱신한다.