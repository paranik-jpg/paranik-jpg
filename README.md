<div align="center">
  <h1>Nikhil Kushwah</h1>
  <p><b>Systems & Backend Engineer | Dual Degree @ IIT Kharagpur ('28)</b></p>

  <p>
    <a href="https://www.linkedin.com/in/mr-nikhil-kushwah"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="mailto:nikhil4409t@gmail.com"><img src="https://img.shields.io/badge/GMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
    <a href="https://leetcode.com/u/jon_snow/"><img src="https://img.shields.io/badge/LEETCODE-370+-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  </p>
</div>

<br/>

### 👤 About Me
- 🎓 Pursuing an **Integrated Dual Degree (B.Tech + M.Tech in Chemical Engineering)** at **IIT Kharagpur ('28)**.
- ⚙️ Focused on **High-Performance C++, Go Concurrency, Low-Level Systems, and AI Inference Infrastructure**.
- 🌐 Active contributor to open-source infrastructure across **CNCF (Meshery)** and distributed database engines (**PingCAP TiDB**).
- 🧠 Strong foundation in **Core CS Fundamentals**: Operating Systems, Database Management Systems, Computer Networks, and Low-Level Design (LLD).
- 🏆 Solved **370+ algorithmic problems** on LeetCode ([`jon_snow`](https://leetcode.com/u/jon_snow/)), focusing on Graphs, Dynamic Programming, and Advanced Data Structures.
- 🎯 Seeking **Remote Software Development Engineer (SDE) & Backend Systems Internships**.

---

### 🛠️ Tech Stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cpp,c,go,py,postgres,redis,prometheus,linux,ubuntu,bash,docker,cmake,git,github,githubactions,vscode&theme=dark" alt="Tech Stack" />
  </a>
</p>

*Systems Primitives: POSIX Sockets, Thread Pools & Backpressure, Server-Sent Events (SSE), Optimistic Concurrency Control (OCC), Write-Ahead Logging (WAL), Transactional Outbox, Redis Streams & Consumer Groups, Distributed Rate Limiting, TCP/IP Protocols, and WebSockets.*

---

### 🌐 Open Source Contributions

- **[PingCAP (TiDB)](https://github.com/pingcap/tidb)**: Fixed date/time storage semantics in the MySQL expression engine ([#71835](https://github.com/pingcap/tidb/pull/71835) `CastIntAsTime` year-to-date conversion truncation) and validated transactional modifiers ([#71803](https://github.com/pingcap/tidb/pull/71803)), verified via table-driven monorepo test suites.
- **[Meshery (CNCF)](https://github.com/meshery/meshery)**: Normalized component relationship schemas during registration ([#22106](https://github.com/meshery/meshery/pull/22106)), added regression tests for payload merging ([#22098](https://github.com/meshery/meshery/pull/22098)), hardened connection error handling ([#21879](https://github.com/meshery/meshery/pull/21879)), centralized component registration helpers ([#21831](https://github.com/meshery/meshery/pull/21831)), and deduplicated model definitions in **[MeshKit](https://github.com/meshery/meshkit)** ([#1124](https://github.com/meshery/meshkit/pull/1124)).
- 🔎 *[Explore all authored open-source pull requests on GitHub](https://github.com/pulls?q=is%3Apr+author%3Aparanik-jpg)*

---

### 🚀 Featured Systems Projects

<table style="border-collapse: collapse; border: none;">
  <tr>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🛡️ <a href="https://github.com/paranik-jpg/streaming_reverse_proxy" style="text-decoration: none;">Aegis: Streaming Proxy & Agentic Runtime</a></h4>
      <p style="color: #8b949e; font-size: 13px;">High-performance, backpressure-aware SSE reverse proxy and resilient tool-execution runtime for LLMs.</p>
      <ul>
        <li>Engineered low-latency <b>Server-Sent Events (SSE)</b> reverse proxy using <code>http.NewResponseController</code> with write deadlines and slow-consumer eviction.</li>
        <li>Propagated <code>context.Context</code> cancellation through bounded channels to immediately abort upstream GPU compute on client disconnect.</li>
        <li>Built an agentic tool runtime with <b>automated schema self-healing</b>, JSON AST error extraction, and an 8 KiB output budget guardrail.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/SSE%20Streaming-FF6B6B?style=flat-square"/>
        <img src="https://img.shields.io/badge/GenAI%20Infra-7928CA?style=flat-square"/>
        <img src="https://img.shields.io/badge/JSON%20Schema-009688?style=flat-square"/>
      </p>
    </td>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🌐 <a href="https://github.com/paranik-jpg/distributed-event-hub" style="text-decoration: none;">Distributed Event Hub</a></h4>
      <p style="color: #8b949e; font-size: 13px;">Event-driven financial ledger & streaming pipeline with Redis Streams and Transactional Outbox.</p>
      <ul>
        <li>ACID double-entry ledger with deterministic row-level locks (<code>SELECT ... FOR NO KEY UPDATE</code>) and Transactional Outbox (<code>SKIP LOCKED</code>).</li>
        <li>Deterministic <b>Redis Streams</b> sharding via <code>xxhash</code>, adaptive micro-batching, and dual-loop Consumer Groups with <code>XAUTOCLAIM</code> failover.</li>
        <li>Poison-pill <b>DLQ isolation</b>, slow-consumer WebSocket eviction, and Prometheus metrics for consumer lag and dispatch latency.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis_Streams-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🏦 <a href="https://github.com/paranik-jpg/bank-ledger-api" style="text-decoration: none;">Production Bank Ledger API</a></h4>
      <p style="color: #8b949e; font-size: 13px;">Production-grade transactional banking ledger API in Go and PostgreSQL.</p>
      <ul>
        <li>Engineered atomic financial transfers under strict ACID guarantees with tuned PostgreSQL connection pools (<code>pgxpool</code>).</li>
        <li>Built robust CLI-driven schema migrations (<code>golang-migrate</code>), structured <code>log/slog</code> observability, and deferred panic recovery.</li>
        <li>Maintained regression safety with automated GitHub Actions CI and containerized test execution.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/ACID%20Transactions-009688?style=flat-square"/>
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
      </p>
    </td>
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
  </tr>
  <tr>
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
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🔬 <a href="https://github.com/paranik-jpg/cs-fundamentals" style="text-decoration: none;">CS Fundamentals & Systems Internals</a></h4>
      <p style="color: #8b949e; font-size: 13px;">Hands-on empirical implementations exploring OS, Concurrency, Architecture, Networking, and Database internals.</p>
      <ul>
        <li>Preemptive CPU scheduling, process cloning, and system call context switch tax benchmarking.</li>
        <li>Thread race condition detection with ThreadSanitizer, circular wait deadlocks, and GDB backtracking.</li>
        <li>SQLite Write-Ahead Logging (WAL), B+ tree indexing benchmarks, and raw socket <code>SO_REUSEPORT</code> load balancing.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C%2B%2B20-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/Linux_Internals-FCC624?style=flat-square&logo=linux&logoColor=black"/>
        <img src="https://img.shields.io/badge/ThreadSanitizer-4E9A06?style=flat-square"/>
        <img src="https://img.shields.io/badge/WAL%20Internals-0052CC?style=flat-square"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>⚡ <a href="https://github.com/paranik-jpg/shortest_Path_Engine" style="text-decoration: none;">Shortest Path Graph Engine</a></h4>
      <p style="color: #8b949e; font-size: 13px;">A high-performance graph processing and micro-benchmarking engine for massive scale networks.</p>
      <ul>
        <li>Optimized Dijkstra's algorithm using a custom priority queue with <b>Lazy Deletion</b> to eliminate relaxation overhead.</li>
        <li>Built benchmark generators leveraging <code>std::mt19937</code> (Mersenne Twister) and microsecond-level timing via <code>&lt;chrono&gt;</code>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/Graph_Algorithms-orange?style=flat-square"/>
        <img src="https://img.shields.io/badge/Benchmarking-red?style=flat-square"/>
      </p>
    </td>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>📦 <a href="https://github.com/paranik-jpg/LFUCache" style="text-decoration: none;">Intrusive LFU Cache Engine</a></h4>
      <p style="color: #8b949e; font-size: 13px;">A production-grade implementation of the Least Frequently Used (LFU) caching strategy in modern C++.</p>
      <ul>
        <li>Guaranteed strict <b>O(1)</b> average time complexity for both <code>get()</code> and <code>put()</code> operations.</li>
        <li>Engineered using custom intrusive doubly-linked frequency lists combined with hash maps for optimal cache eviction.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/Low_Level_Design-purple?style=flat-square"/>
        <img src="https://img.shields.io/badge/Cache_Design-blue?style=flat-square"/>
      </p>
    </td>
  </tr>
</table>

---

### 🎬 Beyond the Terminal
- 🎞️ Breaking down technical cinematography, shot composition, and visual storytelling on Instagram ([@what_nik_watches](https://instagram.com/what_nik_watches)).
- ✂️ Editing lyrical music videos and visual sequences using Shotcut and Clipchamp.
- ♟️ Playing competitive chess (TSG Chess Club) and analyzing tactical endgames.

<br/>

<div align="center">
  <sub>Engineered by Nikhil Kushwah • Built for low latency and high concurrency</sub>
</div>
