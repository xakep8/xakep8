<h1 align="center">Kunal Dubey</h1>
<h3 align="center">Systems & low‑level engineer • I like building things close to the metal.</h3>

---

### 🧠 What I actually enjoy

- Writing <strong>C / C++</strong> that does real work: screen capture, ray tracing, custom allocators, sockets.
- Understanding how things behave under the hood: memory layout, syscalls, buffers, latency.
- Building small tools that feel sharp: focused CLIs, utilities, and experiments that can be plugged into bigger systems later.

---

### 📌 Selected projects (pinned)

| Project | Domain | Main tech |
| ------ | ------ | --------- |
| [zapshare](https://github.com/xakep8/zapshare) | P2P file transfer, networking | C++ |
| [screenCapturer](https://github.com/xakep8/screenCapturer) | Screen capture, cross‑platform | C++ |
| [screenShotTool](https://github.com/xakep8/screenShotTool) | Screenshot CLI, platform APIs | C |
| [raytracing_in_c](https://github.com/xakep8/raytracing_in_c) | Graphics, ray tracing | C + SDL2 |
| [mem_alloc_c](https://github.com/xakep8/mem_alloc_c) | Memory management, allocators | C |
| [windows_socket_practice](https://github.com/xakep8/windows_socket_practice) | Raw sockets, networking | C++ |

#### ⚡ zapshare – P2P file sharing (C++)

Simple P2P file sharing app using a central rendezvous server.  
Sender generates a secret; receiver uses that secret to connect and pull the file.  
Currently works on the same network, with plans for UDP hole punching so peers behind NAT can talk without manual port‑forwarding.

- C++ client plus central coordination server.
- CLI‑driven workflow (`zapshare send` / `zapshare get <secret>`).
- Focus: protocol design, robustness, and eventually NAT traversal.

---

#### 🖥️ screenCapturer – cross‑platform C++ capture

C++ screen capture library/tool aimed to work on Windows, Linux, and macOS.  
Part of a series of projects to get comfortable with cross‑platform graphics/capture APIs and build systems.

- Written in C++, targeting cross‑platform behaviour.
- Playground for performance, frame capture, and platform abstraction.

---

#### 📸 screenShotTool – cross‑platform screenshot CLI (C)

Cross‑platform CLI tool to capture screenshots of either the entire screen or a specified region.  
Uses DXGI on Windows and CoreGraphics on macOS to grab frames.

- Implemented in C with platform‑specific backends.
- Thin abstraction over native APIs, scriptable from the command line.

---

#### 🌈 raytracing_in_c – weekend ray tracer

A “weekend dev” ray tracer in C, using SDL2 for rendering.  
Written to play with computer graphics concepts (rays, spheres, materials) without hiding behind a big engine.

- Core path tracing / ray tracing logic in plain C.
- SDL2 window for displaying rendered frames.
- Sandbox for experimenting with graphics math.

---

#### 🧬 mem_alloc_c – custom malloc/free/calloc/realloc

Implementation of the standard C dynamic memory functions (`malloc`, `calloc`, `realloc`, `free`) to understand allocator internals and OS‑level memory management.

- Manual management of blocks, headers, fragmentation, and reuse.
- Focus: how general‑purpose allocators work under real constraints.

---

#### 🔌 windows_socket_practice – raw sockets in C++

Small practice repo around Windows sockets: playing with connection setup, send/recv loops, and low‑level network behaviour on Windows.

- C++ + Winsock playground.
- Base for future P2P / real‑time / networked experiments.

---

### 🛠️ Tech & interests

- Languages: C, C++, plus higher‑level stuff when it’s the right tool.
- Domains: systems programming, graphics, networking, memory management, P2P.
- I like: tiny focused repos, strong README docs, and code that explains itself.

---

### 📫 Contact

- Email: [kunaldubeyseven@gmail.com](mailto:kunaldubeyseven@gmail.com)
- Open to collaborating on: P2P tools, allocators, networked systems, low‑level utilities, and anything that needs someone willing to dive into the guts.
