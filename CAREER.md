# 경력기술서

> **이보경 (Bokyung Lee)** · 백엔드 엔지니어
> 📧 bokyunglee33@gmail.com · 🔗 [GitHub](https://github.com/Estelle-Lee) · [LinkedIn](https://www.linkedin.com/in/bokyung-estelle-lee/) · [Portfolio](https://www.notion.so/bokyung93/18f6ed8e97b4801187c1ce7371b5e820)

---

## 소개

영국 글래스고 대학 소프트웨어 개발 석사 출신의 백엔드 엔지니어입니다. 복잡한 비즈니스 로직을 설계하고 시스템을 최적화하는 데 강점이 있으며, 차세대 학습 플랫폼(LXP) 구축과 이기종 DBMS 마이그레이션을 주도하며 **쿼리 성능을 85% 이상 개선**했습니다. FFMPEG 기반 미디어 프로세싱과 시스템 자동화 등 기술 난도가 높은 문제를 해결하며 안정적인 서비스 환경을 구축해왔고, 최신 AI 기술 트렌드를 실무 자동화와 미들웨어 최적화에 접목하기 위해 꾸준히 연구하고 있습니다.

### 핵심 역량
- DB 마이그레이션 및 성능 최적화
- 백엔드 아키텍처 및 시스템 고도화
- 미디어 및 프로세스 자동화
- 웹 보안 및 시스템 안정성 강화
- 글로벌 협업 및 학술적 배경

### 기술 스택

| 구분 | 기술 |
|------|------|
| **Language** | Java, Python, JavaScript, C++, PHP |
| **Framework** | Spring Boot, FastAPI, Vue.js, Servlet |
| **Database** | Oracle, Tibero, MySQL, PostgreSQL, Redis |
| **Infra / Tools** | Docker, Linux, RabbitMQ, FFMPEG, Jennifer(APM), REST API, ADL LRS |

---

## 경력

### 주식회사 디유넷 &nbsp;|&nbsp; 기술연구 · 개발연구직 대리 &nbsp;|&nbsp; 2024.06 ~ 재직중 (2년 11개월)

차세대 학습 경험 플랫폼(LXP) 개발 및 고가용성 시스템 운영을 담당하며, 성능 최적화·미디어 처리·시스템 자동화 전반을 수행.

---

#### 1. 차세대 통합 플랫폼(LXP) 구축 및 운영

**개요** &nbsp; 대학 컨소시엄 대상 차세대 학습 경험 플랫폼(LXP)의 핵심 모듈 설계·개발 및 운영

**주요 업무**
- LXP 핵심 모듈 개발 및 기술 표준 수립
- KFEDU 프로젝트: 컨소시엄 전용 LXP 엔드투엔드 배포 및 전담 시스템 안정화 주도
- SELC 운영: 20개 대학 학점 교류 컨소시엄 시스템 유지보수 및 확장 개발

**사용 기술** &nbsp; `Java` `Spring Boot` `Oracle` `Tibero` `ADL LRS`

**성과** &nbsp; LXP 아키텍처 설계 및 핵심 모듈 개발로 **신규 5개 대학 수주**에 기여

---

#### 2. 고가용성 시스템 성능 최적화

**개요** &nbsp; 대규모 부하 환경에서 발생한 시스템 지연을 데이터 기반으로 진단·해결

**주요 업무**
- Jennifer(APM) 기반 병목 트랜잭션 실시간 추적으로 수천 개 쿼리 중 핵심 병목 2개 특정
- 실행계획(Execution Plan) 분석으로 Full Table Scan 및 메모리를 과점유하는 Hash Join을 병목 원인으로 규명
- Nested Loop Join 유도 및 조인 조건·조건절에 최적화된 복합 인덱스(Composite Index) 설계·적용

**사용 기술** &nbsp; `Jennifer(APM)` `Oracle` `Tibero` `Query Optimization`

**성과** &nbsp; 쿼리 수행 시간 **6.0초 → 0.9초 (약 85% 단축)**, 시스템 CPU·Cost 대폭 감소, 2차 부하 테스트 **부하 발생률 0% 달성**

---

#### 3. FFMPEG 기반 미디어 프로세싱 엔진

**개요** &nbsp; 실시간 스트리밍 최적화 및 미디어 처리 자동화 로직 구현

**주요 업무**
- FFMPEG 활용 실시간 스트리밍 최적화
- 코덱 및 키프레임 자동 관리 로직 구현
- 이벤트 기반 메시징 엔진과 연계한 미디어 처리 파이프라인 설계

**사용 기술** &nbsp; `FFMPEG` `Java`

---

#### 4. 시스템 통합(SI) 및 메시징 자동화

**개요** &nbsp; 이기종 시스템 연동 및 전사 공통 메시징 자동화 엔진 구축

**주요 업무**
- 전사 시스템 공통 카카오 알림톡 자동화 로직 및 API 연동 엔진 구축
- DB 에이전트 및 API 미들웨어 성격의 이기종 시스템 연동 모듈 개발
- 고객사 대상 서비스 지표 표준화 제안 및 알림톡 가이드라인 수립·적용
- 알림톡 템플릿 등록 시 참고 가능한 공용 Excel 양식을 제작해 학교에 표준 제공

**사용 기술** &nbsp; `Java` `Spring Boot` `REST API`

**성과** &nbsp; 알림톡 기능이 신규 계약의 주요 기능으로 명시되며 **신규 3개 학교 도입 계약 유치**에 기여

---

#### 5. 이기종 DBMS 마이그레이션

**개요** &nbsp; Oracle 기반 레거시 시스템을 Tibero 환경으로 이관

**주요 업무**
- 이기종 DBMS(Oracle → Tibero) 데이터 이관
- 두 DBMS의 문법·실행계획·인덱스 전략 차이 분석 후 쿼리 재설계
- 서비스 중단 없이 점진적으로 전환하며 쿼리 성능 최적화 병행

**사용 기술** &nbsp; `Oracle` `Tibero` `Query Optimization`

**성과** &nbsp; 무중단 이관 및 마이그레이션 과정 내 쿼리 성능 유지·개선

---

#### 6. 시스템 보안 강화

**개요** &nbsp; 웹 보안 취약점 점검 결과에 따른 보안 정책 적용

**주요 업무**
- CSP(Content Security Policy) 설계·적용으로 XSS 등 웹 보안 위협 차단

**사용 기술** &nbsp; `Web Security(CSP)`

---

## 주요 프로젝트 (대외 활동)

### HackSeoul 2025 (Coupang x AngelHack 주최) &nbsp;|&nbsp; 2025.11

쿠팡 본사에서 진행된 24시간 글로벌 해커톤(8개국 참여)에서 AI 기반 스미싱 탐지·리스크 평가 API **'Smishing Filter'**를 기획부터 배포까지 단독 수행.

- FastAPI 기반 고성능 RESTful API 설계 및 구축 (솔로 개발 및 아키텍처 설계)
- OpenAI GPT-4 Vision API로 문자 텍스트·스크린샷 이미지 내 악성 의도를 동시 분석하는 멀티모달 로직 구현
- Docker, RabbitMQ, Redis를 결합한 비동기·확장형 백엔드 인프라 설계
- 악성 URL 탐지 및 발신 패턴 분석 기반 정량 위험 지표(Risk Score) 산출 로직 개발

**사용 기술** &nbsp; `Python 3.12` `FastAPI` `OpenAI GPT-4 Vision` `Docker` `PostgreSQL` `Redis` `RabbitMQ`

[GitHub](https://github.com/Estelle-Lee/Smishing-Filter) · [YouTube 데모](https://www.youtube.com/watch?v=hXHGs1FBzZ4)

---

### SheCanCode 해커톤 &nbsp;|&nbsp; 2024.03 &nbsp;·&nbsp; 종합 2등

직장 내 포용력 증진 주제 웹 서비스(KidKode) 개발.

- 전체 서비스 기획 참여 및 로그인 이후 화면 개발, Git 기반 협업·병합 수행
- 6시간 제한 내 웹 서비스 기획·개발 완료 및 심사위원 대상 발표 진행

**사용 기술** &nbsp; `JavaScript` `React(JSX)` `HTML` `Figma`

[GitHub](https://github.com/Estelle-Lee/KidKode-SheCanCode-Hackathon)

---

### 기술 트렌드 리서치 및 세미나 참관 &nbsp;|&nbsp; 2021 ~ 현재

- AI·ICT 트렌드 분석: 월드IT쇼(WIS 2026), AI Summit Seoul(2025·2026) 등 정기 참관
- 글로벌 기술 컨퍼런스 학습: Meta Connect 2025 등 차세대 AI·메타버스 기술 흐름 분석
- 습득한 최신 기술을 프로젝트 설계 및 쿼리 성능 최적화 로직에 반영

---

### BCSWomen Lovelace Colloquium 2020 (논문 발표) &nbsp;|&nbsp; 2020.04

글래스고 대학 알고리즘 전공 교수 주최 컨퍼런스에 시각 보조 기구 분석 논문 게재.

> **논문:** *Intelligent Assistive Navigating Device: A relationship between the features and enhanced usability*

---

## 학업 및 학습 프로젝트

GitHub에 공개된 석사 과정 및 부트캠프 학습 결과물입니다.

- **[MSc IT Team Project](https://github.com/Estelle-Lee/MSc-IT-Team-Project)** &nbsp;·&nbsp; A+
  글래스고 대학 석사 필수 팀 프로젝트. 기획~개발~테스트 전 과정을 팀 기반으로 수행.
- **[Advanced Programming](https://github.com/Estelle-Lee/Advanced-Programming)** &nbsp;·&nbsp; A
  석사 고급 프로그래밍 과목 개인 과제.
- **[Django CityLocations](https://github.com/Estelle-Lee/django_cityloc_pkg_Estelle-Lee)**
  부트캠프 과정에서 Django의 앱 구조(INSTALLED_APPS·URLconf 연동)와 설치형 패키지 구성을 학습하며 구현. `Python` `Django`
- **[Bus Booking Automation](https://github.com/Estelle-Lee/bus_booking_automation_app)**
  Nucamp 부트캠프 최종 개인 프로젝트. `Python` `PostgreSQL`
- **[Mozilla Hubs (논문 프로젝트)](https://github.com/Estelle-Lee/hubs)**
  석사 졸업 논문 주제였던 가상공간 접근성 향상 연구를 위해 Mozilla Hubs를 포크하여 작업.

---

## 이전 경력

- **이화자동차정비센타** (2018.01~2018.08) — 사이트 운영·DB 백업·관리 `JavaScript` `PHP` `MySQL` `HTML`
- **mTV** (2016.06~2016.08, 인턴) — 병상용 TV·스마트비전 서비스 기획 및 구성 (메디컬 ICT)

---

## 교육 및 학력

- **University of Glasgow** — MSc Software Development (2019.09~2021.01)
  - 논문: Mozilla Hubs 가상공간 시각장애인 접근성 향상 연구 ([repo](https://github.com/Estelle-Lee/hubs))
- **Nucamp** — Python·SQL·DevOps 부트캠프 수료 (2023.10~2024.03)
  - PostgreSQL, Docker, AWS/Azure/GCP 가상환경, Git 기반 CI/CD 학습
- **서울여자대학교** — 콘텐츠디자인학과 졸업 (2012.01~2017.02)
