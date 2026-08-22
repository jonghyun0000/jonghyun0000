<a id="korean"></a>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&pause=1200&center=true&vCenter=true&width=720&lines=%EC%9D%B4%EC%A2%85%ED%98%84%20%7C%20Indie%20Maker%20%26%20ENTJ%3BBusiness%20%C3%97%20Software%20%40%20Hallym%20Univ.%3B%EA%B8%B0%ED%9A%8D%20%E2%86%92%20%EC%84%A4%EA%B3%84%20%E2%86%92%20%EA%B0%9C%EB%B0%9C%20%E2%86%92%20%EB%B0%B0%ED%8F%AC%EA%B9%8C%EC%A7%80%20%ED%98%BC%EC%9E%90%3BAI-native%20builder%20%C2%B7%20%EC%B6%98%EC%B2%9C" alt="Typing SVG" />
</p>

<h1 align="center">안녕하세요, 이종현입니다</h1>

<p align="center">
  <a href="mailto:king33135867@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-king33135867%40gmail.com-EA4335?logo=gmail&logoColor=white"></a>
  <a href="https://github.com/jonghyun0000"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-jonghyun0000-181717?logo=github&logoColor=white"></a>
</p>

<p align="center"><b>한국어</b> · <a href="#english">English</a></p>

---

> **떠오르면 일단 만들어버리는 사람 — 기획서 대신 배포 링크로 말합니다.**

기획 · 설계 · 개발 · 배포까지 혼자 완결하는 대학생 개발자. 될지 안 될지는 회의가 아니라 돌아가는 결과물로 확인합니다.

한림대학교 경영학 × 소프트웨어 복수전공 (춘천) · 해병대 병장 만기전역

---

## 대표 프로젝트

### 춘천과팅 — 대학생 3:3 매칭 플랫폼

춘천 지역 대학생을 대상으로 한 매칭 서비스. 인증부터 결제 흐름까지 전 과정을 혼자 설계하고 구현했습니다.

- 학생증 사진 업로드 → 관리자 승인으로 이어지는 인증 워크플로
- Supabase RLS 기반 권한 설계 · 시크릿 분리 · 키 로테이션 정책 문서화
- 한 / 영 / 일 / 중 4개 국어 i18n, 무료 플랜 슬립 방지용 GitHub Actions keepalive
- **Stack**: React · TypeScript · Vite · Supabase (PostgreSQL · Auth · Storage) · Vercel

[배포 링크](https://chuncheon-dating4-0.vercel.app/) · [Repo](https://github.com/jonghyun0000/chuncheon-dating5.0)

### 한글 코딩 플랫폼 — 한글 프로그래밍 언어 & 웹 IDE

한글 키워드(만약 / 반복 / 함수)로 동작하는 교육용 언어를 직접 설계하고 구현했습니다.

- 렉서 → 파서 → AST → 트리워킹 인터프리터 직접 구현 (약 1,400줄)
- CodeMirror 6 커스텀 언어 지원: 문법 하이라이팅 · 자동 들여쓰기 · 자동완성 · 호버 툴팁
- 거북이 그래픽 실행 환경, 한글 IME 스마트 따옴표 등 입력기 예외 처리
- **Stack**: TypeScript · React · CodeMirror 6

[Repo](https://github.com/jonghyun0000/Korean-coding-platform)

### 대학 등록금 비교 — 공공데이터 기반 조회·분석 서비스

전국 대학의 등록금 데이터를 정리해 학교별로 조회하고 비교할 수 있게 만든 서비스입니다.

- 대학별 데이터셋 구축과 비교 화면 구성
- **Stack**: Next.js (App Router) · TypeScript · Tailwind CSS

[Repo](https://github.com/jonghyun0000/University-tuition-fees)

### 수어 인식기 — 웹캠 기반 한국 수어 실시간 인식

카메라로 손 모양을 인식해 자음과 단어를 판별하고, 결과를 음성으로 출력합니다.

- MediaPipe Hands 양손 추적 · 제스처 분류 · 인식 신뢰도 표시와 디바운싱
- 자음 10개, 단어 5개 인식 · 한국어 음성 출력(TTS)
- **Stack**: TypeScript · React · MediaPipe

[Repo](https://github.com/jonghyun0000/Sign-language1.0)

### 스마트 교복 키오스크 — 매장 주문 · 수선 · 예약 화면

교복 매장을 상정해 만든 고객용 키오스크와 관리자 콘솔입니다.

- 주문 / 수선 / 교환 / 예약 4개 고객 플로우 + 관리자 통계 대시보드
- **Stack**: Next.js (App Router) · TypeScript · Supabase

[Repo](https://github.com/jonghyun0000/smart-School-uniform3.0)

### Find-Unfollow — 인스타그램 언팔로워 분석 PWA

데이터를 서버로 보내지 않고 브라우저 안에서만 처리하는 프라이버시 우선 설계입니다.

- 인스타그램 데이터 내보내기 파일 파싱 → 언팔 / 맞팔 분석과 통계 차트
- 서비스 워커 · 매니페스트 기반 설치형 PWA
- **Stack**: Next.js · TypeScript · Tailwind CSS

[Repo](https://github.com/jonghyun0000/Find-Unfollow2.1)

---

## 성장 로그

여섯 번의 프로젝트가 곧 여섯 단계의 성장이었습니다.

| 단계 | 프로젝트 | 얻은 것 |
| --- | --- | --- |
| 01 | 상하의 색 매칭 웹앱 | AI 도구를 개발에 제대로 활용하는 법 |
| 02 | 인스타 언팔로워 찾기 | 필요한 것을 직접 만들기 시작 |
| 03 | 춘천과팅 | SQL · 백엔드 · RLS 권한 설계 첫 도입 |
| 04 | 통계 대시보드 | "만들기"에서 "배포하기"로 |
| 05 | 증권사 오픈 API 자동매매 (진행 중) | 외부 API · 키 관리 · 자동화 파이프라인 |
| 06 | 콘텐츠 수익화 실험 | 기술을 수익 구조로 연결하는 감각 |

---

## 일하는 방식

AI 도구(Claude, Cursor 등)를 적극 활용해 구현 속도를 끌어올리되, **요구사항 정의 · DB 스키마와 권한(RLS) 설계 · 배포는 직접** 합니다. 전역 후 5개월간 아이디어를 배포까지 반복해서 밀어붙인 기록이 이 계정입니다.

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white">
</p>

- **Languages** — TypeScript · JavaScript · Python · SQL
- **Frontend** — React · Next.js · Vite · Tailwind CSS
- **Backend / Infra** — Supabase (PostgreSQL · Auth · Storage · RLS) · Vercel · GitHub Actions

---

## 경력

- **2026.03 – 현재** · 한림대학교 학생복지위원회 · 시설국 부장
  - 교내 물품대여 서비스 운영
- **2024.02.19 – 2025.08.18** · 대한민국 해병대 · 병 1303기
  - 병장 만기전역

## 자격증

**데이터 · 분석**
- **SQLD** (SQL 개발자, 한국데이터산업진흥원) — 준비 중
- **사회조사분석사 2급** — 준비 중

**기타**
- 운전면허 1종 보통 · 2023.07.13
- 스키지도자 자격증 LEVEL 1 · 2026.02.02
- 스키지도요원 자격증 TEACHING 1 · 2026.02.12
- 태권도 2단 · 2014.09.15

## 학력

- 한림대학교 경영학과 재학 · 컴퓨터공학계열 복수전공 (2023.03 – )

## Contact

- Email: king33135867@gmail.com

---
---

<a id="english"></a>

<h1 align="center">Hi, I'm JONGHYUN</h1>

<p align="center"><a href="#korean">한국어</a> · <b>English</b></p>

---

> **The kind of person who builds it the moment the idea strikes — a deployed link says more than a planning doc.**

A university student developer who takes projects from idea to deployment solo — planning, architecture, development, and shipping. Ideas get validated by working results, not by meetings.

Business Administration × Software double major @ Hallym University, Chuncheon, Korea · Republic of Korea Marine Corps, honorable discharge as Sergeant

---

## Featured Projects

### Chuncheon Gwating — 3:3 group matching platform for university students

A matching service for students in the Chuncheon area. Designed and built end to end, from verification through the payment flow.

- Student-ID photo upload → admin-approval verification workflow
- Supabase RLS-based authorization design, secret separation, documented key-rotation policy
- 4-language i18n (KO / EN / JA / ZH), GitHub Actions keepalive against free-tier sleep
- **Stack**: React · TypeScript · Vite · Supabase (PostgreSQL · Auth · Storage) · Vercel

[Deployment](https://chuncheon-dating4-0.vercel.app/) · [Repo](https://github.com/jonghyun0000/chuncheon-dating5.0)

### Hangul Coding Platform — a Korean-keyword programming language & web IDE

Designed and implemented an educational language driven by Korean keywords (만약 / 반복 / 함수 — if / loop / function).

- Hand-built lexer → parser → AST → tree-walking interpreter (~1,400 LOC)
- Custom CodeMirror 6 language support: syntax highlighting, auto-indent, autocomplete, hover tooltips
- Turtle-graphics runtime; handles Korean IME edge cases such as smart quotes
- **Stack**: TypeScript · React · CodeMirror 6

[Repo](https://github.com/jonghyun0000/Korean-coding-platform)

### University Tuition Compare — public-data tuition lookup and comparison

Organizes tuition data for universities across Korea into a searchable, comparable interface.

- Per-university dataset construction and comparison views
- **Stack**: Next.js (App Router) · TypeScript · Tailwind CSS

[Repo](https://github.com/jonghyun0000/University-tuition-fees)

### Sign Language Recognizer — real-time Korean sign language via webcam

Recognizes hand shapes through the camera, identifies consonants and words, and speaks the result aloud.

- MediaPipe Hands dual-hand tracking, gesture classification, confidence display and debouncing
- 10 consonants and 5 words recognized, Korean text-to-speech output
- **Stack**: TypeScript · React · MediaPipe

[Repo](https://github.com/jonghyun0000/Sign-language1.0)

### Smart Uniform Kiosk — in-store order / repair / reservation screens

A customer kiosk and admin console designed for a school-uniform store.

- Four customer flows (order / repair / exchange / reservation) + admin statistics dashboard
- **Stack**: Next.js (App Router) · TypeScript · Supabase

[Repo](https://github.com/jonghyun0000/smart-School-uniform3.0)

### Find-Unfollow — Instagram unfollower analysis PWA

Privacy-first design: data never leaves the browser.

- Parses Instagram data-export files → unfollower / mutual analysis with statistics charts
- Installable PWA with service worker and web manifest
- **Stack**: Next.js · TypeScript · Tailwind CSS

[Repo](https://github.com/jonghyun0000/Find-Unfollow2.1)

---

## Growth Log

Six projects, six stages of growth.

| Stage | Project | What it taught me |
| --- | --- | --- |
| 01 | Outfit color-matching web app | Using AI tools properly for real development |
| 02 | Instagram unfollower finder | Building the things I actually needed |
| 03 | Chuncheon Gwating | First real SQL, backend, and RLS authorization design |
| 04 | Statistics dashboard | Moving from "building" to shipping |
| 05 | Brokerage open-API auto trading (in progress) | External APIs, key management, automation pipelines |
| 06 | Content monetization experiments | Connecting technology to revenue |

---

## How I Work

I use AI tools (Claude, Cursor, etc.) aggressively to accelerate implementation, while **owning requirements, DB schema and authorization (RLS) design, and deployment myself**. This account is the record of five months since military discharge of repeatedly pushing ideas all the way to deployment.

## Tech Stack

- **Languages** — TypeScript · JavaScript · Python · SQL
- **Frontend** — React · Next.js · Vite · Tailwind CSS
- **Backend / Infra** — Supabase (PostgreSQL · Auth · Storage · RLS) · Vercel · GitHub Actions

---

## Experience

- **Mar 2026 – Present** · Student Welfare Committee, Hallym University · Director of Facilities
  - Operating the campus equipment-rental service
- **Feb 2024 – Aug 2025** · Republic of Korea Marine Corps · 1303rd class
  - Honorable discharge as Sergeant

## Certifications

**Data & Analysis**
- **SQLD** (SQL Developer, Korea Data Agency) — in preparation
- **Social Research Analyst Level 2** — in preparation

**Others**
- Driver's License, Class 1 Ordinary · Jul 2023
- Ski Instructor Level 1 · Feb 2026
- Ski Teaching 1 · Feb 2026
- Taekwondo 2nd Dan · Sep 2014

## Education

- B.B.A. in progress, double major in Computer Engineering track — Hallym University (Mar 2023 – )

## Contact

- Email: king33135867@gmail.com
