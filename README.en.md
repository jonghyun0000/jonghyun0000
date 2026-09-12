# Jonghyun Lee

![Build something. Make it better.](assets/hero.svg)

My first vibe-coding project was an outfit color matcher. Chuncheon Gwating is the service I feel most attached to. I use AI tools to build, then work on understanding, testing, and improving what I have made.

My current main project is **AIOS**: a local workspace that connects AI conversations with reference material and practical tasks, including execution checks and recovery.

Recent improvements: a color-matching home redesign, solid-color extraction fixes and regression tests; an interactive experiment lab in the coding playground, with 16 new example tests alongside 150 existing smoke checks. See the [Korean profile](https://github.com/jonghyun0000) for the illustrated project collection and improvement records.

I build web applications around everyday problems. I study Business Administration and Software at Hallym University, with experience taking projects from requirements to implementation and deployment.

[한국어](https://github.com/jonghyun0000) · [Email](mailto:king33135867@gmail.com)

## Main project

### AIOS — Local AI Workspace

**Work with AI on my own computer, with approval, verification, and recovery in the same workflow.** This browser-based workspace uses local Ollama models. I build it with AI assistance, verify it through actual execution, and improve it from those results.

- **Workflow:** attach reference material → approve each file write or command → verify execution results → restore file changes without overwriting conflicting later edits.
- **Evidence:** **87 PASS / 3 SKIP** in local browser tests, **15 PASS** for saving last-moment collaborative edits during shutdown, and **2 isolated database restores** without overwriting the original database. These are results from the tested local environment; skipped checks remain explicitly recorded.
- **Current scope:** a project verified in a local development environment, not a publicly hosted web service or a universally installable product. It does not guarantee correct AI answers or successful completion of every task.

`Ollama` `React` `TypeScript` `Fastify` `PostgreSQL` `Redis` `Yjs` `Docker`

**[Source, local setup, and verification records ↗](https://github.com/jonghyun0000/aios)**

## Selected projects

### Hangul Coding Platform
An educational language and web IDE with Korean keywords, console output, and turtle graphics.

- Separates lexing, parsing, AST construction, and interpretation; integrates a CodeMirror editor.
- The repository includes smoke tests for language execution, error messages, input retries, and turtle commands.
- TypeScript · React · CodeMirror 6

[Demo](https://korean-coding-platform.vercel.app) · [Source](https://github.com/jonghyun0000/Korean-coding-platform) · [Tests](https://github.com/jonghyun0000/Korean-coding-platform/blob/main/scripts/smoke.ts)

### Chuncheon Gwating
A 3:3 group-matching service for university students in Chuncheon.

- Organizes student verification, team registration, matching requests, and administration into separate features.
- Client routes distinguish signed-in users and administrators. Production database authorization requires separate verification; route guards alone do not establish data security.
- React · TypeScript · Vite · Supabase

[Demo](https://chuncheon-dating5-0.vercel.app/) · [Source](https://github.com/jonghyun0000/chuncheon-dating5.0) · [Route guard](https://github.com/jonghyun0000/chuncheon-dating5.0/blob/main/src/routes/AdminRoute.tsx)

### Ttukttak — Outfit Color Matching
Extracts representative colors from clothing photos and recommends matching colors.

- Uses central image sampling, K-means clustering, and background weighting.
- Scores color pairs using hue, lightness, saturation, and fashion rules; limits repeated color families.
- Recommendations are rule-based, not a model trained on personal preferences. Lighting and backgrounds can affect extraction.
- React · TypeScript · Vite · Tailwind CSS

[Demo](https://color-matching2-0.vercel.app) · [Source](https://github.com/jonghyun0000/color-matching2.0) · [Recommendation logic](https://github.com/jonghyun0000/color-matching2.0/blob/main/src/lib/color/recommend.ts)

## More work

See the [project directory on my profile](https://github.com/jonghyun0000) for tuition comparison, sign recognition, lottery statistics, a uniform-store kiosk, Instagram data analysis, trading automation, and a campus marketplace.

## Tools and approach

I use AI tools during implementation and work directly on requirements, data structures, authorization design, and deployment. Source and verification references are linked above.

- TypeScript · JavaScript · Python · SQL
- React · Next.js · Vite · Tailwind CSS
- Supabase · PostgreSQL · Vercel · GitHub Actions

## Background

- Business Administration student, double major in Computer Engineering track, Hallym University (2023–)
- Director of Facilities, Student Welfare Committee; campus equipment-rental operations (Mar 2026–)
- Republic of Korea Marine Corps; honorable discharge as Sergeant (Feb 2024–Aug 2025)
- Studying for SQLD and Social Research Analyst Level 2; these are not listed as earned certifications.
