# Hi, I'm Minjun Song (송민준)

**AI 연동과 비동기 데이터 처리를 직접 구현하는 백엔드 개발자**입니다.

단순히 기능을 구현하기보다, 재시도·중복·실패 같은 **경계 상황을 먼저 설계**하는 데 집중합니다.
'왜 느린가 / 왜 중복되는가'를 끝까지 추적해 원인을 고치는 것을 좋아하고,
TDD로 백엔드 테스트 186개·라인 커버리지 약 85%를 유지하며 검증하는 습관을 들였습니다.

---

## Tech Stack

**Languages**

<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

**Backend**

<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>

**Database**

<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white"/>

**Messaging / DevOps**

<img src="https://img.shields.io/badge/Amazon%20SQS-FF4F8B?style=for-the-badge&logo=amazonsqs&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>

---

## Projects

### [WorldDeveloper](https://github.com/Minjun1023/WorldDeveloper) — 해외 취업 지향 개발자 채용 플랫폼 (개인 프로젝트)
비자 스폰서십·원격 근무가 가능한 해외 채용 공고를 자동 수집·정규화해 한국 개발자에게 맞춤 추천하는 풀스택 플랫폼. ATS·잡보드 11종 커넥터 ETL, sentence-transformers 임베딩(pgvector) 기반 추천, 공식 명부 대조 + LLM 비자 판별을 1인으로 구현했습니다.
`Java / Spring Boot` · `Python / FastAPI` · `Next.js` · `PostgreSQL(pgvector)` · `Redis` · `Docker`
[GitHub](https://github.com/Minjun1023/WorldDeveloper) · [배포](https://152.67.215.221.sslip.io/)

### [TripKey](https://github.com/TripKey/tripkey-main) — 여행 메모를 일정표로 만들어주는 서비스 (구름 딥다이브 백엔드 과정 · 4인 팀, 백엔드 담당)
여행 메모를 붙여넣으면 AI가 장소를 추출·그룹화하고 이동시간까지 계산해 하루 단위 일정표로 만들어주는 서비스. AWS SQS + Transactional Outbox로 비동기·멱등 처리(데이터 손실 0), PostGIS 공간쿼리(ST_ClusterDBSCAN) 그룹화, 외부 경로 API 캐시를 담당했습니다.
`Java / Spring Boot` · `Spring Data JPA · PostGIS` · `AWS SQS` · `Python / FastAPI` · `Testcontainers`
[GitHub](https://github.com/TripKey/tripkey-main) · [배포](https://usetripkey.com/)

### [얼마나 알아](https://github.com/Minjun1023/Ulmana-Al-a-Server) — 상식 학습 퀴즈 앱 백엔드 (교내 졸업 프로젝트 · 백엔드 담당)
장르별 상식 문제를 시험·퀴즈·스피드 모드로 풀고 랭킹을 겨루는 학습 앱의 REST API 서버. JWT 인증, 점수/랭킹 집계, 정답률 기반 취약 문제 추천을 구현했고 NGINX·Gunicorn으로 AWS EC2에 직접 배포·운영했습니다.
`Python / Django · DRF` · `SimpleJWT` · `MySQL` · `Gunicorn`
[GitHub](https://github.com/Minjun1023/Ulmana-Al-a-Server)

---

## Contact

- **Email**: songmj5000@naver.com
- **GitHub**: [github.com/Minjun1023](https://github.com/Minjun1023)
