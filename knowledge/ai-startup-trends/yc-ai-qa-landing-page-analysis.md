# YC 2025-2026 AI QA/시뮬레이션 스타트업 랜딩 페이지 분석

- **최종 업데이트**: 2026-03-18
- **출처 신뢰도**: 공식 문서 + 커뮤니티
- **출처**: YC 공식, 각 스타트업 공식 웹사이트, TechCrunch, AI Magazine, HN
- **목적**: 콕스웨이브 랜딩 페이지 초안 작성을 위한 레퍼런스

---

## 분석 대상 스타트업 (10개)

| # | 스타트업 | 핵심 포지셔닝 | YC 배치 | 관련도 |
|---|---------|-------------|---------|--------|
| 1 | Janus | AI 에이전트 시뮬레이션 평가 인프라 | X25 | 높음 |
| 2 | Bluejay | Voice/Text AI 에이전트 QA 에이전시 | X25 | 높음 |
| 3 | Roark | Voice AI 에이전트 테스트/모니터링 | W25 | 높음 |
| 4 | Kashikoi | AI 에이전트 벤치마킹 시뮬레이션 엔진 | X25 | 높음 |
| 5 | Confident AI | LLM 평가/Observability 플랫폼 (DeepEval) | W25 | 높음 |
| 6 | The LLM Data Company | Critical Domain 전문 모델 학습 (doteval) | X25 | 중간 |
| 7 | Sentrial | AI 에이전트 프로덕션 모니터링 | W26 | 중간 |
| 8 | Moda | AI 에이전트 모니터링/신뢰성 레이어 | W26 | 중간 |
| 9 | Artificial Societies | AI 페르소나 네트워크 (마케팅/PR) | W25 | 중간 |
| 10 | Arga Labs | AI 에이전트 검증 인프라 (샌드박스) | S26 | 중간 |

---

## 스타트업별 랜딩 페이지 상세 분석

### 1. Janus (withjanus.com)

**Hero Section**
- Headline: "Infrastructure to Evaluate AI Agents"
- Sub-headline: "Automated evaluation infrastructure built for enterprises to test and improve AI systems at scale."
- CTA: "Book a Demo" (Cal.com 연동)
- 배경: 미니멀 라이트 (#FAFAFA), 이미지/영상 없음

**페이지 구조** (상단→하단)
1. Navigation (Research, Benchmarks, Mission, Book Demo)
2. Hero + CTA
3. Metrics Section (Pathways Explored / Tests Run / Passed / Failed — 실시간 카운터)
4. Evaluation Workflow — 6단계 프로세스 (Generate → Trigger → Trace → Judge → Results → Improve)
5. Trust Statement — "Before Your AI Goes Live, Make It Earn Your Trust"
6. What We Offer — 4가지 핵심 기능
7. Detection Suite — 탐지 역량 쇼케이스 (hallucination, policy, security violations)
8. Use Case Examples — 탐지 가능한 위반 유형 리스트
9. Actionable Guidance — 성능 개선 제안 기능
10. Access Section — "Request platform access" + consultation 예약
11. Footer (YC 배지)

**핵심 메시지**
- 타겟: 엔터프라이즈 AI 에이전트 배포 조직
- 문제: AI 시스템 평가에 수개월 소요, 높은 실패 리스크
- 차별화: "days, not months" / 풀스택 시뮬레이션 / proprietary verification models / 구조화된 trace
- 접근: Enterprise consulting 모델

**디자인**
- 톤: 프로페셔널, 권위적, 엔터프라이즈 중심
- 색상: 블랙 텍스트 + 라이트 배경 (#FAFAFA), 극도로 미니멀
- 시각: 텍스트 중심, 스크린샷/데모 영상 없음
- API/Tool 연동 아이콘 (Stripe, Postgres, Python, Gmail, Slack)

**신뢰 요소**
- "Backed by Y Combinator" 배지
- 구체적 탐지 사례 (unauthorized financial advice, hallucinated medical diagnoses, PII disclosure 등)
- 고객 로고, 추천사 없음

**CTA 전략**
- "Book a Demo" (Hero + Navigation + Access Section) — 총 3회
- Enterprise-only 접근 ("currently available to select enterprises")
- 가격 미노출

---

### 2. Bluejay (getbluejay.ai)

**Hero Section**
- Headline: "End to End Testing for Voice and Chat AI Agents" (YC 공식 기준)
- Tagline: "The world's first quality assurance agency for voice & text AI"
- CTA: 추정 — Demo/Sign Up (Framer SPA로 정확한 추출 실패)
- 배경: 화이트 (#fff), 정교한 애니메이션

**페이지 구조** (Framer 기반 SPA — 부분 추출)
1. Sticky Navigation
2. Hero + 애니메이션 요소
3. Feature Demo (캐러셀/이미지 2개 섹션)
4. 3-column 레이아웃 콘텐츠
5. 복수 Feature Block (gradient 효과)
6. CTA 섹션 (복수)

**핵심 메시지** (YC 프로필 + 언론 보도 기반)
- 타겟: Voice/Text AI 에이전트 개발 팀
- 문제: AI 에이전트의 포괄적 E2E 테스팅 솔루션 부재
- 차별화: "1개월 고객 인터랙션을 5분 안에 시뮬레이션" / 다양한 언어·악센트·감정·배경소음의 디지털 휴먼
- 핵심 기능: Mimic (디지털 휴먼 생성), Skywatch (프로덕션 콜 observability), Research-backed Evaluation

**디자인**
- 톤: 모던, 기술적, 프로페셔널
- 색상: 화이트 배경, cyan/blue 액센트 (#69dcff), 다크 오버레이
- 시각: 정교한 CSS 애니메이션, 제품 스크린샷 캐러셀
- Framer 기반 — 풍부한 인터랙션/트랜지션

**신뢰 요소**
- 고객: Google, 11x, Zocdoc
- Traction: $100K ARR (YC 기간 중 1개월 내 달성), $4M 펀딩
- 투자자: Floodgate, PeakXV, Y Combinator
- 창업자: ex-AWS Bedrock, ex-Microsoft Copilot (23세에 Big Tech 퇴사)

**CTA 전략**
- 복수 CTA 섹션 (정확한 텍스트 미추출)
- 가격 미노출

---

### 3. Roark (roark.ai) — 가장 완성도 높은 랜딩 페이지

**Hero Section**
- Headline: "Never Ship a Broken Voice Agent Again"
- Sub-headline: "Catch the 'uh-oh' moments before your customers do. Roark is the safety net that lets your team ship voice AI with confidence, not crossed fingers."
- CTA: "Book a demo" (Primary) + "Learn more →" (Secondary, 앵커)
- 배경: 솔리드 블랙

**페이지 구조** (상단→하단)
1. Navigation (Product, Pricing, Blog, FAQ, About, Docs + YC 배지)
2. Hero + Dual CTA
3. Social Proof — "Trusted by leading Voice AI teams" + 5개 로고 + "10 million minutes of calls processed"
4. Monitoring & Evaluation (POST-DEPLOYMENT) — 40+ metrics, multi-speaker 분석, evaluators, 대시보드
5. Simulations & Testing (PRE-DEPLOYMENT) — E2E 테스팅, 그래프 기반 대화, 설정 가능한 페르소나
6. Video Section — "See it in action" 데모 영상 (3분 미만)
7. Integrations — VAPI, Retell, LiveKit, Pipecat Cloud 원클릭 연동
8. Investor Logos — YC, F-Prime Capital, True Ventures, Liquid 2 Ventures, MTV
9. Pricing — 3 Tier (Startup $500/월, Growth $1,200/월, Enterprise 커스텀)
10. Blog Section
11. FAQ (5개)
12. Footer (GitHub, LinkedIn, YouTube, HIPAA/SOC 2 배지, Product Hunt 위젯)

**핵심 메시지**
- 타겟: Voice AI 팀 (VAPI, Retell, LiveKit 사용 조직)
- 문제: Voice 에이전트가 프로덕션에서 실패 → 고객이 먼저 발견
- 차별화: "Safety net" (배포 전+후 모두 커버) / 10M+ 콜 분석 경험 / 그래프 기반 테스트 시나리오 / multi-speaker(15명) 지원
- 페르소나: 성별, 언어, 악센트, 감정, 의도 명확도, 배경 스토리 설정

**디자인**
- 톤: 자신감 있고 안심시키는, 기술적이면서 접근 가능 — 대화체 카피 ("uh-oh moments", "not crossed fingers")
- 색상: 블랙 배경, 화이트 텍스트, 바이올렛/퍼플 액센트
- 시각: 대시보드 스크린샷 다수 (latency, sentiment, custom metrics, multi-speaker 분석), 시뮬레이션 인터페이스 (대화 흐름 그래프), 페르소나 설정 패널
- 데모 영상 포함

**신뢰 요소**
- 고객 로고: Radiant Graph, Strala, Podium, BrainCX, Aircall (5개)
- 수치: "10 million minutes of calls" / "40+ built-in metrics" / "Up to 15 speakers" / 테스트 247건, 성공률 85%
- 투자자: YC (W25), F-Prime Capital, True Ventures, Liquid 2 Ventures, MTV
- 컴플라이언스: HIPAA, SOC 2 Type II
- 창업자: ex-AngelList, ex-Akiflow (YC S20)

**CTA 전략**
- Hero: "Book a demo" + "Learn more"
- Pricing: "Get started" (Startup/Growth) + "Get in touch" (Enterprise) — 총 3개
- 가격 **공개**: 3 Tier + 크레딧 기반 과금 명확 표시
- 연락처: founders@roark.ai

---

### 4. Kashikoi (getkashikoi.com)

**Hero Section**
- Headline: "The simulation engine for AI"
- Sub-headline: 추출 실패 (Framer SPA)
- CTA: 추출 실패
- 배경: 미확인

**페이지 구조** (Framer SPA — 부분 추출)
- Navigation + Hero
- 기능 섹션 (구체 구조 미확인)

**핵심 메시지** (YC 프로필 기반)
- 타겟: AI 에이전트 개발/배포 팀
- 문제: prompt engineering bloat, 의미 있는 에이전트 평가의 어려움, 공개 벤치마크를 넘어서는 성능 이해 부족
- 차별화: CPU 친화적 world model로 에이전트를 자율적으로 인터뷰 / 프롬프트 엔지니어링 없이 자동 최적화 / 장기 evaluation alignment
- Tagline: "Simulation Engine for Benchmarking AI Products"

**디자인**
- 색상: 블루 (#126dfb, #0765e8), 화이트, 라이트 그레이, 다크
- 폰트: Geist, Inter
- Framer 기반

**신뢰 요소**
- 창업자: ex-Moveworks/ServiceNow (250+ 커스텀 에이전트 배포), CMU Transformer 연구, Apple 보안 연구자 (CVE 다수)
- 고객 로고, 추천사 미확인

**CTA 전략**
- 미확인 (Framer 렌더링 필요)

---

### 5. Confident AI (confident-ai.com) — 가장 정교한 랜딩 페이지

**Hero Section**
- Headline: "The AI quality platform without the engineering overhead"
- Sub-headline: "Turn traces into datasets, datasets into evals, evals into experiments. No code required — ship better AI with every release."
- CTA: "Try Now For Free" (Primary) + "Request a Demo" (Secondary, 퍼플)
- 배경: 다크 테마 + 그래디언트, YC 로고 배지

**페이지 구조** (상단→하단) — 13개 섹션
1. Hero + Dual CTA
2. Social Proof — "TRUSTED BY 500+ LEADING AI COMPANIES" + 10개 로고 (Panasonic, Toshiba, Samsung, BCG, Epic Games, ByteDance 등)
3. Problem/ROI — "Move fast without breaking your AI" + Humach 케이스 스터디 링크
4. Testimonial — Sean Austin (Humach CAO): "Confident AI increased our speed to market by 200%"
5. Audience Segmentation — "WHO WE SERVE" (Engineers / Product Owners / QA) 각각의 혜택
6. Product Demo — LLM Tracing 시각화 (UUID, agent workflow, latency, token, cost)
7. Features Grid — 6개 기능 카드 (Alert, Dataset auto-curation, Postman for AI apps, Chat simulations, AI risk assessments, Git-based prompt versioning)
8. API Code Example — Python 코드 스니펫 (DeepEval prompt versioning)
9. How It Works — 4단계 (Install DeepEval → Choose Metrics → Plug It In → Run)
10. Enterprise Features — HIPAA/SOC2, Multi-data residency, RBAC, 99.9% SLA, On-prem
11. Community — Discord 2,500+, GitHub 14K+, Docs 100K+ reads/month
12. Testimonials — 5명 (Deloitte, Cisco, Airbus, AstraZeneca, Salesforce)
13. FAQ (7개) + Final CTA

**핵심 메시지**
- 타겟: LLM 앱 개발 Engineering/QA/Product 팀, 규제 산업 엔터프라이즈
- 문제: 실패 시점/원인 미가시성, 수동 평가 병목, Product/Engineering/QA 간 공유 프레임워크 부재
- 차별화: No-code 워크플로우 / traces→datasets→evals→experiments E2E / DeepEval 오픈소스 (14K stars) / 엔터프라이즈 보안

**디자인**
- 톤: 프로페셔널, 자신감, 솔루션 지향
- 색상: 다크 테마 (navy/charcoal #14161a), 섹션별 액센트 (Yellow/Amber, Teal, Blue, Orange)
- 시각: Trace Tree 다이어그램, 6개 기능 카드(SVG 아이콘), Python 코드 스니펫, 4단계 프로세스 인디케이터, 고객 로고, 컴플라이언스 배지
- 코너 도트 장식, 그리드 레이아웃

**신뢰 요소**
- 고객 로고: 10개 엔터프라이즈 (Panasonic, Toshiba, Samsung, BCG, Epic Games, Humach, Finom, Amdocs, ByteDance, Phreesia)
- 추천사: 6명 — Humach CAO, Deloitte VP Product, Cisco Senior ML Engineer, Airbus AI Platform Engineer, AstraZeneca CTO, Salesforce Director of Product
- 수치: 500+ AI companies, 14K+ GitHub stars, 2,500+ Discord, 100K+ docs reads/month, 99.9% SLA
- 투자자: Y Combinator
- 컴플라이언스: SOC 2 Type II, HIPAA, GDPR

**CTA 전략**
- Hero: "Try Now For Free" + "Request a Demo"
- Mid-page: 6개 Explore/Build/Test 링크
- Enterprise: "Get tailored support"
- How-It-Works: "Create an account"
- Community: Discord, GitHub, Docs 외부 링크
- FAQ: "Talk to Human" → 데모 예약
- Footer: 반복
- 가격: 홈페이지 미노출, /pricing 별도 페이지 (Freemium 모델, "no credit card required")

---

### 6. The LLM Data Company (llmdata.com)

**Hero Section**
- Headline: "Training Frontier Models for Critical Domains"
- Sub-headline: "The fox knows many things, but the hedgehog knows one big thing." (ARCHILOCHUS 인용)
- CTA: "Contact Us ->" (mailto) + "See our latest release" → Kos-1 Lite
- 배경: 미니멀

**페이지 구조** (상단→하단) — 간결
1. Navigation (Home, Blog, Rubric Grader, Kos-1 Lite Demo) + Contact CTA
2. Hero
3. Value Proposition — 범용 vs 전문 모델 역량 철학
4. Problem Statement — 모델 특화와 post-training trade-off
5. Solution/Positioning — 소외 도메인 집중
6. The Jagged Frontier 다이어그램 — 현재 frontier vs TLDC 집중 영역 비교
7. Research Section — "Kos-1 Lite: SOTA Medical Model" (2026-03)
8. Footer (GitHub, X, LinkedIn)

**핵심 메시지**
- 타겟: 의료, 법률, 금융 등 정확성 필수 도메인의 AI 조직
- 문제: 대부분 모델이 코딩/tool-use에 집중 → 소외 도메인 역량 부족
- 차별화: "Jagged frontier의 가장 짧은 끝을 밀어올린다" / sycophancy 거부 / 도메인별 전문 모델
- 현재: 의료 도메인 Kos-1 Lite (SOTA HealthBench Hard)

**디자인**
- 톤: 지적, 정밀, 자신감 — 고전 철학 인용
- 시각: Jagged Frontier 다이어그램 (텍스트 기반), 스크린샷/데모 영상 없음
- 매우 미니멀 — 텍스트 중심

**신뢰 요소**
- SOTA on HealthBench Hard
- Kos-1 Lite 데모 (kos.llmdata.com)
- 고객 로고, 추천사 없음

**CTA 전략**
- "Contact Us" (이메일) — 1회
- Kos-1 Lite Demo 링크 + Blog
- 가격 미노출

---

### 7. Sentrial (sentrial.com)

**Hero Section**
- 추출 제한 (Next.js RSC 직렬화)
- Meta Description: "Monitor metrics, track success rates, and measure ROI for your AI agents"

**핵심 메시지** (YC 프로필 + HN 런치 기반)
- Tagline: "Production Monitoring for AI Agents"
- 타겟: AI 에이전트 운영/개발 팀
- 문제: 전통적 평가 프레임워크가 프로덕션에서 무너짐, hallucination/user frustration 미감지
- 차별화: 실시간 장애 패턴 감지 (loops, hallucinations, tool misuse) + 근본 원인 진단 + 수정 제안
- 구현: SDK 몇 줄로 통합, 팀이 정답 예시를 마킹하면 자동 학습

**디자인**
- 다크 모드 지원
- Next.js 기반

**신뢰 요소**
- YC W26
- 창업자: 둘 다 UC Berkeley CS
- HN 런치에서 커뮤니티 피드백 (모바일 표시 이슈, GitHub 링크 깨짐 지적 받음)

**CTA 전략**
- 미확인 (렌더링 필요)

---

### 8. Moda (usemoda.ai)

**Hero Section**
- Headline: "Monitoring for AI Agents."
- Sub-headline: "Catch agent forgetfulness before your users do."
- CTA: "Book a Demo" (Primary) + "View Documentation" (Secondary)
- 배경: 미니멀 화이트

**페이지 구조** (상단→하단) — 11개 섹션
1. Navigation (Docs, Sign in, Book a Demo)
2. Hero + Dual CTA
3. Problem Statement — "Your agents are failing silently. Moda sees what your logs miss."
4. Failure Detection Examples — 4개 실제 대화 시나리오 (tool misuse, forgetfulness, laziness, frustration)
5. Custom Signals — "Describe what to watch for in plain language"
6. Alerts — Slack, Email, Webhooks 실시간 모니터링
7. Agent Replay — "Test fixes before they ship. Replay against real conversations."
8. Data Access — 6개 인터페이스 (Claude Code, Terminal, Custom Dashboard, API, MCP, CLI)
9. Security Monitoring — Prompt injection, jailbreak, RAG poisoning, NSFW detection
10. CTA — "Stop reading logs. Start seeing failures."
11. Footer

**핵심 메시지**
- 타겟: AI 에이전트 개발 팀 (고객 지원, 이커머스, 기술 지원)
- 문제: AI 에이전트가 조용히 실패 — hallucination, 컨텍스트 망각, tool 오용 — 로그에 안 잡힘
- 차별화: 행동 기반 장애 감지(로그 아님) / 설정 불필요 / 자연어 커스텀 시그널 / 실시간 대화 리플레이 / 보안 위협 모니터링

**디자인**
- 톤: 기술적, 긴급하면서 자신감 — "catching" 메타포
- 색상: 화이트 배경, 블랙 텍스트, 최소 액센트
- 시각: JSON 코드 블록, 대화 UI 목업 + 감지 어노테이션, 대시보드 스크린샷, 터미널 출력, 알림 예시
- 스태틱 중심 (최소 애니메이션)

**신뢰 요소**
- "Backed by Y Combinator" 배지
- 감지 신뢰도 수치: 94%, 87%, 91%, 88%
- 장애율/대화 수: 18.3%, 12.1%, 23.7% / 47, 31, 62 flagged conversations
- 고객 로고, 추천사 없음

**CTA 전략**
- Navigation + Hero + Footer: "Book a Demo" + "View Documentation"
- 가격 미노출 — Enterprise/contact-sales 모델

---

### 9. Artificial Societies (societies.io)

**Hero Section**
- Headline (슬로건): "Human Behavior, Simulated"
- Sub-headline: "AI platform that builds networks of AI personas to simulate stakeholder opinions and audience reactions"
- CTA: 추출 실패 (schema.org 데이터만 추출)

**핵심 메시지** (schema.org 기반)
- 타겟: 전략 커뮤니케이션 에이전시, 엔터프라이즈 마케팅 팀, 브랜드 전략가, 정책 분석가, IR 팀
- 문제: 접근 불가능한 오디언스 (정책입안자, Fortune 500 임원, 희소 전문가) + 긴 리서치 타임라인
- 차별화: 95% 의견 분포 정확도, 90% 페르소나 내적 일관성, 250만+ 실제 페르소나 프로필, 300~5,000 연결된 AI 페르소나 네트워크, 4시간 내 결과

**디자인**
- 톤: 프로페셔널, 권위적, 데이터 기반 — 과학적 신뢰성 강조

**신뢰 요소**
- 투자자: Point72 Ventures, Kindred Capital, Y Combinator (W25)
- 펀딩: $5.35M 시드
- 컴플라이언스: SOC 2, GDPR
- 추천사: Sparky Zivin, Senior Managing Director, Teneo Research (5/5)
- 연구: IC2S2 2024 발표, British Journal of Psychology 게재
- 창업자: Cambridge 계산사회과학자, MSc 행동경제학

**CTA 전략**
- Enterprise pricing on request
- 연락: support@societies.io

---

### 10. Arga Labs (argalabs.com)

**Hero Section**
- 페이지 콘텐츠 거의 추출 실패 ("Arga Labs" 타이틀만)

**핵심 메시지** (YC 프로필 기반)
- Tagline: "The validation infrastructure for AI agents"
- 타겟: AI 에이전트 개발 팀
- 문제: 외부 서비스 연동 AI 에이전트의 배포 전 검증이 어려움
- 차별화: 외부 서비스의 fully-functional mock → 프로덕션 유사 샌드박스에서 PR 배포/테스트 / Red-team 테스팅
- 창업자: ex-Amazon (내부 dev tool), ex-Stripe/Goldman Sachs

**CTA 전략**
- 미확인

---

## 패턴 분석

### 공통 패턴

**1. 헤드라인 공식**
- 대부분 "동사 + 결과" 구조: "Never Ship a Broken Voice Agent Again" (Roark), "Catch agent forgetfulness before your users do" (Moda)
- 또는 "X for Y" 포지셔닝: "Infrastructure to Evaluate AI Agents" (Janus), "Monitoring for AI Agents" (Moda)
- 기술적 용어보다 **고객 고통(pain)에 호소**하는 표현 선호

**2. 페이지 구조**
- 대부분 순서: Hero → Social Proof → Problem/Solution → Features → How It Works → (Pricing) → CTA
- Hero 직후 Social Proof 배치가 일반적 (Roark, Confident AI, Moda)
- FAQ 섹션은 하단에 배치 (Roark, Confident AI)

**3. CTA 전략**
- 주요 CTA 유형: "Book a Demo" (Janus, Roark, Moda) 또는 "Try Now For Free" (Confident AI)
- Hero에서 Dual CTA 패턴 자주 사용: Primary(데모/무료 시작) + Secondary(문서/상세 보기)
- 가격 공개는 소수: Roark만 명시적 3 Tier 가격 표시
- 대부분 Enterprise/demo-first 모델

**4. 신뢰 요소**
- YC 배지 (거의 모든 스타트업이 prominently 표시)
- 고객 로고 (Confident AI 10개, Roark 5개)
- 구체적 수치 (Roark: "10M minutes", Confident AI: "500+ companies, 14K+ stars")
- 컴플라이언스 배지 (HIPAA, SOC 2) — 엔터프라이즈 타겟팅 시 필수

**5. 디자인**
- 다크 테마 선호 (Roark, Confident AI, Janus) — 기술적 신뢰감
- 미니멀리즘 — 텍스트 중심, 불필요한 장식 최소화
- 제품 스크린샷/UI 목업이 핵심 시각 요소 (Roark, Moda, Confident AI)
- 데모 영상은 소수만 (Roark)

### 차별화 전략

| 스타트업 | 차별화 접근 |
|---------|-----------|
| Janus | "Enterprise-only" 희소성 — "currently available to select enterprises" |
| Bluejay | "세계 최초 QA 에이전시" 포지셔닝 + 디지털 휴먼(감정/악센트) 강조 |
| Roark | 가장 완성도 높은 풀 페이지 (가격 공개, 데모 영상, 컴플라이언스, 13개 고객 로고) |
| Confident AI | 오픈소스(DeepEval) 커뮤니티 → 엔터프라이즈 전환 전략 + 가장 많은 추천사 |
| Moda | 실제 장애 시나리오 4개를 대화형으로 보여주는 "Show, Don't Tell" |

---

## 콕스웨이브 랜딩 페이지 시사점

### 1. 헤드라인 방향
- 기술 스펙보다 **고객 고통에 호소**: "QA 자동화 플랫폼"보다 "AI 서비스를 출시 전에 깨뜨려 보세요" 같은 방향
- Roark/Moda 스타일의 "before your customers do" 메시지가 효과적

### 2. 구조 권장
- Hero (고통+해결 약속) → Social Proof/Traction → Problem (공감) → Solution/How It Works → Features → CTA
- Hero 직후 신뢰 요소 배치가 업계 표준

### 3. 차별화 강조 포인트
- Janus가 가장 직접적 경쟁자이나 "Enterprise consulting" 모델 — 콕스웨이브는 "셀프서비스" 접근성을 차별화 가능
- 대부분 경쟁사가 개발자(Engineer) 타겟 — 콕스웨이브는 **PM/비개발자도 사용 가능**한 점을 차별화 가능
- "페르소나 + 시나리오 생성의 어려움"을 해결해준다는 점은 Janus/Bluejay도 다루지만, **이해관계자 협업 평가 플랫폼**은 콕스웨이브 고유

### 4. CTA 전략
- 초기 스타트업이므로 "Book a Demo"가 현실적 (Janus, Moda 모델)
- 대기자 등록(waitlist)도 고려 가능
- 가격 공개 여부는 타겟에 따라 결정 — 엔터프라이즈면 미공개, 셀프서비스면 공개 (Roark 참고)

### 5. 시각 요소
- 제품 스크린샷/UI 목업이 핵심 — 실제 동작 화면이 없으면 신뢰 하락
- Moda처럼 **실제 장애 시나리오를 대화형으로 보여주는** 접근이 QA 제품에 효과적
- 다크 테마가 기술 제품에서 선호되는 추세

### 6. 신뢰 구축
- YC 배지 (해당 없음이므로) 대신 **구체적 수치** (시뮬레이션 횟수, 탐지 버그 수 등)와 **파일럿 고객** 로고 우선
- 창업자/팀의 관련 경력 강조 (도메인 전문성)
- 컴플라이언스 (보안) 배지는 엔터프라이즈 타겟팅 시 후순위로 추가

---

## 출처

| 출처 | 유형 | 발행일 | 신뢰도 |
|------|------|--------|--------|
| withjanus.com | 공식 웹사이트 | 2025 | 공식 문서 |
| getbluejay.ai | 공식 웹사이트 | 2025 | 공식 문서 |
| roark.ai | 공식 웹사이트 | 2025 | 공식 문서 |
| getkashikoi.com | 공식 웹사이트 | 2025 | 공식 문서 |
| confident-ai.com | 공식 웹사이트 | 2025 | 공식 문서 |
| llmdata.com | 공식 웹사이트 | 2026 | 공식 문서 |
| sentrial.com | 공식 웹사이트 | 2026 | 공식 문서 |
| usemoda.ai | 공식 웹사이트 | 2026 | 공식 문서 |
| societies.io | 공식 웹사이트 | 2025 | 공식 문서 |
| argalabs.com | 공식 웹사이트 | 2026 | 공식 문서 |
| ycombinator.com/companies/* | YC 공식 프로필 | 2025-2026 | 공식 문서 |
| TechCrunch YC W25 Demo Day | 언론 기사 | 2025-03-13 | 커뮤니티 |
| AI Magazine Bluejay | 언론 기사 | 2025 | 커뮤니티 |
| HN Sentrial Launch | 커뮤니티 | 2026 | 커뮤니티 |
| Alumni Ventures YC S25 분석 | 분석 기사 | 2025 | 커뮤니티 |

리서치 수행일: 2026-03-18
