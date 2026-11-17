# Yhoanes Ander Mendoza Rodriguez

**Software Developer · Systems & AI Engineering**  
Native Android ARM64 Agentic IDEs · Rust Bionic Runtimes · Binary Reverse Engineering · Harness Governance · Full-Stack Web

[**Official Website (`yhoanes.github.io`)**](https://yhoanes.github.io/) · [**LLM Reference (`llms.txt`)**](https://yhoanes.github.io/llms.txt)

I design and build bare-metal **Android ARM64 (`Bionic`)** autonomous AI coding environments, single-binary Rust userspace accelerators, native binary reverse-engineering toolchains, deterministic AI governance frameworks, and full-stack enterprise platforms — focusing on zero-virtualization performance, capability-hardened security boundaries, and deterministic verification.

---

## Native ARM64 Android Agentic IDE Suite (Zero PRoot · Zero Termux)

Five standalone, side-by-side Android APKs executing directly on mobile ARM64 silicon via Linux kernel `execve()`, Gradle-free deterministic `build.sh` pipelines, RSA-4096 signed GitHub Releases OTA updates, and 1-tap native ARM64 Rust MCP plugins:

| Standalone Android IDE | Package & Loopback | Core Architecture & Highlights | Links |
| :--- | :--- | :--- | :--- |
| **[Antigravity for Android](https://github.com/Yhoanes/antigravity-android)** | `com.agy`<br/>`127.0.0.1:45157` | Google Antigravity IDE (`v2.32.1`), binary-patched `seccomp` bypass, `liblse_compat.so` ARMv8.0-A atomics, Rust `agy-box` (`398` bridges, `1,222 MB/s` UFS), Gemini 4 / Claude 5.5 & WebRTC Live Voice. | [Website](https://yhoanes.github.io/antigravity-android/) · [APK](https://github.com/Yhoanes/antigravity-android/releases/latest) |
| **[OpenCode for Android](https://github.com/Yhoanes/opencode-android)** | `com.oc.ide`<br/>`127.0.0.1:45167` | 100% Pure Android Bionic `OpenCode v2.3.0` (`/system/bin/linker64`, zero Glibc shim), `<200 ms` `CookieManager` pairing, 75+ AI providers, Rust `opencode-pty v8` + `oc-box` & hot-reload Extensions. | [Website](https://yhoanes.github.io/opencode-android/) · [APK](https://github.com/Yhoanes/opencode-android/releases/latest) |
| **[Claude Code for Android](https://github.com/Yhoanes/claude-android)** | `com.cc.ide`<br/>`127.0.0.1:45177` | Official Anthropic Claude Code Full-Editor UI (`v2.1.325`) + native ARM64 `claude.elf`, `AndroidKeyStore AES-256-GCM` vault, multi-project SAF sidebar, docked PTY (`cc-box`), voice dictation & Skills Hub. | [Website](https://yhoanes.github.io/claude-android/) · [APK](https://github.com/Yhoanes/claude-android/releases/latest) |
| **[Codex for Android](https://github.com/Yhoanes/codex-android)** | `com.ce.ide`<br/>`127.0.0.1:45197` | Official OpenAI Codex UI (`v26.51111`) + static ARM64 `codex.elf` & `codex-code-mode-host` (`~30 ms` GPT-6 Code Mode MCP), `O(1) webview-bundle.pak` (`<2 ms` for 15.3k modules) & `HMAC-SHA256` auth. | [Website](https://yhoanes.github.io/codex-android/) · [APK](https://github.com/Yhoanes/codex-android/releases/latest) |
| **[DeepSeek for Android](https://github.com/Yhoanes/deepseek-android)** | `com.ds.ide`<br/>`127.0.0.1:45187` | Authentic DeepSeek Harness Desktop (`@deepseek-ai/dsh`), `~2.5s` Rust + Zstandard `mmap` JNI bootstrap (`libds_bootstrap.so`), `ds-box v0.3.1`, PKCE OAuth, offline SenseVoice STT & Cordis HMR plugins. | [Website](https://yhoanes.github.io/deepseek-android/) · [APK](https://github.com/Yhoanes/deepseek-android/releases/latest) |

---

## Featured Ecosystems, Governance & Enterprise Systems

### [Native ARM64 MCP Plugins Marketplace](https://github.com/Yhoanes/antigravity-android-plugins)
**Live OTA Catalog of Compiled Android ARM64 Rust & Bionic MCP Toolchains** · `Rust` · `AArch64 / Bionic` · `Ghidra 12.1.4` · `Vulkan` · `MediaCodec`

Delivers 9 zero-Docker native ARM64 plugins across the Android IDE suite: **Craft Anything + Ghidra 12.1.4** (`v0.5.0`, **335 Rust MCP tools** for ELF, PE, Mach-O, APK/DEX, .NET/NativeAOT, ESP32/UF2, Godot `.pck`, Unity IL2CPP & Wii `.dol` + native ARM64 `decompile`/`sleigh`), **AGY Video Studio** (`h264_mediacodec` GPU), **AGY Video Gen**, **Game Studio 2D/3D** (Godot 4.7 Vulkan + C++/Rust `GDExtension` + offline `.apk` compiler), **Unity Studio Android** (Unity 6.3 LTS + ported official `unity-cli v1.0.0`), **AGY ADB Bridge** (6-digit wireless `127.0.0.1:5555` `uid=2000` without external Shizuku), 91-tool **GitHub MCP**, and headless ARM64 Chromium DevTools.

### [AI Engineering Harness](https://github.com/Yhoanes/ai-engineering-harness)
**Deterministic Agent Governance, Orchestration & Validation Framework** · `Python 3.11+` · `JSON Schema` · `PyYAML` · `Pytest`

Governance and orchestration framework enforcing structured software engineering lifecycles across 18 specialized agent profiles and 16 workflows. Includes a 10-validator deterministic chain, YAML/JSON-Schema Task Contracts, an RBAC Authority Matrix (`DENY_ALL`, `ALLOW_LIST`, `UNRESTRICTED`), automated secret scanning, and portable runtime distribution tooling (`684 passed, 4 skipped` in the automated test suite).

### [Ferretería 7 Hermanos — Retail POS & Inventory ERP](https://github.com/Yhoanes/ferreteria-7-hermanos)
**Point of Sale, Multi-Role Inventory & Reporting System** · `Python 3.12+` · `Django 6.0` · `PostgreSQL` · `ReportLab`

Full-stack retail management system structured into 5 modular Django applications and 16 relational models with database-level integrity constraints, custom RBAC roles (*Administrador*, *Vendedor*, *Almacenero*), supplier stock entry/exit ledgers, split-payment invoicing, automated PDF/Excel reports, and 25 automated tests.

### [Albion Flip Finder](https://github.com/Yhoanes/albion-flip-finder)
**Real-Time Market Arbitrage Scanner for Android** · `Kotlin 2.0` · `Android SDK` · `MVVM` · `Coroutines` · `NATS.io`

Native Android application connecting to the *Albion Online Data Project* NATS broker (`io.nats:jnats`) across Americas, Europe, and Asia servers to stream live market buy/sell orders, compute post-tax net profit/ROI, run a persistent Foreground Service with custom alerts, and provide offline localized catalogs in EN/ES/PT.

---

## Technical Stack

| Area | Technologies |
| :--- | :--- |
| **Languages** | Rust, Java, Kotlin, Python, TypeScript, JavaScript, C/C++ (JNI / POSIX / AArch64), POSIX Shell / Bash, SQL, HTML5, CSS3 |
| **Android & ARM64 Systems** | Pure Android Bionic (`/system/bin/linker64`) & Glibc Userspace, `agy-box` / `oc-box` / `cc-box` / `ce-box` / `ds-box` Rust Multicall Engines, `mmap` + Zstandard JNI Bootstraps, `AndroidKeyStore AES-256-GCM`, AArch64 Binary Patching, Ghidra 12.1.4 Headless (`decompile` / `sleigh`), Wireless ADB / Shizuku (`rish`), Deterministic Gradle-Free APK Toolchains (`aapt`, `javac`, `d8`, `apksigner`) |
| **AI & Agent Systems** | Multi-Agent Orchestration, Model Context Protocol (MCP), GPT-6 Code Mode (`grpc+stdio://`), Cordis HMR, Task Contract Schemas, Deterministic Validation Harnesses, WebRTC Live Voice & Offline `sherpa-onnx` SenseVoice STT |
| **Game & Media Engines** | Godot 4.7 Vulkan + ARM64 `GDExtension`, Unity 6.3 LTS URP + `unity-cli`, Android Hardware `h264_mediacodec` GPU Video Rendering |
| **Web, Data & Testing** | Django 6.0, Node.js, Express, React, Vite, Tailwind CSS, PostgreSQL, SQLite (WAL), NATS.io, ReportLab, OpenPyXL, Pytest, JUnit 4, Vitest |
