<div align="center">

<img src="./assets/banner.svg" alt="animesao // SOFTWARE DEVELOPER & SYSTEMS BUILDER" width="100%">

<br/>

[![Status: Active](https://img.shields.io/badge/STATUS-ACTIVE_BUILDING-0A0A0A?style=flat-square&logo=git&logoColor=white)](https://github.com/animesao)
[![Primary: Cardinal](https://img.shields.io/badge/PRIMARY-CARDINAL_ECOSYSTEM-18181B?style=flat-square&logo=go&logoColor=00ADD8)](https://github.com/animesao/cardinal)
[![Stack: Polyglot](https://img.shields.io/badge/STACK-GO_•_JAVA_•_PYTHON_•_VUE_•_RUST-27272A?style=flat-square)](https://github.com/animesao)
[![Host: Arch Linux](https://img.shields.io/badge/HOST-ARCH_LINUX-18181B?style=flat-square&logo=archlinux&logoColor=1793D1)](https://github.com/animesao)
[![Methodology: AI-Assisted](https://img.shields.io/badge/METHODOLOGY-AI__ASSISTED__ENGINEERING-0A0A0A?style=flat-square&logo=openai&logoColor=white)](https://github.com/animesao)

<br/>

```text
animesao@dev:~$ whoami --verbose
Software Developer & Systems Builder.
Engineering container infrastructure, backend services, web applications, game server systems, and developer tools.
```

</div>

---

### ⚡ About Me

I am a software developer with hands-on experience building across multiple engineering layers — from low-level Linux kernel primitives and container runtimes to high-performance game server plugins, full-stack web applications, automation bots, and desktop AI utilities.

I focus on **end-to-end product development**: designing system architectures, writing idiomatic backend logic, building intuitive web control planes, and automating workflows.

I leverage **AI as a core engineering multiplier** across all my projects — using frontier models as interactive pair-architects for protocol design, algorithmic exploration, edge-case analysis, and rapid test generation.

- 🔭 **Primary Initiative:** [Cardinal](https://github.com/animesao/cardinal) — an open-source, daemonless container infrastructure ecosystem.
- 💻 **Engineering Breadth:** Systems & Infrastructure • Backend & APIs • Full-Stack Web • Minecraft Game Development • Discord & Hosting Automation.
- 💡 **Core Principles:** First-principles architecture, lean abstractions, reliable self-hosting, and practical utility.

---

### 🌐 Primary Initiative: The Cardinal Ecosystem

**[Cardinal](https://github.com/animesao/cardinal)** is my flagship open-source project — a complete, daemonless container infrastructure suite designed from scratch as a fast, resource-efficient alternative to Docker for servers, microservices, and game hosting.

```text
┌──────────────────────────────────────────────────────────────────────────┐
│                           CARDINAL ECOSYSTEM                             │
└──────────────────────────────────────────────────────────────────────────┘
                                      │
                                      ▼
       [ Web Browser / Client ] ──► [ Cardinal Panel ]
                                    • Nuxt 4 + Vue 3 + Tailwind CSS
                                    • Drizzle ORM + SQLite / MySQL
                                           │
                                           │ HTTP REST / WebSockets (Role-based Tokens)
                                           ▼
                                 [ Cardinal Wings Daemon ]
                                    • Lightweight Go management daemon
                                    • Live log streaming & interactive PTY exec
                                           │
                                           │ Local CLI / Direct Process Control
                                           ▼
                                   [ Cardinal Runtime ]
                                    • ~5 MB static Go binary (no dockerd required)
                                    • OCI image pulling, rootfs extraction & layering
                                           │
                           ┌───────────────┴───────────────┐
                           ▼                               ▼
                 [ Linux Namespaces ]            [ Network Bridge ]
                 • cgroups v2 (CPU / Mem limits) • Custom veth pairs + NAT
                 • pivot_root container rootfs   • Dynamic port forwarding
```

| Component | Repository | Role | Tech Stack | Status |
| :--- | :--- | :--- | :--- | :--- |
| **Cardinal** | [`animesao/cardinal`](https://github.com/animesao/cardinal) | Daemonless container engine (~5 MB binary, OCI pull, cgroups v2, bridge networking) | `Go` `OCI` `Linux Kernel` | `v2.4.14` |
| **Cardinal Wings** | [`animesao/cardinal-wings`](https://github.com/animesao/cardinal-wings) | Secure HTTP REST agent for remote node management, RBAC, live streaming & exec | `Go` `REST API` `WebSockets` | `v1.0 Live` |
| **Cardinal Panel** | [`animesao/cardinal-panel`](https://github.com/animesao/cardinal-panel) | Modern web control plane for orchestrating nodes, servers, file management & metrics | `Nuxt 4` `Vue` `Drizzle ORM` | `v0.6.4` |

---

### 📂 Software Engineering Domains & Projects

Beyond Cardinal, I actively build software across several key technical disciplines:

#### 1. ⚙️ Systems, Infrastructure & Kernel Tools
- **[cardinal](https://github.com/animesao/cardinal)** — Daemonless container runtime in Go. Runs OCI containers directly via Linux namespaces, cgroups v2, and bridge networking without a persistent daemon.
- **[cardinal-wings](https://github.com/animesao/cardinal-wings)** — Production REST API daemon for remote node management with multi-token RBAC, log streaming, and interactive PTY execution.
- **[veilnet](https://github.com/animesao/veilnet)** — Linux kernel-space traffic interception and DPI bypass tool built with Traffic Control (TC) and eBPF (`Rust`, `C`).
- **[dotfiles](https://github.com/animesao/dotfiles)** & **[niri-dotfiles](https://github.com/animesao/niri-dotfiles)** — Custom declarative configurations for Arch Linux, Niri, and Hyprland Wayland compositors.

#### 2. 🎮 Game Server Development & Runtime Systems (Minecraft)
- **[ScriptsLab](https://github.com/animesao/ScriptsLab)** — Production-grade plugin framework for Minecraft Paper servers enabling admins to write gameplay features in modern JavaScript with full access to the Bukkit/Paper API via GraalVM Polyglot (`Java 17+`, `GraalVM`).
- **[wa (Wasteland Artifacts)](https://github.com/animesao/wa)** — Comprehensive Paper plugin introducing custom items with active effects, multi-block crafting altars, dungeon loot, and YAML configuration (`Java`).
- **[AntiBot-Pro](https://github.com/animesao/AntiBot-Pro)** — Advanced protection plugin for Velocity proxy servers guarding against bot attacks, malicious proxies/VPNs, and DDoS traffic (`Java`).
- **[dcustomitems](https://github.com/animesao/dcustomitems)** & **[CustomDungeons](https://github.com/animesao/CustomDungeons)** — Custom item systems with attribute bonuses, set mechanics, and procedural dungeon generation (`Java`).

#### 3. 🌐 Web Applications & Control Planes
- **[cardinal-panel](https://github.com/animesao/cardinal-panel)** — Full-stack management dashboard for game servers and containerized workloads. Features real-time console, file browser, and server metrics (`Nuxt 4`, `Vue 3`, `Drizzle ORM`, `SQLite`, `Tailwind CSS`).
- **[billing](https://github.com/animesao/billing)** — Automated billing panel for hosting environments with payment gateway integrations (`Vue.js`, `Node.js`).

#### 4. 🤖 Automation, Bots & Desktop AI Utilities
- **[rem-bg](https://github.com/animesao/rem-bg)** — Local, offline desktop application for neural image background removal with single-file and batch processing (`Python`, `Computer Vision`).
- **[alfheimguide](https://github.com/animesao/alfheimguide)** — Universal open-source Discord bot for community moderation, automation, and server management (`Python`, `discord.py`).
- **[bot-pterodactyl](https://github.com/animesao/bot-pterodactyl)** — Discord bot integrating with Pterodactyl hosting APIs for automated server control and administration (`Python`).

---

### 🛠️ Technical Stack & Toolkit

```text
[LANGUAGES]           Go (Primary) • Java (17+) • Python • TypeScript / JavaScript • Rust • Bash
[SYSTEMS & KERNEL]    Linux (Arch Linux) • Namespaces • cgroups v2 • eBPF • Traffic Control (TC) • OCI
[WEB & FRONTEND]      Nuxt 4 • Vue.js 3 • Tailwind CSS • Vite • HTML5 / Modern CSS
[BACKEND & APIS]      RESTful APIs • WebSockets • GraalVM Polyglot • Drizzle ORM • Node.js
[DATABASES]           SQLite • MySQL / MariaDB • PostgreSQL • Redis
[GAME & PLATFORMS]    PaperMC • Spigot • Velocity Proxy • Bukkit API • Pterodactyl Ecosystem
[TOOLING & DEVOPS]    systemd • Git • GitHub Actions • pnpm • Niri / Hyprland (Wayland)
[EXPLORING]           NixOS • Nix Flakes • Home Manager • Local LLM Inference (llama.cpp, Ollama)
```

---

### 🤖 AI-Assisted Engineering Workflow

I integrate state-of-the-art AI into my daily development loop across all domains:

1. **System & Protocol Design:** Stress-testing API contracts, state machines, and concurrency models to catch race conditions and edge cases before writing code.
2. **Polyglot Implementation:** Accelerating scaffolding across languages (Go runtime primitives, Java Bukkit events, Vue reactivity, Python scripts).
3. **Correctness & Invariant Validation:** Synthesizing unit tests, fuzz testing harnesses, and validating boundary conditions.
4. **Refactoring & Modernization:** Keeping codebases idiomatic, maintaining documentation, and eliminating redundant abstractions.

---

### 📊 Repository Activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=animesao&theme=dark&hide_border=true&background=0A0A0A&stroke=262626&ring=FFFFFF&fire=FFFFFF&currStreakLabel=FFFFFF" alt="GitHub Streak" height="150" />

</div>

---

### 🔗 Connect & Verification

<div align="center">

[![Website](https://img.shields.io/badge/WEBSITE-cardinal.work.gd-18181B?style=flat-square&logo=google-chrome&logoColor=white)](https://cardinal.work.gd/)
[![GitHub](https://img.shields.io/badge/GITHUB-@animesao-18181B?style=flat-square&logo=github&logoColor=white)](https://github.com/animesao)
[![Cardinal](https://img.shields.io/badge/PRIMARY_PROJECT-Cardinal_Runtime-18181B?style=flat-square&logo=go&logoColor=00ADD8)](https://github.com/animesao/cardinal)
[![License: Open Source](https://img.shields.io/badge/LICENSE-APACHE_2.0_/_MIT-18181B?style=flat-square)](https://github.com/animesao)

<br/>

```text
Public Identity: animesao // Multi-Disciplinary Software Developer & Systems Builder
```

</div>
