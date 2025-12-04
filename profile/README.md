# PLUXITY

**스마트시티 · IoT · AI 기반 통합 관제 솔루션**

PLUXITY는 3D 지도 기반의 실시간 IoT 센서 모니터링 및 관제 시스템을 개발하는 팀입니다.

---

## 팀 문서

📚 **[팀 공통 문서](https://github.com/pluxity/docs)**
- 온보딩 가이드
- 개발 환경 셋업
- PR 및 코드 리뷰 가이드
- 아키텍처 문서
- 인프라 운영 가이드

---

## Frontend

### 🎨 [pf-dev](https://github.com/pluxity/pf-dev)
**PLUXITY 공통 디자인 시스템**
- React 19 + TypeScript + Tailwind CSS v4
- Atomic Design 패턴 (65개 컴포넌트)
- Radix UI Primitives + CVA (class-variance-authority)
- Storybook 8 문서화
- Monorepo 구조 (Turborepo + pnpm)

### 🏗️ [plug-siteguard](https://github.com/pluxity/plug-siteguard)
**스마트 건설 현장 관제 시스템**
- React 19 + TypeScript + Tailwind CSS v4
- Monorepo 구조 (Turborepo + pnpm)
- Atomic Design 기반 UI 컴포넌트 라이브러리
- Storybook 8 문서화
- 용인 플랫폼시티 스마트시티 프로젝트

### 🗺️ [plug-platform-atlas](https://github.com/pluxity/plug-platform-atlas)
**실외 지도 기반 관제 시스템**
- Cesium.js 3D 지도 기반 IoT 센서 실시간 모니터링
- React 19 + TypeScript + Tailwind CSS v4
- Monorepo 구조 (Turborepo + pnpm)

### 🌐 [plug-platform](https://github.com/pluxity/plug-platform)
**실내 지도 기반 관제 시스템**
- React 기반 실내 지도 관제 시스템
- 실시간 IoT 센서 모니터링 및 제어

---

## Backend

### ⚙️ [plug-platform-api](https://github.com/pluxity/plug-platform-api)
**통합 관제 API 서버**
- Spring Boot 3 + Java 17
- JPA + QueryDSL
- Spring Security + JWT
- PostgreSQL + Redis
- [API 문서](http://dev.pluxity.com/api/api-docs) · [Swagger UI](http://dev.pluxity.com/api/swagger-ui/index.html)

### 🤖 [a-iot](https://github.com/pluxity/a-iot)
**IoT 디바이스 연동 서버**
- Spring Boot 3 + Java 17
- MQTT / WebSocket 기반 실시간 통신
- IoT 센서 데이터 수집 및 처리

---

## 기술 스택

### Frontend
| Category | Stack |
|----------|-------|
| Framework | React 19 |
| Language | TypeScript |
| Styling | Tailwind CSS v4, CVA |
| UI Components | Radix UI Primitives |
| State | Zustand, SWR |
| Forms | React Hook Form, Zod |
| 3D/Map | Cesium.js |
| Docs | Storybook 8 |
| Build | Vite, Turborepo |
| Package | pnpm |

### Backend
| Category | Stack |
|----------|-------|
| Framework | Spring Boot 3 |
| Language | Java 17 |
| ORM | JPA, QueryDSL |
| Security | Spring Security, JWT |
| Database | PostgreSQL, Redis |
| Protocol | REST API, MQTT, WebSocket |

### Infrastructure
| Category | Stack |
|----------|-------|
| OS | Linux (Ubuntu) |
| Web Server | Nginx |
| Container | Docker |
| Process | PM2 |

---

## 기타 프로젝트

### 🏗️ KT DS 자양1정비촉진구역 관제 프로젝트
- [ktds-jayang](https://github.com/pluxity/ktds-jayang): 관제 시스템
- [KTe-pathFind](https://github.com/pluxity/KTe-pathFind): 모바일 앱 (길찾기/할인정보)

### 🌊 [tancheon_poc](https://github.com/pluxity/tancheon_poc)
탄천 POC 프로젝트

---

**© 2025 PLUXITY. All rights reserved.**
