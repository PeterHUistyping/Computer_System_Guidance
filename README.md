# Computer System Guidance

A collection of *Computer System* Projects, built up from,

- OS
- Concurrent and Distributed System
- Computer Architecture
- Networking, Security, Compiler, etc

Application domain

- Database
- Game Engine

In addition, there are also references (paper, ebook, repo, tool, etc) that's interesting and helpful, ranging from beginner to advanced.

## Projects

<!-- ### Operating System -->

[Operating_System MIT 6.S081](https://github.com/PeterHUistyping/Operating_System), xv6 (Unix Version 6)

- Unix util
- System Call
- Page Table

<!-- ### Database Management System Design -->

[Database_Management_System CMU15-445](https://github.com/PeterHUistyping/CMU15-445_Database_Management_System)

- Data Model (relation, key/value)
- Query (SQL)
- Indexing (tree, hash tables)
- Storage (heap, log-structure)
- Memory Management
  - Buffer Pool Manager
    - LRU Replacer
  - Disk Manager
- Transaction processing
  - Concurrency Control
  - ACID
    - Atomicity: all or none
    - Consistency: invariant
    - Isolation: 2PL, TSO, OCC
    - Durability & Recovery: Logging, Checkpoints
- Parallel architectures (multi-core, distributed)

<!-- ### Distributed System -->

[Distributed_System MIT6.824](https://github.com/PeterHUistyping/MIT6.824-6.5840-Distributed-Systems/)

- Consistency and Linearisability
- Fault Tolerance and replication
  - Replicated State Machines
  - Raft
  - Byzantine Fault Tolerance
- Distributed Transactions
  - Isolation: 2PL, TSO, OCC

Case study

- Google Map Reduce, File System, Spanner

### Scheduling Literature Review

[🌐Review](https://peterhuistyping.github.io/CPU_Scheduling_Review/) | [Github](https://github.com/PeterHUistyping/CPU_Scheduling_Review)

- Scheduler (OS)
- DVFS (cpufreq governor)
- Dynamic Resource Sleep (OS)

## Reference

🌐 [Software Construction MIT 6.031](https://web.mit.edu/6.031/)

- Topic 21: Concurrency
- 23: Mutual Exclusion
- 24: Message passing
- More on Software related topics


🌐 [Building a Modern Computer From First Principles](https://www.nand2tetris.org)
Noam Nisan and Shimon Schocken (MIT Press)

📖[Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/)
Randal E. Bryant and David R. O'Hallaron, Carnegie Mellon University

### Cambridge CompSci

- [Database @ IA](https://www.cl.cam.ac.uk/teaching/2223/Databases/)
- [Operating System @ IA](https://www.cl.cam.ac.uk/teaching/2223/OpSystems/)
- [Concurrent and Distributed @ IB](https://www.cl.cam.ac.uk/teaching/2324/ConcDisSys/)
- [Computer Architecture @ IB](https://www.cl.cam.ac.uk/teaching/2324/IntComArch/)
- [Advanced Architecture @ II](https://www.cl.cam.ac.uk/teaching/2324/AdComArch/)

### Game Engine

[👨‍💻Unreal Engine](https://www.unrealengine.com/en-US)
Source code: https://docs.unrealengine.com/5.2/en-US/downloading-unreal-engine-source-code/
