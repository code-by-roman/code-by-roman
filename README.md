# Hi, I'm Roman 👋

**Full-stack developer and technical project manager.**

I build web apps with **JavaScript, TypeScript and Python**, and I bring 10+ years of shipping products as a project manager and founder. I like turning a vague idea into a plan, a plan into tickets, and tickets into working software, together with a team.

[![Portfolio](https://img.shields.io/badge/Portfolio-cv--roman--pavlenko-0A66C2?style=flat&logo=netlify&logoColor=white)](https://cv-roman-pavlenko.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pavlenko--roman-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pavlenko-roman/)
[![Email](https://img.shields.io/badge/Email-roman.boxes%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:roman.boxes@gmail.com)

---

## 🛠️ Tech stack

| Area                    | Tools                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Languages**           | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4169E1?logo=postgresql&logoColor=white)                                                                                                       |
| **Frontend**            | ![React 19](https://img.shields.io/badge/React_19-20232A?logo=react&logoColor=61DAFB) ![React Router 7](https://img.shields.io/badge/React_Router_7-CA4245?logo=reactrouter&logoColor=white) ![Vite 8](https://img.shields.io/badge/Vite_8-646CFF?logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?logo=tailwindcss&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-443E38)                           |
| **Backend & APIs**      | ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![REST](https://img.shields.io/badge/REST_APIs-555555)                                                                                                                                             |
| **Databases**           | ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?logo=amazondynamodb&logoColor=white)                                                                                         |
| **Cloud & DevOps**      | ![AWS](https://img.shields.io/badge/AWS_Cloud_Practitioner-232F3E?logo=amazonwebservices&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?logo=netlify&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?logo=railway&logoColor=white)                                                                        |
| **Testing & practices** | ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white) Clean Architecture · Git Flow · code review                                                                                                                                                                         |
| **Delivery & tools**    | ![Scrum](https://img.shields.io/badge/Agile-Scrum_%7C_Kanban-6DB33F) ![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white) ![Trello](https://img.shields.io/badge/Trello-0052CC?logo=trello&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white) ![npm](https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) |
| **AI**                  | Working with AI coding agents to plan, build and review features                                                                                                                                                                                                                                                                                                                                                                                                    |

---

## 🚀 Featured work

### 📅 [iMeet / Slots](https://github.com/SlotsForMentoring/Slots) · team project

A scheduling platform that matches trainees with volunteer mentors for 1:1 sessions.
**React 19 · React Router 7 · Vite 8 · Python / FastAPI · Supabase (PostgreSQL) · Google APIs**

- Built the **booking API**: SQLAlchemy model and migration, create-booking endpoint, type-hinted CRUD and services.
- Integrated the **Google Calendar API** so every booking creates a calendar event with a Google Meet link, stored on the booking.
- Wrote endpoint tests for slots and built a read-only **admin "All Slots" oversight page**.
- Worked in a Git Flow team with feature branches, PR reviews, epics, API contracts and sprint plans.

### 🤖 [projectX](https://github.com/code-by-roman/projectX) · CRM system built with AI agents

<!-- TODO(Roman): 1–2 lines on what the CRM does and its stack -->

A CRM system built by orchestrating AI coding agents alongside human collaborators: planning work as issues, letting agents implement and review, and keeping quality high through code review and CI.

### 🗺️ [Discover Catalunya / Discover World](https://github.com/code-by-roman/Discover-Catalunya)

A travel-guide SPA: pick a country, click a region on an SVG map, and browse curated sights with photos, ticket links, opening hours and driving directions from the nearest airport.
**React 19 · React Router 7 · Vite 8 · TypeScript · `@svg-maps` · Vitest · GitHub Actions**

- Clickable, keyboard-navigable region maps built on **`@svg-maps/spain`** and **`@svg-maps/canada`**, driven by one generic `CountryMap` component.
- Nested `:countryId/:regionId/:entryId` routes with **React Router 7**, embedded Google Maps directions.
- **Code-splitting** with `React.lazy` and per-region dynamic `import()`: one ~565 kB bundle became 6–19 kB chunks loaded on demand.
- **GitHub Actions CI** runs lint, typecheck, tests and build on every push and pull request.

### 🐢 [TurtleTalk](https://github.com/code-by-roman/student-new-language-app) · language learning for kids and adults

Word-match and sentence-builder games, spaced-repetition progress, an A1–C2 placement test and a pronunciation check.
**React 19 · TypeScript · Vite 8 · Python / FastAPI · Supabase (Postgres, Auth, Storage) · faster-whisper**

- Rebuilt the **Supabase** schema from SQL: 7 tables, row-level security rules, a storage bucket and a 362-word seed dictionary.
- Python **FastAPI** backend in a Domain-Driven Design layout, with 172 passing `pytest` tests, `ruff` and `mypy` clean.
- Local speech-to-text with **faster-whisper** for pronunciation checks, with no paid API.

---

## ⚙️ How I work

- **Plan first.** Epics, API contracts and sprint plans before code; I ran Scrum delivery as a PM for years.
- **Automate the boring parts.** GitHub Actions for checks and deployment so `main` stays deployable.
- **Build with people and agents.** Clear tickets, small PRs and honest reviews, whether the collaborator is a teammate or an AI agent.

---

## 📜 Background

- 🎓 M.S. in Software Development & Electronic Systems, National Technical University (Ukraine)
- ☁️ AWS Certified Cloud Practitioner (CLF-C02), AWS re/Start graduate
- 💻 Full-Stack Web Developer program, Migracode Barcelona (2025 – 2026)
- 📦 Founder & CEO of Boxes.in.ua (2015 – 2023), Project Manager at Happy design.pro (2022 – 2025)
- 🌍 Ukrainian · Russian · English · Spanish (B1)

📍 **Open to roles in product-driven engineering teams.**
