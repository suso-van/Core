# Core

### Low-Level Systems Engineering Portfolio (20 Projects)
---

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Systems%20Engineering-blue" />
  <img src="https://img.shields.io/badge/Focus-Operating%20Systems-critical" />
  <img src="https://img.shields.io/badge/Focus-Compilers-important" />
  <img src="https://img.shields.io/badge/Focus-Distributed%20Systems-success" />
  <img src="https://img.shields.io/badge/Focus-Storage%20Engines-orange" />
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/C-Low%20Level-blue?logo=c" />
  <img src="https://img.shields.io/badge/C++-Systems-blue?logo=c%2B%2B" />
  <img src="https://img.shields.io/badge/Python-Prototype%20%26%20Testing-yellow?logo=python" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-CI-black?logo=githubactions" />
  <img src="https://img.shields.io/badge/Linux-Development-black?logo=linux" />
</p>

---

## 📌 Overview

**Systems Core** is a structured implementation of 20 serious systems projects designed to build deep expertise in:

* Operating Systems
* Runtime Systems
* Memory Management
* Transactional Storage Engines
* Compiler Construction
* Networking Protocols
* Distributed Consensus

This portfolio emphasizes:

* Implementation from scratch
* Internal architecture clarity
* Performance awareness
* Correctness and invariants
* Engineering discipline

---

# 🎯 Objective

The goal of this initiative is to develop production-grade understanding of core computer systems by building infrastructure-level components rather than application-layer software.

This aligns with:

* GATE CS preparation
* Infrastructure / systems engineering roles
* Research-oriented systems development
* High-performance backend architecture

---

# 🧠 Project Domains (20 Systems)

---

# 1️⃣ Operating Systems & Runtime (6 Projects)

Focus: Process control, scheduling, memory, execution models

### Projects

1. Educational OS Kernel
2. Process Scheduler Simulator
3. Memory Allocator (malloc/free implementation)
4. User-Level Thread Library
5. Virtual Memory Simulator
6. Garbage Collector (Mark–Sweep)

### Concepts Covered

* Process scheduling policies
* Heap management
* Fragmentation handling
* Context switching
* Stack frames
* Page abstraction
* Stop-the-world GC

---

# 2️⃣ Storage & Database Internals (5 Projects)

Focus: Durability, indexing, recovery

### Projects

7. Mini Transactional Storage Engine
8. Standalone B+ Tree
9. Write-Ahead Logging (WAL) System
10. Query Planner & Optimizer
11. Columnar Storage Engine

### Concepts Covered

* ACID properties
* Log Sequence Numbers (LSN)
* Crash recovery (Redo/Undo)
* Page layout
* Cost-based optimization
* Index node splitting/merging

---

# 3️⃣ Compiler & Language Engineering (5 Projects)

Focus: Compilation pipeline, runtime systems

### Projects

12. MiniLang Compiler
13. Intermediate Representation (IR) Builder
14. SSA Transformation Engine
15. Register-Based Virtual Machine
16. JIT Compiler Prototype

### Concepts Covered

* Lexical analysis
* Recursive descent parsing
* Abstract Syntax Trees
* Semantic validation
* Bytecode generation
* Call stack management
* Control flow lowering
* SSA construction
* Runtime execution

---

# 4️⃣ Networking & Distributed Systems (4 Projects)

Focus: Reliability, replication, fault tolerance

### Projects

17. TCP-like Reliable Transport Protocol
18. Distributed Key-Value Store
19. Raft Consensus Implementation
20. Load Balancer with Health Checking

### Concepts Covered

* Sliding window protocols
* Retransmission logic
* Replication strategies
* Leader election
* Log replication
* Fault simulation
* Distributed consistency

---

# 🏗 Architecture Overview

---

## Compiler → Runtime Stack

```
Source Code
    ↓
Lexer → Parser → AST → Semantic Analyzer
    ↓
IR / Bytecode Generator
    ↓
Virtual Machine
    ↓
Memory Allocator
    ↓
Garbage Collector
```

---

## Transactional Storage Pipeline

```
Client
  ↓
Transaction Manager
  ↓
Write-Ahead Log (WAL)
  ↓
B+ Tree Index
  ↓
Page Manager
  ↓
Disk Layer
```

---

## Distributed Infrastructure Stack

```
Client
  ↓
Load Balancer
  ↓
Distributed KV Store
  ↓
Raft Consensus
  ↓
Replicated Log
```

---

# 📊 Engineering Principles

Each project follows:

* Clear subsystem boundaries
* Explicit invariants
* Complexity analysis
* Performance measurement
* Failure-mode documentation
* Reproducible builds

Where applicable:

* Throughput benchmarks
* Latency analysis
* Memory profiling
* Crash recovery simulation

---

# 🛠 Technology Stack

| Layer                   | Technology     |
| ----------------------- | -------------- |
| Low-Level Systems       | C / C++        |
| Prototyping & Testing   | Python         |
| Build Systems           | Make / CMake   |
| CI                      | GitHub Actions |
| Development Environment | Linux          |

---

# 📈 Benchmarking & Evaluation

Each major subsystem includes:

* Micro-benchmarks
* Stress testing
* Performance comparison
* Memory utilization metrics

Performance and correctness are treated as first-class concerns.

---

# 🔬 Learning Philosophy

This portfolio avoids:

* Tutorial-style implementations
* Surface-level abstractions
* Framework-heavy systems

Instead, it emphasizes:

* Manual memory control
* Explicit runtime design
* Low-level concurrency reasoning
* Deterministic system behavior

---

# 🚀 Long-Term Vision

The objective of Systems Core is to build deep expertise in:

* Runtime system architecture
* Transaction durability models
* Distributed fault tolerance
* Compiler backend optimization
* Infrastructure scalability

This repository represents a structured progression toward advanced systems engineering competence.
