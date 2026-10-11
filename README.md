<div align="center">
  <h1>Nikhil Kushwah</h1>
  <p><b>Systems & Backend Engineer | Dual Degree @ IIT Kharagpur ('28)</b></p>

  <p>
    <a href="https://www.linkedin.com/in/mr-nikhil-kushwah"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="mailto:nikhilkushwah2k23@gmail.com"><img src="https://img.shields.io/badge/GMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
    <a href="https://leetcode.com/u/jon_snow/"><img src="https://img.shields.io/badge/LEETCODE-370+-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
    <a href="https://codeforces.com/profile/jon_snow"><img src="https://img.shields.io/badge/CODEFORCES-ACTIVE-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/></a>
  </p>
</div>

<br/>

### 👤 About Me
- 🎓 Pursuing a **Dual Degree (B.Tech + M.Tech in Chemical Engineering)** at **IIT Kharagpur ('28)**.
- ⚙️ Specialized in **High-Performance C++, Go Concurrency, and Low-Level Systems Architecture**.
- 🌐 Active contributor to open-source infrastructure across **CNCF (Meshery)** and distributed database engines (**PingCAP TiDB**).
- 🧠 Strong foundation in **Core CS Fundamentals**: Operating Systems, Database Management Systems, Computer Networks, and Low-Level Design (LLD).
- 🏆 Solved **370+ algorithmic problems** across LeetCode (`jon_snow`) and Codeforces, focusing on Dynamic Programming, Graphs, and Advanced Data Structures.
- 🎯 Open to **Software Development Engineer (SDE) & Backend Systems Internships**.

---

### 🛠️ Tech Stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cpp,c,go,postgres,redis,docker,linux,git,githubactions&theme=dark" alt="Tech Stack" />
  </a>
</p>

*Also specializing in: POSIX Sockets, Multithreading, Write-Ahead Logging (WAL), Distributed Rate Limiting, TCP/IP Protocols, and WebSockets.*

---

### 🌐 Open Source Contributions

- **[Meshery (CNCF)](https://github.com/meshery/meshery)**: Engineered centralized server error stores (`RegistrationErrorStore`), automated AST error-catalog synchronization via MeshKit `errorutil`, and resolved database connection pool cleanup lifecycles.
- **[TiDB (PingCAP)](https://github.com/pingcap/tidb)**: Fixed date/time storage semantics in the MySQL expression engine (`CastIntAsTime` year-to-date conversion), verified via table-driven monorepo test suites.

---

### 🚀 Featured Systems Projects

<table style="border-collapse: collapse; border: none;">
  <tr>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🌐 <a href="https://github.com/paranik-jpg/distributed-event-hub" style="text-decoration: none;">Distributed Event Hub</a></h4>
      <p style="color: #8b949e; font-size: 13px;">High-throughput, distributed real-time event pipeline orchestrated via Docker Compose.</p>
      <ul>
        <li>Full-duplex WebSocket streaming built with <code>gorilla/websocket</code> backed by a distributed Redis Pub/Sub cluster.</li>
        <li>Distributed token-bucket rate limiter via atomic <b>Redis Lua scripting</b> with proxy <code>X-Forwarded-For</code> resolution.</li>
        <li>Cache-aside architecture with <b>randomized TTL jitter</b> to mitigate cache stampedes.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
    </td>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🏦 <a href="https://github.com/paranik-jpg/bank-ledger-api" style="text-decoration: none;">Bank Ledger API</a></h4>
      <p style="color: #8b949e; font-size: 13px;">ACID-compliant transaction processing service with robust connection pooling and CI/CD pipelines.</p>
      <ul>
        <li>Connection pool lifecycle tuning (<code>SetMaxOpenConns</code>, <code>SetConnMaxLifetime</code>) with CLI schema migrations.</li>
        <li>Custom middleware suite: structured JSON logging (<code>log/slog</code>), panic recovery with stack dumps, and context cancellation.</li>
        <li>Automated test suites using interface mocking (<code>httptest</code>) executed via <b>GitHub Actions</b>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
        <img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=github-actions&logoColor=white"/>
        <img src="https://img.shields.io/badge/log%2Fslog-555555?style=flat-square"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>🤖 <a href="https://github.com/paranik-jpg/proxy_server" style="text-decoration: none;">Multi-threaded HTTP Proxy Server</a></h4>
      <p style="color: #8b949e; font-size: 13px;">A high-performance HTTP proxy engine built from scratch in modern C++17 to handle concurrent request routing.</p>
      <ul>
        <li>Engineered low-level networking via raw <b>POSIX sockets</b> and custom fixed-size <b>thread pools</b>.</li>
        <li>Implemented URL parsing, HTTP header manipulation, DNS resolution (<code>getaddrinfo</code>), and graceful signal shutdown.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/POSIX_Sockets-333333?style=flat-square"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
        <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white"/>
      </p>
    </td>
    <td width="50%" style="border: 1px solid #30363d; border-radius: 8px; padding: 16px; background-color: #0d1117;" valign="top">
      <h4>👾 <a href="https://github.com/paranik-jpg/mini_DB" style="text-decoration: none;">MiniDB: Transactional Key-Value Store</a></h4>
      <p style="color: #8b949e; font-size: 13px;">A lightweight, thread-safe, in-memory transactional database engine designed in modern C++17.</p>
      <ul>
        <li>Implemented <b>Write-Ahead Logging (WAL)</b> and delta-based undo logs for state rollback and crash recovery.</li>
        <li>Optimized memory access patterns using thread-local storage design and separated transaction-storage layers.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/DBMS_Internals-E34F26?style=flat-square"/>
        <img src="https://img.shields.io/badge/Multithreading-4E9A06?style=flat-square"/>
        <img src="https://img.shields.io/badge/WAL-0052CC?style=flat-square"/>
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
        <li>Guaranteed strict $O(1)$ average time complexity for both <code>get()</code> and <code>put()</code> operations.</li>
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
- ♟️ Playing competitive chess (TSG Chess Club) and optimizing tactical endgames.

<br/>

<div align="center">
  <sub>Engineered by Nikhil Kushwah • Built for low latency and high concurrency</sub>
</div>
