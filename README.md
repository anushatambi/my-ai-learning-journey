# 🚀 My AI Learning Journey

> 80 weeks. From student to AI Engineer. Documented every step of the way.

## 👩‍💻 About This Repo

This repo tracks my complete journey to becoming an AI Engineer.
I update it every week with what I learned, built, and struggled with.
No shortcuts. No skipping. Just consistent daily progress.

**Student:** Anusha Tambi  
**Start Date:** May 2025  
**Goal:** AI Engineer → Forward Deployed Engineer (FDE)  
**Daily commitment:** 2 hours/day, 5 days/week

---

## 🗺️ The Plan — 3 Phases, 80 Weeks

| Phase | Timeline | Goal |
|-------|----------|------|
| Phase A — Internship Ready | Weeks 1–60 | Python, ML, GenAI, RAG, Agents, Azure |
| Phase B — Job Market Ready | Weeks 61–80 | MLOps, Capstone Projects, Interview Prep |
| Phase C — Senior / FDE Ready | Months 21–36 | Advanced Agents, Domain Specialisation, Leadership |

---

## 📅 Weekly Progress Log

### ✅ Week 1–2 · Dev Environment & Git (A0 Kickstart)
**Status:** 95% complete  
**Topics covered:**
- VS Code + Python 3.11 + Cursor IDE + GitHub Copilot setup
- Git: init, clone, add, commit, push, pull, branch, merge
- SSH key connected to GitHub
- Merge conflict resolution (hands-on)
- 13 Linux terminal commands
- GitHub Profile README published

**Built this week:**
- [`anushatambi`](https://github.com/anushatambi/anushatambi) — GitHub Profile README (live)
- [`ai-learning`](https://github.com/anushatambi/ai-learning) — main working repo
- This repo — `my-ai-learning-journey`

**Key lesson:** Silence in the terminal means success. `rm` is permanent. `curl` is what Python does every time it calls an LLM API.

---

## ✅ Week 3–5 · Python Core for AI (A1)

**Status:** Complete  
**Topics covered:**
- Variables, types, strings, lists, dicts, tuples, sets
- Control flow — if/elif/else, for/while loops
- Functions — args, *args, lambda, return
- Error handling — try/except/raise/finally
- File I/O — read/write text and JSON
- Modules — os, math, random, datetime, dotenv
- APIs — requests, GET/POST, status codes
- First LLM API call (Groq — Llama 3.3 70B)
- OOP — classes, inheritance, special methods

**Built this week:**
- `cli-chatbot`(Groq API + conversation history + JSON export) — [view project](https://github.com/anushatambi/ai-learning)
-  Final Assessment (data processing, API integration, OOP)

**Assessments:** Mini Assessment 1 ✅ · Mini Assessment 2 ✅ 10/10 · Mini Assessment 3 ✅ 9/10

**Final Assessment: PASSED**
- Part 1 MCQ: 28/30 (93%)
- Task 1 — Data Processing: ✅ Passed
- Task 2 — API Integration: ✅ Passed
- Task 3 — OOP: ✅ Passed

**Key lesson:** Every AI app is just Python + API calls. Master the basics and every framework becomes easier.

---

### ✅ Week 6–7 · Advanced Python + Async (A1.2)

**Status:** Complete

**Topics covered:**
- Decorators — @wraps, timing decorators, retry decorator factories (@retry(max_attempts, delay))
- Generators — yield, lazy evaluation, streaming large files/data
- Context managers — with statement, @contextmanager, class-based (__enter__/__exit__)
- Type hints — Optional, Union, List, Dict, Python 3.10+ shorthand (|)
- Async Python — async/await, asyncio.gather() for concurrency, asyncio.create_task()
- Async in practice — asyncio.Semaphore for rate-limiting, error handling with return_exceptions=True

**Built this week:**
- Retry + timer decorators applied to a simulated flaky API call
- Chunked data generator + context manager for tracking progress across a `with` block
- Async batch API caller — semaphore-limited concurrency + graceful error handling (the exact pattern used for calling LLM APIs in batch)
- **Project 3: Async Price Monitor** — fetches prices from 5 mock APIs concurrently, tracks price history across check cycles, and alerts when any price changes by more than 10%

**Final Assessment: PASSED**
- Part 1 MCQ: 16/20 (80%)
- Task 1 — Decorators (@timer + @retry): ✅ Passed
- Task 2 — Generator + Context Manager: ✅ Passed
- Task 3 — Async (Semaphore + batch_fetch + error handling): ✅ Passed

**Key lesson:** Async isn't about doing things faster — it's about not wasting time waiting. Semaphores exist because "run everything at once" breaks the moment a real API has rate limits.

## 🛠️ Tools I Use Daily

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat&logo=cursor&logoColor=white)

---

## 📌 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anusha-tambi-062396374)

---

*Updated weekly. Last update: Week 6-7.*
