## 기술 선택의 이유를 끝까지 고민하고 그 흔적을 프로젝트에 코드로 남기는 백엔드 개발자입니다.

## 🔍 About Me

- 🎓 Samsung SSAFY 14기 · 삼성 SW 역량평가 A형
- ⚙️ Java / Spring Boot 기반 백엔드 개발자를 목표로 공부하고 있습니다
- 🏆 SSAFY 우수 프로젝트 수상 (The Interview)

---

## 🛠 Tech Stack

| | |
|---|---|
| **Language** | ![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| **Framework** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white) ![WebFlux](https://img.shields.io/badge/WebFlux-6DB33F?style=flat&logo=spring&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat) ![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) |
| **Infra / Tools** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white) |

---

## ✨ Featured Projects

### 1. The Interview — AI 기반 실시간 음성 인터뷰 서비스

> 2026.02 – 2026.03 · 5인 팀 · 백엔드 담당  
> `Spring Boot` `Spring WebFlux` `WebSocket(STOMP)` `Redis` `PostgreSQL` `FastAPI` `AWS` `Docker` `Jenkins`

- **Redis Sorted Set + Mono.zip() 병렬화**로 비동기 STT 순서 보장 및 청크 선행 처리 구현 — STT 대기 **2500ms → 1000ms**, 전체 응답 **5.5초 → 4초** 단축 (BE 단독 기여)
- **Facade 패턴**으로 트랜잭션 경계 분리, AI 호출 구간 DB 커넥션 점유 제거 — Spring @Transactional AOP 프록시 내부 호출 문제를 구조적으로 해소
- WebSocket/HTTP 동시 실행 **Race Condition**을 **Redis TTL 락**으로 해결 — 데이터 무결성 확보 및 서버 장애 시 자동 해제 보장

🏆 삼성 SSAFY 프로젝트 우수상  
👉 [프로젝트 레포 링크] · [팀 노션 / 발표 자료 링크]

---

### 2. 이웃집 웰리 — AI 기반 맞춤형 복지 정보 통합 서비스

> 2026.01 – 2026.02 · 6인 팀 · 백엔드 담당  
> `Spring Boot` `Spring Data JPA` `MySQL` `FastAPI` `AWS` `Docker` `Jenkins`

- **Fetch Join + 로컬 캐시** 도입으로 N+1 문제 해결 및 캐시 전략 설계 (변하는 데이터 / 변하지 않는 데이터 분리) — 응답속도 **620ms → 20ms** 단축
- **CompletableFuture 커스텀 ExecutorService**로 외부 AI API 40건 병렬 처리 — ForkJoinPool 공유 사이드이펙트 방지를 위해 전용 풀 격리, 응답시간 **60s → 6s** 단축
- **Schema-First + ddl-auto validate** 도입 주도 — 팀 전체 스키마 불일치로 인한 빌드 실패율 **0%** 달성

👉 [프로젝트 레포 링크] · [팀 노션 / 발표 자료 링크]

---

## 🎓 Experience

| 기간 | 내용 |
|---|---|
| 2025.07 – 2026.06 | 삼성청년SW/AI아카데미 (SSAFY) 14기 · Web 풀스택 과정 |

---

## 📜 Certifications

- 삼성 SW 역량평가 A형
- SQLD

---

## 📊 Stats

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=rlawhdals33)](https://solved.ac/rlawhdals33/)
