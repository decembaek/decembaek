# 백승규 (Seunggyu Baek)

**에이전트를 설계·최적화하고, 기기·서버·대시보드까지 끝까지 구현하는 AI / Full-Stack 엔지니어**

- **Portfolio**: [decembaek.com](https://decembaek.com) · [Notion 포트폴리오](https://abyssinian-loan-ab8.notion.site/170c59ba90e28093b870ca6db3c79d7d)
- **Email**: tmdrbpp123@gmail.com

---

## Experience

- **제논 — AI Engineer (인턴)** *(2026.06 ~ 2026.11)*
  - 국내 대형 금융사 통합 앱 AI 에이전트 시스템 구축 프로젝트 참여
  - 마스터·서브 에이전트 스킬 및 MCP 툴 분석·설계·개발, 툴 명세 4항목 표준화
  - 에이전트 Prefix Cache 구조 개선, 엑셀 → YAML 평가셋 변환 파이프라인 및 E2E 자동화 테스트 구축
- **글로비트 — 인공지능연구소 풀스택 개발자 (주임)** *(2023.04 ~ 2025.10, 2년 7개월)*
  - 스마트 양식·산업안전 R&D: 딥러닝(LSTM·Pose3D·비전) 모델 FastAPI/Django 서빙, TCP 소켓 장비 제어, SSE 모니터링, Next.js 대시보드
  - React SPA → React Router v7 서버 렌더링 구조 전환 주도
  - 사내 첫 Jenkins CI/CD 도입 제안 및 구축 (월 30건+ 수동 배포 작업 자동화)

---

## Featured Projects

| 프로젝트 | 설명 | 기술 스택 | 링크 |
| --- | --- | --- | --- |
| **SocQuery** | 키오스크·PC 원격 장비 관제 (에이전트 ↔ AWS IoT Core mTLS MQTT ↔ API ↔ 대시보드) | Go, TypeScript, Hono, Cloudflare Workers·D1, Next.js | [Agent (Go)](https://github.com/decembaek/socquery-agent-go) · [Backend](https://github.com/decembaek/socquery-saas-backend) |
| **SocFlow** | 인스타그램·Threads·유튜브 3개 채널 통합 업로드·예약 발행 SaaS | TypeScript, Next.js, OAuth | [socflow.app](https://socflow.app) |
| **Logavio** | 브랜드 입력 → AI SVG 로고·목업 생성 → 편집·다운로드 다국어 플랫폼 | Workers AI, Recraft API, gpt-image | [logavio.com](https://logavio.com/ko) |
| **AI 웹 이용 도우미** | 고객사 웹사이트 채팅·음성·AI 커서 안내 및 스킬 관리 하네스 *(개발 중)* | TypeScript, Cloudflare Agents, SSE | — |
| **decembaek.com** | 개인 포트폴리오 및 Workers AI(SSE 스트리밍) 자기소개 챗봇 | Astro, Cloudflare Workers AI | [decembaek.com](https://decembaek.com) · [Repo](https://github.com/decembaek/decembaek-portfolio) |
| **BimOps** | Revit 물량 산출 자동화 애드인 (Domain·DataExchange·UI 계층 분리) | C#, WPF, Revit API | [Repo](https://github.com/decembaek/BimOps) |
| **auto_stock_django** | 한국 주식 종목·업종·시세 수집 및 모의투자 백엔드 | Python, Django, DRF, Celery, Redis, MySQL | [Repo](https://github.com/decembaek/auto_stock_django) |
| **card-zip** | 앱인토스 명함 관리 미니앱 MVP | TypeScript, React Native, Granite, TDS | [Repo](https://github.com/decembaek/card-zip) |

---

## Tech Stack

- **AI / LLM**: LLM API (OpenAI, Anthropic), Multi-Agent · MCP Tool 설계, Prompt / Prefix Cache 최적화, LLM Eval & E2E 테스트, Vector DB, LSTM / Vision 모델 서빙
- **Backend**: Python (FastAPI, Django REST framework), Node.js, TypeScript (Hono), Go
- **Frontend**: Next.js, React, React Router v7, TypeScript, Astro
- **Data & Infra**: PostgreSQL, MySQL, Redis, Cloudflare Workers · D1, AWS (IoT Core), Jenkins CI/CD
