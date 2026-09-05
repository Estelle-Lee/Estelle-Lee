[🇰🇷 한국어](./CAREER.md) | **🇬🇧 English**

# Career History

> **Bokyung Lee** · Backend Engineer — System Automation · Performance Optimization
> 📧 bokyunglee33@gmail.com · 🔗 [GitHub](https://github.com/Estelle-Lee) · [LinkedIn](https://www.linkedin.com/in/bokyung-estelle-lee/) · [Portfolio](https://bokyung93.notion.site/Backend-Engineering-Portfolio-3c06ed8e97b481edb852f70f40308f1e?source=copy_link)

---

## About

A backend engineer who redesigns repetitive operations into automated structures and resolves system bottlenecks through data-driven diagnosis. I have built a messaging automation engine that eliminated manual per-school operations, along with heterogeneous system integration modules (acting as DB agents and API middleware) and a media-processing automation pipeline. Through APM and execution-plan analysis, I **improved core query performance by ~85%**, achieved a **0% load-failure rate** under 2,000 concurrent users, and performed a zero-downtime Oracle → Tibero migration.

I hold a B.Sc. from a science/engineering faculty (coursework in OOP, Java, C/C++, and data structures) and an MSc in Software Development from the University of Glasgow, completed with Distinction. I aim to find root causes in the data rather than treat symptoms, and I am growing toward designing stable, efficient platforms.

### Core Strengths
- System automation and heterogeneous system integration
- Performance optimization and system stability
- DB migration (zero-downtime Oracle → Tibero)
- Learning-data pipeline design (xAPI / LRS)
- Media processing automation
- Web security · global collaboration

### Tech Stack

| Category | Technologies |
|------|------|
| **Language** | Java, Python, JavaScript, C++, PHP |
| **Framework** | Spring Boot, FastAPI, Vue.js, Servlet |
| **Database** | Oracle, Tibero, MySQL, PostgreSQL, Redis |
| **Infra / Tools** | Docker, Linux, FFMPEG, Jennifer (APM), REST API, ADL LRS (xAPI), Nginx |

---

## Experience

### DUNET Co., Ltd. (Dong-A Media Group affiliate) &nbsp;|&nbsp; R&D Center · Engineer (Assistant Manager) &nbsp;|&nbsp; Jun 2024 – Present

Developing and operating systems for university consortiums, covering system automation/integration, performance optimization, data pipelines, and security.

---

#### 1. KakaoTalk Notification Automation Engine & Heterogeneous System Integration &nbsp;·&nbsp; Jul 2025 – Present

**Overview** &nbsp; Built a messaging engine that integrates heterogeneous systems and standardizes/automates per-school notifications, eliminating manual operations

**Key Work**
- Built per-platform KakaoTalk notification API/DB integration and an admin dispatch system for BLU3 (Jangan Univ.) and BLU5 (Wonkwang Univ.)
- Designed and tested dispatch scenarios and procedures optimized for educational operations, such as automated alerts for at-risk learners
- Developed heterogeneous system integration modules acting as DB agents and API middleware
- Created a shared Excel template and parameter spec for notification-template registration, provided to schools as a standard with guidelines

**Stack** &nbsp; `Java` `Spring Boot` `REST API`

**Impact** &nbsp; The notification feature was specified as a key feature in new contracts, contributing to **winning new school adoption deals**

---

#### 2. FFMPEG-Based Media Processing Automation Pipeline &nbsp;·&nbsp; Mar 2025 – Present

**Overview** &nbsp; Implemented video-encoding automation and streaming optimization logic

**Key Work**
- Designed and built single-classroom and admin batch video-encoding logic with Java/FFMPEG and optimized streaming
- Diagnosed a server-side library dependency conflict and resolved the environment issue at its root by switching to a ProcessBuilder approach
- Currently building an agent-API-based media processing module to replace login/integration errors in an external video solution (Panopto)

**Stack** &nbsp; `Java` `FFMPEG` `ProcessBuilder`

---

#### 3. High-Availability System Performance Optimization &nbsp;·&nbsp; Jun 2024 – Present (ongoing)

**Overview** &nbsp; Diagnosed and resolved system latency under heavy load using APM and execution-plan analysis

**Key Work**
- Traced bottleneck transactions in real time with Jennifer (APM), identifying 2 critical bottlenecks among thousands of queries
- Used execution-plan analysis to pinpoint Full Table Scans and memory-heavy Hash Joins as the root causes
- Induced Nested Loop Joins and designed/applied composite indexes optimized for join and filter conditions
- Verified improvements quantitatively through before/after load testing

**Stack** &nbsp; `Jennifer (APM)` `Oracle` `Tibero` `Query Optimization`

**Impact** &nbsp; Query time reduced **from 6.0s to 0.9s (~85% faster)**, significant CPU/Cost reduction, and **0% load-failure rate** under a 2,000 concurrent-user load test — resolved structurally without adding resources

---

#### 4. Hanyang University On-Premise → Cloud Transition (Oracle → Tibero) &nbsp;·&nbsp; Jun 2024 – Aug 2024

**Overview** &nbsp; Migrated the Oracle-based DB to Tibero with zero downtime as part of Hanyang University's on-premise → cloud transition project

**Key Work**
- Reviewed and refined indexes, sequences, and procedures during test/production DB migration, and converted Oracle-specific aggregate functions for the Tibero environment
- Used Jennifer (APM) to compare and verify the system before and after migration, improving slow queries via indexing and query tuning to secure load-test performance
- Modified and tested auxiliary features (e.g., KakaoTalk SMS OTP delivery type) for the Tibero environment

**Stack** &nbsp; `Oracle` `Tibero` `Jennifer (APM)` `Query Optimization`

**Impact** &nbsp; **Completed the cloud transition with zero service downtime** while improving query performance during migration

---

#### 5. Session Clustering — Multi-Server Session Sharing (Luther University LMS-CC) &nbsp;·&nbsp; Feb 2025 – Apr 2025

**Overview** &nbsp; Built a cross-server session-sharing structure so the LMS and credit-exchange (CC) systems could operate as a single environment

**Key Work**
- Added cyberLogin session-handling logic and configured session clustering so sessions could be carried over between servers
- Performed additional migration to maintain sessions, and tested and troubleshot the entire process
- Analyzed and remediated session-sync issues caused by server-time differences across separate servers

**Stack** &nbsp; `Java` `Session Clustering` `Tibero`

---

#### 6. xAPI/LRS Learning-Data Collection & Storage Environment (TFT Lead) &nbsp;·&nbsp; Aug 2024 – May 2025

**Overview** &nbsp; Led a task force to adopt a Learning Record Store (ADL LRS) for collecting and storing learning-activity data in the xAPI standard

**Key Work**
- Led the ADL LRS adoption task force: analyzed the system, built the test environment, and drove interim reporting
- Built the LRS on a live server with Docker; completed Tin Can API / xAPI metric configuration and learning-activity (Statement) transmission tests
- Resolved ADL LRS technical issues, documented server conf settings, and produced Notion-based guidelines for the team
- Applied OAuth authentication to set up a basic admin access environment

**Stack** &nbsp; `Python` `Docker` `xAPI` `Tin Can API` `ADL LRS` `OAuth`

**Impact** &nbsp; The LRS capability was packaged into a **learning-data collection product, now integrated into the platform and actively sold**

---

#### 7. Next-Generation Learning Experience Platform (LXP) — Development & Operations &nbsp;·&nbsp; Oct 2025 – Present

**Overview** &nbsp; Designed, developed, and operated the core modules of an LXP for university consortiums across multiple universities

**Key Work**
- Designed and developed LXP core modules and established technical standards
- Built and deployed the LXP end-to-end for the Hanyang University foundational-convergence consortium (2,000 users; 20+ universities operating on a single site via credit exchange) and completed a load test at 2,000 concurrent users
- Took full ownership of LXP construction and system stabilization for multiple universities 
- Maintained and extended the SELC credit-exchange consortium system (2,000+ users, 20+ universities)

**Stack** &nbsp; `Java` `Spring Boot` `Oracle` `Tibero`

**Impact** &nbsp; LXP architecture design and core module development contributed to **winning 5 new university contracts**

---

#### 8. Web Security Hardening & Vulnerability Response &nbsp;·&nbsp; Oct 2025 – Present (ongoing)

**Overview** &nbsp; Designed and applied security policies based on web-vulnerability assessments, with ongoing response

**Key Work**
- Continuously reviewed and addressed web-vulnerability reports; designed and applied CSP (Content Security Policy) to block XSS and other web threats (applied to Gyeongsang National Univ. credit exchange)
- Reviewed and patched Nginx version-compatibility vulnerabilities (per Hanyang Univ. credit-exchange client request)
- Built and applied a dedicated cookie-management Java module to strengthen cookie/HTTP security (Jun 2026)

**Stack** &nbsp; `Web Security (CSP)` `Nginx` `Java`

---

#### 9. Rural Development Administration — Next-Gen e-HRD System Build &nbsp;·&nbsp; Aug 2024 – Dec 2024

**Overview** &nbsp; Analyzed and developed the user learning area of an education-operations system and implemented new features

**Key Work**
- Analyzed and developed the learning view and My Page area of the user-facing pages and authored table-definition documents
- Designed and implemented new features including the learning-view menu, offline materials/surveys/assignments/exams, and hybrid content (e.g., unifying offline exams into an online random-question format)
- Analyzed the causes and remedies of web vulnerabilities arising in the learning view, addressed them with shared handling logic, and supported final review

**Stack** &nbsp; `Java` `Oracle` `eGovFrame`



#### 10. Multi-Client LMS Build & Maintenance &nbsp;·&nbsp; Jun 2024 – Present

**Overview** &nbsp; Improved LMS features and handled operational issues for multiple university clients

**Key Work**
- Improved LMS features and handled operational issues for multiple clients including Gyeongsang National, Dong-Ah Institute of Media Arts, Chosun College of Science & Technology, Jangan, Konyang, and Korea National University of Transportation
- Responded to client requests such as domain/parameter changes, mobile-screen adjustments, and survey/exam management bug fixes
- Applied commonly improvable items across all learning views via shared methods

**Stack** &nbsp; `Java` `JavaScript` `Oracle` `Tibero`

---

## Featured Projects (External & Personal)

### LXP Video Encoding Agent (Personal Project, In Progress) &nbsp;|&nbsp; Jun 2026 – Present

Building an independent agent in Go that automatically diagnoses video codec-policy violations and re-encodes based on policy — originating from my hands-on FFMPEG media-processing experience at work.

- Designed a decentralized architecture (no central DB or job queue) reflecting a data-sovereignty constraint: each school deploys independently and school data never leaves its boundary
- Implemented a 7-item codec-policy diagnostics module based on ffprobe metadata (H.264 / AAC-LC / MP4 / yuv420p / CFR 30fps, etc.)
- Developing a pipeline that auto-generates ffmpeg commands, transcodes, and re-verifies when a policy violation is found
- Designed structured logging to collect metrics such as transcoding time and policy-compliance (skip) rate

**Stack** &nbsp; `Go` `FFMPEG` `ffprobe`

---

### HackSeoul 2025 (hosted by Coupang x AngelHack) &nbsp;|&nbsp; Nov 2025

At a 24-hour global hackathon held at Coupang HQ (8 countries participating), I solo-built the AI-based smishing detection & risk-scoring API **'Smishing Filter'** from planning to deployment.

- Designed and built a high-performance RESTful API with FastAPI (solo development and architecture design)
- Implemented multimodal logic using OpenAI GPT-4 Vision API to simultaneously analyze malicious intent in message text and screenshot images
- Designed an asynchronous, scalable backend infrastructure with Docker and Redis (RabbitMQ was used in this hackathon)
- Developed a quantitative risk-score logic based on malicious-URL detection and sender-pattern analysis

**Stack** &nbsp; `Python 3.12` `FastAPI` `OpenAI GPT-4 Vision` `Docker` `PostgreSQL` `Redis` `RabbitMQ (hackathon)`

[GitHub](https://github.com/Estelle-Lee/Smishing-Filter) · [YouTube Demo](https://www.youtube.com/watch?v=hXHGs1FBzZ4)

---

### SheCanCode Hackathon &nbsp;|&nbsp; Mar 2024 &nbsp;·&nbsp; 2nd Place Overall

Built a workplace-inclusivity web service (KidKode).

- Participated in overall service planning, developed post-login screens, and handled Git-based collaboration and merges
- Completed planning and development within a 6-hour limit and presented to the judges

**Stack** &nbsp; `JavaScript` `React (JSX)` `HTML` `Figma`

[GitHub](https://github.com/Estelle-Lee/KidKode-SheCanCode-Hackathon)

---

### Technology Trend Research & Seminars &nbsp;|&nbsp; 2021 – Present

- AI/ICT trend analysis: regular attendance at World IT Show (WIS 2026), AI Summit Seoul (2025·2026), etc.
- Global tech conference study: analysis of next-generation technology trends including Meta Connect 2025
- Applied learnings to project design and query performance optimization logic

---

### BCSWomen Lovelace Colloquium 2020 (Paper) &nbsp;|&nbsp; Apr 2020

Published a paper on assistive navigation devices at a conference hosted by an algorithms professor at the University of Glasgow.

> **Paper:** *Intelligent Assistive Navigating Device: A relationship between the features and enhanced usability*

---

## Academic & Learning Projects

Master's coursework and bootcamp deliverables published on GitHub.

- **[MSc IT Team Project](https://github.com/Estelle-Lee/MSc-IT-Team-Project)** &nbsp;·&nbsp; A+
  Required master's team project at the University of Glasgow. Full lifecycle (planning to development to testing) done as a team.
- **[Advanced Programming](https://github.com/Estelle-Lee/Advanced-Programming)** &nbsp;·&nbsp; A
  Individual assignment for the master's advanced programming course.
- **[Bus Booking Automation](https://github.com/Estelle-Lee/bus_booking_automation_app)**
  Final individual project for the Nucamp bootcamp. `Python` `PostgreSQL`
- **[Mozilla Hubs (thesis project)](https://github.com/Estelle-Lee/hubs)**
  Forked Mozilla Hubs for research on improving accessibility in virtual spaces, the subject of my master's thesis.

---

## Previous Experience

- **Ewha Auto Service Center** (Jan 2018 – Aug 2018) — Site operations, DB backup & management `JavaScript` `PHP` `MySQL` `HTML`
- **mTV** (Jun 2016 – Aug 2016, intern) — Planning and composition of bedside-TV / smart-vision services (medical ICT)

---

## Education

- **University of Glasgow** — MSc Software Development (Sep 2019 – Jan 2021)
  - Completed with Distinction · Thesis: Enhancing accessibility in a virtual space for the visually impaired (Mozilla Hubs) ([repo](https://github.com/Estelle-Lee/hubs))
- **Seoul Women's University** — College of Information & Media, Dept. of Content Design (B.Sc.) (Jan 2012 – Feb 2017)
  - Science/engineering faculty · coursework in OOP, Java, C/C++, data structures

---

## Additional Training

- **Nucamp** — Backend, SQL & DevOps with Python bootcamp (Oct 2023 – Mar 2024)
  - PostgreSQL, Docker, AWS EC2, Git-based DevOps
- **Coursera** — Excel Skills for Business: Essentials (Oct 2022 – Dec 2022)
- **KG ITBANK (ITA)** — Big Data with Java & Python (Jun 2017 – Oct 2017)

---

## Certifications

- **SQLD (SQL Developer)** — Korea Data Agency (Dec 2024)
- **Engineer Information Processing** — Written exam passed
- - Took full ownership of LXP construction and system stabilization for multiple universities (Wonkwang, Daedong, Busan Catholic, Konyang — ~200 users each)
