# 🏆 Career Fair Hackathon — Challenge Pack

Welcome to the hackathon! This pack contains **4 independent challenges** across different areas of software engineering. Pick the one that matches your strengths and interests or attempt more than one if you're feeling ambitious.

**Only the first submission will the be reviewed and considered**

All challenges are **2 days long** and **AI tools are fully allowed**. Use whatever helps you build the best product.

---

## 📁 Challenges Overview

| # | Folder | Challenge | Focus Area |
|---|--------|-----------|------------|
| 1 | `taskflow/` | TaskFlow | Backend / REST API |
| 2 | `ask-campus/` | Ask Campus | AI / RAG Chatbot |
| 3 | `nutriscan/` | NutriScan | Frontend / UI·UX |
| 4 | `nowbot/` | NowBot | AI / Real-Time Data |

---

## 1 — TaskFlow `taskflow/`

**What is it?**
Build a personal to-do list REST API from scratch. Users can create, read, update, and delete tasks through HTTP endpoints. Judges will test your API live using Postman no frontend required.

**Who is it for:**
Students interested in backend development, APIs, databases, and DevOps fundamentals.

**Levels at a glance:**
- Level 1 — Core CRUD: all 6 endpoints working in memory
- Level 2 — Validation & Filtering: input validation, query parameters, sorting
- Level 3 — Persistence & Polish: real database via Docker Compose, stats endpoint, optional UI

**What to read:**
📄 [taskflow/taskflow-challenge.pdf](taskflow/taskflow-challenge.pdf)


---

## 2 — Ask Campus `ask-campus/`

**What is it?**
Build a chatbot that answers natural language questions about a university student dataset. Given a CSV of student records — enrollments, classes, grades, and scores — a user should be able to ask questions like *"Who scored the highest in Math?"* or *"What classes is Ahmed enrolled in?"* and get accurate answers.

**Who is it for:**
Students interested in AI, LLMs, prompt engineering, and building intelligent applications.

**Levels at a glance:**
- Level 1 — Get the Data Talking: load the CSV, pass it to an LLM, return correct answers
- Level 2 — Go Deeper: aggregations, rankings, follow-up questions with conversation context
- Level 3 — Make It Usable: a real chat UI with session history and graceful error handling

**What to read first:**
📄 [ask-campus/ask-campus-challenge.pdf](ask-campus/ask-campus-challenge.pdf)

**What is provided:**
- 📊 `ask-campus/university_records.csv` — the student dataset your chatbot must answer questions about

---

## 3 — NutriScan `nutriscan/`

**What is it?**
A two-part UI/UX and frontend challenge. First you will 

**design** — producing wireframes for both a desktop and mobile version of a calorie tracking app. 

**build** — turning your desktop wireframe into a fully working web application. No backend or database required; all data lives in the browser.


**Who is it for:**
Students interested in UI/UX design, frontend development, and building polished user interfaces.

**Levels at a glance:**
- Level 1 — Design + Core Tracker: wireframes for all screens + working meal log with localStorage
- Level 2 — Richer Experience: progress bar, per-meal breakdown, edit functionality, validation
- Level 3 — Polish & Delight: app matches wireframe, meal history, food library, optional chart

**What to read first:**
📄 [nutriscan/nutriscan-challenge.pdf](nutriscan/nutriscan-challenge.pdf)


---

## 4 — NowBot `nowbot/`

**What is it?**
Build a chatbot that answers questions about what is happening **right now** — live sports news and real-time weather. Unlike a regular chatbot, NowBot must fetch fresh data from two real APIs on every query and use an LLM to turn that raw data into a clear, natural answer.


**Who is it for:**
Students interested in AI, API integration, real-time data, and building intelligent assistants.

**Levels at a glance:**
- Level 1 — Live Data, Real Answers: connect both APIs, detect query type, return a grounded answer
- Level 2 — Smarter Routing: dynamic location detection, sport filtering, conversation context
- Level 3 — A Real Product: full chat UI, source display, error handling, session location preference

**What to read first:**
📄 [nowbot/nowbot-challenge.pdf](nowbot/nowbot-challenge.pdf)


---


## 📋 General Rules

- AI tools are **fully allowed** — use any LLM, code generator, or design assistant you like
- You may use any programming language or framework unless the challenge specifies otherwise
- Submit your source code and a README explaining how to run your project
- Be ready to demo live judges will interact with your app directly

---

## 💡 Tips That Apply to Every Challenge

- **Read the full brief before writing a single line of code.** The levels build on each other — knowing where you are headed helps you structure your work.
- **Get Level 1 working first.** A clean, complete Level 1 beats a half-broken Level 3.
- **Test as you go.** Don't wait until the end to find out something is broken.
- **Use realistic data in your demo.** It makes a much stronger impression than placeholder content.
- **Write a README.** Judges should be able to run your project with one command.

---

*Good luck — we can't wait to see what you build!* 🚀# GUTECH-Career-Fair
