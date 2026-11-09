<h1 align="center">안녕하세요, 홍성찬입니다 👋</h1>
<p align="center"><b>운영 환경을 먼저 생각하는 백엔드 개발자</b></p>

<p align="center">
㈜현대벤디스에서 7개월간 운영 중인 Spring 서비스를 유지보수했습니다.<br>
동시성 제어와 성능 최적화에 관심이 많아, 문제가 생기면 부하 테스트로 직접 재현하고 원인을 찾아 해결합니다.
</p>

<br>

## 🛠 기술 스택

**Backend**<br>
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Database**<br>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)

**Frontend**<br>
![React](https://img.shields.io/badge/React-181717?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**Data**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**Cloud**<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)

**Etc**<br>
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![JMeter](https://img.shields.io/badge/Apache%20JMeter-D22128?style=flat-square&logo=apachejmeter&logoColor=white)

<br>

## 📌 프로젝트

### 🎫 실시간 티켓 예매 시스템
`개인 · 2026.04 – 2026.06` · Spring Boot · JPA · JWT · JMeter

동시 예매 상황을 가정한 콘서트 좌석 예매 시스템입니다. JMeter로 1,000개 동시 요청을 걸어 중복 예매를 재현하고 JPA Optimistic Lock으로 막았습니다. 다시 측정하다 드러난 500 응답은 409로 바꾸고 MySQL 데드락은 쿼리 실행 순서를 바꿔 해결해, 서버 도달 기준 500 응답을 478건에서 0건으로 줄였습니다. Dependabot으로 의존성 CVE 경고 87건을 점검해 Spring Boot 패치 업그레이드로 83건을 해결했습니다.

**[Repo →](https://github.com/hongsungchan88/ticketing)**

---

### 📚 LMS (학습 관리 시스템)
`팀 6명 · 2025.09 – 2025.12` · Spring Boot · React · TypeScript

창업 동아리 팀 프로젝트에 참여해 학생·강사 회원가입 화면, 학과 조회, 과제 등록 파일 전송(FormData), 수강신청 화면 수정을 맡았습니다.

**[Repo →](https://github.com/hongsungchan88/Lms-Fullstack)**

---

### ⚽ SPORTS PREDICT LIVE
`팀 4명 · 2026.06` · Spring Boot · Spring Security · JWT · OAuth2 · OpenAI API · AWS EC2

야구·축구·LoL 실시간 중계와 AI 승부예측 서비스입니다. 회원·일정·순위/기록·AI 예측 파트를 맡아 Spring Security·JWT 인증, 카카오·구글 OAuth2 로그인, 이메일 인증, OpenAI 승부예측(응답 스키마 고정, 경기당 DB 캐싱)을 구현했고 기능 정의서 91건을 작성했습니다 (본인 커밋 113건, 팀 내 최다).

**[Repo →](https://github.com/hongsungchan88/Sports-predict-live)** (팀 저장소 [Clutch-team-project/Sports-predict-live](https://github.com/Clutch-team-project/Sports-predict-live)의 포크 · 담당 파트 정리)

---

### 🤖 COGI - Code Guide
`팀 4명 · 2026.06 – 2026.08` · Spring Boot 4.1 · JPA · MariaDB · javaparser · Spring RestClient

GitHub PR을 자동 분석해 AI 코드리뷰를 제공하고, 반복되는 이슈를 약점으로 통계화해 맞춤 학습으로 연결하는 서비스입니다. PR 리뷰 파이프라인(Webhook 수신·서명 검증, Diff 추출, AST 컨텍스트 최적화), AI 4개 벤더(Claude·OpenAI·Gemini·Groq) RestClient 연동, 리뷰 결과 대시보드, 팀원 초대·권한 관리를 담당했습니다.

**[Repo →](https://github.com/hongsungchan88/COGI)** (팀 저장소 [Leeuswa/COGI](https://github.com/Leeuswa/COGI)의 포크 · 담당 파트 정리)

<br>

## 🔗 Links

[![GitHub](https://img.shields.io/badge/GitHub-hongsungchan88-181717?style=flat-square&logo=github)](https://github.com/hongsungchan88)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=githubpages&logoColor=white)](https://hongsungchan88.github.io)
