# Zero-to-One Advisor

IT/AI 업계 PM 출신, YC Batch 경험이 있는 초기 스타트업 전문가 에이전트입니다.

## 핵심 역할

1. **아이디어 검증 컨설팅**: 고객 가설(문제 및 솔루션)을 체계적으로 검증
2. **랜딩 페이지 컨설팅**: 검증 목적의 랜딩 페이지 구축
3. **Sales Deck 컨설팅**: 초기 고객 영업을 위한 Sales Deck 작성
4. **AI 트렌드 분석**: IT/AI 업계 최신 트렌드 분석

## 멘토

- **Eric Ries**: Lean Startup, Build-Measure-Learn, MVP
- **Peter Thiel**: Zero to One, Contrarian Thinking, Distribution
- **Paul Graham**: Make Something People Want, Do Things That Don't Scale

## 설치 가이드

1. 이 디렉토리를 별도 프로젝트로 사용합니다 (Claude Code에서 `cd experts/zero-to-one-advisor`)
2. Claude Code를 실행하면 `CLAUDE.md`가 자동으로 로드됩니다
3. 핵심 명령어를 사용하여 컨설팅을 시작합니다

## MCP 설정

startup-researcher subagent가 YouTube MCP 서버를 사용합니다. 다음 환경 변수를 설정해야 합니다:

| 환경 변수 | 설명 |
|-----------|------|
| `YOUTUBE_API_KEY` | YouTube Data API v3 키 ([Google Cloud Console](https://console.cloud.google.com/)에서 발급) |

설정 후 `claude mcp list`로 youtube-data 서버 연결을 확인합니다.

## 사용법

```bash
# 아이디어 검증 컨설팅
/idea-validation-consulting

# 랜딩 페이지 컨설팅
/landing-page-consulting

# Sales Deck 컨설팅
/sales-deck-consulting

# AI 트렌드 분석
/ai-trend-analysis
```

## 프로젝트 구조

```
zero-to-one-advisor/
├── CLAUDE.md                    # 전문가 상시 컨텍스트
├── README.md                    # 본 파일
├── references/                  # CLAUDE.md 참조 가이드
├── .claude/
│   ├── skills/                  # 4개 핵심 skill
│   │   ├── idea-validation-consulting/
│   │   ├── landing-page-consulting/
│   │   ├── sales-deck-consulting/
│   │   └── ai-trend-analysis/
│   └── agents/                  # startup-researcher subagent
├── memory/                      # Memory 시스템
└── knowledge/                   # Knowledge 시스템 (5개 카테고리)
```

## Knowledge 카테고리

| 카테고리 | 설명 | topic 수 |
|----------|------|----------|
| idea-validation | 아이디어 검증 방법론 | 4 |
| validation-case-studies | 검증 사례 연구 | 4 |
| startup-sales | 스타트업 영업/Sales Deck | 3 |
| ai-startup-trends | AI 스타트업 트렌드 | 1 |
| mentor-philosophy | 멘토 철학 (Ries, Thiel, Graham) | 3 |
