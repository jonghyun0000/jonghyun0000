<p align="center"><img src="assets/profile/hero-en.png" width="100%" alt="Jonghyun Lee — From everyday problems to working products." /></p>

I study Business Administration and Software at Hallym University. My first project recommended outfit colors; since then, I have explored campus services, educational tools, a local AI workspace, and a video editor. I build with AI assistance and improve my work through execution checks and hands-on use.

[king33135867@gmail.com](mailto:king33135867@gmail.com) · [한국어](README.md)

## Now

- Building [AIOS](#aios), a local workspace that connects files on my computer with AI conversations.
- Refining [JH CUT Studio](#jhcut), a macOS video editor with Korean subtitles and translation, in its local development build.
- Running the campus equipment-rental service as Director of Facilities on the Student Welfare Committee.

## Featured projects

<a id="aios"></a>
<a href="https://github.com/jonghyun0000/aios"><img src="assets/profile/aios-en.png" width="100%" alt="AIOS — Local AI Workspace" /></a>
A workspace connecting personal reference material and AI conversations with task approval, execution checks, and recovery.

<details>
<summary>Implementation and verification scope</summary>

- Attach reference material and approve individual file changes or commands.
- Check exit codes and file hashes; stop recovery when it conflicts with later edits.
- Real AI and file operations run locally. The public demo uses fictional documents and simulated replies to illustrate the workflow.

</details>

`TypeScript` `React` `Fastify` `PostgreSQL` `Ollama`

[Try the workflow](https://aios-demo-mu.vercel.app) · [Source and setup](https://github.com/jonghyun0000/aios) · [Verification records](https://github.com/jonghyun0000/aios/blob/main/docs/43-web-model-selection.md)

<a id="jhcut"></a>
<a href="https://github.com/jonghyun0000/JHCutStudio"><img src="assets/profile/jhcut-en.png" width="100%" alt="JH CUT Studio — Local Video Editor for macOS" /></a>
A Korean-first editor connecting video editing, captions, translation, and export on a local computer.

<details>
<summary>Implementation and verification scope</summary>

- Timeline editing, automatic captions, and translation between Korean, Japanese, and English.
- Checkpoints and resume support for long tasks, with output quality checks.
- Currently a local development build, with installation instructions and documented verification scope.

</details>

`Swift` `macOS` `whisper.cpp`

[Source](https://github.com/jonghyun0000/JHCutStudio) · [Setup](https://github.com/jonghyun0000/JHCutStudio/blob/main/docs/INSTALL-0.7.md) · [Verification status](https://github.com/jonghyun0000/JHCutStudio/blob/main/docs/STATUS.md)

<a id="poseidon"></a>
<a href="https://github.com/jonghyun0000/project-poseidon"><img src="assets/profile/poseidon-en.png" width="100%" alt="Project Poseidon — Ocean Data and Voyage Simulation" /></a>
A research project comparing wave and marine wind data with observations and exploring changes across routes and departure conditions.

<details>
<summary>Implementation and verification scope</summary>

- Connects global forecasts, port search, and voyage simulation.
- Records observational comparisons and conditions with insufficient samples separately.
- Still in research and validation; suitability for operational navigation has not been established.

</details>

`Python` `FastAPI` `JAX` `MapLibre`

[Source and research](https://github.com/jonghyun0000/project-poseidon) · [Observational validation](https://github.com/jonghyun0000/project-poseidon/blob/main/docs/PHASE24_GLOBAL_OBSERVATIONAL_VALIDATION.md)

<a id="chuncheon"></a>
<a href="https://github.com/jonghyun0000/chuncheon-dating5.0"><img src="assets/profile/chuncheon-en.png" width="100%" alt="Chuncheon Gwating — Student Matching Service" /></a>
A 1:1–4:4 matching web app for university students in Chuncheon. It connects student verification, team registration, matching requests, and administration in one workflow.

<details>
<summary>Implementation and verification scope</summary>

- Student verification, team and member registration, matching requests and acceptance, and administration screens.
- Improvements to atomic team saves, concurrent matching, personal data access, and registration and withdrawal flows.
- Published application, browser, and database verification records, with local tests distinguished from production deployment checks.

</details>

`React` `TypeScript` `Supabase` `Vercel`

[Open the service](https://chuncheon-dating5-0.vercel.app/) · [Source](https://github.com/jonghyun0000/chuncheon-dating5.0) · [Verification records](https://github.com/jonghyun0000/chuncheon-dating5.0/blob/main/docs/validation/README.md)

## Services and tools

<table width="100%">
<tr>
<td width="33%" valign="top">
<strong>PromPotion</strong><br />
A web MVP for composing, copying, and saving architecture prompts from visual selections. No image generation API is connected.
<p>
<a href="https://prompotion.vercel.app"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-try-en-dark.png" /><img src="assets/profile/btn-try-en-light.png" width="93" height="28" alt="Try PromPotion" /></picture></a>
<a href="https://github.com/jonghyun0000/prompotion"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="PromPotion source" /></picture></a>
</p>
</td>
<td width="33%" valign="top">
<strong>Hangul Coding Playground</strong><br />
An educational web app connecting a Korean-keyword language engine, code editor, and turtle graphics.
<p>
<a href="https://korean-coding-platform.vercel.app"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-try-en-dark.png" /><img src="assets/profile/btn-try-en-light.png" width="93" height="28" alt="Try Hangul Coding Playground" /></picture></a>
<a href="https://github.com/jonghyun0000/Korean-coding-platform"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="Hangul Coding Playground source" /></picture></a>
</p>
</td>
<td width="33%" valign="top">
<strong>Unfollow Lens 2.2</strong><br />
A PWA that analyzes Instagram JSON relationships and changes between snapshots in the browser.
<p>
<a href="https://re-campus-yngl.vercel.app"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-try-en-dark.png" /><img src="assets/profile/btn-try-en-light.png" width="93" height="28" alt="Try Unfollow Lens 2.2" /></picture></a>
<a href="https://github.com/jonghyun0000/Find-Unfollow2.1"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="Unfollow Lens 2.2 source" /></picture></a>
</p>
</td>
</tr>
</table>

## More work

<table width="100%">
<tr>
<td width="50%" valign="top">
<strong>Ttukttak — Outfit Color Matching</strong><br />
My first vibe-coding project: representative color extraction and rule-based outfit combinations.
<p>
<a href="https://color-matching2-0.vercel.app"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-try-en-dark.png" /><img src="assets/profile/btn-try-en-light.png" width="93" height="28" alt="Try Ttukttak — Outfit Color Matching" /></picture></a>
<a href="https://github.com/jonghyun0000/color-matching2.0"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="Ttukttak — Outfit Color Matching source" /></picture></a>
</p>
</td>
<td width="50%" valign="top">
<strong>Tuition Receipt</strong><br />
Explore and compare university financial disclosures with data provenance.
<p>
<a href="https://university-tuition-fees.vercel.app"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-try-en-dark.png" /><img src="assets/profile/btn-try-en-light.png" width="93" height="28" alt="Try Tuition Receipt" /></picture></a>
<a href="https://github.com/jonghyun0000/University-tuition-fees"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="Tuition Receipt source" /></picture></a>
</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<strong>Lotto 6/45 Statistics</strong><br />
Draw statistics and tests of number-selection assumptions. This is not a winning-number prediction service.
<p>
<a href="https://lotto-645-stats.vercel.app"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-try-en-dark.png" /><img src="assets/profile/btn-try-en-light.png" width="93" height="28" alt="Try Lotto 6/45 Statistics" /></picture></a>
<a href="https://github.com/jonghyun0000/lotto-645-stats"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="Lotto 6/45 Statistics source" /></picture></a>
</p>
</td>
<td width="50%" valign="top">
<strong>ABBA</strong><br />
Goal-based financial plan calculations and AI explanations. Account connections are UI mockups; run this project locally.
<p>
<a href="https://github.com/jonghyun0000/abba-finance-hackathon#시작하기"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-setup-en-dark.png" /><img src="assets/profile/btn-setup-en-light.png" width="102" height="28" alt="Run ABBA locally" /></picture></a>
<a href="https://github.com/jonghyun0000/abba-finance-hackathon"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="ABBA source" /></picture></a>
</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<strong>Re:Campus</strong><br />
A browser-storage marketplace demo with illustrative environmental metrics.
<p>
<a href="https://re-campus.vercel.app"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-try-en-dark.png" /><img src="assets/profile/btn-try-en-light.png" width="93" height="28" alt="Try Re:Campus" /></picture></a>
<a href="https://github.com/jonghyun0000/Re-Campus1.0"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="Re:Campus source" /></picture></a>
</p>
</td>
<td width="50%" valign="top">
<strong>School Uniform Kiosk</strong><br />
Customer and administration screens for uniform orders, alterations, exchanges, and reservations.
<p>
<a href="https://smart-school-uniform-app2-0-iw2y.vercel.app/customer"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-try-en-dark.png" /><img src="assets/profile/btn-try-en-light.png" width="93" height="28" alt="Try School Uniform Kiosk" /></picture></a>
<a href="https://github.com/jonghyun0000/smart-School-uniform3.0"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="School Uniform Kiosk source" /></picture></a>
</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<strong>Hand Tracking and Gesture Classification</strong><br />
An experiment in webcam hand tracking and rule-based classification, with explicit uncertainty in handshape mappings.
<p>
<a href="https://sign-language1-0-jsqy.vercel.app/"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-try-en-dark.png" /><img src="assets/profile/btn-try-en-light.png" width="93" height="28" alt="Try Hand Tracking and Gesture Classification" /></picture></a>
<a href="https://github.com/jonghyun0000/Sign-language1.0"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="Hand Tracking and Gesture Classification source" /></picture></a>
</p>
</td>
<td width="50%" valign="top">
<strong>US Stock Trading Bot</strong><br />
Order, fill, and accounting consistency; documented defects and improvements. Local simulation setup is available.
<p>
<a href="https://github.com/jonghyun0000/Toss-US-Auto-Trading-Bot#실행"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-setup-en-dark.png" /><img src="assets/profile/btn-setup-en-light.png" width="102" height="28" alt="Run US Stock Trading Bot locally" /></picture></a>
<a href="https://github.com/jonghyun0000/Toss-US-Auto-Trading-Bot"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/profile/btn-source-en-dark.png" /><img src="assets/profile/btn-source-en-light.png" width="82" height="28" alt="US Stock Trading Bot source" /></picture></a>
</p>
</td>
</tr>
</table>

## Technologies used in these projects

- **Web:** TypeScript · React · Next.js
- **Backend and data:** Fastify · Python · FastAPI · PostgreSQL · Supabase
- **Local AI and apps:** Ollama · Swift · whisper.cpp
- **Execution and verification:** Docker · GitHub Actions · unit and browser tests

## Beyond code

I use business studies to think about why a service is needed, and software to explore how it can work.

- Business Administration student, double major in Computer Engineering track, Hallym University (Mar 2023–)
- Director of Facilities, Student Welfare Committee; campus equipment-rental operations (Mar 2026–)

<details>
<summary>Other experience and learning</summary>

- Republic of Korea Marine Corps; completed service as Sergeant (Feb 2024–Aug 2025)
- Studying for SQLD and Social Research Analyst Level 2
- Qualifications: Korean Class 1 driver's license; ski instructor LEVEL 1 and TEACHING 1; Taekwondo 2nd Dan

</details>
