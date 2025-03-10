# awesome-kernel-security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A collection of kernel security papers, posts and articles.

## Table of Contents

- [awesome-kernel-security ](#awesome-kernel-security-)
  - [Table of Contents](#table-of-contents)
  - [Static Analysis](#static-analysis)
    - [Pointer \& Dataflow Analysis](#pointer--dataflow-analysis)
    - [Static Lockset Analysis](#static-lockset-analysis)
    - [Formal Verification](#formal-verification)
    - [Symbolic Execution](#symbolic-execution)
  - [Dynamic Analysis](#dynamic-analysis)
    - [Fuzzing](#fuzzing)
    - [Dynamic Lockset Analysis](#dynamic-lockset-analysis)
  - [Hybrid Approach](#hybrid-approach)
  - [Other](#other)


## Static Analysis

### Pointer & Dataflow Analysis
- [DLOS: Effective Static Detection of Deadlocks in OS Kernels](https://www.usenix.org/conference/atc22/presentation/bai)
- [DR. CHECKER: A Soundy Analysis for Linux Kernel Drivers](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/machiry)
- [LLMDFA: Analyzing Dataflow in Code with Large Language Models](https://arxiv.org/abs/2402.10754)
- [SVF: Interprocedural Static Value-Flow Analysis in LLVM](http://yuleisui.github.io/publications/cc16.pdf)

### Static Lockset Analysis
- [Effective Static Analysis of Concurrency Use-After-Free Bugs in Linux Device Drivers](https://www.usenix.org/conference/atc19/presentation/bai)
- [Fast and Precise Symbolic Analysis of Concurrency Bugs in Device Drivers (T)](http://ieeexplore.ieee.org/document/7372006/)
- [LR-Miner: Static Race Detection in OS Kernels by Mining Locking Rules](https://www.usenix.org/conference/usenixsecurity24/presentation/li-tuo)

### Formal Verification

### Symbolic Execution
- [Enhancing Static Analysis for Practical Bug Detection: An LLM-Integrated Approach](https://dl.acm.org/doi/10.1145/3649828)

## Dynamic Analysis

### Fuzzing
- [Krace: Data Race Fuzzing for Kernel File Systems](https://ieeexplore.ieee.org/document/9152693/)
- [SegFuzz: Segmentizing Thread Interleaving to Discover Kernel Concurrency Bugs through Fuzzing](https://ieeexplore.ieee.org/document/10179398/)
- [Snowboard: Finding Kernel Concurrency Bugs through Systematic Inter-thread Communication Analysis](https://dl.acm.org/doi/10.1145/3477132.3483549)
- [Snowcat: Efficient Kernel Concurrency Testing using a Learned Coverage Predictor](https://dl.acm.org/doi/10.1145/3600006.3613148)

### Dynamic Lockset Analysis

## Hybrid Approach
- [Razzer: Finding Kernel Race Bugs through Fuzzing](https://ieeexplore.ieee.org/document/8835326/)

## Other
- [Detecting Kernel Memory Bugs through Inconsistent Memory Management Intention Inferences](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-dinghao-detecting)
- [OFence: Pairing Barriers to Find Concurrency Bugs in the Linux Kernel](https://dl.acm.org/doi/10.1145/3552326.3567504)
