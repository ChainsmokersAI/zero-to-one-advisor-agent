# Sales Deck 초안 작성

> 상태: 진행 중
> 시작일: 2026-03-25
> 최종 업데이트: 2026-03-25

## 목표

Coxwave AI 서비스 QA 자동화 서비스의 Sales Deck 초안 2개 버전을 작성합니다.
- **Version A**: Zuora 벤치마킹 — Andy Raskin Strategic Narrative
- **Version B**: Linear 벤치마킹 — Problem-Solution
- 산출물: `outputs/sales-deck-draft-version-a.md`, `outputs/sales-deck-draft-version-b.md`

현재 단계(아이디어 검증, MVP 개발 중)에서 Social Proof가 부족하므로, Design Partner 확보를 위한 Discovery Deck 성격.

## 확정 사항

| 결정 | 내용 | 확정일 |
|------|------|--------|
| Old Game | "The Ship-and-Pray Game" — 빠르게 출시하고 프로덕션에서 고치는 전략이 AI 시대에 통하지 않음 | 2026-03-25 |
| New Game | "희망이 아닌 증거를 가지고 출시하라" — 사전 배포 시뮬레이션이 새로운 표준 | 2026-03-25 |
| 카피 언어 | 영어 (브로셔/랜딩 페이지 일관성) | 2026-03-25 |
| 서사 톤 | "시뮬레이션의 시대" — QA 공포가 아닌 기회+새 게임 규칙으로 균형 | 2026-03-25 |
| 차별화 | "We don't test your agent. We simulate your users." | 2026-03-25 |
| 근거 자료 | 공신력 높은 출처 필수 (Gartner, McKinsey, HBR 등). 보안/신뢰에 과도 집중하지 않기 | 2026-03-25 |

## Version A 구조 (Strategic Narrative, 12~14장)

| # | 섹션 | 장수 | 역할 |
|---|------|------|------|
| 1 | Name the Old Game | 3~4 | 기존 게임(Ship & Pray) 명명 + 실패 근거 |
| 2 | Name the Stakes | 2~3 | 적응하지 못하면 생기는 일 (가볍게) |
| 3 | Promised Land | 1~2 | 시뮬레이션으로 확신을 가지고 출시하는 미래 |
| 4 | Obstacles + Magic Gifts | 3~4 | 장벽 + 3단계 워크플로우 |
| 5 | Evidence + CTA | 1~2 | 파트너 크레딧 + Design Partner CTA |

서사 핵심 흐름:
1. AI 에이전트 폭발적 성장 (기회)
2. 기존 방식(Ship & Pray) 한계 (가볍게 1~2장)
3. **AI로 사용자를 시뮬레이션할 수 있는 시대** ← 핵심 전환점
4. 시뮬레이션으로 확신을 가지고 출시 (Promised Land)
5. Coxwave가 이것을 가능하게 한다 (Magic Gifts)

주의: "Old Way"(방어적 반응 유발)가 아닌 "Old Game"(과거에는 통했던 전략)으로 프레이밍.

## Version B 구조 (Problem-Solution, 8~10장)

| # | 섹션 | 장수 | 역할 |
|---|------|------|------|
| 1 | Cover | 1 | 도발적 오프닝 "Don't Ship and Pray." |
| 2 | Product Intro | 1 | Coxwave Align 소개 |
| 3 | Problem | 2 | 감정적 프레이밍 + 인과 체인 |
| 4 | Solution | 2~3 | 3단계 워크플로우 + 차별화 |
| 5 | Social Proof + CTA | 1~2 | 파트너 크레딧 + Dual CTA |

서사적 루프: "Don't Ship and Pray." (오프닝) ↔ "Ship with Confidence. Start today." (클로징)

## 근거 자료 (리서치 완료)

상세: `knowledge/ai-startup-trends/ai-service-trust-and-qa-market-2025.md`

핵심 데이터:
- Gartner: 엔터프라이즈 앱 40%가 2026년까지 AI 에이전트 탑재
- McKinsey: 88% AI 채택, 6%만 전사 전환 달성
- HBR: AI 에이전트 완전 신뢰 기업 6% (86% 투자 확대 예정)
- AI 테스팅 시장: $10.1억 → $46.4억 (Fortune Business Insights)
- Air Canada, Chevrolet 챗봇 사고 사례 (ABA, VentureBeat)
- AI Simulation/Synthetic User 트렌드: **추가 리서치 필요**

## 재사용 자산

| 자산 | 출처 |
|------|------|
| "Don't Ship and Pray. Ship with Confidence." | MWC 브로셔 |
| 3단계 워크플로우 (Generate → Simulate → Evaluate) | MWC 브로셔 |
| "Find failures before your users do." | MWC 브로셔 |
| PM 인용문 ("Every sprint, QA is on the plan...") | 랜딩 페이지 초안 |
| Dual CTA (Get Early Access + Book a Demo) | 랜딩 페이지 초안 |
| 파트너 크레딧 (Anthropic, OpenAI) | MWC 브로셔 |

## 현재 진행 상황

- [x] 청사진 합의 (두 버전 구조, 서사, 차별화 전략)
- [x] 근거 자료 리서치 (14건 확보, knowledge/ 기록 완료)
- [ ] AI Simulation/Synthetic User 트렌드 추가 리서치
- [ ] Version A 슬라이드별 작성
- [ ] Version B 슬라이드별 작성
- [ ] 교차 비교 및 최종 정리

다음 단계: AI Simulation 추가 리서치 → Version A 슬라이드 작성 시작

## 참조 파일

- `outputs/sales-deck-analysis-zuora-playtestcloud-linear.md` — 3건 벤치마크 분석
- `knowledge/startup-sales/andy-raskin-strategic-narrative.md` — Andy Raskin 프레임워크
- `knowledge/ai-startup-trends/ai-service-trust-and-qa-market-2025.md` — 근거 자료
- `memory/service-context.md` — Coxwave 서비스 맥락
- `outputs/landing-page-draft.md` — 랜딩 페이지 초안 (재사용 카피)

## 세션 로그

### [2026-03-25] 세션 1

- **논의**:
  - Sales Deck 2개 버전 작성 방향 청사진 제시
  - Old Game 3개 후보(Scripted Test / Happy Path / Ship-and-Pray) 제안
  - 근거 자료 리서치 수행 (14건 데이터 포인트)
- **결정**:
  - Old Game: "The Ship-and-Pray Game" 선택
  - 카피 언어: 영어
  - 서사 톤: 보안/신뢰 공포에 과도 집중하지 않기, AI Simulation에 더 초점
- **사용자 피드백**:
  - 근거 자료에서 보안/신뢰에 너무 무겁게 가지 않기
  - AI Simulation으로 User Research하는 관점도 추가
  - Knowledge 업데이트 누락 지적 → 즉시 반영
- **다음 단계**: AI Simulation 추가 리서치 → Version A 슬라이드 작성 시작
