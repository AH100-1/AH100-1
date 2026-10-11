## 박상우 · Backend Developer

AI 스타트업에서 B2B SaaS의 **프로덕션 백엔드**를 개발했습니다. 서비스를 멈추지 않고 안전하게 바꾸는 일에 관심이 많습니다.
대량 발송 큐, 인증 보안, 외부 연동을 다뤄 왔고, 연구 프로젝트에서는 측정으로 가설을 검증해 왔습니다.

- 💼 **GRINDA AI** 풀스택 인턴 (2025.12 – 2026.04) — B2B AI 세일즈 자동화 SaaS [Rinda](https://rinda.ai)
- 🎓 충남대학교 컴퓨터융합학부 (블록체인 부전공) · 2027.02 졸업예정
- 🏫 NHN Academy 백엔드 7기
- 🛰️ NET 챌린지 캠프 시즌13 본선 진출 · 최종 발표 예정
- 📜 SQLD

### 💼 Work — GRINDA AI (Rinda)
- **대량 메일 발송 인프라**
  - 플랜별 일일·월간 한도와 50건/3분 분산 발송을 만들었습니다.
  - BullMQ에서 잡이 유실되면 감지해 복구하는 로직을 넣었습니다.
- **보안 강화**
  - 토큰을 HS256 서명 JWT로, API 키 암호화를 AES-256-GCM으로 무중단 전환했습니다.
  - 워크스페이스 데이터 노출, XSS 취약점을 수정하고 Cloudflare Turnstile을 단계적으로 도입했습니다.
- **SSE 결과 유실 해결**: 세션별 이벤트 버퍼와 폴링 복구 방식을 설계했습니다.
- `Bun` `Elysia` `PostgreSQL` `Drizzle` `Redis` `BullMQ` `React`

### 🚀 Projects
| 프로젝트 | 내용 | 기술 |
|---|---|---|
| [**chaekmate**](https://github.com/nhnacademy-be11-1) | MSA 온라인 서점 (NHN Academy 팀). 포인트·리뷰 도메인 담당. 이력 원장 방식의 포인트, `AFTER_COMMIT` 이벤트 기반 적립·복구 | Spring Boot 3, Spring Cloud, JPA, Redis, RabbitMQ |
| [**SkyLens 3D**](https://github.com/AH100-1/cumulus3d) | 드론 편대 영상 3D 복원 (NET 챌린지). COLMAP/GLOMAP, 3DGS 실험, V100 HPC 이식. Rust 점진 복원 엔진 | Python, Rust, CUDA, Slurm |
| [**PawFeeder**](https://github.com/pet-project-1/pet-project) | 보호소 개체 인식 자동 급식기. 웹과 Supabase 담당 | React, Supabase, pgvector, YOLOv8 |

### 🛠 Tech Stack
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
<br/>
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![Elysia](https://img.shields.io/badge/Elysia-7C3AED?style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### 📫 Contact
- dev.parksangwoo@gmail.com
