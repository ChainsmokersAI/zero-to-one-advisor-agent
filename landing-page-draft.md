# 콕스웨이브 Align 랜딩 페이지 전략

> **목적**: MVP 공개 앞두고 서비스 소개 + Early Access 인입
> **대상**: Warm Traffic 우선 (지인, 네트워크), 추후 Cold Traffic 확장
> **카피 언어**: 영어 (브로셔 일관성 + 글로벌 타겟)
> **디자인 방향**: Dark mode + Blue accent (브로셔 일관성 + 기술 신뢰)
> **CTA**: "Get Early Access" (Primary) + "Book a Demo" (Secondary)

---

## 전략적 방향

### 1. Problem-First 접근

**근거:**
- 벤치마크 분석: Pain-first 헤드라인이 Feature-first보다 전환율이 높음
  - Roark "Never Ship a Broken Voice Agent Again" > Kashikoi "The simulation engine for AI"
  - Moda "Catch agent forgetfulness before your users do" > Janus "Infrastructure to Evaluate AI Agents"
  - RowFlow "Forms suck." — 도발적 직설 카피가 공감 극대화
- 고객 인터뷰에서 QA 문제 인식이 약했으므로, 페이지가 문제를 "일깨우는" 역할 필요
- 리더십이 중시하는 페르소나 생성은 How It Works에서 "이렇게 해결한다"로 자연스럽게 등장

### 2. Dual CTA 전략

**두 CTA의 역할이 다르다:**

| | Get Early Access | Book a Demo |
|--|-----------------|-------------|
| **행동 수준** | 낮은 커밋 (폼 제출 30초) | 높은 커밋 (30분 미팅) |
| **검증 목적** | 수요 폭 — 얼마나 많은 사람이 관심 있나? | 수요 깊이 — 누가 시간 투자할 만큼 진지한가? |
| **데이터** | 관심 고객 리스트 + 역할/단계 분포 | 초기 영업 파이프라인 |
| **타겟** | "관심은 있지만 아직 미팅까지는..." | "지금 당장 문제를 해결하고 싶다" |

**검증 관점에서의 핵심 가치:**
- Early Access 폼 데이터 자체가 검증 데이터 — 누가 관심 있는지(역할, 회사 규모, AI 에이전트 단계)를 구조화하여 수집
- Demo 예약율 / Early Access 신청율의 비율이 시장 온도를 측정하는 지표

**플랫폼:**

| CTA | 추천 플랫폼 | 이유 |
|-----|-----------|------|
| Get Early Access | **Tally** (무료) 또는 랜딩 페이지 빌더 내장 폼 | 무료, 깔끔한 UI, Notion/Slack 연동, 응답 무제한 |
| Book a Demo | **Cal.com** (무료, 오픈소스) | 무료, Google Calendar 연동, 커스텀 질문 추가 가능 |

**Early Access 폼 항목:**

| 항목 | 필수 여부 | 목적 |
|------|---------|------|
| Work Email | 필수 | 연락 + 회사 도메인으로 세그먼트 가능 |
| Name | 필수 | 기본 |
| Role | 필수 (선택형) | PM / AI Engineer / QA Engineer / Other → 타겟 고객 분포 검증 |
| Company | 선택 | 리드 퀄리피케이션 |
| AI 에이전트 현황 | 선택 (선택형) | In Production / In Development / Planning → 긴급도 파악 |

> 필수 항목 최소화(3개)하여 전환율 유지, 선택 항목으로 검증 데이터 추가 수집. 5개가 상한선.

---

## 페이지 구조

### 전체 서사 흐름

```
[Hook + CTA] → [문제 환기] → [해결 방법] → [제품 깊이] → [이의 처리] → [행동 촉구]
```

방문자의 심리 여정:
1. "이게 뭐지?" — Hero: 3초 내 가치 전달 + Dual CTA
2. "나도 이 문제..." — Problem Bridge: 강렬한 한 마디로 공감
3. "어떻게 해결하지?" — How It Works ⭐: 3단계 + 각 Step에 목업
4. "구체적으로 뭐가 가능하지?" — Key Capabilities: 제품 깊이 + 각 카드에 목업
5. "근데 이건 어떻게 되지?" — FAQ: 마지막 이의 처리
6. "해볼까." — Final CTA: 전환 재촉

### 구조 요약

| # | 섹션 | 핵심 목적 | 브로셔 대응 | 주요 벤치마크 |
|---|------|----------|-----------|-------------|
| 1 | **Hero** | 3초 내 가치 전달 + Dual CTA | Page 2 헤드라인/서브카피 | Roark, RowFlow |
| — | **Problem Bridge** | 강렬한 한 마디로 문제 환기 | Page 3 PM 인용문 | SimCare, Roark |
| 2 | **How It Works** ⭐ | 핵심 차별점 + 진입 장벽 낮음 | Page 3 3단계 워크플로우 | Janus, SimCare |
| 3 | **Key Capabilities** | 제품 깊이 전달 | Page 4 "Why Teams Choose" | Janus, Roark |
| 4 | **FAQ** | 전환 직전 이의 처리 | — | Roark, Confident AI |
| 5 | **Final CTA** | 전환 재촉 | Page 1 CTA | Moda, Roark |

### 논의를 통해 제거된 섹션

| 제거된 섹션 | 근거 |
|------------|------|
| **Trust Bar** | 파트너/Accelerator 로고가 신규 기획/개발 중인 아이디어에 대한 Reference가 아님 |
| **Visual Proof (별도 섹션)** | How It Works + Key Capabilities 각 항목에 목업 삽입으로 대체 |
| **Who It's For** | 벤치마크 8개 중 1곳만 사용. Warm Traffic 대상이면 역할 구분 불필요 |
| **What Align Catches** | How It Works Step 03 + Key Capabilities 카드 1과 내용 중복 |

---

## 섹션별 상세

### 섹션 1: Hero

| 항목 | 내용 |
|------|------|
| **핵심 목적** | 3초 내 가치 전달 + Dual CTA |
| **서사적 역할** | 첫인상 — "이것은 AI 에이전트 QA를 자동화하는 도구"를 즉시 이해 |
| **주요 벤치마크** | Roark (결과 중심 헤드라인 + Dual CTA), RowFlow (Eyebrow + Headline + Sub-copy 3층), 브로셔 Page 1-2 |

#### 카피

```
[Eyebrow]    QA Simulation for AI Agents

[Headline]   Don't Ship and Pray.
             Ship with Confidence.

[Sub-copy]   Simulate your users at scale.
             Find failures before they do.

[CTA]        [Get Early Access]    [Book a Demo]
```

- **Eyebrow** — "QA Simulation for AI Agents": 브로셔 Page 2 우상단 기존 카피. 카테고리를 먼저 명시하여 "이게 뭐 하는 건지" 즉시 전달
- **Headline** — "Don't Ship and Pray. Ship with Confidence.": 브로셔 Page 1 커버 카피. "Ship and pray"는 QA 없이 배포하는 개발 문화에서 널리 쓰이는 표현으로 즉시 공감. 대비 구조(Don't X. Do Y.)가 기억에 남음
- **Sub-copy** — "Simulate your users at scale. Find failures before they do.": 브로셔 Page 2 카피 조합. 1문장: HOW(시뮬레이션), 2문장: VALUE(사용자보다 먼저 실패 발견)
- **Primary CTA** — "Get Early Access": 밝은 블루 배경 + 흰 텍스트
- **Secondary CTA** — "Book a Demo": 투명 배경 + 흰 테두리 (ghost button)

> **헤드라인 대안:** "Find Your AI Agent's Failures Before Your Users Do." (직접적 pain-first, 다만 Roark 서브카피와 유사) / "Ship Your AI Agent with Confidence." (깔끔하지만 pain 부재)

#### 의도 및 레퍼런스

- **3층 구조(Eyebrow + Headline + Sub-copy)**: RowFlow, Janus 패턴. Eyebrow가 카테고리를 전달하므로 Headline이 감성 훅에 집중 가능
- **Dual CTA**: Roark, SimCare, Confident AI 패턴. 낮은 커밋(Early Access)과 높은 커밋(Demo)을 동시 수용
- **브로셔 카피 최대 활용**: 이미 검증된(MWC 행사용) 카피를 재사용하여 브랜드 일관성 유지

#### 디자인 방향

- **레이아웃**: 좌측 텍스트(Eyebrow → Headline → Sub-copy → CTA) + 우측 제품 목업. Full viewport height (100vh)
- **Hero 비주얼**: 페르소나들이 AI Agent와 대화하는 시뮬레이션 화면 목업 (브로셔 Page 3 참조). 플레이스홀더 → 제품 완성 후 교체
- **컬러**: 배경 다크(#0a0a0a ~ #111111) + 블루 그래디언트(브로셔 Page 2 빛줄기). Eyebrow 밝은 블루 소형 대문자. Primary CTA 블루(#126dfb), Secondary CTA ghost button
- **타이포**: Headline 큰 볼드 산세리프, Eyebrow 소형 대문자(letter-spacing 넓게), Sub-copy Regular weight
- **Navigation**: 로고(Coxwave Align) 좌측 + "Get Early Access" 우측. Sticky header. 섹션 수가 적으므로 별도 메뉴 불필요
- **모바일**: CTA 세로 스택, Headline 최소 28px, 텍스트 중앙 정렬 → 하단 목업

---

### Problem Bridge

| 항목 | 내용 |
|------|------|
| **핵심 목적** | QA 문제를 강렬한 한 마디로 환기 |
| **서사적 역할** | Hero의 "Ship and Pray" → 실제 현장의 목소리로 공감 구체화 → 솔루션 기대감 전환 |
| **주요 벤치마크** | SimCare ("Role play is slow. Inconsistent. Outdated."), Roark ("uh-oh moments" 한 줄), 브로셔 Page 3 |

> Problem을 별도 섹션으로 깊게 다루지 않는 이유: 벤치마크 대다수가 Problem을 한 줄~한 문단으로 처리. 랜딩 페이지의 역할은 "교육"이 아니라 "공감 유도" — 공감하는 사람만 전환시키고, 문제를 못 느끼는 사람은 영업/인터뷰에서 설득하는 것이 현실적.

#### 카피

```
"Every sprint, QA is on the plan.
 Every sprint, it's the first thing cut."
 — AI Product Manager at a Series A startup

What if QA took minutes, not weeks?
```

- **PM 인용문**: 브로셔 Page 3 원문을 핵심 2문장으로 축약. "Every sprint... Every sprint..." 반복 구조가 공감의 핵심
- **전환 문구**: "What if QA took minutes, not weeks?" — 브로셔 Page 3 기존 카피. 문제 → 솔루션 기대감 전환점

#### 디자인 방향

- 인용문: 좌측 블루 세로선(4px) + 이탤릭 (브로셔 Page 3 스타일)
- 전환 문구: 큰 타이포, 중앙 정렬
- 전체 높이: 뷰포트의 30-40% — 빠르게 통과하는 전환 장치
- 배경: Hero와 동일한 다크 톤 (섹션 구분선 없이 자연스러운 흐름)

---

### 섹션 2: How It Works ⭐

| 항목 | 내용 |
|------|------|
| **핵심 목적** | 핵심 차별점 어필 + 진입 장벽 낮음을 시각적으로 증명 |
| **서사적 역할** | Problem Bridge "What if QA took minutes?"에 대한 직접적 답변 |
| **주요 벤치마크** | Janus (6단계 넘버링), 브로셔 Page 3-4 (3단계), SimCare (GIF 카드) |

**가장 강조하는 섹션** — 카피와 비주얼 에셋에 가장 공을 들임.

#### 카피

**섹션 헤드라인:** "How It Works"

**Step 1:**
```
01  Just Talk to Our Agent

    Describe your AI service through a simple conversation.
    Our agent asks the right questions — no documentation,
    no setup required.
```
- 어필: 가상 에이전트와 상담 — "대화만 하면 된다" 진입 장벽 제로
- 비주얼: 에이전트 대화 UI 목업

**Step 2:**
```
02  Get Hyper-Realistic Personas

    From your conversation, Align generates detailed personas —
    complete with goals, emotions, and edge-case behaviors
    you haven't considered.
```
- 어필: 실재할 법한 페르소나 자동 생성 — 핵심 차별점
- 비주얼: 페르소나 카드 2-3장 (브로셔 Page 3 "Gwen" 스타일)
- > 대안: "Get Real-World Personas" — 품질(Hyper-Realistic)보다 현실 대응(Real-World)을 강조하고 싶을 때

**Step 3:**
```
03  See What Breaks

    Personas run real multi-turn conversations with your agent.
    Review the results and pinpoint exactly where it fails.
```
- 어필: 간편한 문제 파악 — 결과의 명확성
- 비주얼: 결과 대시보드 또는 대화 로그 (실패 지점 하이라이트)

#### 의도 및 레퍼런스

**각 Step의 전략적 의도:**
- Step 01 — 진입 장벽 제로: "Just"가 낮은 진입 장벽 강조. 브로셔 "Chat about your agent"를 행동 유도적으로 변환
- Step 02 — 핵심 차별점: 리더십이 중시하는 정교한 페르소나 생성. "Hyper-Realistic"는 AI/시뮬레이션 업계에서 일반적 표현으로 PM/Engineer에게 제품 역량을 강하게 어필
- Step 03 — 결과의 명확성: "See What Breaks"는 브로셔 "Find failures"를 3단어로 압축. "pinpoint exactly"로 모호한 결과가 아닌 정확한 실패 지점 식별 약속

#### 디자인 방향

- **레이아웃**: 3단계 세로 흐름, 좌우 교대 배치 (01: 좌텍스트/우목업, 02: 좌목업/우텍스트, 03: 좌텍스트/우목업). 넘버링(01, 02, 03) 큰 숫자 블루 액센트. Step 사이 충분한 여백
- **비주얼 에셋 (플레이스홀더)**: 01 에이전트 대화 UI / 02 페르소나 카드(Gwen 스타일) / 03 결과 대시보드(평가 카드)
- **컬러**: 배경 약간 밝은 다크(#141414 ~ #1a1a1a). 넘버링 블루(#126dfb). 제목 흰색, 설명 라이트 그레이
- **모바일**: 좌우 교대 → 전부 "텍스트 위 / 목업 아래" 세로 스택

---

### 섹션 3: Key Capabilities

| 항목 | 내용 |
|------|------|
| **핵심 목적** | "무엇이 가능한지" — 제품 깊이 전달 |
| **서사적 역할** | How It Works "얼마나 쉬운지" → 이 섹션 "얼마나 강력한지". 간편한 진입 → 강력한 결과 서사의 후반부 |
| **주요 벤치마크** | Janus (Detection Suite 6가지 역량), Roark (pre/post deployment 분리), 브로셔 Page 4 |

#### 카피

**섹션 헤드라인:** "Why Teams Choose Align"

**카드 1:**
```
Test Beyond the Happy Path

Edge cases. Unusual personas. Prompt injections.
Align generates scenarios that cover the 1% of users
most teams never test for — the ones who break
everything on day one.
```
- 비주얼: 대화 분기 다이어그램 (브로셔 Page 4의 Turn 1→2→3→4 트리)

**카드 2:**
```
Conversations That Run Themselves

No need to manually chat with your agent for every test case.
Align auto-generates natural, multi-turn conversations —
each one tailored to its scenario and persona.
```
- 비주얼: Learn → Generate → Simulate → Evaluate 플로우 카드 (브로셔 Page 4)

**카드 3:**
```
Your Source of Truth for Evaluation

PMs, AI Engineers, and QA — all evaluating quality
in one workspace. Define criteria, assign reviewers,
and track results without switching tools.
```
- 비주얼: Evaluation Metrics 테이블 목업 (브로셔 Page 4)

#### 의도 및 레퍼런스

**3개 카드 — 고객 가치 중심 프레이밍:**

| 카드 | 고객 가치 | 대응하는 Pain Point |
|------|----------|-------------------|
| Test Beyond the Happy Path | 시나리오 다양성 — 1% 엣지케이스 + 악의적 공격까지 | Pain #1 — 페르소나/시나리오 기획의 어려움 |
| Conversations That Run Themselves | 자동화 — 수동 대화 불필요, 테스트케이스별 자동 생성 | Pain #2 — Multi-Turn 시뮬레이션의 소모성 |
| Your Source of Truth for Evaluation | 팀 협업 — PM/Engineer/QA 모두의 평가 플랫폼 | Pain #3 — 통합 평가/분석 환경 부재 |

#### 디자인 방향

- **레이아웃**: 가로 3카드 배치. 각 카드에 상단 비주얼/아이콘 + 제목 + 설명. 카드 간 동일 높이
- **컬러**: 카드 배경 약간 밝은 다크(#1e1e1e ~ #222222), 미세한 보더. 제목 흰색 볼드, 설명 라이트 그레이
- **모바일**: 가로 3카드 → 세로 1열 스택

---

### 섹션 4: FAQ

| 항목 | 내용 |
|------|------|
| **핵심 목적** | 전환 직전의 마지막 이의 처리 |
| **서사적 역할** | Key Capabilities까지 관심을 가진 방문자의 장벽을 해소하여 Final CTA로 연결 |
| **주요 벤치마크** | Roark (5개 아코디언), Confident AI (7개), RowFlow (5개) |

#### 카피

**섹션 헤드라인:** "FAQ"

```
Q: Is Early Access free?
A: Yes. Early Access is completely free.
   We're looking for design partners who can
   share honest feedback as we shape the product.

Q: What types of AI agents does Align work with?
A: Any conversational AI agent with an API endpoint —
   customer support bots, internal assistants,
   sales agents, and more.

Q: Can I create my own personas and scenarios?
A: Absolutely. You can also feed in your own data —
   a few real examples are all Align needs to generate
   significantly higher-quality test cases from them.

Q: Is my data secure?
A: Yes — and for teams with strict requirements,
   we're planning to offer a self-hosted deployment option.
   Reach out for details.
```

#### 의도 및 레퍼런스

| Q | 대응하는 장벽 | 전략적 의도 |
|---|-------------|-----------|
| Q1 (무료?) | 비용 | MVP 단계 첫 의문 선제 처리. "design partner"로 협력자 포지셔닝 |
| Q2 (호환성?) | 기술 | "API endpoint만 있으면 된다"로 범위 넓게 전달 |
| Q3 (커스텀?) | 자유도 | 직접 생성 가능 + 실제 데이터 소량 입력 시 고품질 생성이라는 제품 가치 전달 |
| Q4 (보안?) | 신뢰 | Self-hosting 예정으로 엔터프라이즈 대응. "Reach out"이 Demo 예약 유도 |

> 4개로 시작, 추후 실제 문의가 쌓이면 추가 가능.

#### 디자인 방향

- **레이아웃**: 아코디언 (클릭 → 답변 펼침). 최대 너비 700-800px 중앙 정렬
- **컬러**: 질문 흰색 볼드, 답변 라이트 그레이. 구분선 미세한 그레이 보더. +/− 아이콘 블루 액센트
- **모바일**: 아코디언은 모바일 최적 패턴 — 변경 불필요

---

### 섹션 5: Final CTA

| 항목 | 내용 |
|------|------|
| **핵심 목적** | 전환 재촉 — 페이지 하단 CTA 반복 |
| **서사적 역할** | 전체 서사 완결 + 최종 행동 유도. 페이지 끝까지 스크롤한 = 관심 높은 방문자 |
| **주요 벤치마크** | Moda ("Stop reading logs. Start seeing failures." + CTA), Roark (가격+CTA) |

#### 카피

```
Stop shipping and hoping for the best.

[Get Early Access]    [Book a Demo]

Free during Early Access.
```

- **압축 메시지**: "Stop shipping and hoping for the best." — Hero "Don't Ship and Pray"의 변주로 서사 완결. "Pray" → "hoping for the best"로 표현을 바꾸면서 동일 메시지 강화
- **Dual CTA 반복**: Hero와 동일한 버튼 구성
- **혜택 문구**: "Free during Early Access." — FAQ Q1 내용을 한 줄로 재확인. 전환의 마지막 마찰 제거

#### 디자인 방향

- **레이아웃**: 중앙 정렬. 메시지 → CTA → 혜택 문구 → 연락처/로고. 뷰포트 40-50%, 충분한 여백으로 CTA에 시선 집중
- **컬러**: Hero와 동일한 다크 + 블루 그래디언트 — 페이지 시작과 끝을 시각적으로 연결. CTA 버튼 Hero와 동일 스타일
- **Footer**: sales@coxwave.com + Coxwave Align 로고 + 저작권

---

## 확정 사항

| 항목 | 결정 | 비고 |
|------|------|------|
| **카피 언어** | 영어 | 브로셔 일관성 + 글로벌 타겟 |
| **비주얼 에셋** | 플레이스홀더 | 제품 디자인 완성 후 교체 |
| **팀 크레딧** | 노출하지 않음 | — |
| **Trust Bar** | 미적용 | 파트너 로고가 현 아이디어의 Reference가 아님 |
| **CTA 플랫폼** | Tally + Cal.com | 둘 다 무료 |

## 참조 자료

| 파일 | 역할 |
|------|------|
| `knowledge/ai-startup-trends/yc-ai-qa-landing-page-analysis.md` | YC AI QA 스타트업 8개 벤치마크 분석 |
| `user-inputs/customer-research/yc-ai-startup-landing-page-deep-research-1.md` | 사용자 제공 deep research 1편 |
| `user-inputs/customer-research/yc-ai-startup-landing-page-deep-research-2.md` | 사용자 제공 deep research 2편 |
| `user-inputs/product-tech/02.19_MWC Align Consulting Pamphlet_A4.pdf` | MWC 브로셔 (기존 카피, 디자인 방향) |
| `memory/service-context.md` | 서비스 맥락 (문제/솔루션 가설, 리스크) |
