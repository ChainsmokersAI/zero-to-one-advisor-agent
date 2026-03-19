# 작업 이력

최근 순으로 기록합니다.

---

## [2026-03-19] context 파일 규칙 일반화 (READ+WRITE-BACK + READ 트리거 보편화)

- **사용자 요청**: (1) service-context.md에 WRITE-BACK 규칙이 없어 확인된 사실 미반영 문제 해결 + 확장성 설계 (2) context 파일 READ 트리거를 "skill/subagent 실행 전" → "모든 작업 시작 전"으로 보편화하여 규칙 3, 4, 5 간 일관성 확보
- **처리 방안**: (1) "context 파일" 일반 개념 도입 — CLAUDE.md READ 일반화 + WRITE-BACK 추가, 4개 SKILL Step 0 일반화, memory-system-guide.md에 context 파일 정의/목록 신설 (2) CLAUDE.md context 파일 READ 규칙에 "[사전 확인]" 태그 + "모든 작업 시작 전" 트리거 적용, memory-system-guide.md READ 항목도 동일하게 보편화
- **결과**: 10개 파일 수정(READ+WRITE-BACK) + 5개 파일 수정(READ 트리거 보편화). CLAUDE.md 규칙 3(context), 4(Knowledge), 5(User Inputs)의 사전 확인 트리거가 동일 패턴으로 통일
- **특이점**: 사용자가 확장성 관점 피드백 → 일반 개념 재설계. READ 트리거가 좁게 설정되어 일반 질문에서 context 미참조 문제 발견 → 보편화
- **배운점**: (1) 규칙 설계 시 확장성 고려 필수 (2) 유사 규칙의 트리거 조건은 일관되게 설정해야 한다 — 좁은 트리거는 예외 상황을 만든다

## [2026-03-18] 랜딩 페이지 전략 Phase 1-2 완료 — landing-page-draft.md 생성

- **사용자 요청**: 콕스웨이브 Align 랜딩 페이지 전략 기획 — 9개 섹션 구조 논의 → 확정(5섹션+Bridge) → 섹션별 상세 카피/레퍼런스/디자인 작성
- **처리 방안**: 계획서 기반으로 Phase 1(구조 논의) 실행 — 사용자 피드백으로 9개→5+Bridge로 축소 → Phase 2(섹션별 상세) 실행 — 매 섹션 작성 후 사용자 리뷰/피드백 반영 → 최종 정리 및 파일명 변경
- **결과**: `landing-page-draft.md` 최종 산출물 생성. 5개 섹션(Hero, How It Works, Key Capabilities, FAQ, Final CTA) + 1개 Bridge(Problem Bridge). 전략적 방향 3가지(Problem-First, Dual CTA, Trust Bar 미적용) 확정. Dual CTA 플랫폼(Tally + Cal.com) 및 Early Access 폼 항목까지 설계
- **특이점**:
  - Phase 1에서 사용자 논의를 통해 9개 섹션을 5+Bridge로 대폭 축소 — Trust Bar, Visual Proof(별도), Who It's For, What Align Catches 제거
  - Key Capabilities 카드 내용을 사용자가 기능 중심 → 고객 가치 중심으로 전면 교체 지시
  - "Hyper-Realistic" vs "Real-World" 표현 논의 → Hyper-Realistic 채택, Real-World는 대안으로 기록
  - What Align Catches 섹션이 기존 섹션과 중복된다는 사용자 피드백으로 FAQ로 교체
- **배운점**:
  - 초안을 과하게 제시하고(9개) 사용자와 깎아나가는 방식이 효과적 — 없는 것을 추가하는 것보다 있는 것을 제거하는 것이 논의가 쉬움
  - 카피 옵션 제시 시 2-3개 대안 + trade-off 분석이 사용자 의사결정을 돕는다
  - 기존 마케팅 자료(브로셔)가 카피의 최고 소재 — 이미 검증된 문구를 재활용하는 것이 새로 쓰는 것보다 효율적이고 브랜드 일관성도 유지

## [2026-03-18] 랜딩 페이지 전략 Phase 1 — 9개 섹션 구조 초안 작성

- **사용자 요청**: 콕스웨이브 Align 랜딩 페이지 전략 기획 — Phase 1(구조 논의 및 확정) 실행
- **처리 방안**: 계획서 기반으로 전체 참조 자료 읽기(MEMORY.md, service-context.md, knowledge, user-inputs 4건, 브로셔 PDF, 이전 중간 산출물) → 9개 섹션 구조 초안 작성 → `landing-page-strategy-a.md` 교체
- **결과**: 9개 섹션(Hero, Trust Bar, Problem, How It Works, Key Capabilities, Visual Proof, Who It's For, FAQ, Final CTA) 구조 + 전략적 방향(Problem-First, Dual CTA, Trust 전략) + 각 섹션별 목적/서사적 역할/벤치마크/구성요소 초안 완료
- **특이점**: 이전 세션의 중간 산출물(Hero, Problem Bridge, How It Works, What We Offer 3개 섹션)을 참조하되, 9개 섹션 구조로 전면 재설계. Trust Bar, Visual Proof, Who It's For, FAQ, Final CTA 5개 섹션 신규 추가
- **배운점**: —

## [2026-03-18] 사용자 자료 3건 user-inputs 등록

- **사용자 요청**: 프로젝트 root에 업로드된 3개 파일(YC AI 스타트업 랜딩 페이지 분석 2편 + MWC Align 브로셔)을 user-inputs 시스템에 등록
- **처리 방안**: 계획서 기반으로 파일 3개를 분류 디렉토리로 이동(customer-research/ 2건, product-tech/ 1건), index.md 테이블에 3건 추가, 메모리 업데이트
- **결과**: user-inputs/index.md에 3건 등록 완료, root에서 파일 제거 완료
- **특이점**: 계획 단계에서 메모리 업데이트를 실행 단계에 포함시킨 첫 사례 — 이전 세션에서 반복된 메모리 업데이트 누락 방지
- **배운점**: 작업 계획 시 메모리 업데이트를 명시적 실행 단계로 포함시키면 누락을 방지할 수 있다

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
