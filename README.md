<div align="center">

# Rajwat Singh

**Backend & Infrastructure**  ·  Computer Science, Gettysburg College '27

`Go` · `PostgreSQL` · `CI/CD` · `TypeScript`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rajwat-singh-159ab3147)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rajwat2004@gmail.com)

</div>

---

I work on the parts of a system that have to hold up when everything happens at once — build
pipelines, database constraints, payment callbacks. Currently a software engineering intern at
**Tekvortex** on the **InvisiRisk** team, where I moved CI/CD for 500+ repositories onto GitHub
Actions. Previously shipped production .NET at **Re: Members**.

Graduating **May 2027** and looking for **new-grad software engineering roles** in backend,
infrastructure, and platform engineering.

---

## Selected Work

### 🏟️ [khel-arena](https://github.com/RajwatSingh/khel-arena) — Futsal booking platform
`Next.js` `TypeScript` `Supabase` `PostgreSQL`

Booking systems fail in one specific way: two people claim the same slot at the same instant. I
solved it in the database rather than in application code — **Postgres advisory locks** around the
booking transaction plus **`EXCLUDE` constraints** on overlapping time ranges, so conflicting
claims are rejected by Postgres itself and no application-level check can race past them.

Bookable slots are generated **virtually** from operating hours and pricing rules instead of being
materialized as rows. Payments run through eSewa and Khalti with verified server-to-server
callbacks. Covered by Vitest unit and integration tests in a GitHub Actions pipeline.

### 💳 [Palamedes](https://palamedes-5af1.onrender.com/login/?next=/dashboard/) — Financial dashboard *(live)*
`Django` `Python` `Stripe`

Automates dues collection for a 60-member organization, replacing spreadsheet tracking as the
system of record for member balances. Stripe integration handles single, partial, and bulk
payments; removing manual payment matching brought ledger accuracy to 100%. Built it as chapter
Treasurer — I am also its primary user.

### ⚙️ [interpreter](https://github.com/RajwatSingh/interpreter) — Monkey language interpreter
`Go`

A lexer, Pratt parser, and evaluator for the Monkey language, written in Go. Working through
Thorsten Ball's *Writing an Interpreter in Go* to get closer to how language tooling actually
works underneath.

---

## Experience

**Software Engineer Intern** — Tekvortex *(InvisiRisk team)* · May 2026 – Present
- Migrated InvisiRisk CI/CD workflows onto **GitHub Actions** across **500+ repositories**,
  consolidating per-repo pipeline config into shared reusable workflows so changes ship from one
  place instead of 500.
- Built a data labeling interface that replaced manual inspection as the collection path for a new
  ML model, turning **13,000** raw JSON captures and **4.5M** network traffic calls into a labeled
  training set.
- Integrated a security proxy into CI/CD YAML config so scanning applied automatically to
  **7,000+ builds** with no per-repository setup step.

**Software Engineer Intern** — Re: Members · May 2025 – Aug 2025
- Closed **30 tickets in 50 days**, the highest among all peer interns, shipping production changes
  to a **.NET/C#** financial platform used by national Greek organizations.
- Fixed incorrect account balances on the transaction page by correcting the date parameter passed
  to the underlying stored procedure; added client-side file size validation to the data import page.

**Grader & Teaching Assistant** — Gettysburg College CS Department · Jan 2025 – May 2025
- Held weekly office hours for **50+ students**, debugging student code and explaining both the
  error and the reasoning behind the fix.

---

## Toolkit

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Infrastructure**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Frameworks**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)

---

## Education

**B.S. Computer Science** — Gettysburg College · Expected May 2027
**GPA 4.08 / 4.00** *(A+ = 4.33)* · Dean's List, 5 of 6 terms

Operating Systems · Computer Networks · Advanced Systems Design · Databases ·
Computer Organization & Assembly · Data Structures & Algorithms · Theory of Computation

**Honors**
- **Abraham Lincoln Scholar** — Gettysburg College merit scholarship, $40,000
- **Founder Daniel William Cooper Scholar** — Sigma Chi Foundation, **1 of 7 nationwide**, $10,000

---

<div align="center">

**Open to new-grad software engineering roles starting 2027**

[rajwat2004@gmail.com](mailto:rajwat2004@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rajwat-singh-159ab3147)

</div>
