<div align="center">
  <h1>Nikhil Kushwah</h1>
  <p><strong>Systems & Backend Engineer | Dual Degree @ IIT Kharagpur ('28)</strong></p>

  <p>
    <a href="https://linkedin.com/in/mr-nikhil-kushwah"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="mailto:nikhil4409t@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
    <a href="https://leetcode.com/u/HjZcdRKqOJ/"><img src="https://img.shields.io/badge/LeetCode-360+-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/></a>
    <a href="https://codeforces.com/profile/Heisenberg_ww_1"><img src="https://img.shields.io/badge/Codeforces-Active-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces"/></a>
    <div><a href="https://cloud.layer5.io/user/20bbed03-241c-4647-a3b1-eeab83fddb1e?tab=badges&badge=first-design" alt="First Design" ><img width="175px" height="252px" src="https://badges.layer5.io/assets/badges/first-design/first-design.png" alt="First Design" /></a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<sup><a href="https://badges.layer5.io"></a></sup></div>
  </p>
</div>

---

### 👨‍💻 About Me

* 🎓 Pursuing a **Dual Degree (B.Tech + M.Tech in Chemical Engineering)** at **IIT Kharagpur** ('28).
* ⚙️ Specialized in **High-Performance C++**, **Go Concurrency**, and **Low-Level Systems Architecture**.
* 🧠 Strong foundation in **Core CS Fundamentals**: Operating Systems, Database Management Systems, Computer Networks, and Low-Level Design (LLD).
* 🏆 Solved **360+ algorithmic problems** across LeetCode and Codeforces, focusing on Dynamic Programming, Graphs, and Advanced Data Structures.
* 📬 Open to **Software Development Engineer (SDE) & Backend Systems Internships**.

---

### 🛠️ Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,go,py,linux,bash,docker,cmake,git,github,vscode,ubuntu" alt="Tech Stack Icons"/>
</div>

<div align="center">
  <p><em>Also specializing in: <strong>POSIX Sockets, Multithreading, Write-Ahead Logging (WAL), TCP/IP Protocols, and GROMACS</strong></em></p>
</div>

---

### 🚀 Featured Systems Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🌐 <a href="https://github.com/paranik-jpg/proxy_server">Multi-threaded HTTP Proxy Server</a></h4>
      <p>A high-performance HTTP proxy engine built from scratch in modern C++17 to handle concurrent request routing.</p>
      <ul>
        <li>Engineered low-level networking via raw <strong>POSIX sockets</strong> and custom fixed-size <strong>thread pools</strong>.</li>
        <li>Implemented URL parsing, HTTP header manipulation, DNS resolution (<code>getaddrinfo</code>), and graceful signal shutdown.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/POSIX_Sockets-000000?style=flat-square"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
        <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>💾 <a href="https://github.com/paranik-jpg/mini_DB">MiniDB: Transactional Key-Value Store</a></h4>
      <p>A lightweight, thread-safe, in-memory transactional database engine designed in modern C++17.</p>
      <ul>
        <li>Implemented <strong>Write-Ahead Logging (WAL)</strong> and delta-based undo logs for state rollback and crash recovery.</li>
        <li>Optimized memory access patterns using thread-local storage design and separated transaction-storage layers.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/DBMS_Internals-FF6F00?style=flat-square"/>
        <img src="https://img.shields.io/badge/Multithreading-4B8BBE?style=flat-square"/>
        <img src="https://img.shields.io/badge/WAL-00599C?style=flat-square"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>⚡ <a href="https://github.com/paranik-jpg/shortest_Path_Engine">Shortest Path Graph Engine</a></h4>
      <p>A high-performance graph processing and micro-benchmarking engine for massive scale networks.</p>
      <ul>
        <li>Optimized Dijkstra’s algorithm using a custom priority queue with <strong>Lazy Deletion</strong> to eliminate relaxation overhead.</li>
        <li>Built benchmark generators leveraging <code>std::mt19937</code> (Mersenne Twister) and microsecond-level timing via <code>&lt;chrono&gt;</code>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/Graph_Algorithms-008080?style=flat-square"/>
        <img src="https://img.shields.io/badge/Benchmarking-E95420?style=flat-square"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>📦 <a href="https://github.com/paranik-jpg/LFUCache">Intrusive LFU Cache Engine</a></h4>
      <p>A production-grade implementation of the Least Frequently Used (LFU) caching strategy in modern C++.</p>
      <ul>
        <li>Guaranteed strict $O(1)$ average time complexity for both <code>get()</code> and <code>put()</code> operations.</li>
        <li>Engineered using custom intrusive doubly-linked frequency lists combined with hash maps for optimal cache eviction.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/C++17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
        <img src="https://img.shields.io/badge/Low_Level_Design-5C2D91?style=flat-square"/>
        <img src="https://img.shields.io/badge/Cache_Design-007ACC?style=flat-square"/>
      </p>
    </td>
  </tr>
</table>

---

### 🎬 Beyond the Terminal

* 🎥 Breaking down technical cinematography, shot composition, and visual storytelling on Instagram ([@what_nik_watches](https://instagram.com/what_nik_watches)).
* 🎞️ Editing lyrical music videos and visual sequences using Shotcut and Clipchamp.
* ♟️ Playing competitive chess and optimizing mobile gaming HUD layouts.

---

<div align="center">
  <sub>Engineered by Nikhil Kushwah • Built for low latency and high concurrency</sub>
</div>
