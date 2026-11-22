# 백승규 (Seunggyu Baek)

AI Agent · Backend · Full-Stack Engineer  
- **Portfolio**: [decembaek.com](https://decembaek.com) · [Notion](https://abyssinian-loan-ab8.notion.site/170c59ba90e28093b870ca6db3c79d7d)
- **Email**: tmdrbpp123@gmail.com

---

## Experience

- **제논 — AI Engineer (인턴)** *(2026.06 ~ 2026.11)*
  - 국내 대형 금융사 통합 앱 AI 에이전트 시스템 구축 프로젝트
  - 약 50개 도메인 스킬·MCP 툴 분석·설계·개발 및 툴 명세 4항목 표준화
  - 스킬 목록 `frontmatter` 정렬 순서 고정으로 **에이전트 Prefix Cache 적중률 약 75% → 90% 개선**
  - 약 50개 스킬 시나리오 대상 Python 비동기 E2E 자동화 테스트 및 엑셀→YAML 평가셋 변환 파이프라인 구축
- **글로비트 — 인공지능연구소 풀스택 개발자 (주임)** *(2023.04 ~ 2025.10, 2년 7개월)*
  - PyTorch LSTM 수온 예측 모델 GPU(CUDA) 연산 전환 및 FastAPI·Django 서빙, SSE 실시간 모니터링
  - 스마트 양식·산업안전 R&D: 딥러닝(Pose3D·비전) 서빙, TCP 소켓 장비 제어, Next.js 대시보드
  - React SPA → React Router v7 서버 렌더링 구조 전환 주도 (3명 협업)
  - 사내 첫 Jenkins CI/CD 도입 제안 및 구축 (월 30건+ 수동 배포 작업 자동화)

---

## Featured Projects

| 프로젝트 | 설명 | 기술 스택 | 링크 |
| --- | --- | --- | --- |
| **SocQuery** | 키오스크·PC 원격 장비 관제 (에이전트 ↔ AWS IoT Core mTLS MQTT ↔ API ↔ 대시보드) | Go, TypeScript, Hono, Cloudflare Workers·D1, Next.js | [Agent (Go)](https://github.com/decembaek/socquery-agent-go) · [Backend](https://github.com/decembaek/socquery-saas-backend) |
| **샛별** | 인스타그램 댓글·DM 실시간 자동응답 서비스 (기획·개발) | TypeScript, Meta Webhook, Serverless | [satbyul.com](https://satbyul.com) |
| **SocFlow** | 인스타그램·Threads·유튜브 3개 채널 OAuth 통합 업로드·예약 발행 SaaS | TypeScript, Next.js, OAuth | [socflow.app](https://socflow.app) |
| **Logavio** | 브랜드 입력 → AI SVG 로고·목업 생성 → 편집·다운로드 다국어 플랫폼 | Workers AI, Recraft API, gpt-image | [logavio.com](https://logavio.com/ko) |
| **AI 웹 이용 도우미** | 웹사이트 SDK 위젯 기반 DOM 정보 수집·안내 웹 에이전트 *(개발 진행 중)* | TypeScript, SDK, DOM, Cloudflare Agents, SSE | — |
| **decembaek.com** | 개인 포트폴리오 및 Workers AI(SSE 스트리밍) 자기소개 챗봇 | Astro, Cloudflare Workers AI | [decembaek.com](https://decembaek.com) · [Repo](https://github.com/decembaek/decembaek-portfolio) |
| **BimOps** | Revit 물량 산출 자동화 애드인 (Domain·DataExchange·UI 계층 분리) | C#, WPF, Revit API | [Repo](https://github.com/decembaek/BimOps) |
| **auto_stock_django** | 한국 주식 종목·업종·시세 수집 및 모의투자 백엔드 | Python, Django, DRF, Celery, Redis, MySQL | [Repo](https://github.com/decembaek/auto_stock_django) |
| **card-zip** | 앱인토스 명함 관리 미니앱 MVP | TypeScript, React Native, Granite, TDS | [Repo](https://github.com/decembaek/card-zip) |

---

## Tech Stack

- **AI / LLM**: LLM API (OpenAI, Anthropic), Multi-Agent · MCP Tool 설계, Prefix Cache 최적화, 비동기 E2E 테스트 · LLM Eval, Vector DB, PyTorch(CUDA) · LSTM · Pose3D
- **Backend**: Python (FastAPI, Django REST framework), Go, TypeScript (Node.js, Hono)
- **Frontend**: Next.js, React, React Router v7, TypeScript, Astro
- **Data & Infra**: PostgreSQL, MySQL, Redis, Cloudflare (Workers·Agents·D1), AWS (IoT Core), Serverless, Meta Webhook, Jenkins CI/CD
