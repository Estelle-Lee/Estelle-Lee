# 경력기술서

**🇰🇷 한국어** | [🇬🇧 English](./CAREER.en.md)

> **이보경 (Bokyung Lee)** · 백엔드 엔지니어 — 시스템 자동화 · 성능 최적화
> 📧 bokyunglee33@gmail.com · 🔗 [GitHub](https://github.com/Estelle-Lee) · [LinkedIn](https://www.linkedin.com/in/bokyung-estelle-lee/) · [Portfolio](https://bokyung93.notion.site/Backend-Engineering-Portfolio-3c06ed8e97b481edb852f70f40308f1e?source=copy_link)

---

## 소개

반복되는 운영을 자동화 구조로 재설계하고, 시스템 병목을 데이터로 진단해 해결하는 백엔드 엔지니어입니다. 학교별 수작업 알림 운영을 제거한 메시징 자동화 엔진을 구축했고, DB 에이전트·API 미들웨어 성격의 이기종 시스템 연동 모듈과 미디어 처리 자동화 파이프라인을 개발했습니다. 또한 APM·실행계획 분석 기반으로 시스템 병목을 진단해 **핵심 쿼리를 약 85% 개선**하고, 동시접속 2,000명 부하 환경에서 **부하 발생률 0%**를 달성했으며, Oracle → Tibero 무중단 이관을 수행했습니다.

학부(이공계 B.Sc)에서 객체지향·Java·C/C++·자료구조를 전공하고, 영국 글래스고 대학 소프트웨어 개발 석사를 Distinction(최우수)으로 수료했습니다. 표면이 아닌 근본 원인을 데이터로 찾아 시스템을 더 효율적으로 만드는 일을 지향하며, 안정적이고 효율적인 플랫폼을 설계하는 엔지니어로 성장하고 있습니다.

### 핵심 역량
- 시스템 자동화 및 이기종 시스템 연동
- 성능 최적화 및 시스템 안정성 강화
- DB 마이그레이션 (Oracle → Tibero 무중단 이관)
- 학습데이터 파이프라인(xAPI·LRS) 설계
- 미디어 처리 자동화
- 웹 보안 · 글로벌 협업

### 기술 스택

| 구분 | 기술 |
|------|------|
| **Language** | Java, Python, JavaScript, C++, PHP |
| **Framework** | Spring Boot, FastAPI, Vue.js, Servlet |
| **Database** | Oracle, Tibero, MySQL, PostgreSQL, Redis |
| **Infra / Tools** | Docker, Linux, FFMPEG, Jennifer(APM), REST API, ADL LRS(xAPI), Nginx |

---

## 경력

### 주식회사 디유넷 (동아미디어그룹 계열) &nbsp;|&nbsp; 기술연구소 · 개발연구직 대리 &nbsp;|&nbsp; 2024.06 ~ 재직중

대학 컨소시엄 대상 시스템을 개발·운영하며 시스템 자동화·연동, 성능 최적화, 데이터 파이프라인, 보안 전반을 수행.

---

#### 1. 카카오 알림톡 자동화 엔진 및 이기종 시스템 통합 &nbsp;·&nbsp; 2025.07 ~ 현재

**개요** &nbsp; 이기종 시스템을 연동하고 학교별 알림 발송을 표준화·자동화하는 메시징 엔진을 구축해 수작업 운영을 제거

**주요 업무**
- BLU3(장안대)·BLU5(원광대) 등 플랫폼별 알림톡 API·DB 연동 및 관리자 발송 체계 구축
- 학습부진자 대상 자동 알림 등 교육 운영에 최적화된 발송 시나리오와 프로시저 설계·테스트
- DB 에이전트 및 API 미들웨어 성격의 이기종 시스템 연동 모듈 개발
- 알림톡 템플릿 등록용 공용 Excel 양식·파라미터 지표를 제작해 학교에 표준 제공 및 가이드라인 수립

**사용 기술** &nbsp; `Java` `Spring Boot` `REST API`

**성과** &nbsp; 알림톡 기능이 신규 계약의 주요 기능으로 명시되며 **신규 학교 도입 계약 유치**에 기여

---

#### 2. FFMPEG 기반 미디어 처리 자동화 파이프라인 &nbsp;·&nbsp; 2025.03 ~ 현재

**개요** &nbsp; 영상 인코딩 자동화 및 스트리밍 최적화 로직 구현

**주요 업무**
- Java로 FFMPEG 기반 강의실 단건·관리자 일괄 영상 인코딩 로직 설계·구축 및 스트리밍 최적화
- 서버 내 라이브러리 종속성 충돌 문제를 진단하고 ProcessBuilder 방식으로 전환해 환경 이슈 근본 해결
- 외부 영상 솔루션(Panopto)의 로그인·연동 오류를 대체하기 위한 에이전트 API 방식 미디어 처리 모듈 자체 개발 중

**사용 기술** &nbsp; `Java` `FFMPEG` `ProcessBuilder`

---

#### 3. 고가용성 시스템 성능 최적화 &nbsp;·&nbsp; 2024.06 ~ 현재 (상시)

**개요** &nbsp; 대규모 부하 환경에서 발생한 시스템 지연을 APM·실행계획 분석 기반으로 진단·해결

**주요 업무**
- Jennifer(APM) 기반 병목 트랜잭션 실시간 추적으로 수천 개 쿼리 중 핵심 병목 2개 특정
- 실행계획(Execution Plan) 분석으로 Full Table Scan 및 메모리를 과점유하는 Hash Join을 병목 원인으로 규명
- Nested Loop Join 유도 및 조인 조건·조건절에 최적화된 복합 인덱스(Composite Index) 설계·적용
- 개선 전후를 부하 테스트로 정량 비교해 효과 검증

**사용 기술** &nbsp; `Jennifer(APM)` `Oracle` `Tibero` `Query Optimization`

**성과** &nbsp; 쿼리 수행 시간 **6.0초 → 0.9초 (약 85% 단축)**, 시스템 CPU·Cost 대폭 감소, 동시접속 2,000명 부하 테스트 **부하 발생률 0% 달성**. 자원 증설 없이 구조적으로 해결

---

#### 4. 한양대 온프레미스 → 클라우드 전환 (Oracle → Tibero) &nbsp;·&nbsp; 2024.06 ~ 2024.08

**개요** &nbsp; 한양대 시스템의 온프레미스 → 클라우드 전환사업에서 Oracle 기반 DB를 Tibero로 무중단 이관

**주요 업무**
- 테스트·운영 DB 이관 시 인덱스·시퀀스·프로시저 점검·보완 및 Oracle 전용 집계함수를 Tibero 환경에 맞게 변환
- Jennifer(APM)로 이관 전후 시스템 비교 검증, 속도가 느린 쿼리를 인덱스·쿼리 튜닝으로 개선해 부하 테스트 성능 확보
- 카카오 SMS OTP 발송 타입 변경 등 부가 기능을 Tibero 환경에 맞춰 수정·테스트

**사용 기술** &nbsp; `Oracle` `Tibero` `Jennifer(APM)` `Query Optimization`

**성과** &nbsp; **서비스 중단 없이 클라우드 전환 완료**, 이관 과정에서 쿼리 성능 함께 개선

---

#### 5. 세션 클러스터링 — 멀티 서버 세션 공유 (루터대 LMS-CC) &nbsp;·&nbsp; 2025.02 ~ 2025.04

**개요** &nbsp; LMS와 학점교류(CC) 시스템을 하나의 환경처럼 운영하기 위한 서버 간 세션 공유 구조 구축

**주요 업무**
- cyberLogin 세션 처리 로직 추가 및 서버 간 세션을 이어받도록 세션 클러스터링 구성
- 세션 유지를 위한 추가 마이그레이션 수행 및 전체 프로세스 테스트·트러블슈팅
- 별도 서버 간 서버 시간 차이로 발생하는 세션 연동 이슈 분석·보완

**사용 기술** &nbsp; `Java` `Session Clustering` `Tibero`

---

#### 6. xAPI/LRS 학습데이터 수집·저장 환경 구축 (TFT 주관) &nbsp;·&nbsp; 2024.08 ~ 2025.05

**개요** &nbsp; 학습 활동 데이터를 표준(xAPI)으로 수집·저장하기 위한 학습 기록 저장소(ADL LRS) 도입을 TFT 주관으로 수행

**주요 업무**
- ADL LRS 도입 TFT를 주관해 시스템 분석 및 테스트 환경 구축, 중간 보고 주도
- Docker 기반으로 실서버에 LRS를 구축하고 Tin Can API·xAPI 지표 설정 및 학습 활동 데이터(Statement) 전송 테스트 완료
- ADL LRS 기술 이슈 해결 및 서버 conf 설정 문서화, Notion 기반 가이드라인 제작·공유
- OAuth 인증 적용으로 기본 admin 접근 환경 구성

**사용 기술** &nbsp; `Python` `Docker` `xAPI` `Tin Can API` `ADL LRS` `OAuth`

**성과** &nbsp; 구축한 LRS 기능을 **학습데이터 수집 상품으로 구성해 현재 플랫폼에 탑재·판매 중**

---

#### 7. 차세대 학습 경험 플랫폼(LXP) 구축 및 운영 &nbsp;·&nbsp; 2025.10 ~ 현재

**개요** &nbsp; 대학 컨소시엄 대상 차세대 학습 경험 플랫폼(LXP)의 핵심 모듈을 설계·개발하고 다수 대학에 구축·운영

**주요 업무**
- LXP 핵심 모듈을 설계·개발하고 기술 표준 수립
- 한양대 기초융합 컨소시엄(2,000명, 학점교류로 한 사이트에 20개 이상 대학 운영) LXP를 엔드투엔드로 구축·배포하고 동시접속 2,000명 부하 테스트 완료
- 원광대·대동대·부산가톨릭대·건양대(각 200명 규모) 등 다수 대학 LXP 구축 및 시스템 안정화 전담


**사용 기술** &nbsp; `Java` `Spring Boot` `Oracle` `Tibero`

**성과** &nbsp; LXP 아키텍처 설계 및 핵심 모듈 개발로 **신규 5개 대학 수주**에 기여

---

#### 8. 웹 보안 강화 및 취약점 대응 &nbsp;·&nbsp; 2025.10 ~ 현재 (상시)

**개요** &nbsp; 웹 취약점 점검 결과에 따른 보안 정책 설계·적용 및 상시 대응

**주요 업무**
- 웹 취약점 점검 보고서 상시 검토·조치, CSP(Content Security Policy) 설계·적용으로 XSS 등 웹 보안 위협 차단 (경상국립대 학점교류 적용)
- Nginx 버전 호환성 관련 취약점 점검·패치 (한양대 학점교류 고객 요청 사항)
- 쿠키·HTTP 보안 강화를 위해 쿠키 관리 전용 Java 모듈 별도 구축·적용 (2026.06)

**사용 기술** &nbsp; `Web Security(CSP)` `Nginx` `Java`

---

#### 9. 농촌진흥청 차세대 e-HRD 시스템 구축 &nbsp;·&nbsp; 2024.08 ~ 2024.12

**개요** &nbsp; 교육 운영 시스템의 사용자 학습 영역 분석·개발 및 신규 기능 구현

**주요 업무**
- 사용자 페이지의 학습창 및 마이페이지 영역 분석·개발 및 테이블 정의서 작성
- 학습창 메뉴, 오프라인 교재·설문·과제·시험, 하이브리드 콘텐츠 등 신규 기능 설계·구현 (오프라인 시험을 온라인 랜덤 출제 방식으로 통합 등)
- 학습창에서 발생한 웹 취약점의 원인과 대응 방법을 분석해 공통 처리 로직으로 조치하고 최종 점검 지원

**사용 기술** &nbsp; `Java` `Oracle` `전자정부프레임워크`

---

#### 10. 다수 고객사 LMS 구축 및 유지보수 &nbsp;·&nbsp; 2024.06 ~ 현재

**개요** &nbsp; 다수 대학 고객사의 LMS 기능 개선 및 운영 이슈 대응

**주요 업무**
- 경상국립대·동아방송예술대·조선이공대·장안대·건양대·한국교통대 등 다수 고객사 LMS 기능 개선 및 운영 이슈 처리
- 도메인·파라미터 변경, 모바일 화면 보정, 설문·시험 관리 오류 수정 등 고객 요청 사항 대응
- 공통으로 보완 가능한 사항은 공통 메소드를 생성해 전 학습창에 일괄 적용

**사용 기술** &nbsp; `Java` `JavaScript` `Oracle` `Tibero`

---

## 주요 프로젝트 (대외·개인)

### LXP 영상 인코딩 에이전트 (개인 프로젝트, 진행 중) &nbsp;|&nbsp; 2026.06 ~

실무 FFMPEG 미디어 처리 경험에서 출발해, 영상 코덱 정책 위반을 자동 진단하고 정책 기반으로 자동 인코딩하는 독립 에이전트를 Go로 개발 중.

- 학교별 독립 배포(데이터 주권: 학교 데이터가 본사로 넘어오지 않음) 제약을 반영한 무중앙(중앙 DB·작업 큐 없음) 아키텍처로 설계
- ffprobe 메타데이터 기반 7항목 코덱 정책(H.264/AAC-LC/MP4/yuv420p/CFR 30fps 등) 진단기 구현 완료
- 정책 위반 시 ffmpeg 명령을 자동 생성·변환하고 재검증하는 파이프라인 개발 진행 중
- 변환시간·정책 준수(skip)율 등 지표를 구조화 로그로 수집하도록 설계

**사용 기술** &nbsp; `Go` `FFMPEG` `ffprobe`

---

### HackSeoul 2025 (Coupang x AngelHack 주최) &nbsp;|&nbsp; 2025.11

쿠팡 본사에서 진행된 24시간 글로벌 해커톤(8개국 참여)에서 AI 기반 스미싱 탐지·리스크 평가 API **'Smishing Filter'**를 기획부터 배포까지 단독 수행.

- FastAPI 기반 고성능 RESTful API 설계 및 구축 (솔로 개발 및 아키텍처 설계)
- OpenAI GPT-4 Vision API로 문자 텍스트·스크린샷 이미지 내 악성 의도를 동시 분석하는 멀티모달 로직 구현
- Docker·Redis 기반 비동기·확장형 백엔드 인프라 설계 (RabbitMQ는 본 해커톤에서 사용한 경험)
- 악성 URL 탐지 및 발신 패턴 분석 기반 정량 위험 지표(Risk Score) 산출 로직 개발

**사용 기술** &nbsp; `Python 3.12` `FastAPI` `OpenAI GPT-4 Vision` `Docker` `PostgreSQL` `Redis` `RabbitMQ(해커톤)`

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
- 글로벌 기술 컨퍼런스 학습: Meta Connect 2025 등 차세대 기술 흐름 분석
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
- **[Bus Booking Automation](https://github.com/Estelle-Lee/bus_booking_automation_app)**
  Nucamp 부트캠프 최종 개인 프로젝트. `Python` `PostgreSQL`
- **[Mozilla Hubs (논문 프로젝트)](https://github.com/Estelle-Lee/hubs)**
  석사 졸업 논문 주제였던 가상공간 접근성 향상 연구를 위해 Mozilla Hubs를 포크하여 작업.

---

## 이전 경력

- **이화자동차정비센타** (2018.01~2018.08) — 사이트 운영·DB 백업·관리 `JavaScript` `PHP` `MySQL` `HTML`
- **mTV** (2016.06~2016.08, 인턴) — 병상용 TV·스마트비전 서비스 기획 및 구성 (메디컬 ICT)

---

## 학력

- **University of Glasgow** — MSc Software Development (2019.09~2021.01)
  - Distinction(최우수) 수료 · 논문: Mozilla Hubs 가상공간 시각장애인 접근성 향상 연구 ([repo](https://github.com/Estelle-Lee/hubs))
- **서울여자대학교** — 정보미디어대학 콘텐츠디자인학과 (이학사, B.Sc) (2012.01~2017.02)
  - 이공계열 전공 · 객체지향 프로그래밍, Java, C/C++, 자료구조 이수

---

## 기타 교육

- **Nucamp** — Backend·SQL·DevOps with Python 부트캠프 수료 (2023.10~2024.03)
  - PostgreSQL, Docker, AWS EC2, Git 기반 DevOps 학습
- **Coursera** — Excel Skills for Business: Essentials 수료 (2022.10~2022.12)
- **KG ITBANK (ITA 지능정보산업기술협회)** — 자바·파이썬 활용 빅데이터 교육 수료 (2017.06~2017.10)

---

## 자격증

- **SQLD (SQL 개발자)** — 한국데이터산업진흥원 (2024.12)
- **정보처리기사** — 필기 합격
- - SELC 학점교류 컨소시엄(2,000명 이상, 20개 이상 대학) 시스템 유지보수 및 확장 개발
