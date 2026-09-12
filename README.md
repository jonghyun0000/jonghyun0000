<p align="center"><img src="assets/hero.svg" width="100%" alt="이종현 — 아이디어를 만들고, 쓰면서 배웁니다. 경영학 × 소프트웨어, 한림대학교" /></p>

<p align="center">
<a href="mailto:king33135867@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_me-263454?style=flat-square&logo=gmail&logoColor=white" alt="이메일" /></a>
<img src="https://img.shields.io/badge/Hallym-Business_%C3%97_Software-53658A?style=flat-square" alt="한림대학교 경영학 × 소프트웨어" />
<a href="README.en.md"><img src="https://img.shields.io/badge/Read_in-English-716396?style=flat-square" alt="English profile" /></a>
</p>

한림대학교에서 경영학과 소프트웨어를 공부하는 **이종현**입니다. 생활에서 발견한 문제를 웹으로 만들고 있습니다. 첫 바이브코딩이었던 옷 색 매칭에서 시작해, 지역 대학생 서비스와 교육 도구로 관심을 넓혔습니다.

AI와 함께 구현하고, 만든 것을 이해하고 검증하며 개선하는 과정도 이곳에 기록합니다.

현재 가장 집중하는 프로젝트는 **AIOS**입니다. 대화만 하는 AI를 넘어, 내 컴퓨터의 자료와 작업을 연결하고 실행 결과와 복구 가능성까지 확인하는 로컬 작업공간을 만들고 있습니다.

## Main project

### AIOS — 로컬 AI 작업공간

**내 컴퓨터에서 AI와 작업하고, 승인·검증·복구까지 이어지는 흐름.** Ollama 로컬 모델을 연결한 브라우저 작업공간으로, AI와 함께 구현하고 실제 실행으로 확인하며 개선하고 있습니다.

- **작업 흐름:** 자료 연결 → 파일 쓰기·명령 실행 건별 승인 → 실행 결과 검증 → 이후 수정과 충돌하면 덮어쓰지 않는 파일 복구.
- **확인한 근거:** 로컬 브라우저 테스트 **87 PASS / 3 SKIP**, 종료 직전 협업 편집의 저장 검증 **15 PASS**, 기존 DB를 덮어쓰지 않는 **격리 DB 복원 2회**. 검사 당시 환경의 결과이며, 생략한 항목도 구분해 기록합니다.
- **현재 범위:** 로컬 개발 환경에서 검증한 프로젝트입니다. 공개 웹서비스나 모든 컴퓨터에서 바로 설치되는 제품은 아니며, AI 답변의 정확도나 모든 작업의 성공을 보장하지 않습니다.

`Ollama` `React` `TypeScript` `Fastify` `PostgreSQL` `Redis` `Yjs` `Docker`

**[소스·실행 안내·검증 기록 ↗](https://github.com/jonghyun0000/aios)**

## Selected work

### 춘천과팅

<a href="https://chuncheon-dating5-0.vercel.app/"><img src="assets/chuncheon.svg" width="100%" alt="춘천과팅 — 춘천 지역 대학생을 위한 3:3 매칭 서비스" /></a>

**춘천 지역 대학생을 위한 3:3 매칭 서비스.** 가장 애착을 갖고 발전시켜 온 프로젝트입니다. 학생 인증부터 팀 등록, 매칭 요청, 관리자 화면까지 하나의 흐름으로 연결했습니다.

`React` `TypeScript` `Supabase` `Vercel`

**[서비스 열기 ↗](https://chuncheon-dating5-0.vercel.app/)** · [저장소](https://github.com/jonghyun0000/chuncheon-dating5.0)

### 뚝딱 — 컬러매칭

<a href="https://color-matching2-0.vercel.app"><img src="assets/color.svg" width="100%" alt="뚝딱 컬러매칭 — 첫 바이브코딩 프로젝트, 옷 사진에서 색 추출과 조합 추천" /></a>

**“이 옷에 무슨 색을 입지?”에서 시작한 첫 바이브코딩.** 옷 사진에서 대표 색을 추출하고, 상황에 맞는 색 조합을 추천합니다. 사진 없이 색을 눌러 바로 체험할 수도 있습니다.

- **만든 것:** K-means 색 추출, 색 조합 추천과 이유, 상황별 모드, 즐겨찾기.
- **개선한 것:** 단색 사진 분석 오류 수정, 같은 입력의 결과 재현, 업로드 오류 안내와 키보드 포커스.
- **확인할 수 있는 근거:** 색 추출 경계 사례와 등록 색 전체의 추천 제약을 확인하는 자동 테스트. 추천 점수는 취향이나 정확도 확률이 아닌 규칙 기반 참고값입니다.

`React` `TypeScript` `Vite` `Color analysis`

**[직접 체험하기 ↗](https://color-matching2-0.vercel.app)** · [저장소](https://github.com/jonghyun0000/color-matching2.0) · [테스트](https://github.com/jonghyun0000/color-matching2.0/blob/main/scripts/color.test.ts) · [개선 기록](https://github.com/jonghyun0000/color-matching2.0/blob/main/docs/UPGRADE.md)

### 한글코딩 놀이터

<a href="https://korean-coding-platform.vercel.app"><img src="assets/hangul.svg" width="100%" alt="한글코딩 놀이터 — 한글 코드와 거북이 그림으로 배우는 교육 도구" /></a>

**코딩을 처음 배우는 사람이, 아는 말로 시작할 수 있도록.** 한글 코드와 거북이 그래픽을 연결한 교육용 웹앱입니다. 언어 처리와 학습 경험을 더 이해하며 발전시키고 있는 프로젝트입니다.

- **만든 것:** 한글 언어 엔진, CodeMirror 편집기, 12차시 미션과 학습 진도 저장.
- **개선한 것:** 변의 수와 누적 합을 바꿔보는 예제 실험실. 먼저 예상하고, 설명을 보고, 코드로 실행하는 흐름을 추가했습니다.
- **확인할 수 있는 근거:** 기존 문법·미션 스모크 테스트 150개와 새 실험 예제 테스트 16개. 코드 교체·페이지 이동 시 저장 처리도 보완했습니다.

`TypeScript` `React` `CodeMirror` `Canvas`

**[놀이터 열기 ↗](https://korean-coding-platform.vercel.app)** · [저장소](https://github.com/jonghyun0000/Korean-coding-platform) · [테스트](https://github.com/jonghyun0000/Korean-coding-platform/tree/main/scripts) · [개선 기록](https://github.com/jonghyun0000/Korean-coding-platform/blob/main/docs/UPGRADE.md)

## Also built

| 프로젝트 | 다룬 문제 |
| :--- | :--- |
| [대학 등록금 비교](https://github.com/jonghyun0000/University-tuition-fees) | 공공데이터를 대학별로 조회하고 비교하기 |
| [수어 인식기](https://github.com/jonghyun0000/Sign-language1.0) | 웹캠 손 추적과 제스처 분류 |
| [로또 통계](https://github.com/jonghyun0000/lotto-645-stats) | 역대 회차 통계와 예측 가능성 검정 |
| [스마트 교복 키오스크](https://github.com/jonghyun0000/smart-School-uniform3.0) | 매장의 주문·수선·교환·예약 흐름 |
| [Find-Unfollow](https://github.com/jonghyun0000/Find-Unfollow2.1) | 브라우저 안에서 인스타그램 데이터 분석 |
| [미국주식 자동매매](https://github.com/jonghyun0000/Toss-US-Auto-Trading-Bot) | Python 자동화와 결함 감사 기록 |
| [Re-Campus](https://github.com/jonghyun0000/Re-Campus1.0) | 캠퍼스 중고거래와 탄소 절감량 환산 |

## Tools I work with

<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/React-192C3D?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Next.js-20242D?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Supabase-164C3C?style=flat-square&logo=supabase&logoColor=3FCF8E" alt="Supabase" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

## Beyond code

경영학의 관점으로 서비스의 필요성을 생각하고, 소프트웨어로 작게 구현해 봅니다.

- **한림대학교** 경영학과 · 컴퓨터공학계열 복수전공 (2023.03–)
- **학생복지위원회 시설국 부장** · 교내 물품대여 서비스 운영 (2026.03–)
- **대한민국 해병대** 병장 만기전역 (2024.02–2025.08)

<details>
<summary>학습 중인 분야 · 기타 자격</summary>

학습·시험 준비: SQLD, 사회조사분석사 2급

취득 자격: 운전면허 1종 보통 · 스키지도자 LEVEL 1 · 스키지도요원 TEACHING 1 · 태권도 2단

</details>

---

<p align="center"><b>작은 문제에서 시작해, 더 나은 결과물로.</b><br /><a href="mailto:king33135867@gmail.com">king33135867@gmail.com</a></p>
