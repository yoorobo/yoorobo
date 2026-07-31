# 유정학 · Yoo Jeonghak

**AI Service & Automation Full-Stack Builder**

25년 만에 개발자로 다시 출발해, 생성형 AI·자동화·AWS 위에 실제 운영 가능한 서비스를 만드는 솔로파운더 트랙을 걷고 있습니다.
코드를 단순 생성하는 데 그치지 않고 요구사항·설계·구현·검증·승인 게이트를 연결합니다.
멀티에이전트 협업에서도 계획하고 검증하며 감사 가능한 개발 방식을 실험합니다.

`Spring Boot · Python Automation · AWS · Agent Governance · Isaac Sim`

---

## Current Focus — 2026.07

### 두드림 KDT

**생성형 AI와 AWS 클라우드를 활용한 풀스택 & 자동화 실무 개발**
기간: 2026-06-29 ~ 2026-09-01

- 현재 학습: Java 17 · Spring Boot · Spring Security · OAuth2 · Spring Data JPA · MySQL · REST API
- 자동화·클라우드: Python automation · Streamlit · AWS architecture
- 목표: Final Project에 Agent Governance MVP 통합

### [beauty-reservation](https://github.com/yoorobo/beauty-reservation)

**Active · Course baseline complete · Productization next**

Spring Boot + MySQL + Thymeleaf 기반 예약 서비스입니다. Local 및 Kakao/Google OAuth2 인증 흐름, REST Report API 4종, `X-API-KEY` 기반 machine-to-machine 인증, Python Excel 보고서와 Streamlit 운영 대시보드를 구현했습니다.

- 기준 commit: `7c94cb34b91c84a8d2752198f1399fcc44eff1e0`
- 2026-07-31 강의 프로젝트 대시보드 완료
- 현재 실서비스 수준 전환을 위한 기반으로 사용

### BeautyLink

**Foreigner-friendly K-Beauty reservation MVP**
**Design SSOT completed · Implementation next**

- 고정 범위: single salon · hair services only · English request · AI structured output
- 결과와 예약: Korean salon summary · reservation request · My Bookings
- 사용자 흐름: Home → AI Consultation → Review Summary → Reservation Request → My Bookings
- 기본 상태: `REQUESTED → CONFIRMED → COMPLETED`
- 추가 상태: `CANCELED / NO_SHOW`

아직 구현 완료 단계가 아니며 별도 신규 AI 테이블 없이 기존 `beauty-reservation` 구조에서 선별 이식할 예정입니다.

---

## Agent Governance & Development Harness

역할이 나뉜 AI 에이전트 팀을 하네스로 묶어, 사람 개발팀의 의사결정 구조를 1인 개발 흐름에 적용합니다.

- **1 / 0 / 2 decision gate** — 1: approve · 0: reject · 2: conditional hold
- WO(Work Order) 기반 범위 통제와 구현자·검증자 역할 분리
- push 전 secret scan과 evidence-based completion report
- branch / diff / commit / push 단계별 승인 게이트
- Final Project에서 감사·로그·승인 게이트 MVP로 확장 예정

---

## Projects

### Active & Next

**[beauty-reservation](https://github.com/yoorobo/beauty-reservation)** — 예약 서비스와 운영 대시보드
`Active · Course baseline complete · Productization next`

**BeautyLink** — Foreigner-friendly K-Beauty reservation MVP
`Design complete · Implementation next` · 공개 저장소 준비 전

**[springboot-qna-board](https://github.com/yoorobo/springboot-qna-board)** — Spring Security authentication evolution and board project
직접 구현 세션에서 Spring Security와 Kakao/Google OAuth2로 인증을 발전시킨 게시판 프로젝트입니다.

### Previous Projects

**KDT 생성형 AI 서비스 연작** — 여행챗봇 → 이메일비서 → FAQ/RAG 챗봇
시스템 프롬프트·Human-in-the-loop·RAG 실습: [skyweb](https://github.com/yoorobo/skyweb) → [emailbot](https://github.com/yoorobo/emailbot) → FAQ/RAG prototype.

**[rpa_excel_email](https://github.com/yoorobo/rpa_excel_email)** — 업무보고 자동화 앱
엑셀 업무일기에서 GPT 분석과 보고서 초안을 만들고, 사람의 2단계 승인 후 이메일을 발송하는 Human-in-the-loop 자동화 프로젝트입니다.

**[chaebol-explorer](https://github.com/yoorobo/chaebol-explorer)** — 재벌 지배구조 시각화 + AWS Bedrock AI 분석
한국 대기업집단의 순환출자·소유지배 괴리를 시각화하고 AWS Bedrock으로 분석한 이전 프로젝트입니다.

**[gwae-state](https://github.com/yoorobo/gwae-state)** — 손동작으로 주역 64괘를 도출·해석하는 웹앱 (GWAE)
MediaPipe 손동작 입력과 Firebase를 결합한 이전 프로젝트입니다.

**[FALCON-1](https://github.com/yoorobo/FALCON-1)** — ROS2 로봇 시스템용 AI 에이전트 하네스
Isaac Sim · Isaac Lab · ROS2 · MoveIt으로 이어진 foundational work이자 previous track입니다.

**[SmartFarm](https://github.com/yoorobo/SmartFarm)** — ESP32-CAM 기반 스마트팜
펌웨어부터 제어 GUI까지 하드웨어·소프트웨어를 통합한 이전 프로젝트입니다.

---

## 기술 스택과 환경

`Java 17 · Spring Boot · Spring Security · JPA · MySQL · REST API`
`Python · Streamlit · Automation · AWS · 생성형 AI / LLM`
`Isaac Sim · Isaac Lab · ROS2 · MoveIt · Docker`

환경: Ubuntu · Windows academy PC · IntelliJ IDEA · Antigravity · GitHub synchronization · Python venv

---

## 자격 및 학습

- 정보처리기사: 합격
- AWS SAA-C03: Preparing
- AWS AI Practitioner: SAA 이후 계획
- Physical AI 과정 수료 (ROS2 로보틱스)
- 두드림 KDT 생성형 AI·AWS 풀스택 과정 수강 중

---

*이 프로필은 진행 중인 작업의 기록입니다. Last updated: 2026-07-31*
