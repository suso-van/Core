# Core 

### Low-Level Systems • Runtime Design • Storage Engines • Distributed Infrastructure

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Systems%20Engineering-blue" />
  <img src="https://img.shields.io/badge/Domain-Operating%20Systems-critical" />
  <img src="https://img.shields.io/badge/Domain-DBMS-success" />
  <img src="https://img.shields.io/badge/Domain-Compiler%20Design-orange" />
  <img src="https://img.shields.io/badge/Domain-Distributed%20Systems-purple" />
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/C-Low%20Level%20Systems-blue?logo=c" />
  <img src="https://img.shields.io/badge/C++-Performance%20Engineering-blue?logo=c%2B%2B" />
  <img src="https://img.shields.io/badge/Python-Prototyping%20%26%20Testing-yellow?logo=python" />
  <img src="https://img.shields.io/badge/Linux-Development-black?logo=linux" />
  <img src="https://img.shields.io/badge/Git-GitHub-orange?logo=git" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-CI-black?logo=githubactions" />
</p>

---

## 📌 Overview

This repository is a structured systems engineering initiative focused on implementing low-level computer science concepts through real systems projects.

The portfolio covers:

- Operating Systems
- Runtime Systems
- Memory Management
- Database Internals
- Compiler Construction
- Networking Protocols
- Distributed Systems
- High-Performance Infrastructure

The objective is to move beyond tutorial-level projects and develop implementation-level understanding of modern systems architecture.

---

# 🎯 Goals

- Build deep systems intuition through implementation
- Strengthen core CS fundamentals for GATE CS
- Explore runtime and infrastructure engineering
- Understand storage and compiler internals
- Develop performance-oriented engineering habits
- Study correctness, reliability, and fault tolerance

---

# 🧠 Core 20 Systems Projects

---

# 🖥 Operating Systems

| # | Project | Topics |
|---|---|---|
| 1 | Educational OS Kernel ✅ | Scheduling, Memory Management, Concurrency |
| 2 | Memory Allocator | malloc/free, Fragmentation, Free Lists |
| 3 | User-Level Thread Library | Context Switching, Cooperative Scheduling |
| 4 | Virtual Memory Simulator | Paging, TLB, Page Replacement |

---

# 🗄 DBMS & Storage Systems

| # | Project | Topics |
|---|---|---|
| 5 | Transactional Storage Engine ✅ | WAL, Crash Recovery, Transactions |
| 6 | B+ Tree Storage Engine | Indexing, Page Layout, Persistence |
| 7 | Query Planner & Optimizer | Logical Plans, Cost Estimation |
| 8 | Columnar Storage Engine | Column Storage, Compression |

---

# ⚙️ Compiler Design & Runtime Systems

| # | Project | Topics |
|---|---|---|
| 9 | MiniLang Compiler ✅ | Lexer, Parser, AST, Bytecode VM |
| 10 | Intermediate Representation Builder | CFG, IR Generation |
| 11 | SSA Transformation Engine | Dominance Analysis, Phi Nodes |
| 12 | Register-Based Virtual Machine | Runtime Execution, Instruction Dispatch |

---

# 🌐 Networking & Distributed Systems

| # | Project | Topics |
|---|---|---|
| 13 | TCP-like Reliable Protocol | Sliding Window, ACKs, Retransmission |
| 14 | Distributed Key-Value Store | Replication, Persistence, RPC |
| 15 | Raft Consensus Algorithm | Leader Election, Replicated Logs |
| 16 | Load Balancer with Health Checking | Failover, Routing, Health Probes |

---

# ⚡ High-Performance Systems

| # | Project | Topics |
|---|---|---|
| 17 | Order Matching Engine ✅ | Low-Latency Matching, Priority Queues |
| 18 | External Sorting Engine | Disk-Aware Sorting, Merge Strategies |

---

# 🧠 Theory & Runtime Foundations

| # | Project | Topics |
|---|---|---|
| 19 | Garbage Collector | Mark-Sweep GC, Heap Traversal |
| 20 | Regex Engine / Automata Simulator | DFA/NFA, Regex Parsing |

---

# 🏗 Architecture Focus Areas

---

## Runtime Systems

```text
Source Code
    ↓
Lexer → Parser → AST
    ↓
IR / Bytecode
    ↓
Virtual Machine
    ↓
Memory Allocator
    ↓
Garbage Collector
```

---

## Storage Systems

```text
Client
  ↓
Transaction Layer
  ↓
Write-Ahead Log
  ↓
B+ Tree Index
  ↓
Page Manager
  ↓
Disk
```

---

## Distributed Systems

```text
Client
  ↓
Load Balancer
  ↓
Distributed KV Store
  ↓
Raft Consensus
  ↓
Replicated Persistent Log
```

---

# 📚 Subject Coverage

| Subject | Covered Through |
|---|---|
| Operating Systems | Projects 1–4 |
| DBMS | Projects 5–8 |
| Compiler Design | Projects 9–12 |
| Computer Networks | Project 13 |
| Distributed Systems | Projects 14–16 |
| Algorithms & Performance | Projects 17–18 |
| Theory of Computation | Project 20 |
| Runtime Systems | Project 19 |

---

# 🛠 Technology Stack

| Category | Technologies |
|---|---|
| Systems Programming | C, C++ |
| Prototyping & Testing | Python |
| Build Systems | Make, CMake |
| Version Control | Git, GitHub |
| Development Environment | Linux |

---

# 📊 Engineering Principles

Each project emphasizes:

- Clear subsystem boundaries
- Explicit invariants
- Performance measurement
- Benchmarking and profiling
- Failure-mode analysis
- Modular architecture
- Reproducible builds

---

# 📈 Benchmarking & Evaluation

Projects may include:

- Throughput measurement
- Latency analysis
- Memory profiling
- Stress testing
- Crash recovery simulations

Performance and correctness are treated as first-class engineering concerns.

---

# 🚀 Long-Term Direction

This portfolio is focused on building deep understanding of:

- Runtime architecture
- Transaction durability
- Compiler internals
- Distributed fault tolerance
- Systems scalability
- Infrastructure engineering

The emphasis is depth, correctness, and implementation-level systems knowledge.

---

# 📌 Current Status

### Completed / Active Projects

- ✅ Educational OS Kernel
- ✅ MiniLang Compiler
- ✅ Order Matching Engine
- ✅ Transactional Storage Engine

---

# 📜 License

MIT License
