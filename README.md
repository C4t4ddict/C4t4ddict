# 안녕하세요, C4t4ddict입니다 👋

모바일 앱과 웹, 백엔드를 개발하고 클라우드 배포와 운영 환경까지 연결합니다.
최근에는 FGC의 배포·관측성 구축과 끼리끼리의 앱·웹 개발에 집중하고 있습니다.

## ⭐ Featured Projects

### [FGC — 보험 수수료 정산 플랫폼](https://github.com/feegachu/fgc)
`Java 21` · `Spring Boot` · `Spring Batch` · `Spring Data JPA` · `PostgreSQL` · `React` · `TypeScript`

GA 보험대리점의 수수료 산정·분급·환수·대사와 1,200% 한도 검증을 지원하는 팀 프로젝트입니다. **배포를 담당**하며 정산 백엔드와 React 화면 개발에도 참여하고 있습니다.

- **배포·CI/CD:** AWS 개발·스테이징 환경에서 검증한 릴리스를 신한 운영 서버로 승격하는 Jenkins 파이프라인을 구현했습니다. 동일 커밋·이미지 digest 검증, 수동 승인, DB 백업, API 상태 및 HTTPS 점검을 배포 절차에 연결했습니다. ([PR #595](https://github.com/feegachu/fgc/pull/595))
- **운영·관측성:** Docker Compose 기반으로 Micrometer·Prometheus·Grafana·Alertmanager·Blackbox Exporter를 구성했습니다. HTTP·JVM·DB 커넥션 풀·배치 지표, 장애·복구 알림, 재배포 시 모니터링 설정 보존을 구현했습니다. ([PR #868](https://github.com/feegachu/fgc/pull/868), [#902](https://github.com/feegachu/fgc/pull/902), [#909](https://github.com/feegachu/fgc/pull/909))
- **백엔드·웹:** 정산 대사 API와 트랜잭션 처리를 개발하고 MyBatis 기반 데이터 접근을 JPA로 전환했습니다. 대사·검증원장·한도 검증 화면을 React로 전환했습니다. ([PR #398](https://github.com/feegachu/fgc/pull/398), [#504](https://github.com/feegachu/fgc/pull/504), [#505](https://github.com/feegachu/fgc/pull/505), [#506](https://github.com/feegachu/fgc/pull/506))

### [끼리끼리 (kkiri-kkiri)](https://github.com/C4t4ddict/kkiri-kkiri)
`React Native` · `React` · `Vite` · `TypeScript` · `Node.js` · `Express` · `MySQL` · `Oracle Cloud Infrastructure`

공모전·대외활동을 탐색하고 팀을 구성해 목표와 지원 과정을 관리하는 활동 플랫폼입니다. React Native 앱과 React/Vite 웹이 Express·MySQL API를 공유하도록 구성했으며, **Oracle Cloud Infrastructure(OCI)에 배포**했습니다.

- **앱·웹:** 활동 탐색, 팀 모집·지원, 일정·목표 관리와 기업 커리큘럼을 모바일 앱과 웹으로 제공합니다.
- **서버:** 이메일·학교 인증과 운영자 권한 검증, 활동 수집 크롤러를 구현했습니다.
- **운영 최적화:** SQL 페이지네이션, 단기 캐시·동시 조회 병합, 요청 제한, DB 커넥션 풀 제한, gzip과 상태 점검을 적용했습니다. ([PR #110](https://github.com/C4t4ddict/kkiri-kkiri/pull/110))

## 🚀 Projects

### [Shoply](https://github.com/C4t4ddict/shoply)
`JavaScript` · `Chrome Extension` · `Manifest V3`

여러 쇼핑몰의 상품을 쇼핑 플레이리스트에 모으고, 수량과 환율을 반영한 원화 합계를 계산하는 로컬 전용 Chrome 확장 프로그램입니다. Manifest V3와 Vanilla JavaScript로 구현했습니다.

### [StudyPilot](https://github.com/C4t4ddict/studypilot-flutter-app) (개발 중)
`Flutter` · `Dart` · `Supabase`

가이드라인 → 커리큘럼 → Todo → 캘린더로 학습 계획과 실행을 연결하는 프로토타입입니다. Flutter 단일 코드베이스로 Web, iOS, Android를 지원하며 Supabase와 로컬 데모 모드를 제공합니다.

### [HoyaTradingSW v2.1](https://github.com/C4t4ddict/hoyatradingsw-v2-1)
`Next.js` · `FastAPI` · `Python` · `scikit-learn/XGBoost`

Binance API와 TradingView Webhook을 연결한 자동매매·백테스트·모의투자 플랫폼입니다. 기존 엔진을 유지하면서 FastAPI/Next.js 구조와 시장 인텔리전스·ML 예측 파이프라인으로 확장하고 있습니다.

## 🛠 Tech Stack

프로젝트에서 사용한 기술을 중심으로 정리했습니다.

| 분야 | 사용 기술 |
| --- | --- |
| Backend | Java · Spring Boot · Spring Security · Spring Batch · Spring Data JPA · Node.js · Express · Python · FastAPI |
| Frontend & Mobile | React · React Native · TypeScript · JavaScript · Vite · Next.js · Flutter · Dart |
| Database | PostgreSQL · MySQL · Flyway · Supabase |
| Cloud & Deployment | AWS · Oracle Cloud Infrastructure(OCI) · Linux · Docker · Docker Compose · Podman · Nginx |
| CI/CD | Jenkins · GitHub Actions · GitHub Container Registry(GHCR) |
| Monitoring | Spring Boot Actuator · Micrometer · Prometheus · Grafana · Alertmanager · Blackbox Exporter |
| Testing | JUnit · Testcontainers · Vitest · Playwright |

## 📊 GitHub Activity

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=C4t4ddict&theme=tokyonight&layout=compact)

<a href="https://www.gitanimals.org/en-US?utm_medium=image&utm_source=C4t4ddict&utm_content=farm">
  <img src="https://render.gitanimals.org/farms/C4t4ddict" width="600" height="300" />
</a>
