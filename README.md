<div align="center">

# 신현수 · Shin Hyun Soo

**1%의 정확도 향상과 1초의 지연 단축에 집착합니다**

AI 제품을 만들고, 측정하고, 운영합니다 —
생성 파이프라인부터 RAG 평가 루프, 배포 후 품질 모니터링까지 수명주기 전체를 직접 완주합니다.

[![Email](https://img.shields.io/badge/shyunsu3%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:shyunsu3@gmail.com)
[![AIM Live](https://img.shields.io/badge/AIM_Live-qaaimsync.com-2563EB?logo=googlechrome&logoColor=white)](https://qaaimsync.com)

</div>

---

## 🔭 대표 프로젝트 — [AIM](https://github.com/Shin-H-S/AIM)

> **"이번 배포, 이전보다 정말 나아졌을까?"**

배포 후 웹서비스의 품질 변화를 근거 기반으로 판단하는 **AI 품질 모니터링 플랫폼**입니다.
기획·설계부터 배포·운영까지 혼자 완주해 [qaaimsync.com](https://qaaimsync.com)에서 실서비스 중이며,
**AIM이 AIM 자신을 첫 프로젝트로 등록해 스스로를 모니터링합니다.**

- 검사 하나로 **가용성 · SSL · Lighthouse 성능 · Playwright 사용자 흐름**을 측정하고, 결정론적 점수로 배포 간 회귀를 감지
- **LLM은 서술만, 판단은 코드가** — 수집된 근거만으로 원인과 조치를 진단하는 evidence 기반 AI 리포트
- CI 배포 훅으로 배포 직후 자동 검사, Oracle Cloud A1(ARM) 단일 VM에서 Docker Compose 운영 — GCP에서 데이터 무손실 이전 완주

`FastAPI` · `Next.js 16` · `Celery/Redis` · `Playwright` · `Lighthouse` · `Claude API` · `PostgreSQL`

**커밋 260+ · 머지 PR 111 · 테스트 460+**

> 🚧 **지금은 조사 에이전트를 개발 중** — 인시던트가 나면 도구 루프로 검사 결과를 직접 조사해
> 원인을 7유형으로 분류하고 조치를 제안하는 LLM 에이전트. 평가부터 먼저 — 실측 사고를 포함한
> 평가셋 105건과 코드 채점기를 완성하고, 규칙 베이스라인(정확도 91~94%)을 목표선으로 고정했습니다.

## 👥 팀 프로젝트

| 프로젝트 | 역할 | 한 일 · 결과 |
|---|---|---|
| **[Bidcoin](https://github.com/BidMind/Bidcoin)**<br>공공조달 RFP 분석 RAG | RAG 코어<br>(5인 팀) | embedding·retriever·reranker·RAG API v2→v4 구현, LLM-as-Judge 평가 루프(47문항·6지표) 11회 반복 — correctness **0.425 → 0.782 (+84%)**, context recall **+48.6%** |
| **[Go_Gachi](https://github.com/Shin-H-S/Go_Gachi)**<br>소상공인 AI 광고 크리에이티브 생성 | 팀장<br>BE 파이프라인 | 이미지 생성 파이프라인 설계, 타이밍 로그로 구간별 병목 실측, 생성 응답 base64 → URL 전환으로 페이로드 **2.12MB → 0.3KB** |
| **[알약 객체 탐지](https://github.com/Shin-H-S/Code_it-Basic-Project)**<br>YOLOv11 경구약 이미지 탐지 | 모델·실험 리드<br>(공동) | copy-paste 증강 파이프라인 구현, 증강 조합 통제 실험으로 mAP50-95 **+1.4~1.5%p** — Kaggle Public **0.95581** (mAP@[0.75:0.95]) |

## 🛠 기술 스택

| 영역 | 스택 |
|---|---|
| **AI/ML** | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![YOLOv11](https://img.shields.io/badge/YOLOv11-111F68) ![FAISS](https://img.shields.io/badge/FAISS-0467DF) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FC521F) ![Claude API](https://img.shields.io/badge/Claude_API-D97757?logo=anthropic&logoColor=white) ![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?logo=openai&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?logo=redis&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?logo=celery&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-087EA4?logo=react&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white) |
| **Infra** | ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?logo=oracle&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white) ![Lighthouse](https://img.shields.io/badge/Lighthouse-F44B21?logo=lighthouse&logoColor=white) |

---

<div align="center">

이 페이지의 모든 숫자는 저장소 커밋 · 평가 로그 · 리더보드에서 실측한 값입니다.

📫 [shyunsu3@gmail.com](mailto:shyunsu3@gmail.com)

</div>
