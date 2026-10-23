<div align="center">
  <h1>Nikhil Kushwah</h1>
  <p><b>Distributed Systems & Infrastructure Engineer | C++ & Go | Open Source (CNCF, TiDB)</b></p>
  <p>Dual Degree (B.Tech + M.Tech) @ <b>IIT Kharagpur ('28)</b></p>

  <p>
    <a href="https://www.linkedin.com/in/mr-nikhil-kushwah"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="mailto:nikhilkushwah2k23@gmail.com"><img src="https://img.shields.io/badge/GMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
    <a href="https://leetcode.com/u/jon_snow/"><img src="https://img.shields.io/badge/LEETCODE-370+-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
    <a href="https://codeforces.com/profile/Heisenberg_ww_1"><img src="https://img.shields.io/badge/CODEFORCES-Heisenberg__ww__1-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/></a>
  </p>
</div>

<br/>

### 👤 About Me
- 🎓 Pursuing a **Dual Degree (B.Tech + M.Tech in Chemical Engineering)** at **IIT Kharagpur ('28)**.
- ⚙️ Focused on **Distributed Consensus, Low-Level Systems, Vector Search Engines, and AI Inference Infrastructure**.
- 🌐 Active contributor to open-source infrastructure across **CNCF (Meshery)** and distributed database engines (**PingCAP TiDB**).
- 🧠 Deep focus on **Core CS Fundamentals**: Operating Systems, Storage Engines, Network Protocols, and Concurrency Primitives.
- 🏆 Solved **370+ algorithmic problems** across LeetCode and Codeforces ([`Heisenberg_ww_1`](https://codeforces.com/profile/Heisenberg_ww_1)), focusing on Dynamic Programming, Graphs, and Advanced Data Structures.
- 🎯 Open to **Software Development Engineer (SDE) & Distributed Systems / Backend Internships**.

---

### 🛠️ Tech Stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cpp,c,go,py,postgres,redis,prometheus,linux,ubuntu,bash,docker,cmake,git,github,githubactions,vscode&theme=dark" alt="Tech Stack" />
  </a>
</p>

*Specialized Core:* Raft Consensus, Vector Similarity & Quantization, POSIX Sockets, Thread Pools & Backpressure, Server-Sent Events (SSE), Optimistic Concurrency Control (OCC), Write-Ahead Logging (WAL), Redis Pub/Sub, and WebSockets.

---

### 🌐 Open Source Contributions

| Organization / Repo | Description & Impact | Focus Area |
| :--- | :--- | :--- |
| **[PingCAP (TiDB)](https://github.com/pingcap/tidb)** | Fixed date/time storage semantics in the MySQL expression engine ([#71835](https://github.com/pingcap/tidb/pull/71835) `CastIntAsTime` year-to-date conversion truncation); validated transactional modifiers ([#71803](https://github.com/pingcap/tidb/pull/71803)). | `Go` `Distributed SQL` `Table-driven Tests` |
| **[Meshery (CNCF)](https://github.com/meshery/meshery)** | Normalized component relationship schemas during registration ([#22106](https://github.com/meshery/meshery/pull/22106)), added regression tests for payload merging ([#22098](https://github.com/meshery/meshery/pull/22098)), hardened connection error handling ([#21879](https://github.com/meshery/meshery/pull/21879)), centralized component helpers ([#21831](https://github.com/meshery/meshery/pull/21831)). | `Go` `Cloud Native` `Kubernetes Management` |
| **[MeshKit (CNCF)](https://github.com/meshery/meshkit)** | Deduplicated model definitions & schemas ([#1124](https://github.com/meshery/meshkit/pull/1124)). | `Go` `Microservices` `Data Schemas` |

*🔎 [Explore all authored open-source pull requests on GitHub](https://github.com/pulls?q=is%3Apr+author%3Aparanik-jpg)*

---

### 🚀 Featured Systems Projects

<table style="border-collapse: collapse; border: none;">
  <tr>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>⚡ <a href="https://github.com/paranik-jpg/VectorIndexCPP" style="text-decoration: none;">In-Memory Vector Similarity Search Engine</a></h4>
      <p style="color: #8b949e; font-size: 13px;">High-performance vector index engine in C++20 for similarity search over dense embeddings.</p>
      <ul>
        <li>Engineered cosine & Euclidean metric spaces with bounded Min-Heap top-k collection.</li>
        <li>Architected thread-safe concurrent reads and atomic index mutations using <code>std::shared_mutex</code>.</li>
        <li>Rigorous unit & stress testing validated clean execution under <b>ThreadSanitizer (TSan)</b>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C%2B%2B20-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/Vector%20Search-FF6B6B?style=flat-square"/>
        <img src="https://img.shields.io/badge/AI%20Infra-7928CA?style=flat-square"/>
        <img src="https://img.shields.io/badge/TSan%20Verified-4E9A06?style=flat-square"/>
      </p>
    </td>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🛡️ <a href="https://github.com/paranik-jpg/streaming_reverse_proxy" style="text-decoration: none;">Aegis: Streaming Proxy & Agentic Runtime</a></h4>
      <p style="color: #8b949e; font-size: 13px;">High-performance, backpressure-aware SSE reverse proxy and resilient tool-execution runtime for LLMs.</p>
      <ul>
        <li>Engineered low-latency <b>Server-Sent Events (SSE)</b> reverse proxy with bounded token ring buffers (cap: 2) and slow-consumer eviction (1.5s threshold).</li>
        <li>Propagated <code>context.Context</code> cancellation to immediately abort upstream GPU compute upon client disconnect.</li>
        <li>Built an agentic tool runtime with <b>automated schema self-healing</b>, AST error extraction, and an 8 KiB output budget.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/SSE%20Streaming-FF6B6B?style=flat-square"/>
        <img src="https://img.shields.io/badge/GenAI%20Infra-7928CA?style=flat-square"/>
        <img src="https://img.shields.io/badge/JSON%20Schema-009688?style=flat-square"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🌐 <a href="https://github.com/paranik-jpg/distributed-event-hub" style="text-decoration: none;">Distributed Event Hub</a></h4>
      <p style="color: #8b949e; font-size: 13px;">High-throughput, distributed real-time event pipeline orchestrated via Docker Compose.</p>
      <ul>
        <li>Full-duplex WebSocket streaming with dual read/write pumps, slow-client drops, and a distributed <b>Redis Pub/Sub</b> backplane.</li>
        <li>Distributed <b>fixed-window rate limiter</b> via atomic Redis Lua scripting with reverse-proxy <code>X-Forwarded-For</code> traversal.</li>
        <li>Cache-aside architecture with <b>randomized TTL jitter</b> to mitigate backend cache stampedes.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
    </td>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🏦 <a href="https://github.com/paranik-jpg/bank-ledger-api" style="text-decoration: none;">Production Bank Ledger API</a></h4>
      <p style="color: #8b949e; font-size: 13px;">Production-grade transactional banking ledger API in Go and PostgreSQL.</p>
      <ul>
        <li>Engineered atomic financial transfers under strict ACID guarantees with tuned PostgreSQL connection pools.</li>
        <li>Built robust CLI-driven schema migrations, structured <code>log/slog</code> observability, and deferred panic recovery.</li>
        <li>Maintained regression safety with automated GitHub Actions CI and containerized test execution.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/ACID%20Transactions-009688?style=flat-square"/>
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>👾 <a href="https://github.com/paranik-jpg/mini_DB" style="text-decoration: none;">MiniDB: Transactional Key-Value Store</a></h4>
      <p style="color: #8b949e; font-size: 13px;">An ACID-compliant, in-memory transactional storage engine designed from scratch in modern C++17.</p>
      <ul>
        <li>Engineered <b>Optimistic Concurrency Control (OCC)</b> with local redo/undo buffering, read-your-own-writes isolation, and commit validation.</li>
        <li>Implemented <b>nested transaction savepoints</b> with hierarchical parent merging and isolated rollbacks.</li>
        <li>Built an append-only <b>Write-Ahead Log (WAL)</b> with hex-encoding for delimiter safety and crash-replay recovery.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/OCC%20%2F%20ACID-E34F26?style=flat-square"/>
        <img src="https://img.shields.io/badge/shared__mutex-4E9A06?style=flat-square"/>
        <img src="https://img.shields.io/badge/WAL%20Recovery-0052CC?style=flat-square"/>
      </p>
    </td>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🤖 <a href="https://github.com/paranik-jpg/proxy_server" style="text-decoration: none;">Multi-threaded HTTP Proxy Server</a></h4>
      <p style="color: #8b949e; font-size: 13px;">A hardened forward HTTP proxy engine built from scratch in C++17 using raw Linux POSIX system calls.</p>
      <ul>
        <li>Architected a bounded producer-consumer <b>Thread Pool</b> with 100ms timed backpressure rejection and failure-domain task isolation.</li>
        <li>Hardened network transmission: atomic <code>sendAll()</code> with <code>MSG_NOSIGNAL</code> (anti-SIGPIPE crash defense) and <code>EINTR</code> syscall recovery.</li>
        <li>Enforced Slowloris DoS mitigation via 8 KB header ceilings and <code>SO_RCVTIMEO</code> socket timeout guards.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/POSIX_Sockets-333333?style=flat-square"/>
        <img src="https://img.shields.io/badge/ASan%20%2F%20Valgrind-4E9A06?style=flat-square"/>
        <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white"/>
      </p>
    </td>
  </tr>
</table>

---

### 🔬 Systems Research & CS Internals
- **[CS Fundamentals & Empirical Internals](https://github.com/paranik-jpg/cs-fundamentals)**: Hands-on benchmarking and implementations of preemptive CPU scheduling, context-switch cost estimation, ThreadSanitizer data-race diagnostics, circular deadlocks, SQLite WAL journaling, and B+ tree indexing benchmarks.
- **[Shortest Path Graph Engine](https://github.com/paranik-jpg/shortest_Path_Engine)**: Optimized Dijkstra graph processor using lazy deletion priority queues and Mersenne Twister micro-benchmarks.
- **[Intrusive LFU Cache Engine](https://github.com/paranik-jpg/LFUCache)**: Strict $O(1)$ LFU cache in C++ with custom intrusive doubly-linked frequency chains and hash maps.

---

### 🎬 Beyond the Terminal
- 🎞️ Breaking down technical cinematography, shot composition, and visual storytelling on Instagram ([@what_nik_watches](https://instagram.com/what_nik_watches)).
- ✂️ Editing lyrical music videos and visual sequences using Shotcut and Clipchamp.
- ♟️ Playing competitive chess (TSG Chess Club) and optimizing tactical endgames.

<br/>

<div align="center">
  <sub>Engineered by Nikhil Kushwah • Built for low latency, high concurrency, and distributed resilience</sub>
</div>
