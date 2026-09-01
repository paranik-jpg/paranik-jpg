# Hi there, I'm Nikhil Kushwah 👋

**Systems & Backend Engineering | Dual Degree @ IIT Kharagpur ('28)**

I am an undergraduate at IIT Kharagpur blending my academic background with a rigorous focus on low-level systems programming, backend architecture, and high-performance computing. I thrive in Linux/Ubuntu environments, preferring to build infrastructure and concurrent applications from the ground up rather than relying on heavy top-level frameworks.

### 🚀 What I'm Building & Learning
*   **Backend & Systems:** Transitioning from C++ POSIX networking into Go concurrency (Goroutines, Channels, Worker Pools) and scalable HTTP server architectures.
*   **DevOps & Linux Internals:** Expanding practical knowledge of Linux permissions (Setuid, Sticky Bits), process management, and containerization via Docker.
*   **Computer Science Fundamentals:** Deeply focused on internal database mechanics (ACID, 2PL, B+ Trees), OS resource management (Virtual Memory, Process Synchronization), and networking protocols (TCP/IP, DNS lifecycle).
*   **Competitive Programming:** Actively solving algorithmic challenges with 360+ problems cleared on LeetCode and consistent participation in Codeforces contests.

### 💻 Core Tech Stack
*   **Languages:** C++17, Go, Python, SQL, C
*   **Architecture & Systems:** POSIX Sockets, Multithreading (`std::mutex`, `std::condition_variable`), Write-Ahead Logging (WAL), OOP, System Calls
*   **Tools & Environment:** Linux (WSL 2), Docker, CMake, Git, Bash

---

### 🛠️ Featured Systems Engineering Projects

**[Multi-threaded HTTP Proxy Server](https://github.com/paranik-jpg/proxy_server)**
A high-performance HTTP proxy engine built entirely from scratch in C++17.
*   Engineered concurrent client-server request handling using raw POSIX sockets and a custom fixed-size thread pool.
*   Implemented low-level network architectures for DNS resolution (`getaddrinfo`), HTTP header parsing, and graceful signal shutdown.

**[MiniDB: Transactional Key-Value Store](https://github.com/paranik-jpg/mini_DB)**
A lightweight, thread-safe, in-memory database engine demonstrating core DBMS concurrency controls.
*   Developed persistent state recovery using Write-Ahead Logging (WAL) and delta-based undo logs.
*   Optimized memory access with thread-local design, parent-child transaction merging, and separated storage/transaction logic.

**[Shortest Path Graph Engine](https://github.com/paranik-jpg/shortest_Path_Engine)**
A high-performance graph algorithm engine built with modern software engineering practices.
*   Optimized Dijkstra's algorithm using a custom priority queue with Lazy Deletion to minimize overhead during edge relaxations.
*   Integrated the `<chrono>` library for microsecond-level benchmarking and the Mersenne Twister (`std::mt19937`) for massive random-graph generation.

**[LFU Cache Engine](https://github.com/paranik-jpg/LFUCache)**
A modular implementation of the Least Frequently Used (LFU) Cache.
*   Achieved O(1) average time complexity for operations by engineering a custom intrusive doubly-linked list integrated with hash maps.

**Custom Utilities**
*   **Focus Tracker:** A strictly functional time-management dashboard built for my personal deep-work cycles. Engineered with specialized 5-minute increment intervals, intentionally omitting a total logged time display and reset button to enforce continuous forward momentum without backward-looking metrics.

---

### 🎬 Beyond the Terminal

When I'm not debugging memory leaks or tracing kernel hardware sequences, I'm likely:
*   Breaking down technical cinematography, shot composition, and screenwriting (you can find my film analysis on Instagram at `@what_nik_watches`).
*   Editing lyrical music videos and visual montages using Shotcut and Clipchamp.
*   Playing competitive chess or optimizing my BGMI layouts.

📫 **Open to Backend Engineering and SDE internship opportunities. Feel free to explore my repositories or reach out!**
