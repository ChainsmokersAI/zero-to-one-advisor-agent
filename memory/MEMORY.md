# Zero-to-One Advisor Memory

## 프로젝트 현황

- **버전**: 초기 구축 완료 (2026-03-16) → service-context.md 추가 (2026-03-17)
- **구조**: 4개 skill (idea-validation-consulting, landing-page-consulting, sales-deck-consulting, ai-trend-analysis) + 1개 subagent (startup-researcher) + Memory + Knowledge (5개 카테고리, 15개 topic)
- **멘토**: Eric Ries, Peter Thiel, Paul Graham
- **컨설팅 대상**: 콕스웨이브(Coxwave)의 AI 서비스 QA 자동화 서비스 — 아이디어 검증 단계, MVP 개발 중 (상세: [service-context.md](service-context.md))

## 다음 세션 할 일

- service-context.md 보완: 사용자가 핵심 포인트, 검증 현황, 리스크/걱정되는 점 등 추가 정보를 제공할 예정 — 제공받는 대로 service-context.md에 반영
- 랜딩 페이지 초안 작성: 사용자가 "내일까지 랜딩 페이지 초안 작성 필요"라고 언급 (2026-03-17 기준)

## 핵심 교훈

### Memory/Knowledge 운영

- Memory 기록 순서: MEMORY.md → 하위 파일들(task-log, lessons-learned, user-preferences) → auto memory
- 프로젝트 memory/가 auto memory보다 항상 우선
- Knowledge 규칙 4번의 두 의무(사전 확인 + 사후 기록)는 독립적이다 — 하나만 지키면 되는 것이 아니라 둘 다 매번 지켜야 한다
- 세션 재시작이 필요한 작업 시, 반드시 미완료 작업을 MEMORY.md `## 다음 세션 할 일`에 기록한 후 종료해야 한다 (세션 핸드오프)
- Knowledge 카테고리명은 내용을 즉시 파악할 수 있도록 구체적으로 명명해야 한다

### 범용 원칙

- 사용자의 용어를 자의적으로 해석하지 않는다 — 범위를 정확히 확인하고 반영해야 한다
- 교훈의 핵심 원리를 이해하고, 예시에 과도 집중하지 않는다

## 자주 하는 실수

| 실수 | 해결법 |
|------|--------|
| Memory 기록 누락 | 모든 작업 완료 후 반드시 Memory 업데이트 — MEMORY.md의 **최근 완료** 필드를 포함하여 task-log, lessons-learned 등 하위 파일도 빠짐없이 |
| 프로젝트 memory 우선순위 역전 | 기록 순서: 프로젝트 memory/ 먼저 → auto memory 그 다음. 절대 뒤바꾸지 않는다 |
| Knowledge index.md topic 수 미갱신 | topic 파일 추가 시 반드시 루트 index.md의 topic 수도 함께 갱신 |
| 사용자 요청 처리 시 knowledge/ 미확인 | 반드시 knowledge/를 먼저 확인한 후 작업을 시작한다. 확인 없이 작업을 시작하지 않는다 |
| 웹 서칭 후 knowledge 업데이트 누락 | 웹 서칭을 수행했으면, 작업 완료 전 반드시 knowledge topic을 생성/업데이트한다 |
| 세션 재시작 전 미완료 작업 미기록 | 세션 핸드오프: MEMORY.md `## 다음 세션 할 일`에 미완료 작업 + 배경 맥락을 기록한 후 종료한다 |
| 사용자 후속 약속/의도를 "다음 세션 할 일"에 미기록 | 사용자가 "다음에 ~하겠다", "나중에 ~제공하겠다" 등 후속 작업을 언급하면, 즉시 "다음 세션 할 일"에 기록한다 |
| MEMORY.md 버전/현황 필드 미갱신 | 새 파일 추가, 구조 변경 등 프로젝트에 변화가 있으면, 반드시 프로젝트 현황(버전 등)을 함께 갱신한다 |

## 사용자 핵심 선호

- 구체적 피드백을 주고받으며 점진적 개선하는 방식
- 근거 기반 + 비판적 사고 + 불확실성 명시를 최우선 원칙으로
- 전문 용어는 원문 표기 (skill, subagent 등)
- 파일 수정 시 기존 문체(~합니다 등) 반드시 유지
- Git Push 대상 프로젝트이므로 개인 정보(이름, 이메일 등) 파일에 포함 금지
- 메모리 시스템을 최우선으로 중시 — 모든 작업 후 반드시 전체 점검(task-log, 실수, 교훈, 선호도) 수행

## 참조

- [service-context.md](service-context.md): 컨설팅 대상 서비스 맥락 (회사, 문제/솔루션 가설, 현재 단계)
- [task-log.md](task-log.md): 작업 이력
- [lessons-learned.md](lessons-learned.md): 학습 기록
- [user-preferences.md](user-preferences.md): 사용자 선호도
