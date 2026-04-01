# Hi, I'm HARDYHADI 👋

Java / Spring Boot 백엔드 개발자입니다.
인증 보안 솔루션, 모바일 앱 API, 기업 관리 시스템을 개발하고 있습니다.

📧 jw0001118@naver.com

---

## 💼 Experience

**Dream Security** · Backend Developer `2023.11 ~`

> 국내 보안 전문 기업. FIDO 인증, PKI, 전자서명 솔루션 개발 및 운영.

- FIDO 기반 무선인증 서비스 **Verigate Duo** 관리자/브랜드 페이지 개발
- 기업 고객 계정·서비스 관리 어드민 시스템 개발 (company-admin, dpacto-agency)
- 미션 기반 스마트 알람 앱 **Timee** 백엔드 REST API 서버 개발
- 전사 Spring Boot 3.x 마이그레이션 및 WAR 배포 환경 구성

---

## 🛠 Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-0097A7?style=flat-square)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white)

### Database & Cache
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Auth & Integration
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-4285F4?style=flat-square&logo=google&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase_FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![SAML](https://img.shields.io/badge/SAML_2.0-E34F26?style=flat-square)

### DevOps & Tools
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![JaCoCo](https://img.shields.io/badge/JaCoCo-F01F7A?style=flat-square)

### Testing
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white)
![TestContainers](https://img.shields.io/badge/TestContainers-9B59B6?style=flat-square)

---

## 📦 Projects

### 🔐 Verigate Duo Admin · [→ auth-console](https://github.com/HARDYHADI/auth-console)
> FIDO 인증 서비스 관리 콘솔 · `Spring Boot 3.5.7`

FIDO 기반 무선인증 서비스의 운영자용 관리 시스템.

- 이용기관 · 사용자 · 앱 등록/관리, QR·딥링크 발급
- 감사 로그, 인증 로그, 대시보드 지표 제공
- 서버 이중화를 위한 Spring Session JDBC 세션 클러스터링
- 엑셀 다운로드(Apache POI), 운영자 OTP 인증

`Spring Boot` `JPA` `QueryDSL` `Spring Security` `Thymeleaf` `MariaDB` `Spring Session JDBC` `Swagger` `JaCoCo`

---

### 🌐 Verigate Duo Brand · [→ auth-demo](https://github.com/HARDYHADI/auth-demo)
> FIDO 인증 데모 페이지 · `Spring Boot 3.5.9`

Verigate Duo 체험 흐름(등록 → 로그인 → PUSH 인증 → 완료)을 브랜드 페이지와 데모 팝업으로 제공.

- Redis Sentinel 기반 Flow 상태 저장소 구성
- Redis Streams를 활용한 PUSH 콜백 수신
- Spring Retry 기반 외부 AP 서버 통신 안정화
- P6Spy SQL 로깅으로 쿼리 최적화

`Spring Boot` `Thymeleaf` `MariaDB` `Redis Sentinel` `Redis Streams` `Spring Retry` `jQuery` `Swiper`

---

### ⏰ Timee API Server · [→ smart-alarm-api](https://github.com/HARDYHADI/smart-alarm-api)
> 미션 기반 스마트 알람 앱 백엔드 · `Spring Boot 3.5.6`

Google / Apple 소셜 로그인, 미션 알람, 친구·케어 기능, FCM 푸시, 인앱 결제 검증을 제공하는 REST API 서버.

- OAuth2 (Google, Apple Sign-In) + 자체 JWT 인증 구조
- 8가지 미션 타입 알람 시스템 및 친구·케어 소셜 기능
- App Store / Google Play 인앱 결제 서버 검증
- FCM 푸시 알림 (Firebase Admin SDK)
- Flyway DB 마이그레이션, TestContainers 통합 테스트
- GitLab CI/CD 파이프라인 + Docker 배포

`Spring Boot` `OAuth2` `JWT` `JPA` `QueryDSL` `MariaDB` `Redis` `Firebase FCM` `Apple App Store API` `Google Play API` `Flyway` `TestContainers` `Swagger` `JaCoCo`

---

### 🏢 Company Admin / Dpacto Agency · [→ enterprise-admin](https://github.com/HARDYHADI/enterprise-admin)
> 기업 고객 관리 어드민 · `Spring Boot 3.4.3`

기업 고객 계정 및 서비스 관리 시스템.

- SAML 2.0 SSO 연동
- Redis 세션 클러스터링 (Spring Session + Jedis)
- QR 코드 발급 (ZXing), 엑셀 내보내기 (Apache POI)
- WebFlux 기반 외부 API 비동기 연동
- JavaMail 이메일 발송

`Spring Boot` `JPA` `QueryDSL` `Spring Security` `Redis Session` `WebFlux` `Thymeleaf` `MariaDB` `SAML` `Apache POI` `ZXing`

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=HARDYHADI&show_icons=true&theme=default&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=HARDYHADI&layout=compact&hide_border=true)
