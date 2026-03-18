# 작업 이력

최근 순으로 기록합니다.

---

## [2026-03-18] user-inputs/ 사용자 제공 자료 저장소 설계

- **사용자 요청**: 사용자가 별도로 조사/작성한 원본 자료를 저장할 user-inputs/ 디렉토리 신규 설계 — 기존 Memory/Knowledge 2체계를 3체계로 확장
- **처리 방안**: 계획서 기반으로 8개 파일 작업 — user-inputs/ 디렉토리 구조 생성(index.md + customer-research/ + product-tech/), references/user-inputs-guide.md 신규 생성, CLAUDE.md 규칙 5번 삽입 및 기존 5~7번→6~8번 번호 변경 + 프로젝트 구조 추가, references/memory-system-guide.md와 knowledge-system-guide.md의 2체계 비교표를 3체계로 확장, MEMORY.md 프로젝트 현황 업데이트
- **결과**: 신규 생성 4개(index.md, user-inputs-guide.md, .gitkeep 2개), 수정 4개(CLAUDE.md, memory-system-guide.md, knowledge-system-guide.md, MEMORY.md)
- **특이점**: 작업 완료 후 메모리 업데이트를 누락하여 사용자 지적받음
- **배운점**: 구조 변경 작업도 예외 없이 작업 완료 = 메모리 업데이트 포함이다

## [2026-03-18] 메모리 시스템 개선: 사용자 피드백 반영

- **사용자 요청**: MEMORY.md 버전 필드 역할 중복 해소, task-log.md 형식 구체화, SPA 크롤링 이슈 할일 기록
- **처리 방안**: MEMORY.md `버전`→`최근 작업` 필드 변경 (최근 작업만 표시), task-log.md 5개 항목 구조로 전면 개편 + 최근 순 정렬, memory-system-guide.md 형식 업데이트, 피드백/교훈 기록
- **결과**: MEMORY.md, task-log.md, memory-system-guide.md, user-preferences.md, lessons-learned.md 5개 파일 수정 완료
- **특이점**: 없음
- **배운점**: 메모리 필드의 역할 중복을 주기적으로 점검해야 한다 — 시스템이 성장하면서 필드 간 역할이 겹칠 수 있다

## [2026-03-18] YC AI QA 스타트업 랜딩 페이지 리서치

- **사용자 요청**: 랜딩 페이지 초안 작성을 위한 사전 리서치 — YC 2025-2026 배치에서 AI QA/시뮬레이션 유사 스타트업 탐색 및 랜딩 페이지 분석
- **처리 방안**: startup-researcher subagent로 후보 발굴 → 사용자 확인 (10개 전수 조사 결정) → WebFetch로 10개 랜딩 페이지 크롤링/분석 → 패턴 도출 및 콕스웨이브 시사점 정리
- **결과**: knowledge/ai-startup-trends/yc-ai-qa-landing-page-analysis.md 신규 생성, knowledge index 업데이트 (topic 15→16)
- **특이점**: 4개 SPA 사이트(Kashikoi, Bluejay, Sentrial, Arga Labs) 크롤링 제한 → YC 프로필/HN/언론 보조 소스로 보완
- **배운점**: WebFetch는 Framer/Next.js RSC 기반 SPA의 콘텐츠 추출이 제한적 — 보조 소스 전략을 사전에 수립해야 한다

## [2026-03-18] service-context.md 보완: 핵심 포인트, 리스크 추가

- **사용자 요청**: service-context.md에 핵심 포인트와 리스크 정보 추가
- **처리 방안**: 사용자 공유 정보를 service-context.md에 반영 + 임의로 추가한 항목(경쟁 환경, 랜딩 페이지/Sales Deck 진행 현황) 삭제
- **결과**: service-context.md 보완 완료
- **특이점**: 사용자가 언급하지 않은 항목을 임의로 추가하여 지적받음
- **배운점**: 사용자가 직접 요청한 범위만 반영하고, 임의로 확장하지 않는다

## [2026-03-18] service-context.md 참조 체계 구축

- **사용자 요청**: service-context.md를 skill/subagent 실행 시 필수로 읽도록 참조 체계 구축
- **처리 방안**: 7개 파일 수정 — CLAUDE.md 규칙 3, 4개 skill 워크플로우 0단계, startup-researcher 공통 원칙, memory-system-guide 구조/역할
- **결과**: skill/subagent 실행 시 서비스 맥락 필수 읽기를 명시적으로 강제하는 체계 완성
- **특이점**: 없음
- **배운점**: 새 메모리 파일 추가 시 참조 체계 설계까지가 완료 기준이다

## [2026-03-17] MEMORY.md 피드백 반영

- **사용자 요청**: MEMORY.md의 "다음 세션 할 일" 및 버전 필드 수정
- **처리 방안**: 사용자 피드백 2건(후속 약속 미기록, 버전 미갱신) 반영
- **결과**: MEMORY.md 수정 완료
- **특이점**: 없음
- **배운점**: 사용자 발언 중 "다음에 ~하겠다"는 의도를 놓치지 않고 "다음 세션 할 일"에 기록해야 한다

## [2026-03-17] service-context.md 생성

- **사용자 요청**: 콕스웨이브 AI 서비스 QA 자동화 서비스 맥락 정리
- **처리 방안**: 사용자 제공 정보를 기반으로 service-context.md 생성 (회사 정보, 고객 문제 가설 3개, 솔루션 가설, 현재 단계)
- **결과**: service-context.md 생성 완료, MEMORY.md에 참조 링크 추가
- **특이점**: 없음
- **배운점**: 파일 생성 후 참조 체계(누가, 언제, 어디서 읽는지)까지 설계해야 한다
