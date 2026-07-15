# 유정학 · Yoo Jeonghak

**클라우드 인프라 위에 AI 서비스를 직접 짓는 1인 개발자입니다.**
AI 에이전트로 구성된 개발 하네스를 운영하며, 기획부터 배포까지 풀스택을 혼자 완결하는 방식으로 일합니다.

> 인프라 위의 AI 서비스 — 만드는 과정을 공개로 기록합니다.

---

## 지금 만들고 있는 것

### 두드림 KDT 트랙 (2026)

**[springboot-qna-board](https://github.com/yoorobo/springboot-qna-board)** — Spring Boot 기반 Q&A 게시판 · **In Progress**
회원·게시판·검색·권한을 밑바닥부터 구현하고 인증을 단계적으로 발전시킨 학습 프로젝트. 인증 발전: 직접 구현 세션 → Spring Security → OAuth2 소셜 로그인(카카오·구글). `Java · Spring Boot · Spring Security · JPA · MySQL`

**KDT 생성형 AI 서비스 연작** — 여행챗봇 → 이메일비서 → FAQ/RAG 챗봇
시스템 프롬프트 설계·Human-in-the-loop·RAG를 주제별로 실습한 생성형 AI 앱 묶음: [skyweb](https://github.com/yoorobo/skyweb)(여행 상담 챗봇, **Completed**) → [emailbot](https://github.com/yoorobo/emailbot)(AI 이메일 비서, **Completed**) → FAQ/RAG 챗봇(**Prototype**, 준비 중). `Python · FastAPI · Streamlit · React · 생성형 AI / LLM`

---

### 그 밖의 프로젝트

**[chaebol-explorer](https://github.com/yoorobo/chaebol-explorer)** — 재벌 지배구조 시각화 + AWS Bedrock AI 분석
한국 대기업집단의 순환출자·소유지배 괴리(Wedge)를 인터랙티브 그래프로 시각화하고, AWS Bedrock(Amazon Nova)으로 지배구조 리스크를 분석. `React/TS · Lambda · DynamoDB · Bedrock`

**[gwae-state](https://github.com/yoorobo/gwae-state)** — 손동작으로 주역 64괘를 도출·해석하는 웹앱 (GWAE)
MediaPipe 손동작 입력으로 작괘(作卦)하여 64괘를 해석·공유. 라이브 서비스 운영 중. `정적 JS · MediaPipe · Firebase`

**[FALCON-1](https://github.com/yoorobo/FALCON-1)** — ROS2 로봇 시스템용 AI 에이전트 하네스
에이전트 기반 개발 방법론을 로보틱스에 적용한 프로젝트. `ROS2`

**[SmartFarm](https://github.com/yoorobo/SmartFarm)** — ESP32-CAM 기반 스마트팜
펌웨어부터 제어 GUI까지 하드웨어·소프트웨어를 통합한 풀스택 사례. `C++ · Python · ESP32`

---

## 일하는 방식 — AI 에이전트 하네스

역할이 나뉜 AI 에이전트 팀을 하네스로 묶어, 사람 개발팀의 의사결정 구조를 1인 체제로 구현합니다.

- 전략·문서 / 구현·빌드 / 셸 실행·조사 / 검증·게이팅 / 딥리서치 — 각 역할을 분리해 운영
- **WO(작업지시서)** 로 작업을 내리고, 결정은 **ADR(아키텍처 결정 기록)** 로 남기며, **1/0/2 게이팅**(승인·거부·보류)으로 검증
- 빠르게 만들고, 기록을 남기고, 다음 결정에 반영하는 루프

> KDT 실습에서도 WO 기반 범위 정의와 구현 전후 검증 기록을 적용하고 있습니다.

---

## 기술 스택

`AWS (Bedrock · Lambda · DynamoDB)` · `Python` · `Java / Spring Boot · Spring Security · JPA` · `TypeScript / React` · `생성형 AI / LLM` · `ROS2` · `자동화 · RPA` · `Docker`

---

## 배경

- 정보처리기사
- Physical AI 과정 수료 (ROS2 로보틱스)
- 두드림 KDT 생성형 AI·AWS 풀스택 과정 (2026-06-29 ~ 2026-09-01, 수강 중)

---

*이 프로필은 진행 중인 작업의 기록입니다. (최종 업데이트: 2026-07-15)*
