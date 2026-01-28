<h1 align="center">Kunal Dubey</h1>
<h3 align="center">Systems & low‑level engineer • I like building things close to the metal.</h3>

---

### 🧠 What I actually enjoy

- Writing **C / C++** that does real work: screen capture, ray tracing, custom allocators, sockets.
- Understanding how things behave under the hood: memory layout, syscalls, buffers, latency.
- Building small tools that feel sharp: focused CLIs, utilities, and experiments that can be plugged into bigger systems later.

---

### 📌 Selected projects (pinned)

#### ⚡ zapshare – P2P file sharing (C++)

Simple P2P file sharing app using a central rendezvous server.  
Sender generates a secret; receiver uses that secret to connect and pull the file.  
Currently works on the same network, with plans for **UDP hole punching** so peers behind NAT can talk without manual port‑forwarding. [file:1]

- C++ client + central coordination server.
- CLI‑driven workflow (`zapshare send` / `zapshare get <secret>`).
- Focus: protocol design, robustness, and eventually NAT traversal.

---

#### 🖥️ screenCapturer – cross‑platform C++ capture

C++ screen capture library/tool aimed to work on **Windows, Linux, and macOS**.  
Part of a series of projects to get comfortable with cross‑platform graphics/capture APIs and build systems. [file:1]

- Written in C++, targeting cross‑platform behaviour.
- Used as a playground for performance, frame capture, and platform abstraction.

---

#### 📸 screenShotTool – cross‑platform screenshot CLI (C)

Cross‑platform CLI tool to capture screenshots of either the entire screen or a specified region.  
Uses **DXGI** on Windows and **CoreGraphics** on macOS to grab frames. [file:1]

- Implemented in C with platform‑specific backends.
- Focus: thin abstraction over native APIs, scriptable from the command line.

---

#### 🌈 raytracing_in_c – weekend ray tracer

A “weekend dev” ray tracer in **C**, using **SDL2** for rendering.  
Written to play with computer graphics concepts (rays, spheres, materials) without hiding behind a big engine. [file:1]

- Core path tracing / ray tracing logic in plain C.
- SDL2 window for displaying rendered frames.
- Great sandbox for experimenting with graphics math.

---

#### 🧬 mem_alloc_c – custom malloc/free/calloc/realloc

Implementation of the standard C dynamic memory functions (`malloc`, `calloc`, `realloc`, `free`) to understand allocator internals and OS‑level memory management. [file:1]

- Manual management of blocks, headers, fragmentation, and reuse.
- Focus: learning how general‑purpose allocators work under real constraints.

---

#### 🔌 windows_socket_practice – raw sockets in C++

Small practice repo around Windows sockets: playing with connection setup, send/recv loops, and low‑level network behaviour on Windows. [file:1]

- C++ + Winsock playground.
- Good base for future P2P/real‑time/networked experiments.

---

### 🛠️ Tech & interests

- Languages: **C**, **C++**, some higher‑level stuff when needed.
- Domains: systems programming, graphics, networking, memory management, P2P.
- I like: tiny focused repos, strong README docs, and code that explains itself.

---

### 📫 Contact

- Email: `kunaldubeyseven@gmail.com`
- Open to collaborating on: P2P tools, allocators, networked systems, low‑level utilities, and anything that needs someone willing to dive into the guts.
