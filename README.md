<!-- ╔══════════════════════════════════════════════════════════════════╗ -->
<!-- ║  NODE_01 // NITIN MITTAL — BACKEND CONTROL SYSTEM v3.7.3      ║ -->
<!-- ║  The backend never sleeps.                                     ║ -->
<!-- ╚══════════════════════════════════════════════════════════════════╝ -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-boot.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-boot.svg" />
  <img src="assets/hero-boot.svg" alt="Backend infrastructure animation showing a request flowing through API gateway, authentication, business logic, and database before returning 200 OK" width="100%" />
</picture>

</div>

<br/>

<!-- ═══════════════ IDENTITY ═══════════════ -->

<div align="center">

```
┌──────────────────────────────────────────────────────────┐
│  NITIN MITTAL                                            │
│  Java · Backend Engineering · DSA · System Design        │
│  ─────────────────────────────────────────────────────   │
│  "I don't just want to make things work.                 │
│   I want to understand why they work."                   │
└──────────────────────────────────────────────────────────┘
```

</div>

I am a Computer Science student focused on **backend engineering**, **Java**, and **data structures & algorithms**. Rather than stopping at code that simply runs, I am interested in how reliable server-side systems behave under the surface — how databases enforce consistency, how concurrency introduces race conditions, and how systems recover when network calls or transactions fail.

Currently practicing **DSA daily on NeetCode**, building core Java applications, and actively learning **Spring Boot**, relational database design, and fundamental **system design** concepts. Learning through disciplined practice: building, breaking components down, and understanding failure modes.

<br/>

<!-- ═══════════════ SIGNATURE: FAILURE → RECOVERY ═══════════════ -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/failure-recovery.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/failure-recovery.svg" />
  <img src="assets/failure-recovery.svg" alt="Animation showing a request pipeline encountering a 503 error, displaying diagnostic logs, retrying, and recovering to 200 OK" width="100%" />
</picture>

<sub><i>System resilience demonstration — requests encounter failures, timeouts, and state issues in the real world; designing recovery pathways is where backend engineering begins.</i></sub>

</div>

<br/>

<!-- ═══════════════ AREAS OF INTEREST ═══════════════ -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/interests-map.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/interests-map.svg" />
  <img src="assets/interests-map.svg" alt="Infrastructure map showing backend engineering areas of interest: API Design, HTTP, Auth, Databases, Concurrency, System Design, Transactions, and Error Handling" width="100%" />
</picture>

</div>

<br/>

<!-- ═══════════════ CORE REPOSITORIES ═══════════════ -->

## `/system/services`

Primary repositories highlighting algorithmic problem-solving, data structure implementations, and persistent data storage in Java:

<table>
<tr>
<td width="50%" valign="top">

### 🟢 [`Smart_Contact_Book`](https://github.com/Nitinmittal373/Smart_Contact_Book)
`STATUS: ACTIVE` &nbsp;|&nbsp; `LANG: Java` &nbsp;|&nbsp; `CORE DSA`

A modular Java console application where each feature is deliberately mapped to a dedicated data structure:
- **Prefix Search:** Custom `Trie` implementation for auto-complete lookups
- **Fast Lookup & Deletion:** `HashMap` for $O(1)$ operations
- **State Reversal:** `Stack (Deque)` supporting multi-level undo
- **Recent Lookups:** `Queue (Deque)` maintaining the last 5 searches
- **Ordered Views:** `TreeMap` for alphabetical sorting
- **Priority Favorites:** `PriorityQueue` for importance-ranked retrieval
- **Persistence:** Local file I/O for state serialization

**Engineering Focus:** Practical application of data structures to real functional requirements, synchronizing deletions across multiple collections, and handling edge cases in memory management.

</td>
<td width="50%" valign="top">

### 🟢 [`neetcode-submissions`](https://github.com/Nitinmittal373/neetcode-submissions)
`STATUS: ACTIVE` &nbsp;|&nbsp; `LANG: Java` &nbsp;|&nbsp; `ALGORITHMS`

Continuous repository tracking problem solving across core computer science domains via NeetCode:
- **Arrays & Hashing:** Lookup optimization, frequency analysis
- **Two Pointers & Sliding Window:** Subarray and substring efficiency
- **Stack & Binary Search:** Logarithmic search boundaries
- **Trees & Graphs:** Recursive traversals, BFS, DFS
- **Dynamic Programming:** Subproblem caching and state transitions

**Engineering Focus:** Time and space complexity trade-offs ($O(n)$ space vs. compute latency), idiomatic Java implementations, and building algorithmic intuition for scalable data processing.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🟡 [`ExpenseTracker`](https://github.com/Nitinmittal373/ExpenseTracker)
`STATUS: COMPLETED` &nbsp;|&nbsp; `LANG: Java` &nbsp;|&nbsp; `DATABASE PERSISTENCE`

A personal expense manager built in Java. While packaged with an Android Material interface, the primary technical exercise centers on relational persistence and asynchronous database operations:
- **Relational Storage:** Room Database (SQLite abstraction) managing expense entities and category relations
- **Data Access Layer:** DAO interface defining CRUD transactions and aggregate total queries
- **Concurrency Isolation:** Asynchronous operations isolated from UI execution using `ExecutorService` background workers
- **Data Integrity:** Consistent state synchronization across views and persistent storage across app restarts

**Engineering Focus:** Entity design, schema integrity, background thread isolation, and error-resilient state transitions.

</td>
</tr>
</table>

<details>
<summary><code>$ ls /archive/auxiliary-projects --all</code> &nbsp; <i>(Compact view: exploratory, frontend & academic repositories)</i></summary>
<br/>

These projects reflect earlier explorations across web development, hackathons, scripting, and coursework before narrowing focus exclusively to backend systems:

| Repository | Stack | Context & Notes |
|:---|:---:|:---|
| [`HACKATHON_DTU_2026`](https://github.com/Nitinmittal373/HACKATHON_DTU_2026) | JavaScript | Rapid product prototype developed under time constraints during the DTU 2026 hackathon. |
| [`Fitness-Club-Website`](https://github.com/Nitinmittal373/Fitness-Club-Website) | HTML · CSS · JS | Static client-side site exploring semantic layout, responsive styling, and UI interactions. |
| [`PERSONAL_FINANCE_TRACKER`](https://github.com/Nitinmittal373/PERSONAL_FINANCE_TRACKER) | Python | Early exploration into Python syntax, file operations, and CLI calculations. |
| [`SLOT_MACHINE`](https://github.com/Nitinmittal373/SLOT_MACHINE) | Python | CLI game script practicing conditional logic and random number generation. |
| [`PYTHON-TASK`](https://github.com/Nitinmittal373/PYTHON-TASK) | Python | Basic syntax and algorithm exercises in Python. |
| [`DEMO`](https://github.com/Nitinmittal373/DEMO) | HTML | Early experimentation sandbox for basic markup structure. |
| [`BASIC_ML_PROJECT`](https://github.com/Nitinmittal373/BASIC_ML_PROJECT) | Jupyter Notebook | Coursework notebook exploring introductory machine learning concepts. |
| [`NUMPY`](https://github.com/Nitinmittal373/NUMPY) · [`PANDAS`](https://github.com/Nitinmittal373/PANDAS) | Jupyter Notebook | Data manipulation and numerical computing exercises. |

</details>

<br/>

<!-- ═══════════════ BACKEND LAB ═══════════════ -->

## `/system/backend-lab`

A dedicated space for prototyping and validating core backend mechanics through isolated, problem-focused builds. These architectures focus on correctness under concurrency and reliability over superficial features:

| System Prototype | Target Stack | Core Engineering Challenge | Status |
|:---|:---:|:---|:---:|
| **Concurrency-Safe Booking System** | Java · Spring Boot · PostgreSQL | Preventing overselling/double-booking under high concurrent request volume using database row locks (pessimistic vs. optimistic locking) and isolation levels. | `[PLANNED]` |
| **Reliable Wallet Ledger** | Java · Spring Boot · SQL | Guaranteeing transaction atomicity and double-entry consistency for account transfers, incorporating idempotent request keys to prevent duplicate deductions. | `[PLANNED]` |
| **API Reliability Toolkit** | Java · Spring Boot | Implementing automated retry policies with exponential backoff & jitter, rate limiting, and circuit breaker fallbacks for resilient service communication. | `[PLANNED]` |

<br/>

<!-- ═══════════════ ENGINEERING NOTES ═══════════════ -->

## `/system/engineering-notes`

Technical documentation and post-mortems in progress as I study distributed fundamentals, concurrency patterns, and storage engines:

| Topic & Research Area | Focus Area | Status |
|:---|:---|:---:|
| `concurrency/race-conditions-java` | Synchronization primitives, volatile memory semantics, and shared mutable state pitfalls in multi-threaded Java applications | `[IN QUEUE]` |
| `databases/transaction-correctness-acid` | Anatomy of transaction rollbacks, partial failures, and dirty/phantom reads across standard ANSI SQL isolation levels | `[IN QUEUE]` |
| `api-design/idempotency-under-retries` | Structuring RESTful mutating operations with deduplication tokens to handle client network timeouts safely | `[IN QUEUE]` |
| `debugging/connection-pool-exhaustion` | Analyzing connection pool leaks, slow queries, and thread blocking in server-side database adapters | `[IN QUEUE]` |
| `storage/indexes-and-btree-lookups` | How B-Tree indexing influences sequential reads, disk I/O, and query planning efficiency | `[IN QUEUE]` |

<br/>

<!-- ═══════════════ TECH STACK ═══════════════ -->

## `/system/stack`

A factual inventory of tools, languages, and concepts categorized by actual current usage:

```
┌─────────────────────────── CURRENTLY USING ───────────────────────────┐
│ • Language:               Java (JDK 17+) — primary object-oriented    │
│ • Problem Solving:        Data Structures & Algorithms (NeetCode)     │
│ • Persistence:            SQLite / Room Database (Schema, DAOs, CRUD) │
│ • Scripting:              Python (utility scripts & automation)       │
│ • Version Control:        Git & GitHub (daily commits, repo sync)     │
│ • Environment:            Windows & Linux Shell fundamentals          │
└───────────────────────────────────────────────────────────────────────┘
┌────────────────────────── CURRENTLY LEARNING ─────────────────────────┐
│ • Web & Services:         Spring Boot, RESTful APIs, HTTP Lifecycle   │
│ • Relational DBs:         Database normalization, indexing, SQL joins │
│ • System Design:          Client-server architecture, caching basics, │
│                           horizontal vs. vertical scaling concepts    │
└───────────────────────────────────────────────────────────────────────┘
┌──────────────────── ENGINEERING CONCEPTS EXPLORING ───────────────────┐
│ • Concurrency:            Thread safety, race conditions, atomic ops  │
│ • Data Correctness:       ACID properties, isolation levels, commits  │
│ • System Resilience:      Idempotent API design, backoff, retries     │
└───────────────────────────────────────────────────────────────────────┘
```

<br/>

<!-- ═══════════════ WHOAMI ═══════════════ -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/whoami.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/whoami.svg" />
  <img src="assets/whoami.svg" alt="Terminal animation showing developer traits: curiosity high, debugging ongoing, edge cases worth investigating, architecture learning by building" width="560" />
</picture>

</div>

<br/>

<!-- ═══════════════ METRICS ═══════════════ -->

## `/system/metrics`

<div align="center">

<img height="155" src="https://github-readme-stats.vercel.app/api?username=Nitinmittal373&show_icons=true&theme=dark&bg_color=0a0e0a&title_color=00ff88&text_color=557755&icon_color=00d4ff&hide_border=true&border_radius=8" alt="GitHub stats" />
&nbsp;&nbsp;
<img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nitinmittal373&layout=compact&theme=dark&bg_color=0a0e0a&title_color=00ff88&text_color=557755&hide_border=true&border_radius=8" alt="Top languages" />

</div>

<br/>

<!-- ═══════════════ CONNECT ═══════════════ -->

## `/system/connect`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Nitinmittal373-0d1a0d?style=flat-square&logo=github&logoColor=00ff88&labelColor=0a0e0a)](https://github.com/Nitinmittal373)
&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nitinmittal373-0d1a0d?style=flat-square&logo=linkedin&logoColor=00d4ff&labelColor=0a0e0a)](https://www.linkedin.com/in/nitinmittal373)

</div>

<br/>

<!-- ═══════════════ FOOTER ═══════════════ -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/footer.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/footer.svg" />
  <img src="assets/footer.svg" alt="System shutdown: all services stopped, waiting for the next request" width="100%" />
</picture>

</div>

<!-- ╔══════════════════════════════════════════════════════════════════╗ -->
<!-- ║  END OF TRANSMISSION                                           ║ -->
<!-- ║  NODE_01 — Repos are a work in progress, and so am I.          ║ -->
<!-- ╚══════════════════════════════════════════════════════════════════╝ -->
