<div align="center">
  <h1>Nikhil Kushwah</h1>
  <p><b>Systems & Backend Engineer | Dual Degree @ IIT Kharagpur ('28)</b></p>

  <p>
    <a href="https://www.linkedin.com/in/mr-nikhil-kushwah"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="mailto:nikhilkushwah2k23@gmail.com"><img src="https://img.shields.io/badge/GMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
    <a href="https://leetcode.com/u/jon_snow/"><img src="https://img.shields.io/badge/LEETCODE-370+-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
    <a href="https://codeforces.com/profile/jon_snow"><img src="https://img.shields.io/badge/CODEFORCES-ACTIVE-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/></a>
  </p>

  <br/>
  <p align="center">
  <a href="https://layer5.io">
    <img src="https://img.shields.io/badge/Layer5-Design%20Pioneer-00B39F?style=for-the-badge&logo=cncf&logoColor=white" alt="Layer5 Design Pioneer"/>
  </a>
</p>
</div>

<br/>

### 👤 About Me
- 🎓 Pursuing an Integrated Dual Degree (**B.Tech + M.Tech in Chemical Engineering**) at **IIT Kharagpur ('28)**.
- ⚙️ Focused on **Low-Level Systems Architecture, Concurrency, and Distributed Backend Infrastructure** (Modern C++ & Go).
- 🌐 Active contributor to open-source infrastructure projects across **CNCF (Meshery)** and distributed database engines (**PingCAP TiDB**).
- 🧠 Solid grounding in **Core CS Fundamentals**: Operating Systems, Database Management Systems, Computer Networks, and Low-Level Design (LLD).
- 🏆 Solved **370+ algorithmic problems** across LeetCode (`jon_snow`) and Codeforces, with a focus on Dynamic Programming, Graphs, and Monotonic Stacks.
- 🎯 Seeking **Software Development Engineer (SDE) & Backend Systems Internships**.

---

### 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/C++17/20-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/>
</p>

> *Specializing in: POSIX Sockets, Multithreading & Synchronization, Write-Ahead Logging (WAL), TCP/IP & HTTP Internals, Distributed Rate Limiting, and Full-Duplex WebSockets.*

---

### 🌐 Open Source Contributions

- **[Meshery (CNCF)](https://github.com/meshery/meshery)**: Engineered centralized server error stores (`RegistrationErrorStore`), automated AST error-catalog synchronization via MeshKit `errorutil`, and resolved database connection pool cleanup lifecycles.
- **[TiDB (PingCAP)](https://github.com/pingcap/tidb)**: Fixed date/time storage semantics in the MySQL expression engine (`CastIntAsTime` year-to-date conversion), verified via table-driven monorepo test suites.

---

### 🚀 Featured Systems & Backend Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🌐 <a href="https://github.com/paranik-jpg/distributed-event-hub">Distributed Event Hub</a></h4>
      <p>High-throughput, distributed real-time event pipeline orchestrated via Docker Compose.</p>
      <ul>
        <li>Full-duplex WebSocket streaming built with <code>gorilla/websocket</code> backed by a distributed Redis Pub/Sub cluster.</li>
        <li>Distributed token-bucket rate limiter via atomic Redis Lua scripting with reverse proxy <code>X-Forwarded-For</code> resolution.</li>
        <li>Cache-aside architecture with randomized TTL jitter to mitigate cache stampedes.</li>
      </ul>
      <p>
        <code>Go</code> <code>Redis</code> <code>WebSockets</code> <code>Docker Compose</code> <code>Lua</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>🏦 <a href="https://github.com/paranik-jpg/bank-ledger-api">Bank Ledger API</a></h4>
      <p>ACID-compliant transaction processing service with robust connection pooling and CI/CD pipelines.</p>
      <ul>
        <li>Connection pool lifecycle tuning (<code>SetMaxOpenConns</code>, <code>SetConnMaxLifetime</code>) with CLI schema migrations.</li>
        <li>Custom middleware suite: structured JSON logging (<code>log/slog</code>), panic recovery with stack dumps, and context cancellation.</li>
        <li>Automated test suites using interface mocking (<code>httptest</code>) executed via GitHub Actions.</li>
      </ul>
      <p>
        <code>Go</code> <code>PostgreSQL</code> <code>Docker</code> <code>CI/CD</code> <code>slog</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🔌 <a href="https://github.com/paranik-jpg/proxy_server">Multi-threaded HTTP Proxy Server</a></h4>
      <p>Modular forward proxy engine built from scratch in C++ to route concurrent HTTP client traffic.</p>
      <ul>
        <li>Engineered low-level networking over raw POSIX sockets with fixed-size worker thread pools.</li>
        <li>Implemented URL parsing, HTTP stream relaying with fixed buffers, and socket timeouts (<code>SO_RCVTIMEO</code>).</li>
      </ul>
      <p>
        <code>C++17</code> <code>POSIX Sockets</code> <code>Multithreading</code> <code>Docker</code> <code>CMake</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>💾 <a href="https://github.com/paranik-jpg/mini_DB">MiniDB: Transactional Key-Value Store</a></h4>
      <p>Lightweight, thread-safe in-memory key-value engine with persistent durability guarantees.</p>
      <ul>
        <li>Implemented sequential Write-Ahead Logging (WAL) and delta-based Undo Logs for nested transaction rollbacks.</li>
        <li>Enforced thread-safe operations via <code>std::mutex</code>, condition variables, and thread-local transaction contexts.</li>
      </ul>
      <p>
        <code>C++17</code> <code>DBMS Internals</code> <code>WAL</code> <code>Concurrency</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/paranik-jpg/shortest_Path_Engine">Shortest Path Graph Engine</a></h4>
      <p>Modular C++ graph traversal and micro-benchmarking engine for large network topologies.</p>
      <ul>
        <li>Optimized Dijkstra's algorithm using priority queues with lazy deletion to eliminate relaxation overhead.</li>
        <li>Benchmarked on graphs with 100k vertices and 500k edges (completing in 120ms) using Mersenne Twister (<code>std::mt19937</code>).</li>
      </ul>
      <p>
        <code>C++17</code> <code>Graph Algorithms</code> <code>CMake</code> <code>Benchmarking</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>📦 <a href="https://github.com/paranik-jpg/LFUCache">Intrusive LFU Cache Engine</a></h4>
      <p>Production-grade, strict O(1) Least Frequently Used cache implementation.</p>
      <ul>
        <li>Guaranteed strict O(1) time complexity for both <code>get()</code> and <code>put()</code> operations.</li>
        <li>Engineered using custom intrusive doubly-linked frequency buckets combined with hash maps for deterministic tie-breaking.</li>
      </ul>
      <p>
        <code>C++17</code> <code>Data Structure Design</code> <code>Low-Level Design</code>
      </p>
    </td>
  </tr>
</table>

---

### 🎬 Beyond the Terminal
- 🎞️ Breaking down technical cinematography, composition, and visual storytelling on Instagram ([@what_nik_watches](https://instagram.com/what_nik_watches)).
- ✂️ Editing lyrical music videos and visual sequences using Shotcut and Clipchamp.
- ♟️ Playing competitive chess (TSG Chess Club) and analyzing tactical endgames.

<br/>

<div align="center">
  <sub>Engineered by Nikhil Kushwah • Built for low latency, memory safety, and high concurrency</sub>
</div>
