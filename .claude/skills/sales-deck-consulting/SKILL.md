---
name: sales-deck-consulting
description: |
  초기 고객 확보를 위한 Sales Deck을 설계하고 작성합니다. Andy Raskin 5단계 서사 구조와 First Round 8섹션 프레임워크를 활용합니다. 사용자가 Sales Deck이나 영업 자료 작성, 고객 대상 제안서 준비, Founder-Led Sales 전략을 요청할 때 사용합니다.
user_invocable: true
---

# Sales Deck 작성 컨설팅

## 핵심 원칙

### Andy Raskin 5단계 서사 구조
1. **Name a Big Change**: 세상에서 일어나고 있는 크고 관련 있는 변화를 명명
2. **Show Winners and Losers**: 이 변화가 큰 승자와 패자를 만든다는 것을 보여줌
3. **Paint the Promised Land**: 고객이 달성할 이상적 상태를 제시
4. **Position Your Solution as Magic**: 제품을 고객이 Promised Land에 도달하도록 돕는 도구로 포지셔닝
5. **Provide Social Proof**: 유사 고객이 이미 Promised Land에 도달한 성공 스토리

### First Round Review 8섹션
1. Problem Definition → 2. Target Audience → 3. Problem Costs → 4. Existing Solutions & Gaps → 5. Market Changes → 6. Solution Mechanism → 7. Proof of Superiority → 8. Pricing

### Distribution is Everything (Peter Thiel)
- "If you have invented something new but you haven't invented an effective way to sell it, you have a bad business."
- "Poor sales rather than bad product is the most common cause of failure."
- Sales Deck은 영업 도구이자 Distribution 전략의 핵심 요소

### Founder-Led Sales (Paul Graham)
- "Startups take off because the founders make them take off."
- 초기에는 창업자가 직접 영업 — Do Things That Don't Scale
- Sales Deck은 창업자의 영업 도구이며, 반복적 피드백으로 개선

## 워크플로우

### 0. 서비스 맥락 확인 (필수)

`memory/service-context.md`를 Read 도구로 읽어 컨설팅 대상 서비스의 맥락(회사 정보, 고객 문제 가설, 솔루션 가설, 현재 단계 등)을 파악합니다. 이후 단계에서 사용자에게 이미 파악된 내용을 중복 질문하지 않습니다.

### 1. 목적 확인 (필수)

대상이 고객인지 투자자인지 확인합니다.
- 대상이 고객/바이어면 Sales Deck → 본 skill 진행
- 대상이 투자자면 Pitch Deck → 본 skill 범위 밖임을 안내
- 불분명하면 질문하여 확인

추가 확인:
- 어떤 제품/서비스를 영업하려는지
- 타겟 고객은 누구인지 (B2B? B2C? 의사결정자는?)
- 현재 영업 단계 (첫 영업? 기존 덱 개선?)

### 2. 제품/고객 이해

심층 파악:
- **제품**: 핵심 가치 제안, 경쟁 우위, 작동 방식
- **타겟 고객**: 의사결정자, Pain Point, 구매 프로세스
- **경쟁 환경**: 기존 대안, 차별화 포인트
- **증거**: 사용 사례, 성공 지표, 고객 피드백 (있는 경우)

### 3. 프레임워크 선택 및 구성 제안

상황에 맞는 프레임워크를 제안합니다:

**Andy Raskin 5단계** — 시장 변화가 명확하고 서사(narrative)가 강할 때:
- 변화 명명 → 승자/패자 → Promised Land → 솔루션 → Social Proof
- 장점: 강력한 스토리텔링, 감정적 공명
- knowledge/startup-sales/sales-deck-framework.md 참조

**First Round 8섹션** — 구체적 데이터와 ROI 중심의 B2B 영업에 적합:
- 문제 → 대상 → 비용 → 기존 솔루션 → 시장 변화 → 해결 방식 → 증거 → 가격
- 장점: 체계적, 데이터 중심, 이의 대응 구조

**하이브리드 접근** — 두 프레임워크의 장점을 결합할 수도 있음

필요 시 startup-researcher subagent로 모범 Sales Deck 사례를 조사합니다.

### 4. 슬라이드별 내용 초안

각 슬라이드의 구체적 내용을 제안합니다:
- **핵심 메시지**: 이 슬라이드에서 전달할 한 가지 핵심
- **데이터/증거**: 주장을 뒷받침하는 수치와 사례
- **비주얼 방향**: 차트, 이미지, 아이콘 등의 방향
- **카피 초안**: 헤드라인과 핵심 문구

실행 원칙:
- "The shorter the feedback loop between hearing an objection from a customer and building a slide to combat that objection, the better."
- 마스터 덱(전체 슬라이드)을 유지하고 상황에 맞게 포크
- 프레젠팅 덱(라이브) vs 전송 덱(팔로업) 구분

### 5. Founder-Led Sales 가이드

초기 영업 전략을 함께 제안합니다:
- 첫 10명 고객 확보 전략
- 수동 아웃리치 방법 (이메일, DM, 직접 방문)
- 무료 트라이얼 / 사전 주문 전략
- 이 단계의 목표는 매출이 아닌 아이디어 검증과 초기 PMF 발견
- knowledge/startup-sales/founder-led-sales.md 참조

### 6. 피드백 수렴

사용자의 질문과 피드백을 반영합니다.
- 기존 Sales Deck 리뷰 요청 시 프레임워크 기반 분석
- 영업 결과 피드백이 있다면 함께 분석하여 덱 개선
- 78%의 바이어가 자기 주도적으로 학습 — 전송 덱의 완결성 중요

## 참조 Knowledge

- `knowledge/startup-sales/sales-deck-framework.md` — Andy Raskin 5단계 + First Round 8섹션
- `knowledge/startup-sales/sales-deck-vs-pitch-deck.md` — Sales Deck과 Pitch Deck 비교
- `knowledge/startup-sales/founder-led-sales.md` — Founder-Led Sales 전략
