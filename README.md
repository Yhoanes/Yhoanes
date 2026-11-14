# Yhoanes Ander Mendoza Rodriguez

**Software Developer · Systems Engineering**  
AI Engineering · Agent Orchestration · Harness Engineering · Native Android & ARM64 Systems · Full-Stack Web

I design and build autonomous AI agent environments, deterministic engineering frameworks, native Android and ARM64 systems, real-time data pipelines, and full-stack business platforms. My engineering approach centers on clear domain architecture, low-level runtime reliability, strict security boundaries, and automated verification.

---

## Core Areas of Practice

- **AI Engineering & Agent Orchestration** — Multi-agent routing, Model Context Protocol (MCP) server integration, structured software engineering workflows (`discovery -> architecture -> implementation -> verification`), Role-Based Access Control (RBAC) authority matrices, JSON-Schema Task Contracts, and token-budgeted context packing.
- **Native ARM64 Runtimes & Reverse Engineering** — Bare-metal Android `Bionic`/`Glibc` userspace environments, `AArch64` binary patching (`seccomp` / `CLONE_NEWUSER` sandbox bypass, `ARMv8.0-A` LSE atomics emulation), two-tier native binary analysis (`Rust` MCP + headless `Ghidra 12.1.4`), and Gradle-free deterministic APK toolchains.
- **Harness Engineering & Governance** — Deterministic validation chains, governed execution sandboxes, pre/post-execution scope verification, and automated secret and machine-path scanning.
- **Backend & Web Systems** — Python (`Django 6.0`), TypeScript (`Node.js`, `Express`), React (`Vite`, `Tailwind CSS`), relational database design, role-based access control, and automated PDF/Excel reporting (`ReportLab`, `OpenPyXL`, `ExcelJS`).
- **Mobile Engineering (Android)** — Native Android development in Kotlin and Java, MVVM architecture (`ViewModel`, `LiveData`, `ViewBinding`), Kotlin Coroutines, Foreground Services, WebRTC/WebAudio pipelines, real-time NATS message streaming, and offline-first document processing.
- **Databases & Data Integrity** — PostgreSQL and SQLite (WAL mode), database-level `CheckConstraint` and case-insensitive `UniqueConstraint` enforcement, and transactional stock/order ledgers.

---

## Featured Open-Source Projects

### [Antigravity for Android](https://github.com/Yhoanes/antigravity-android) · [Official Site](https://yhoanes.github.io/antigravity-android/)
**Standalone Google Antigravity IDE & Native ARM64 Reverse-Engineering APK** · `Java` · `Rust (agy-box)` · `AArch64 / Bionic` · `Ghidra 12.1.4` · `MCP` · `WebRTC`

Native Android (`Bionic`/`Glibc`) autonomous coding IDE and binary reverse-engineering environment executing directly on physical ARM64 hardware without PRoot or QEMU virtualization overhead (`1,222 MB/s` UFS reads, `84,395 IOPS`). Includes the single-binary **`agy-box` Rust runtime accelerator** (4-thread parallel `pkg`, `41 ms` `inotify` `agy-daemon` in `900 KB` heap, `112x` faster NEON path rewriting, and `398` zero-shell symlinks), HTTP/2 stream resume guard (`<1s` background rehydration), Live Voice WebRTC, 1-tap OTA updates, and the live **[Built for Android Plugin Marketplace](https://github.com/Yhoanes/antigravity-android-plugins)** (`AGY Video Studio` GPU `h264_mediacodec`, `Craft Anything` **302 Rust MCP tools** + native ARM64 **Ghidra 12.1.4**, `Game Studio 2D/3D`, and 91-tool `GitHub MCP`).

### [AI Engineering Harness](https://github.com/Yhoanes/ai-engineering-harness)
**Deterministic Agent Governance, Orchestration & Validation Framework** · `Python 3.11+` · `JSON Schema` · `PyYAML` · `Pytest`

Governance and orchestration framework that enforces structured software engineering lifecycles across 18 specialized agent profiles and 16 workflows. Includes a 10-validator deterministic chain, YAML/JSON-Schema Task Contracts, an RBAC Authority Matrix (`DENY_ALL`, `ALLOW_LIST`, `UNRESTRICTED`), automated secret scanning, and portable runtime distribution tooling (`684 passed, 4 skipped` in the automated test suite).

### [Ferretería 7 Hermanos — Retail POS & Inventory ERP](https://github.com/Yhoanes/ferreteria-7-hermanos)
**Point of Sale, Multi-Role Inventory & Reporting System** · `Python 3.12+` · `Django 6.0` · `PostgreSQL` · `ReportLab`

Full-stack retail management system developed as a Systems Engineering Capstone Project (*Proyecto de Grado*). Structured into 5 modular Django applications and 16 relational models with database-level integrity constraints, custom RBAC roles (*Administrador*, *Vendedor*, *Almacenero*), supplier stock entry/exit ledgers, split-payment invoicing, automated PDF/Excel reports, and 25 automated tests.

### [Albion Flip Finder](https://github.com/Yhoanes/albion-flip-finder)
**Real-Time Market Arbitrage Scanner for Android** · `Kotlin 2.0` · `Android SDK` · `MVVM` · `Coroutines` · `NATS.io`

Native Android application that connects to the *Albion Online Data Project* NATS broker (`io.nats:jnats`) across Americas, Europe, and Asia servers to stream live market buy/sell orders. Computes net profit and ROI after market taxes (Premium vs. non-Premium fees), runs a persistent Foreground Service with custom profit alerts, and provides offline localized item catalogs in English, Spanish, and Portuguese.

---

## Technical Stack

| Area | Technologies |
| :--- | :--- |
| **Languages** | Python, Kotlin, Java, TypeScript, JavaScript, POSIX Shell / Bash, SQL, C++ (JNI / POSIX integration), HTML5, CSS3 |
| **AI & Agent Systems** | Agent Orchestration, Model Context Protocol (MCP), Task Contract Schemas, Deterministic Validation Harnesses, Context Packing, Workflow Governance, Live Voice WebRTC |
| **Android & ARM64 Systems** | Android SDK (API 24–36), Bionic / Glibc Userspace, AArch64 Binary Patching, Ghidra 12.1.4 Headless (`decompile` / `sleigh`), Craft Anything (Rust MCP), Shizuku (`rish`), Jetpack MVVM, Kotlin Coroutines, Foreground Services, NATS Client, Firebase Auth, Material Design 3 |
| **Web & Backend** | Django 6.0, Node.js, Express, React 18, Vite, Tailwind CSS, WebSockets, WhatsApp Automation (`Baileys`) |
| **Data & Reporting** | PostgreSQL, SQLite, ReportLab, xhtml2pdf, OpenPyXL, ExcelJS, Apache POI |
| **Testing & Tooling** | Pytest, Django TestCase, JUnit 4, Vitest, Ruff, Deterministic APK Pipeline (`aapt` / `d8` / `apksigner`), Git |
