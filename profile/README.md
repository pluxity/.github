# PLUXITY

**스마트시티 · IoT · 3D 시각화 기반 통합 관제 솔루션**

PLUXITY는 3D 지도 기반의 실시간 IoT 센서 모니터링 및 관제 시스템을 개발하는 팀입니다.

---

## 팀 문서 · 프로젝트 보드

| 링크 | 설명 |
|------|------|
| 📚 **[docs](https://github.com/pluxity/docs)** | 팀 공통 문서 (온보딩, 아키텍처, API, 인프라) |
| 📋 **[PF FrontEnd Board](https://github.com/orgs/pluxity/projects/17)** | 프론트엔드 팀 프로젝트 관리 |
| 📋 **[PF BackEnd Board](https://github.com/orgs/pluxity/projects/20)** | 백엔드 팀 프로젝트 관리 |

---

## 핵심 레포지토리

### 🎨 [pf-frontend](https://github.com/pluxity/pf-frontend)

**PF DEV 프론트엔드 모노레포**

- **Apps**: yongin-platform-app, yongin-platform-admin, model-gps-tool, isr
- **Packages**: @pf-dev/ui, @pf-dev/map (CesiumJS), @pf-dev/three (R3F), @pf-dev/cctv (HLS/WHEP), @pf-dev/services, @pf-dev/api, @pf-dev/fonts
- **Stack**: React 19, Vite 7, TypeScript 5, Tailwind CSS v4, Storybook 10, Turborepo, pnpm 10

### ⚙️ [pf-backend](https://github.com/pluxity/pf-backend)

**PF DEV 백엔드 모노레포**

- **Common**: core, auth (RBAC + JWT Cookie), file (S3/Local), messaging (WebSocket/STOMP), test-support
- **Apps**: safers, yongin-platform
- **Stack**: Kotlin 2.3, Spring Boot 4, Java 25, Gradle 9.3, GitHub Actions CI/CD

### 📡 [PlugMTX](https://github.com/pluxity/PlugMTX)

**미디어 스트리밍 서버 (MediaMTX Fork)**

- Go 기반, WebRTC/HLS Dashboard, PTZ Control
- Hikvision ISAPI 연동

---

## 프로젝트별 레포지토리

| 레포 | 설명 | 기술 |
|------|------|------|
| [plug-platform-atlas](https://github.com/pluxity/plug-platform-atlas) | 실외 지도 기반 관제 | CesiumJS, React 19 |
| [aiot-api](https://github.com/pluxity/aiot-api) | plug-platform-atlas 백엔드 | Kotlin, Spring Boot |
| [plug-siteguard](https://github.com/pluxity/plug-siteguard) | 용인플랫폼시티 스마트건설 | React 19, Tailwind v4 |

---

## 아카이브 / 레거시

| 레포 | 설명 |
|------|------|
| [plug-platform](https://github.com/pluxity/plug-platform) | 실내 지도 기반 관제 (Cesium + Three.js) |
| [plug-platform-api](https://github.com/pluxity/plug-platform-api) | plug-platform 백엔드 (Java, Spring Boot) |
| [tancheon_poc](https://github.com/pluxity/tancheon_poc) | 탄천 POC |

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

## 내부 도구

| 도구 | 설명 |
|------|------|
| [weekly-report](https://github.com/pluxity/weekly-report) | LLM 기반 주간보고 자동화 시스템 |
| [docs](https://github.com/pluxity/docs) | 팀 공통 문서 (온보딩, 아키텍처, API, 인프라) |

---

**© 2026 PLUXITY. All rights reserved.**
