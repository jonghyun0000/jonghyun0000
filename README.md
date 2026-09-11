# 이종현 · Jonghyun Lee

생활 속 문제를 웹 서비스로 구현하는 대학생 개발자입니다.  
한림대학교에서 경영학과 소프트웨어를 공부하며, 요구사항 정리부터 구현과 배포까지 경험하고 있습니다.

[English](https://github.com/jonghyun0000/jonghyun0000/blob/main/README.en.md) · [Email](mailto:king33135867@gmail.com)

## 대표 프로젝트

### 01. 한글 코딩 플랫폼
**한글로 코드를 작성하고 실행하는 교육용 언어와 웹 IDE**

한글 키워드로 변수·조건문·반복문·함수를 작성하고, 실행 결과를 콘솔과 거북이 그래픽으로 확인합니다.

- **구현:** 렉서 → 파서 → AST → 인터프리터로 언어 처리 단계를 분리하고, CodeMirror 기반 편집기를 연결했습니다.
- **검증 근거:** 저장소의 스모크 테스트에 문법 실행, 오류 메시지, 입력 재시도, 거북이 명령에 대한 확인 사례가 있습니다.
- **기술:** TypeScript · React · CodeMirror 6

[데모](https://korean-coding-platform.vercel.app) · [코드](https://github.com/jonghyun0000/Korean-coding-platform) · [언어 엔진](https://github.com/jonghyun0000/Korean-coding-platform/tree/main/src/lang) · [테스트 코드](https://github.com/jonghyun0000/Korean-coding-platform/blob/main/scripts/smoke.ts)

### 02. 춘천과팅
**춘천 지역 대학생을 위한 3:3 매칭 서비스**

학생 인증, 팀 등록, 매칭 요청과 관리자 화면을 하나의 서비스 흐름으로 구성했습니다.

- **구현:** 인증·팀·매칭·관리자 기능을 나누고, 로그인 상태와 역할에 따라 화면 접근을 구분했습니다.
- **설계 포인트:** 클라이언트의 접근 제어와 서버의 데이터 권한은 별개입니다. 공개 코드에서는 화면 접근 로직을 확인할 수 있으며, 운영 DB 정책은 별도 검증 대상입니다.
- **기술:** React · TypeScript · Vite · Supabase

[데모](https://chuncheon-dating5-0.vercel.app/) · [코드](https://github.com/jonghyun0000/chuncheon-dating5.0) · [기능 구조](https://github.com/jonghyun0000/chuncheon-dating5.0/tree/main/src/features) · [관리자 접근 로직](https://github.com/jonghyun0000/chuncheon-dating5.0/blob/main/src/routes/AdminRoute.tsx)

### 03. 뚝딱 — 상하의 컬러매칭
**옷 사진의 대표 색을 추출하고 어울리는 색 조합을 추천하는 웹앱**

- **구현:** 이미지 중앙 영역에서 픽셀을 샘플링하고, K-means와 배경색 가중치로 대표 색을 추출합니다.
- **설계 포인트:** 색상·명도·채도와 패션 페어를 점수화합니다. 같은 색 계열의 추천 수를 제한해 결과의 다양성을 확보합니다.
- **한계:** 규칙 기반 추천으로, 개인 취향을 학습하는 AI 모델은 아닙니다. 조명과 배경에 따라 추출 결과가 달라질 수 있습니다.
- **기술:** React · TypeScript · Vite · Tailwind CSS

[데모](https://color-matching2-0.vercel.app) · [코드](https://github.com/jonghyun0000/color-matching2.0) · [색 추출](https://github.com/jonghyun0000/color-matching2.0/blob/main/src/lib/color/extract.ts) · [추천 로직](https://github.com/jonghyun0000/color-matching2.0/blob/main/src/lib/color/recommend.ts)

## 다른 프로젝트

| 프로젝트 | 다룬 문제와 기술 |
| --- | --- |
| [대학 등록금 비교](https://github.com/jonghyun0000/University-tuition-fees) | 공공데이터 기반 대학별 등록금 조회·비교 · Next.js |
| [수어 인식기](https://github.com/jonghyun0000/Sign-language1.0) | 웹캠 손 추적과 제스처 분류 · MediaPipe |
| [로또 통계](https://github.com/jonghyun0000/lotto-645-stats) | 역대 회차 통계와 예측 가능성 검정 · 오프라인 PWA |
| [스마트 교복 키오스크](https://github.com/jonghyun0000/smart-School-uniform3.0) | 주문·수선·교환·예약 화면과 관리자 콘솔 |
| [Find-Unfollow](https://github.com/jonghyun0000/Find-Unfollow2.1) | 브라우저에서 처리하는 인스타그램 데이터 분석 |
| [미국주식 자동매매](https://github.com/jonghyun0000/Toss-US-Auto-Trading-Bot) | Python 기반 자동화와 결함 감사 기록 |
| [Re-Campus](https://github.com/jonghyun0000/Re-Campus1.0) | 캠퍼스 중고거래와 탄소 절감량 환산 |

## 개발 방식과 기술

AI 도구를 구현에 활용하며, 요구사항 정의·데이터 구조·권한 설계·배포를 직접 다룹니다. 프로젝트별 구현과 검증 근거는 위 코드 링크에서 확인할 수 있습니다.

- **언어:** TypeScript · JavaScript · Python · SQL
- **프론트엔드:** React · Next.js · Vite · Tailwind CSS
- **데이터·배포:** Supabase · PostgreSQL · Vercel · GitHub Actions

## 배경

- 한림대학교 경영학과 재학 · 컴퓨터공학계열 복수전공 (2023.03–)
- 한림대학교 학생복지위원회 시설국 부장 · 교내 물품대여 서비스 운영 (2026.03–)
- 대한민국 해병대 병장 만기전역 (2024.02–2025.08)

<details>
<summary>학습 중인 분야와 기타 자격</summary>

**학습·시험 준비:** SQLD · 사회조사분석사 2급

**취득 자격:** 운전면허 1종 보통 (2023.07) · 스키지도자 LEVEL 1 (2026.02) · 스키지도요원 TEACHING 1 (2026.02) · 태권도 2단 (2014.09)

</details>
