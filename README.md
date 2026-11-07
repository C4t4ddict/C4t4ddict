<div align="center">

# 안녕하세요, C4t4ddict입니다 👋

**앱과 웹에서 클라우드 운영까지, 서비스를 연결하는 개발자**

모바일 앱과 웹, 백엔드를 개발하고 클라우드 배포와 운영 환경까지 연결합니다.<br>
최근에는 **FGC의 배포·관측성 구축**과 **끼리끼리의 앱·웹 개발**에 집중하고 있습니다.

[![GitHub](https://img.shields.io/badge/C4t4ddict-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/C4t4ddict)
[![FGC](https://img.shields.io/badge/FGC-2563EB?style=flat-square)](https://github.com/feegachu/fgc)
[![끼리끼리](https://img.shields.io/badge/끼리끼리-14B8A6?style=flat-square)](https://github.com/C4t4ddict/kkiri-kkiri)

</div>

<br>

## ⭐ Featured Projects

### [FGC — 보험 수수료 정산 플랫폼](https://github.com/feegachu/fgc)

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

GA 보험대리점의 수수료 산정·분급·환수·대사와 1,200% 한도 검증을 지원하는 팀 프로젝트입니다. **배포를 담당**하며 정산 백엔드와 React 화면 개발에도 참여하고 있습니다.

- **배포·CI/CD:** AWS 개발·스테이징 환경에서 검증한 릴리스를 신한 운영 서버로 승격하는 Jenkins 파이프라인을 구현했습니다. 동일 커밋·이미지 digest 검증, 수동 승인, DB 백업, API 상태 및 HTTPS 점검을 배포 절차에 연결했습니다. ([PR #595](https://github.com/feegachu/fgc/pull/595))
- **운영·관측성:** Docker Compose 기반으로 Micrometer·Prometheus·Grafana·Alertmanager·Blackbox Exporter를 구성했습니다. HTTP·JVM·DB 커넥션 풀·배치 지표, 장애·복구 알림, 재배포 시 모니터링 설정 보존을 구현했습니다. ([PR #868](https://github.com/feegachu/fgc/pull/868), [#902](https://github.com/feegachu/fgc/pull/902), [#909](https://github.com/feegachu/fgc/pull/909))
- **백엔드·웹:** 정산 대사 API와 트랜잭션 처리를 개발하고 MyBatis 기반 데이터 접근을 JPA로 전환했습니다. 대사·검증원장·한도 검증 화면을 React로 전환했습니다. ([PR #398](https://github.com/feegachu/fgc/pull/398), [#504](https://github.com/feegachu/fgc/pull/504), [#505](https://github.com/feegachu/fgc/pull/505), [#506](https://github.com/feegachu/fgc/pull/506))

### [끼리끼리 (kkiri-kkiri)](https://github.com/C4t4ddict/kkiri-kkiri)

![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat-square)

공모전·대외활동을 탐색하고 팀을 구성해 목표와 지원 과정을 관리하는 활동 플랫폼입니다. React Native 앱과 React/Vite 웹이 Express·MySQL API를 공유하도록 구성했으며, **Oracle Cloud Infrastructure(OCI)에 배포**했습니다.

- **앱·웹:** 활동 탐색, 팀 모집·지원, 일정·목표 관리와 기업 커리큘럼을 모바일 앱과 웹으로 제공합니다.
- **서버:** 이메일·학교 인증과 운영자 권한 검증, 활동 수집 크롤러를 구현했습니다.
- **운영 최적화:** SQL 페이지네이션, 단기 캐시·동시 조회 병합, 요청 제한, DB 커넥션 풀 제한, gzip과 상태 점검을 적용했습니다. ([PR #110](https://github.com/C4t4ddict/kkiri-kkiri/pull/110))

<br>

## 🚀 More Projects

### [Shoply](https://github.com/C4t4ddict/shoply)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000000)
![Chrome Extension](https://img.shields.io/badge/Chrome%20Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest%20V3-5F6368?style=flat-square)

여러 쇼핑몰의 상품을 쇼핑 플레이리스트에 모으고, 수량과 환율을 반영한 원화 합계를 계산하는 로컬 전용 Chrome 확장 프로그램입니다. Manifest V3와 Vanilla JavaScript로 구현했습니다.

### [StudyPilot](https://github.com/C4t4ddict/studypilot-flutter-app) (개발 중)

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=000000)

가이드라인 → 커리큘럼 → Todo → 캘린더로 학습 계획과 실행을 연결하는 프로토타입입니다. Flutter 단일 코드베이스로 Web, iOS, Android를 지원하며 Supabase와 로컬 데모 모드를 제공합니다.

### [HoyaTradingSW v2.1](https://github.com/C4t4ddict/hoyatradingsw-v2-1)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)

Binance API와 TradingView Webhook을 연결한 자동매매·백테스트·모의투자 플랫폼입니다. 기존 엔진을 유지하면서 FastAPI/Next.js 구조와 시장 인텔리전스·ML 예측 파이프라인으로 확장하고 있습니다.

<br>

## 🛠 Tech Stack

<table>
  <tr>
    <td>Languages</td>
    <td><img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" /> <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000000" /> <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" /></td>
  </tr>
  <tr>
    <td>Frontend</td>
    <td><img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" /> <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" /></td>
  </tr>
  <tr>
    <td>Mobile</td>
    <td><img alt="React Native" src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" /> <img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" /></td>
  </tr>
  <tr>
    <td>Backend</td>
    <td><img alt="Spring Boot" src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" /> <img alt="Spring Security" src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" /> <img alt="Spring Batch" src="https://img.shields.io/badge/Spring%20Batch-6DB33F?style=flat-square&logo=spring&logoColor=white" /> <img alt="Spring Data JPA" src="https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white" /> <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" /> <img alt="Express" src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" /> <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /></td>
  </tr>
  <tr>
    <td>Database</td>
    <td><img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" /> <img alt="Flyway" src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white" /> <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=000000" /></td>
  </tr>
  <tr>
    <td>Infrastructure</td>
    <td><img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=000000" /> <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img alt="Docker Compose" src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img alt="Podman" src="https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white" /> <img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" /></td>
  </tr>
  <tr>
    <td>Cloud</td>
    <td><img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square" /> <img alt="Oracle Cloud" src="https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat-square" /></td>
  </tr>
  <tr>
    <td>CI/CD</td>
    <td><img alt="Jenkins" src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" /> <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" /> <img alt="GHCR" src="https://img.shields.io/badge/GHCR-181717?style=flat-square&logo=github&logoColor=white" /></td>
  </tr>
  <tr>
    <td>Observability</td>
    <td><img alt="Actuator" src="https://img.shields.io/badge/Actuator-6DB33F?style=flat-square&logo=springboot&logoColor=white" /> <img alt="Micrometer" src="https://img.shields.io/badge/Micrometer-117A65?style=flat-square" /> <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" /> <img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" /> <img alt="Alertmanager" src="https://img.shields.io/badge/Alertmanager-E6522C?style=flat-square&logo=prometheus&logoColor=white" /> <img alt="Blackbox Exporter" src="https://img.shields.io/badge/Blackbox%20Exporter-34495E?style=flat-square&logo=prometheus&logoColor=white" /></td>
  </tr>
  <tr>
    <td>Testing</td>
    <td><img alt="JUnit" src="https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white" /> <img alt="Testcontainers" src="https://img.shields.io/badge/Testcontainers-2496ED?style=flat-square&logo=testcontainers&logoColor=white" /> <img alt="Vitest" src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" /> <img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square" /></td>
  </tr>
</table>

<br>

## 📊 GitHub Activity

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=C4t4ddict&theme=tokyonight&layout=compact)

<a href="https://www.gitanimals.org/en-US?utm_medium=image&utm_source=C4t4ddict&utm_content=farm">
  <img src="https://render.gitanimals.org/farms/C4t4ddict" width="600" height="300" />
</a>
