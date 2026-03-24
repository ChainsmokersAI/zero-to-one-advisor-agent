# 작업 이력

최근 순으로 기록합니다.

---

## [2026-03-24] Sales Deck 3건 실물 슬라이드별 상세 분석

- **사용자 요청**: 업로드한 Sales Deck PDF 3건(Zuora 20장, PlaytestCloud 16장, Linear 8장)을 상세 분석. Zuora는 Andy Raskin Strategic Narrative 관점, PlaytestCloud는 Coxwave 비교 포함
- **처리 방안**: startup-researcher subagent로 Andy Raskin 원문 분석 2차 출처 수집(LinkedIn 미러, BrandGym, Zuora 공식, Ink Narrates 등) → PDF 실물 슬라이드별 분석(Zuora 5단계 매핑, PlaytestCloud 전략 패턴 + Coxwave 비교, Linear Problem-Solution 구조) → 3개 Deck 비교 종합 + Coxwave 적용 시사점 도출 → knowledge/sales-deck-framework.md 업데이트(원문 인용, 프레임워크 진화 테이블, 후속 글 목록, 복사 금지 주의사항)
- **결과**: outputs/sales-deck-analysis-zuora-playtestcloud-linear.md 신규 생성, knowledge/sales-deck-framework.md 업데이트, outputs/index.md 갱신
- **특이점**: Zuora 원문 Medium 기사 403 접근 불가 → LinkedIn 미러 및 2차 출처로 보완. Coxwave 적용 시사점으로 "Linear식 Problem-Solution + PlaytestCloud의 워크플로우 패턴 + Zuora의 서사 프레이밍 축약"의 하이브리드 접근 권장
- **배운점**: —

## [2026-03-24] outputs/ 산출물 폴더 신설

- **사용자 요청**: 작업 산출물을 저장할 별도 폴더 생성
- **처리 방안**: `outputs/` 디렉토리 + `index.md` 생성 → `landing-page-draft.md`를 root에서 `outputs/`로 이동 → CLAUDE.md 프로젝트 구조 섹션에 항목 추가 → MEMORY.md 갱신
- **결과**: outputs/ 신설, index.md 생성(산출물 1건 등록), CLAUDE.md·MEMORY.md 업데이트
- **특이점**: 사용자가 `deliverables/` 대신 `outputs/`로 폴더명 변경 요청
- **배운점**: —

## [2026-03-24] Sales Deck 참고 예시 PDF 3건 user-inputs 등록

- **사용자 요청**: Sales Deck 작성 참고용 PDF 3건(PlaytestCloud, Zuora, Linear)을 프로젝트 root에 업로드 → user-inputs에 등록 요청
- **처리 방안**: 3개 PDF 전체 페이지 확인 → 기존 분류 체계에 맞지 않아 `sales-marketing/` 분류 신설(사용자 승인) → 파일 이동 → index.md에 3건 추가 + 분류 체계 테이블 업데이트 → user-inputs-guide.md 디렉토리 구조 및 분류 저장 규칙 업데이트 → MEMORY.md 갱신
- **결과**: user-inputs/sales-marketing/ 신설, PDF 3건 등록, index.md·user-inputs-guide.md·MEMORY.md 업데이트
- **특이점**: 없음
- **배운점**: —

## [2026-03-24] Andy Raskin 영상 상세 내용을 별도 문서로 분리

- **사용자 요청**: 방금 정리한 Andy Raskin 영상 2건 상세 내용을 별도 문서로 빼서 정리
- **처리 방안**: andy-raskin-strategic-narrative.md 신규 생성(영상 2건 상세 내용 이동) → sales-deck-case-studies.md 3-2 섹션을 요약+링크로 축소(708줄→377줄) → startup-sales/index.md에 topic 추가 → knowledge/index.md topic 수 갱신(17→18) → MEMORY.md 구조·최근작업 갱신
- **결과**: andy-raskin-strategic-narrative.md 신규 생성, sales-deck-case-studies.md 경량화, index 2개 갱신
- **특이점**: MEMORY.md 최근 작업과 task-log 업데이트를 누락하여 사용자 지적 2회 발생
- **배운점**: 하나의 세션에서 여러 작업을 순차 수행할 때, 각 작업 완료 시점마다 메모리를 업데이트해야 한다 — 마지막에 몰아서 하면 직전 작업만 기록하고 후속 작업을 누락하기 쉽다

## [2026-03-24] Andy Raskin 영상 2건 Timestamp별 상세 내용 정리

- **사용자 요청**: sales-deck-case-studies.md의 '3-2. 권장 시청' 영상 2건(Lenny's Podcast, FounderCoHo)의 주요 내용을 Timestamp와 매핑하여 상세하게 정리
- **처리 방안**: YouTube Transcript API 추출 시도(실패 — 자막 파일 미제공) → startup-researcher subagent 2개 병렬로 2차 출처(뉴스레터, 팟캐스트 요약 서비스, 인터뷰 기사, Andy Raskin 본인 글 등) 수집 → 영상 Description의 Timestamp 구조 기반으로 교차 종합
- **결과**: sales-deck-case-studies.md 3-2 섹션 대폭 확장. 영상 1(Lenny's Podcast): 17개 Timestamp별 상세 내용 + 5단계 프레임워크 진화 비교표 + 360Learning 사례 심층. 영상 2(FounderCoHo): 16개 Timestamp별 상세 내용 + Gong 사례 5가지 차별화 축 + AI 시대 적용 원칙 4가지. 각 섹션에 출처 링크 부착
- **특이점**: (1) YouTube Transcript 직접 추출 실패 — 두 영상 모두 자막 파일 미제공. 사용자가 "2차 출처 기반임을 명시해야 한다"고 피드백 → 출처 안내 블록 추가, 각 섹션에 클릭 가능한 출처 링크 부착 (2) 사용자가 출처 태그를 URL 링크로 변경 요청 → `[[사이트명](URL)]` 형식으로 변경
- **배운점**: (1) Transcript 없이 2차 출처로 영상 내용을 정리할 때, "직접 요약이 아닌 2차 출처 기반"임을 반드시 명시해야 한다 (2) 출처 태그는 클릭 가능한 링크로 제공하는 것이 사용자 경험에 훨씬 좋다

## [2026-03-19] Sales Deck 사례 리서치 — 3개 스트림 병렬 실행

- **사용자 요청**: Sales Deck 모범 사례 리서치 계획 실행 — 4개 스트림 중 Stream 1(실물 Deck), Stream 2(Pre-MVP 가이드), Stream 3(영상 콘텐츠)을 startup-researcher subagent 3개 병렬 실행
- **처리 방안**: 3개 subagent 병렬 실행 → 결과 종합 → Stream 4(경쟁사 분석) 불필요 판단 → knowledge 파일 생성 → Memory 업데이트
- **결과**: knowledge/startup-sales/sales-deck-case-studies.md 신규 생성 (4파트 구성: 실물 Deck 사례 9건, Pre-MVP 가이드 18건, 영상 콘텐츠 8건, Coxwave 적용 시사점). startup-sales/ index.md topic 추가, 루트 index.md topic 수 16→17 갱신
- **특이점**: Sales Deck 실물은 예상대로 극히 드물었음. 가장 유사한 사례는 PlaytestCloud(게임 QA)와 Galileo AI(LLM Evaluation). Pre-MVP 단계에서는 "Sales Deck"보다 "Discovery Deck" + Design Partner Program이 더 적합하다는 일관된 결론. Stream 4는 1-3의 결과가 충분하여 생략
- **배운점**: Pre-MVP 단계에서의 핵심 영업 자료는 전통적 Sales Deck이 아닌 Discovery Deck(문제 공감 + 비전 제시 + Design Partner 모집)이다

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
