## 안녕하세요, 유선영입니다. 
안정적인 금융/인증 도메인부터 트렌디한 AI Agent 및 실시간 통신 시스템까지, 비즈니스 문제를 아키텍처로 해결하는 것을 즐깁니다.

## 🛠️ 기술 스택 (Tech Stack)

| 분류 | 기술 / 도구 |
| :--- | :--- |
| **언어 (Languages)** | ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) |
| **백엔드 (Backend)** | ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white) ![JUnit5](https://img.shields.io/badge/JUnit5-f5f5f5?style=for-the-badge&logo=junit5&logoColor=dc524a) |
| **프론트엔드 (Frontend)** | ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) |
| **데이터베이스 & 캐시** | ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) |
| **서버 & 인프라** | ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) |
| **형상관리 & CI/CD** | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white) ![Gitea](https://img.shields.io/badge/Gitea-34495E?style=for-the-badge&logo=gitea&logoColor=5D9425) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) |
| **AI / LLM** | ![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white) ![Qwen](https://img.shields.io/badge/Qwen-6950EF?style=for-the-badge&logo=qwen&logoColor=white) |

---

## 🎯 핵심 역량 (Core Competencies)
5년간 다양한 비즈니스 도메인을 리딩하며 아래의 엔지니어링 문제를 해결해 왔습니다.

* **금융 및 전자서명인증 도메인 스페셜리스트**
  * OAuth 2.0 / OIDC 표준 기반 대내외 연동 인증 시스템 설계 및 구축
  * 공개키 암호학(PKI) 기반 서명 검증 및 인증서 체인 처리 모듈 라이브러리화
* **오픈 API & 트래픽 통제 아키텍처**
  * 대규모 대외 기관 연동을 위한 API Gateway 설계 (Rate Limiting, IP White-list 제어)
  * 다중 테넌트(Multi-tenancy) 환경의 B2B SaaS 결제 및 크라우드펀딩 시스템 안정화
* **폐쇄망(Air-Gapped) 및 가상화 인프라 환경 대응**
  * 대내외 망분리 및 방화벽 제약 환경에서의 백엔드 아키텍처 수립 경험
  * 사내 프라이빗 저장소(GitLab, Gitea) 운영 및 컨테이너(Docker) 기반 자립형 빌드/배포 자동화
* **실시간 통신 및 최신 기술 융합**
  * WebSocket과 Redis Pub/Sub을 결합한 대규모 실시간 채팅/상담 인프라 구축
  * LLM 오케스트레이션 도구를 활용한 AI Agent 기반 가상 워크플로우 자동화 구현

---

## 🚀 진행 중인 프로젝트 (Featured Projects)
*각 프로젝트는 금융권 수준의 엄격한 브랜치 전략(Git Flow), PR 템플릿, 코드 퀄리티를 지향하며 빌드 중입니다.*

### 1️⃣ [B2B SaaS 기반 크라우드펀딩 및 전자서명 플랫폼]
> **Key 테마:** `금융인증`, `오픈 API`, `폐쇄망 대응`, `결제 시스템`
* **Overview:** 기업 고객을 위한 멀티테넌시 구조의 펀딩 시스템으로, 엄격한 네트워크 제한 환경을 고려한 아키텍처입니다.
* **Core:** 
  * OAuth 2.0/OIDC 기반 인증 서버 및 PKI 전자서명 계약 검증 엔진 구현
  * API Gateway 단에서의 Throttling 및 트래픽 제어 정책 적용
  * 인터넷이 차단된 폐쇄망 환경 배포를 위한 배포 자동화(CI/CD) 스크립트화

### 2️⃣ [AI Agent 연동 실시간 고객 응답 및 협업 솔루션]
> **Key 테마:** `AI Agent`, `채팅-웹소켓`, `대규모 커넥션 튜닝`
* **Overview:** 대규모 실시간 트래픽 환경에서 AI가 사용자의 요청을 분석하고 스스로 문제를 해결하는 지능형 채팅 인프라입니다.
* **Core:**
  * WebSocket + Redis Pub/Sub 구조를 통한 분산 환경에서의 실시간 동기화
  * 리눅스 서버 환경에서의 커넥션 포트 및 파일 디스크립터 최적화
  * 사용자의 발화를 파악해 정산/인증 API를 자동 수행하는 AI 에이전트 워크플로우 구축

---
📫 **Contact & Links**
* **Email:** seonyoungyoo@gmail.com
* **Blog:** seonyoungyoo.github.io
