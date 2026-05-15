# PLUXITY

**스마트시티 · IoT · 3D 시각화 기반 통합 관제 솔루션**

PLUXITY는 3D 지도 기반의 실시간 IoT 센서 모니터링 및 관제 시스템을 개발하는 팀입니다.

---

## 프로젝트 관리

> 모든 이슈와 작업은 하나의 통합 보드에서 관리됩니다.

### [Platform Dev](https://github.com/orgs/pluxity/projects/24)

전체 프로젝트의 이슈 트래킹, 스프린트 관리, 진행 상황을 한눈에 확인할 수 있습니다.

| 연계 레포지토리 | 설명 |
|----------------|------|
| [pf-frontend](https://github.com/pluxity/pf-frontend) | 프론트엔드 모노레포 |
| [pf-backend](https://github.com/pluxity/pf-backend) | 백엔드 모노레포 |
| [safers](https://github.com/pluxity/safers) | 세이퍼스 V2 프론트엔드 (React) |
| [safers-api](https://github.com/pluxity/safers-api) | 세이퍼스 V2 백엔드 API (Kotlin/Spring Boot) |
| [weekly-report](https://github.com/pluxity/weekly-report) | 주간보고 자동화 |

---

## 메인 프로젝트

### [pf-frontend](https://github.com/pluxity/pf-frontend)

**프론트엔드 모노레포** — React 19, Vite 7, TypeScript 5, Tailwind CSS v4, Turborepo

- **Apps**: yongin-platform-app, yongin-platform-admin, model-gps-tool
- **Packages**: @pf-dev/ui, @pf-dev/map (CesiumJS), @pf-dev/three (R3F), @pf-dev/cctv (HLS/WHEP), @pf-dev/services, @pf-dev/api, @pf-dev/fonts

### [pf-backend](https://github.com/pluxity/pf-backend)

**백엔드 모노레포** — Kotlin 2.3, Spring Boot 4, Java 25, Gradle 9.3

- **Common**: core, auth (RBAC + JWT Cookie), file (S3/Local), messaging (WebSocket/STOMP), test-support
- **Apps**: safers, yongin-platform, weekly-report

### [Hoban-Live-CV](https://github.com/pluxity/Hoban-Live-CV)

**호반건설 라이브 Computer Vision** — 실시간 영상 기반 CV 분석

---

## 팀 문서

### [docs](https://github.com/pluxity/docs)

팀 공통 문서 저장소 — 온보딩, 아키텍처, API 스펙, 인프라 가이드

---

## 서브 프로젝트

| 레포 | 설명 | 비고 |
|------|------|------|
| [weekly-report](https://github.com/pluxity/weekly-report) | LLM 기반 자연어 주간보고 자동화 시스템 | Platform Dev 연계 |
| [safers](https://github.com/pluxity/safers) | 세이퍼스 V2 A2UI 버전 | Platform Dev 연계 |

---

## 진행중 프로젝트

| 레포 | 설명 | 기술 |
|------|------|------|
| [plug-platform-atlas](https://github.com/pluxity/plug-platform-atlas) | 실외 지도 기반 관제 | CesiumJS, React 19 |
| [aiot-api](https://github.com/pluxity/aiot-api) | plug-platform-atlas 백엔드 | Kotlin, Spring Boot |
| [tancheon_poc](https://github.com/pluxity/tancheon_poc) | 탄천 악취모니터링 POC | - |

---

## 인프라 · 내부 도구

| 레포 | 설명 |
|------|------|
| [PlugMTX](https://github.com/pluxity/PlugMTX) | Go 기반 미디어 스트리밍 서버 (MediaMTX Fork) — WebRTC/HLS, PTZ Control |
| [pluxity-issues](https://github.com/pluxity/pluxity-issues) | 전사 이슈 트래커 (GitHub 외부 프로젝트 포함) |

---

## 아카이브

| 레포 | 설명 |
|------|------|
| [plug-platform](https://github.com/pluxity/plug-platform) | 실내 지도 기반 관제 (Cesium + Three.js) |
| [plug-platform-api](https://github.com/pluxity/plug-platform-api) | plug-platform 백엔드 (Java, Spring Boot) |
| [plug-siteguard](https://github.com/pluxity/plug-siteguard) | 호반 용인플랫폼시티 스마트건설 |
| [ktds-jayang](https://github.com/pluxity/ktds-jayang) | KT DS 자양1재정비촉진구역 관제 |
| [KTe-pathFind](https://github.com/pluxity/KTe-pathFind) | KTe 모바일앱 (길찾기/할인정보) |

---

## 기술 스택

### Frontend

| Category | Stack |
|----------|-------|
| Framework | React 19 |
| Language | TypeScript 5 |
| Build | Vite 7, Turborepo |
| Styling | Tailwind CSS v4, Radix UI |
| State | Zustand, SWR |
| Forms | React Hook Form, Zod |
| 3D/Map | CesiumJS, Three.js (R3F) |
| Streaming | HLS.js, WHEP |
| Docs | Storybook 10 |
| Package | pnpm 10 |

### Backend

| Category | Stack |
|----------|-------|
| Language | Kotlin 2.3, Java 25 |
| Framework | Spring Boot 4 |
| ORM | JPA, QueryDSL |
| Auth | RBAC + JWT Cookie |
| Database | PostgreSQL, Redis |
| Protocol | REST API, WebSocket/STOMP, MQTT |
| Build | Gradle 9.3 |
| CI/CD | GitHub Actions |

### Infrastructure

| Category | Stack |
|----------|-------|
| OS | Linux (Ubuntu) |
| Web Server | Nginx |
| Container | Docker |
| Streaming | MediaMTX (PlugMTX) |

---

**© 2026 PLUXITY. All rights reserved.**
