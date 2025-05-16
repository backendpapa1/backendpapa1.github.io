---
title: A New Chapter - Diving Into Systems Programming
date: 2025-05-15
layout: post
---


Hey everyone 👋,

This post was meant to be a friendly hello—but let’s skip the fluff and get to it.

After 8 years in web development, it's been an incredible journey. I've built countless UIs, worked with modern frameworks, and seen the ecosystem evolve at breakneck speed. But lately, I've felt a shift. The web space, with its endless layers of abstraction and framework wars, has started to feel... stale. It’s become more about stacking libraries than solving core computing problems.

So, I’m hitting the reset button.

## Why Systems?

I want to fall in love with computing again. That means digging beneath the surface—closer to the metal. Less framework, more fundamentals. Less copy-paste, more thinking. I’m moving into systems programming. I don’t have it all figured out yet, but that’s the point. This is about exploration, curiosity, and challenge.

I'll be working with low-level languages like **C, C++, Rust, Go, and Elixir/Erlang**. It’ll be a mix of reading, building, breaking, and rebuilding—lots of docs, lots of books. To keep me on track and make this fun, I asked ChatGPT to generate a roadmap. Here's what it came up with:

---

# 🛠️ 12-Month Systems Programming Roadmap

**Goal:** Learn the fundamentals of systems programming  
**Time Commitment:** ~180 hours/month (7 hrs/day × 6 days/week)

Each month will focus on:

- 📘 Key Books  
- 📚 Courses  
- 💻 Projects  
- 🧠 Core Concepts  
- 🎯 Milestones

---

### 📅 Month 1: Linux & C Fundamentals

**Books**  
- _The Linux Command Line_ – William Shotts  
- _The C Programming Language_ – Kernighan & Ritchie  

**Courses**  
- CS50x  
- LinuxJourney  

**Projects**  
- Bash file explorer  
- Reimplement `cp`, `mv`, `cat` in C  

**Concepts**  
- C basics: variables, memory, pointers  
- Linux file system, permissions  
- Compilation: `gcc`, `make`  

**Milestone**  
- Build 5+ Linux tools, use terminal exclusively  

---

### 📅 Month 2: C Deep Dive + Data Structures

**Books**  
- _Modern C_ – Jens Gustedt  
- _Data Structures in C_ – Noel Kalicharan  

**Courses**  
- MIT 6.087  

**Projects**  
- Linked list, stack, queue, hash map, tree  

**Concepts**  
- Memory management  
- Structs, unions, enums  
- Debugging with `gdb`, `valgrind`  

**Milestone**  
- CLI task manager using C structures  

---

### 📅 Month 3: OS Internals + Build a Shell

**Books**  
- _Operating Systems: Three Easy Pieces_  
- _Advanced C Programming_ – Peter van der Linden  

**Courses**  
- Write a Shell in C  

**Projects**  
- Build a shell (piping, redirection, background jobs)  
- Mini init system  

**Concepts**  
- Processes, fork/exec/wait  
- Signals, file descriptors  
- Scheduling and memory layout  

**Milestone**  
- Functional shell with job control  

---

### 📅 Month 4: Rust CLI Tools

**Books**  
- _The Rust Programming Language_  
- _Rust for Rustaceans_ – Jon Gjengset  

**Courses**  
- Rustlings  
- Jon Gjengset’s YouTube  

**Projects**  
- Todo CLI using `structopt` and `serde`  
- Port data structures to Rust  

**Concepts**  
- Ownership, borrowing, lifetimes  
- Traits, pattern matching, enums  
- Rust tooling: `cargo`, `clippy`, `rustfmt`  

**Milestone**  
- Ship 2 Rust command-line tools  

---

### 📅 Month 5: Networking in C & Rust

**Books**  
- _Beej’s Guide to Network Programming_  
- Async Networking with Tokio  

**Courses**  
- Stanford CS144  

**Projects**  
- TCP chat server in C  
- HTTP server in Rust using `hyper`  

**Concepts**  
- Sockets, TCP/UDP  
- Event loops, `select`/`poll`/`epoll`  
- DNS, HTTP parsing  

**Milestone**  
- Real-time chat + HTTP server  

---

### 📅 Month 6: Write a Compiler

**Books**  
- _Crafting Interpreters_ – Robert Nystrom  
- _Let’s Build a Simple Compiler_ – Jack Crenshaw  

**Courses**  
- Nand2Tetris  
- LLVM tutorials  

**Projects**  
- Toy language interpreter  
- Parse expressions like `2 + (3 * 4)`  

**Concepts**  
- Parsing, tokens, ASTs  
- Interpreting vs compiling  
- Bytecode  

**Milestone**  
- Toy language with expression parsing and execution  

---

### 📅 Month 7: C++ Fundamentals

**Books**  
- _A Tour of C++_ – Bjarne Stroustrup  
- _Effective C++_ – Scott Meyers  

**Courses**  
- CppCon videos  

**Projects**  
- OOP CLI app  
- Implement smart pointers, RAII  

**Concepts**  
- Templates, classes, inheritance  
- Modern C++ features: `auto`, ranges, lambdas  
- STL  

**Milestone**  
- Modern CLI app in C++  

---

### 📅 Month 8: Write a Kernel

**Books**  
- _Write Your Own OS_  
- _The Little OS Book_  

**Projects**  
- Bootloader  
- Framebuffer + keyboard input  
- Minimal kernel in C or Rust  

**Concepts**  
- Boot process  
- Interrupts, segmentation  
- Kernel memory  

**Milestone**  
- Bootable kernel that handles input/output  

---

### 📅 Month 9: Go Language + Systems Integration

**Books**  
- _The Go Programming Language_  
- _Go Systems Programming_  

**Courses**  
- Go by Example  
- Go Tour  

**Projects**  
- Port shell or CLI app to Go  
- Concurrent log processor  

**Concepts**  
- Goroutines, channels  
- Interfaces, file I/O  
- Static binary compilation  

**Milestone**  
- Efficient systems tool in Go  

---

### 📅 Month 10: Advanced Concurrency

**Books**  
- _The Art of Multiprocessor Programming_  
- _Rust Atomics and Locks_  

**Courses**  
- MIT 6.828 or Stanford CS140e  

**Projects**  
- Thread-safe queue  
- Parallel web scraper  

**Concepts**  
- Threads, locks, atomics  
- Shared memory vs message passing  
- Memory models  

**Milestone**  
- Multithreaded, lock-safe app in Go or Rust  

---

### 📅 Month 11: Databases & File Systems

**Books**  
- _Designing Data-Intensive Applications_ – Martin Kleppmann  
- _Build Your Own Database_ → [cstack.github.io/db_tutorial](https://cstack.github.io/db_tutorial/)  

**Projects**  
- Toy DB engine  
- Log-structured file system  

**Concepts**  
- Storage engines, B-trees, journaling  
- ACID, WAL, file formats  
- `mmap`, paging  

**Milestone**  
- Working toy DB with persistent querying  

---

### 📅 Month 12: Final Projects + Security

**Books**  
- _Hacking: The Art of Exploitation_  
- _Practical Binary Analysis_  
- _Rootkits: Subverting the Windows Kernel_  

**Final Projects**  
- Dropbox-style CLI sync tool  
- Custom bootloader + kernel  
- Mini container runtime  
- Binary reverse engineering  

**Milestone**  
- Ship 1–2 major projects + prep for open source or interviews  

---

## Supporting Tools & Communities

**Tools**  
- `gdb`, `valgrind`, `perf`, `strace`, `lldb`  
- `cargo`, `make`, `cmake`  
- Docker, QEMU, Git, SSH  

**Communities**  
- [r/embedded](https://reddit.com/r/embedded)  
- [r/rust](https://reddit.com/r/rust)  
- [Rustaceans Discord](https://discord.gg/rust-lang)  

---

## Final Notes

This doesn’t mean I’ll spend exactly 12 months—I’ll compress it where I can. I’m also switching entirely to Vim. No IDEs. These days autocomplete feels like it’s doing too much thinking for me. Time to go manual and get creative again.

I’ll be documenting every step of this journey here. This blog is my tracker, journal, and motivation board.

Feel free to reach out:

📬 **akejupaul10@gmail.com**

Thanks for reading,  
**Paul**
