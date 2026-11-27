# 안녕하세요, 개발자 김윤정입니다 👋

> 헤맨 만큼 내 땅이다.

경영학과 소프트웨어를 함께 공부하며, 사용자의 문제를 정의하고 웹 서비스로 해결하는 과정을 좋아합니다.\
화면과 API, 데이터의 흐름을 연결하고, 예외 상황에서도 서비스가 의도대로 동작하는지 확인합니다.

[GitHub](https://github.com/jyk3716) · [블로그](https://blog.naver.com/jyk3716)

## 프로젝트로 쌓은 경험

### 집으로 · 청년 주거지원 신청 준비 서비스

**팀장 · 서비스 기획 · 풀스택 개발** | 단국대학교 캡스톤디자인 · 2026.09–11 · 4인 팀

🏆 **2026년 SW중심대학사업단 캡스톤 페스티벌 우수상** · 2026.11.27

공고마다 흩어진 조건과 제출서류, 신청 일정을 개인별 준비 목록으로 연결하는 웹 서비스입니다.

- 사용자 문제를 바탕으로 기능 범위와 우선순위를 정하고, 기술 스택 선정과 개발 일정 수립을 주도했습니다.
- 조건 확인부터 서류 준비, 일정 확인, 진행 상태 기록으로 이어지는 사용자 흐름을 설계했습니다.
- 다중 탭에서 준비 기록이 덮어써지는 문제를 재현하고, 버전 검사 누락을 원인으로 좁혀 수정 방향과 회귀 검증 결과를 확인했습니다.

**기술**: React · TypeScript · Java · Spring Boot · PostgreSQL\
[서비스](https://jibro.live/) · [저장소](https://github.com/Cho-Mi-Kim/jibro)

### 미리줌 · 증여 사전 설계 서비스

**풀스택 개발 · 시뮬레이션 기능 UI/API/DB** | 2026.07–08 · 6인 팀

증여 시점과 금융상품 조합에 따른 예상 세액과 미래가치를 비교하는 서비스입니다.

- 조건 입력, 전략 비교, 상품 선택, 결과 저장을 연결하는 시뮬레이션 화면과 API를 구현했습니다.
- 과거 증여 이력, 공제 갱신, 연령 변화와 상품별 운용 조건을 계산 로직에 반영했습니다.
- 입력값과 상품 정보, 계산 기준을 스냅샷으로 보존하고, Caffeine을 활용해 중복 요청을 처리했습니다.
- 운용기간과 상품 가입기간의 경계에서 발생하는 오류를 재현하고, 전략별 평가 기준과 잔여 기간 처리 로직을 개선했습니다.

**기술**: Vue 3 · Java · Spring Framework · MyBatis · MySQL\
[프론트엔드](https://github.com/KB-IT-s-your-life-PJT-23-4/frontend) · [백엔드](https://github.com/KB-IT-s-your-life-PJT-23-4/backend)

### 내 인생 마지막 가계부 · 시니어 가계부 서비스

**PM · 프론트엔드 개발** | 2026.04 · 4인 팀

- 프로젝트 구조 설계와 화면 통합을 담당하고, Pinia 기반 거래·날짜 상태와 월별 수입·지출·잔액 계산을 공통화했습니다.
- Axios와 JSON Server 모의 API를 연동해 거래 변경을 화면에 반영하고, 금액 표시 형식과 저장값을 분리했습니다.

**기술**: Vue 3 · Pinia · Axios · JSON Server

### 세미비즈 · 반도체 기업 프로파일 서비스

**백엔드 개발** | 2025.06–09 · 4인 팀 · ㈜한국전시 산학 연계

기업의 기본정보와 재무, 제품, 협력사 정보를 연결해 조회하고 관리하는 웹 서비스입니다.

- 기업·재무·제품·협력사 관계를 모델링하고, Prisma와 SQL Server를 연결했습니다.
- 기업 정보 조회·등록·수정 API에 필수값과 사업자등록번호 중복 검증, 오류 응답을 적용했습니다.
- Nodemailer와 SMTP 기반 담당자 메일 발송 API를 구현하고, 연락 UI와 반응형 화면 통합에 참여했습니다.

**기술**: React · Next.js · TypeScript · Prisma · SQL Server · Nodemailer\
기업 연계 프로젝트로 소스코드는 비공개입니다.

## 교육과 실무 경험

| 기간                 | 경험                       | 주요 내용                                       |
| ------------------ | ------------------------ | ------------------------------------------- |
| 2023.03–2027.08 예정 | **단국대학교**                | 경영학 주전공 · SW융합경제경영 복수전공 · 인공지능학 부전공         |
| 2026.03–08         | **KB IT’s Your Life 7기** | 웹 풀스택 교육 · 가계부 및 미리줌 팀 프로젝트 · 기자단 활동        |
| 2025.09–2026.02    | **한국토지주택공사 전세임대1팀 현장실습** | 자격심사·권리분석·계약등록 업무 지원 · 반복 문의를 유발하는 양식 오류 개선 |
| 2025.07–08         | **SK AI Dream Camp**     | AI 학습 및 실습                                  |
| 2025.06–09         | **단국산학아카데미 5기**          | ㈜한국전시 연계 세미비즈 개발                            |

## 수상

- **2026년 SW중심대학사업단 캡스톤 페스티벌 우수상** · 집으로 · 2026.11.27
- **현장실습 체험 수기 공모전 최우수상** · 2026.10.07
- **롯데마트·슈퍼 아이디어 경진대회 2등&#x20;**· 2024.11.08

## 자격

- **SQLD** · 2025.12.12
- **ADsP** · 2025.03.21

## 사용 기술

| 구분 | 사용 기술 |
| --- | --- |
| **Languages** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Backend** | ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![MyBatis](https://img.shields.io/badge/MyBatis-525252?style=flat-square) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white) |
