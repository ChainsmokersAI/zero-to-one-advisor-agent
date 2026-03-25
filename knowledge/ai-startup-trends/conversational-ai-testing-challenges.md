# Conversational AI 테스팅의 구조적 어려움

> Sales Deck Obstacle 슬라이드 (Slide 8) 근거 자료 — 자유로운 UX/대화형 AI의 테스팅 도전 과제
> 최종 업데이트: 2026-03-25
> 주요 출처: Sierra AI, OpenAI/Anthropic/DeepMind 연구진, NNGroup, LangChain, ACM/KAIST, Cyara, QualiZeal

---

## 1. 비결정성(Non-Determinism) 문제

### Sierra tau-bench: GPT-4o도 25% 일관성

- **내용**: Sierra AI의 tau-bench 벤치마크에서 GPT-4o가 동일 태스크를 8회 반복 수행 시 일관된 성공률이 약 25%에 불과
- **시사점**: 같은 입력을 줘도 결과가 매번 다르므로, 전통적 QA의 "기대 결과 vs 실제 결과" 비교 방식 자체가 불가
- 출처: [Sierra AI tau-bench](https://github.com/sierra-research/tau-bench) (2024)
- 신뢰도: **공식 문서** (오픈소스 벤치마크)

### 저명 인사 발언

> "You can't assert your way out of non-determinism."

- **발언자**: Venkat Peri (AI 엔지니어, 테스팅 전문가)
- **맥락**: LLM 기반 시스템 테스팅의 근본적 한계 설명
- 출처: 블로그/기술 포스트
- 신뢰도: **커뮤니티**

> "LLM calls kept on messing up... building reliable agents is quite hard."

- **발언자**: Harrison Chase (LangChain CEO)
- **맥락**: AI 에이전트 개발 시 안정성 확보의 어려움 토로
- 출처: LangChain 블로그/발표
- 신뢰도: **저명 인사**

---

## 2. 무한한 입력 공간 (Infinite Input Space)

### 학술 논문: 6가지 구조적 도전 과제

- **출처**: Chalmers/KAIST 공동 연구 (2024)
- **6가지 도전 과제**:
  1. **무한 입력 공간**: 자유 텍스트 입력으로 가능한 시나리오가 사실상 무한
  2. **비결정적 출력**: 같은 입력에도 매번 다른 응답
  3. **동적 상태**: 대화가 진행됨에 따라 컨텍스트가 변화
  4. **능력 진화**: 모델 업데이트마다 행동 패턴 변경
  5. **보안/윤리**: Prompt injection, jailbreak 등 악의적 공격
  6. **멀티모달 통합**: 텍스트 + 이미지 + 음성 결합 시 복잡도 폭발
- **핵심 인용**:

> "Correctness is a distribution of outcomes, not a binary property."

- 신뢰도: **공식 문서** (학술 논문)

### 적응적 공격 연구: 12개 방어 기법 무력화

- **내용**: OpenAI/Anthropic/DeepMind 연구진이 12개 방어 기법을 테스트한 결과, 적응적 공격에 대해 90%+ 성공률
- **시사점**: 스크립트 기반 보안 테스트로는 AI 서비스의 보안을 보장할 수 없음
- 출처: 공동 연구 논문 (2024)
- 신뢰도: **공식 문서** (AI 안전 연구)

---

## 3. 전통 UI vs 대화형 UI 테스팅 비교

### NNGroup: 스크립트 이탈 시 즉시 문제 발생

> "As soon as users deviated from the prescribed script, problems occurred."

- **맥락**: Conversational AI UX 연구에서 사용자가 예상된 대화 흐름을 벗어나는 순간 문제 발생
- **시사점**: 전통적 QA(정해진 시나리오 테스트)로는 자유로운 대화의 품질을 보장할 수 없음
- 출처: [Nielsen Norman Group](https://www.nngroup.com) Conversational AI UX 연구
- 신뢰도: **저명 인사** (UX 연구 분야 권위)

### QualiZeal: 전통 도구의 한계

> "Traditional tools were built for static UIs, not for back-and-forth conversation."

- **맥락**: AI QA 전문 기업의 분석
- **시사점**: 기존 테스팅 프레임워크(Selenium, Cypress 등)는 정적 UI 요소를 위해 설계 — 동적 대화에 부적합
- 출처: QualiZeal 블로그/분석
- 신뢰도: **커뮤니티**

### Cyara: "Impossible Manual Task"

- **내용**: Conversational AI 테스팅을 "impossible manual task"로 규정
- **맥락**: 대화형 AI 테스팅 전문 기업의 시장 분석
- 출처: Cyara 보고서/블로그
- 신뢰도: **커뮤니티**

---

## 4. 전통 UI vs 대화형 UI 대비 구조

| 차원 | 전통 UI (웹/앱) | 대화형 AI (채팅 UI) |
|------|----------------|-------------------|
| **입력 방식** | 제한됨 (버튼, 드롭다운, 폼) | 무제한 (자유 텍스트) |
| **출력 결정성** | 결정적 (같은 입력 → 같은 결과) | 비결정적 (같은 입력 → 다른 결과) |
| **테스트 시나리오** | 유한 (UI 요소 수에 비례) | 사실상 무한 (자연어 조합) |
| **상태 관리** | 정적 (URL, 세션) | 동적 (대화 컨텍스트 변화) |
| **테스트 도구** | 성숙 (Selenium, Cypress) | 미성숙 (전용 도구 부재) |
| **Pass/Fail 기준** | 명확 (기대값 == 실제값) | 모호 ("적절한" 응답의 스펙트럼) |

---

## Sales Deck 활용 가이드

**Slide 8 Obstacle 섹션에 가장 효과적인 3가지:**

1. **전통 UI vs 대화형 UI 대비표** — 한눈에 "왜 기존 QA가 통하지 않는지" 시각화
2. **Sierra tau-bench**: "GPT-4o도 동일 태스크 8회 반복 시 25% 일관성" — 비결정성 문제의 정량적 증거
3. **NNGroup 인용**: "As soon as users deviated from the prescribed script, problems occurred" — 자유로운 UX의 테스팅 한계를 권위 있는 출처로

**서사적 활용**: "AI 서비스는 사용자에게 채팅이라는 무한한 자유도를 부여합니다. 전통적 QA 도구는 버튼과 폼을 위해 만들어졌습니다. 이 근본적 불일치가 첫 번째 장벽입니다."
