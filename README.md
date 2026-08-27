# Hi, I'm Victor 👋

I'm a recent **Computer Science graduate from UC Berkeley**. I like building software at
both ends of the stack — from AVX2 intrinsics and B+ tree indexes up to autonomous agents
and the dashboards people actually use.

- 🔭 Interested in systems programming, performance engineering, applied cryptography, AI agents, and full-stack development
- 🛠️ Recently shipped an autonomous AI grant-finding agent, an end-to-end encrypted file-sharing system, and a parallel convolution optimizer
- 💼 Previously Software Developer Intern at **Geopogo**, and a CS Teaching Assistant who tutored 240 students
- 🎓 B.A. Computer Science, UC Berkeley (2026) · A.S. Computer Science, Pasadena City College (2024)
- 📫 Reach me on [LinkedIn](https://linkedin.com/in/victorkhant) · [Portfolio Website](https://victorkhant.github.io/Portfolio-Website/) · victor.mkhant@gmail.com

---

## 🧰 Tech Stack

![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white)

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=anthropic&logoColor=white)

---

## 🚀 Featured Projects
### [BellyUp — Surplus Food Dispatch](https://github.com/VictorKhant/Build-For-Good/tree/Vic-final) · `Python` · `FastAPI` · `SciPy` · `Leaflet` · `OSRM`
A three-sided dispatch board that moves end-of-night restaurant surplus to the downtown San
Diego blocks where need is actually counted — scored on meals served net of what the run
costs the collector, over **382 blocks** from the Downtown San Diego Partnership street count.
Routes on the real street network via a precomputed **69,169-pair directed matrix**, so
one-ways and freeway ramps are respected and a route is never a straight line through a
building. Assigns the whole evening as one optimal bipartite matching instead of report-by-
report, recovering **$345 of net value** the greedy pass gave away at the same spread. Every
rejected pairing returns a reason rather than disappearing, and outreach locations are
enforced agency-only at the API layer — block-aggregated so the output cannot be
operationalised for enforcement.

<a href="https://bellyup.vercel.app/"><img src="https://img.shields.io/badge/Live_app-222?style=flat&logo=githubpages&logoColor=white" alt="Live App"></a>
<a href="https://www.youtube.com/watch?v=DPjVAOSpjb8"><img src="https://img.shields.io/badge/Watch_the_demo-FF0000?style=flat&logo=youtube&logoColor=white" alt="Watch the demo"></a>

### [Fundworthy — AI Grant-Finder Agent](https://github.com/VictorKhant/Fundworthy) · `Python` · `FastAPI` · `React` · `Claude API`
An autonomous agent that cuts a nonprofit's weekly grant search from 10+ hours to near-zero.
It crawls funders, filters, and returns a short, ranked, sourced list — with a tiered
LLM-scoring pipeline that holds each run under ~$1 and reports _"amount not stated"_ rather
than hallucinating a number. Encrypted on-disk key storage, a pytest suite with a
ranking-calibration test, and CI/CD via GitHub Actions.

<a href="https://fundworthy.duckdns.org/"><img src="https://img.shields.io/badge/Live_app-222?style=flat&logo=githubpages&logoColor=white" alt="Live App"></a>

### [Parallel 2D Convolution Optimizer](https://github.com/VictorKhant/Parallel-2D-Convolution-Optimizer) · `C` · `AVX2` · `OpenMP` · `Open MPI`
A high-performance image/video convolution engine, optimized through three stacked layers
of parallelism — SIMD vectorization, multithreading, and multiprocessing — for a **9.16×
speedup** over the naive baseline.

### [End-to-End Encrypted File-Sharing System](https://gitfront.io/r/VictorKhant/doQe3wqhgNZS/File-Sharing-System/) · `Go`
A secure multi-user file-sharing client designed to run on a completely untrusted server,
using RSA, AES, HMAC, and Argon2 to guarantee confidentiality, integrity, and authenticity.
Cryptographically enforced access revocation, validated against 14 integration tests.
_Source available on request._

### [SQL Database Management System](https://github.com/VictorKhant/SQL-Database-Management-System) · `C++`
A relational database engine built entirely from scratch: a state-machine tokenizer, a
Shunting-Yard expression parser, a custom B+ tree index for O(log n) lookups, and
persistent binary storage.

<a href="https://www.youtube.com/watch?v=N3vFsQg-IL4"><img src="https://img.shields.io/badge/Watch_the_demo-FF0000?style=flat&logo=youtube&logoColor=white" alt="Watch the demo"></a>
