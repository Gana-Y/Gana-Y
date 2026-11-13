<!-- ================================================================ -->
<!--         Ganesh Yandigeri — Applied AI & Systems Engineer         -->
<!-- ================================================================ -->
<div align="center">

<h1 align="center">
  Ganesh Yandigeri
</h1>

<h3 align="center">
  <code>AI Systems & Backend Engineer &nbsp;•&nbsp; High-Throughput RAG &nbsp;•&nbsp; Sandboxed Execution &nbsp;•&nbsp; Low-Latency APIs</code>
</h3>

<p align="center">
  <strong>Bangalore, India</strong> &nbsp;•&nbsp; 
  <a href="mailto:ganeshyandigeri1@gmail.com">ganeshyandigeri1@gmail.com</a> &nbsp;•&nbsp; 
  <a href="https://ganesh-y.vercel.app">ganesh-y.vercel.app</a>
</p>

<p align="center">
  <em>"Bridging foundation models with operating system primitives. Software engineering first; AI applied with telemetry, evals, and strict latency budgets."</em>
</p>

<!-- ================================================================ -->
<!--                         QUICK VERIFICATION BAR                   -->
<!-- ================================================================ -->

<p align="center">
  <img src="https://img.shields.io/badge/MCA%20Candidate-Atria%20Institute%20of%20Tech-1461FF?style=flat-square&logo=academia" alt="Education" />
  <img src="https://img.shields.io/badge/CGPA-9.35%20%2F%2010.0-success?style=flat-square" alt="CGPA" />
  <img src="https://img.shields.io/badge/Retrieval%20SLA-Sub--200ms%20HNSW-blueviolet?style=flat-square" alt="SLA" />
  <img src="https://img.shields.io/badge/Execution%20Telemetry-Sub--millisecond-orange?style=flat-square" alt="Telemetry" />
  <img src="https://img.shields.io/badge/Automated%20Tests-100%25%20Passing%20(Pytest)-brightgreen?style=flat-square" alt="Pytest" />
</p>

<!-- ================================================================ -->
<!--                         CONNECTIVITY LINKS                       -->
<!-- ================================================================ -->

<p align="center">
  <a href="https://github.com/Gana-Y">
    <img src="https://img.shields.io/badge/GITHUB-%23000000.svg?style=for-the-badge&logo=github&logoColor=white"/>
  </a>&nbsp;
  <a href="https://www.linkedin.com/in/ganesh-yandigeri">
    <img src="https://img.shields.io/badge/LINKEDIN-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>&nbsp;
  <a href="https://x.com/Ganesh821060">
    <img src="https://img.shields.io/badge/X_(TWITTER)-%23000000.svg?style=for-the-badge&logo=X&logoColor=white"/>
  </a>&nbsp;
  <a href="mailto:ganeshyandigeri1@gmail.com">
    <img src="https://img.shields.io/badge/EMAIL-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>&nbsp;
  <a href="https://ganesh-y.vercel.app">
    <img src="https://img.shields.io/badge/PORTFOLIO-%230077B5.svg?style=for-the-badge&logo=googlechrome&logoColor=white"/>
  </a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=Gana-Y&label=Profile+Views&color=1461FF&style=for-the-badge"/>
</p>

<!-- ================================================================ -->
<!--                         SYSTEMS TECH STACK                       -->
<!-- ================================================================ -->

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B%20%7C%20FastAPI%20%7C%20AsyncIO-161b22?style=flat-square&logo=python"/>&nbsp;
  <img src="https://img.shields.io/badge/Linux%20cgroups%20v2%20%7C%20Docker-161b22?style=flat-square&logo=linux"/>&nbsp;
  <img src="https://img.shields.io/badge/ChromaDB%20(HNSW)%20%7C%20Redis%20Cache-161b22?style=flat-square&logo=redis"/>&nbsp;
  <img src="https://img.shields.io/badge/PostgreSQL%20%7C%20SQLAlchemy%20ORM-161b22?style=flat-square&logo=postgresql"/>&nbsp;
  <img src="https://img.shields.io/badge/React%2019%20%7C%20TypeScript%20%7C%20Tailwind-161b22?style=flat-square&logo=react"/>
</p>

</div>

---

<!-- ================================================================ -->
<!--           Neural Workstation Animated ASCII Profile Card         -->
<!-- ================================================================ -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Gana-Y/Gana-Y/main/dark_mode.svg?v=20261105b">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Gana-Y/Gana-Y/main/light_mode.svg?v=20261105b">
    <img alt="Ganesh Yandigeri Animated ASCII Terminal Profile Card" src="https://raw.githubusercontent.com/Gana-Y/Gana-Y/main/dark_mode.svg?v=20261105b" width="850">
  </picture>
</div>

---

## 🏛️ Flagship Production Systems

### 🚀 1. Florix AI — Enterprise-Grade Multimodal RAG Platform
> **Production AI Academic Engine & Real-Time Viva Defense Arbiter**
> 
> *Stack: Python, FastAPI (AsyncIO), Google Gemini API, ChromaDB (HNSW), PostgreSQL (SQLAlchemy), SlowAPI, React 19*

* **In-Database RAG Architecture:** Ingests high-density technical textbooks, PDFs, and YouTube transcripts with hierarchical parent-child chunking and metadata-filtered dense vector search.
* **Deterministic Sub-200ms Retrieval:** Engineered custom HNSW index parameters (`M=16`, `ef_construction=64`, `ef_search=40`) delivering sub-200ms semantic search with SQLite/Postgres fallback cascades.
* **Semantic Caching & Token Economics:** Two-tier Redis cache matching query embeddings at $\tau \ge 0.92$ cosine similarity, dropping median LLM response latency from $1.8\text{s}$ down to $12\text{ms}$ and eliminating redundant API billing.
* **High-Concurrency Telemetry:** Modeled student streaks, comprehension evaluations, and spaced-repetition memory retention across $15+$ relational PostgreSQL tables via SQLAlchemy with connection-pooled async sessions.
* **Verification:** Evaluated with automated regression suites across 555+ assertions validating hallucination rates $<2.1\%$.

👉 **[Inspect Florix AI Repository ↗](https://github.com/Gana-Y/Florix_AI)** • **[System Architecture Spec ↗](https://github.com/Gana-Y/Florix_AI#architecture)**

---

### ⚡ 2. Vesper — Isolated Code Execution Engine & 7-State POSIX Arbiter
> **Hardened Linux Sandbox & Microsecond Code Evaluation Arbiter**
> 
> *Stack: Python, Linux cgroups v2, Docker Security Envelopes, Seccomp, POSIX Primitives, Pytest*

* **Defense-in-Depth Isolation Envelope:**
  * **Memory Boundaries:** Enforces strict un-swappable memory ceilings ($128\text{MB}$) via Linux `cgroups v2` (`memory.max`).
  * **Fork-Bomb Immunity:** Hard-capped thread and process ceilings strictly limited to $64$ execution tasks (`pids.max`).
  * **Ephemeral Storage:** Root filesystem mounted strictly read-only; execution occurs within ephemeral, zero-persistence `tmpfs` RAM scratchpads unmounted immediately post-verdict.
  * **Air-Gapped Networking:** Built with `network_mode: none` ensuring zero socket allocation and zero data exfiltration from untrusted user payloads.
* **7-State Deterministic POSIX State Machine:**
  * Implements atomic execution verdicts: `AC` (Accepted), `WA` (Wrong Answer), `TLE` (Time Limit Exceeded), `MLE` (Memory Limit Exceeded), `RE` (Runtime Error), `CE` (Compilation Error), and `OLE` (Output Limit Exceeded).
* **Sub-Millisecond Telemetry:** High-resolution timers recording execution CPU cycles down to sub-millisecond precision. 100% Pytest pass rates across boundary invariants, memory leak regression tests, and security breakout payloads.

👉 **[Inspect Vesper Repository ↗](https://github.com/Gana-Y/vesper-engine)** • **[POSIX State Machine Specification ↗](https://github.com/Gana-Y/vesper-engine#state-machine)**

---

### 📈 3. OrderCore — High-Throughput Limit Order Book & Matching Engine
> **Sub-Microsecond Low-Latency Financial Matching Engine**
> 
> *Stack: Python, FastAPI, WebSockets, Dual Priority Heaps, Red-Black Trees, AsyncIO*

* **Throughput & Latency Benchmarks:** Processes **$136{,}000\text{ orders/second}$** at a median execution latency of **$4.3\mu\text{s}$**.
* **Order Book Mechanics:** Dual-heap price-time priority matching engine ($O(1)$ best bid/ask resolution, $O(1)$ amortized cancellations via hash-indexed pointers).
* **High-Frequency Concurrency:** Non-blocking async event loop streaming live orderbook depth over bidirectional WebSockets.

👉 **[Inspect OrderCore Repository ↗](https://github.com/Gana-Y/OrderCore)**

---

## 📚 Open-Source Systems & Architecture Vaults

Curated technical publications, system design handbooks, and open-source infrastructure tools maintained for the global engineering community:

| Repository | Focus & Architecture | Impact & Highlights |
|:---|:---|:---:|
| 🧠 [**LLM-System-Patterns**](https://github.com/Gana-Y/LLM-System-Patterns) | Production RAG patterns, sub-300ms latency budgets, HyDE, RRF, and the Production Disaster Manual. | **Enterprise AI System Design Manual** |
| ⚡ [**Zero-Bill-Cloud-Stack**](https://github.com/Gana-Y/Zero-Bill-Cloud-Stack) | Production $0.00 cloud infrastructure matrix: Koyeb, Neon, Upstash, Qdrant & Cloudflare R2. | **Zero-Card Cloud Architecture** |
| 🔌 [**Supercharged-MCP**](https://github.com/Gana-Y/Supercharged-MCP) | Model Context Protocol handbook: 25+ production servers, Python FastMCP & TS SDK starters, Docker sandbox. | **Anthropic MCP Production Kit** |
| 🎓 [**Free-Courses**](https://github.com/Gana-Y/Free-Courses) | Verified 100% free courses & certifications from NVIDIA, Anthropic, AWS, Google, Harvard, and MIT. | **Free Developer Vault** |
| 📚 [**AI-ML-Notes**](https://github.com/Gana-Y/AI-ML-Notes) | In-depth mathematical breakdowns of Deep Learning, Attention mechanisms, and Transformer architectures. | **Applied AI Knowledge Base** |

---

## 📊 Live Engineering Activity & Metrics

<div align="center">
  <p align="center">
    <img src="https://github-stats-extended.vercel.app/api?username=Gana-Y&show_icons=true&hide_border=true&theme=tokyonight&bg_color=0d1117&title_color=1461FF&icon_color=1461FF&text_color=c9d1d9&count_private=true&include_all_commits=true" height="210"/>
    &nbsp;&nbsp;
    <img src="https://streak-stats.demolab.com?user=Gana-Y&theme=tokyonight&hide_border=true&background=0d1117&ring=1461FF&fire=ff6b35&currStreakLabel=1461FF&sideLabels=c9d1d9&dates=c9d1d9" height="210"/>
  </p>
  <p align="center">
    <img height="195" src="https://github-stats-extended.vercel.app/api/top-langs/?username=Gana-Y&layout=compact&hide_border=true&theme=tokyonight&bg_color=0d1117&title_color=1461FF&text_color=c9d1d9&langs_count=8"/>
  </p>
</div>

---

## ⚡ Live Telemetry & GitHub Contributions

<br/>

### 📊 System Overview & Languages Activity
<p align="center">
  <img src="github-metrics-overview.svg" alt="Overview Metrics"/>
</p>

<br/>

### 📅 3D Isometric Commit Matrix
<p align="center">
  <img src="github-metrics-calendar.svg" alt="3D Isometric Contributions Calendar"/>
</p>

<br/>

### 🏆 Verified Engineering Milestones
<p align="center">
  <img src="github-metrics-achievements.svg" alt="Engineering Achievements Badges"/>
</p>

---

## ⚡ Algorithmic Problem Solving (LeetCode)

<div align="center">

[![LeetCode Stats](https://leetcard.jacoblin.cool/Ganesh_Op?theme=dark&font=Fira+Code&ext=heatmap&border=0&radius=10&width=750)](https://leetcode.com/u/Ganesh_Op/)

</div>

---

## 🐍 Continuous Contribution Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Gana-Y/Gana-Y/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Gana-Y/Gana-Y/output/github-snake.svg"/>
  <img alt="github contribution snake" src="https://raw.githubusercontent.com/Gana-Y/Gana-Y/output/github-snake.svg"/>
</picture>

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1461FF,50:0d1b4b,100:0d0d0d&height=120&section=footer&animation=fadeIn" width="100%"/>

**`> Ganesh Yandigeri // Systems & Applied AI // Shipping Production Infrastructure`**

</div>
