<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Ertugrul-Pakdamar/Ertugrul-Pakdamar/blob/main/img/banner-dark.png">
  <img alt="banner" src="https://github.com/Ertugrul-Pakdamar/Ertugrul-Pakdamar/blob/main/img/banner-light.png">
</picture>

<div align="center">

# Ertuğrul Pakdamar

### Embedded Systems C Developer

Building deterministic, zero-malloc system software for resource-constrained and real-time environments.

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ertugrul-pakdamar/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=linktree&logoColor=white)](https://linktr.ee/ertugrulpakdamar)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ertu.pakdamar@gmail.com)

</div>

---

### About

Software developer based in Istanbul, currently a student at **42 Türkiye (École 42)**. My path started with low-level system programming in C and Unix, which gave me a deep understanding of how computers actually work under the hood. I now apply that foundation to writing production-grade C libraries for embedded and real-time systems.

- **Current focus:** deterministic C frameworks and zero-malloc memory management for embedded targets
- **Approach:** predictable time complexity, minimal dependencies, portable and testable C

---

### Tech Stack

<div align="center">

**Systems & Languages**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Embedded & Real-Time**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![GNU Make](https://img.shields.io/badge/GNU_Make-A42E2B?style=for-the-badge&logo=gnu&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-3A3A3A?style=for-the-badge&logo=gnu&logoColor=white)
![Valgrind](https://img.shields.io/badge/Valgrind-2E3A3F?style=for-the-badge&logo=valgrind&logoColor=white)

</div>

---
 
### Featured Projects
 
#### 🔗 [ertugrul-pakdamar/**libmem**](https://github.com/Ertugrul-Pakdamar/libmem)
##### Deterministic, zero-malloc memory management library

Eliminates the unpredictability of runtime `malloc`/`free` calls in embedded targets. Memory pools are pre-allocated up front, so allocation and deallocation run in constant, predictable time — no fragmentation, no surprises under load.

![C](https://img.shields.io/badge/language-C-00599C?style=flat-square&logo=c)
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![PRs](https://img.shields.io/badge/PRs-welcome-blueviolet?style=flat-square)
 
#### 🔗 [ertugrul-pakdamar/**libqueue**](https://github.com/Ertugrul-Pakdamar/libqueue)
##### Lock-free SPSC queue, built on libmem

Enables inter-thread data transfer without mutex overhead and with deterministic latency. Integrates directly with `libmem`, so no dynamic allocation is ever required on the hot path.

![C](https://img.shields.io/badge/language-C-00599C?style=flat-square&logo=c)
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![PRs](https://img.shields.io/badge/PRs-welcome-blueviolet?style=flat-square)
 
#### 🔗 [ertugrul-pakdamar/**AegisLink**](https://github.com/Ertugrul-Pakdamar/AegisLink)
##### Deterministic UDP-based data transfer protocol

A custom protocol layer built on top of `libqueue`, designed for reliable and predictable data transfer between real-time systems — forming a fully deterministic, end-to-end data pipeline.

![C](https://img.shields.io/badge/language-C-00599C?style=flat-square&logo=c)
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![PRs](https://img.shields.io/badge/PRs-welcome-blueviolet?style=flat-square)
 
---
 
### 42 Türkiye — CS Foundations
 
Projects from the 42 core curriculum, focused on algorithms, memory management, and system architecture.
 
| Project | Focus Area | Status |
|---|---|:---:|
| [**Minishell**](https://github.com/VedatZeybek/42-minishell) | Bash-like shell — parsing, processes, signals | ✅ |
| [**Philosophers**](https://github.com/Ertugrul-Pakdamar/42_ring3_philosophers) | Concurrency, threads, mutexes, deadlock prevention | ✅ |
| [**Push_swap**](https://github.com/Ertugrul-Pakdamar/42_ring2_push_swap) | Sorting algorithms, complexity analysis (Big O) | ✅ |
| [**FdF**](https://github.com/Ertugrul-Pakdamar/42_ring2_fdf) | Graphics programming, event handling, matrix transforms | ✅ |
| [**Pipex**](https://github.com/Ertugrul-Pakdamar/42_ring2_pipex) | Unix pipes, I/O redirection, file descriptors | ✅ |
| [**Libft**](https://github.com/Ertugrul-Pakdamar/42_ring0_libft) & [**Printf**](https://github.com/Ertugrul-Pakdamar/42_ring1_printf) | Rewriting standard C libraries from scratch | ✅ |
 
<div align="center">
 
<img src="https://capsule-render.vercel.app/api?type=waving&color=00ADD8&height=100&section=footer" width="100%"/>
</div>
