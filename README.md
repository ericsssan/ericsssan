# Hi, I'm Eric 👋

Senior full-stack engineer in Singapore. By day I ship full-stack products; in my spare time I go deep on **low-level systems** — building language tooling and network stacks from scratch, mostly in **Zig** — because the best way to understand a system is to rebuild it.

The headline project: a complete **JavaScript/TypeScript toolchain in Zig** — a parser, a type checker, a compiler, and a linter, each a standalone library you can use on its own.

---

### 🛠️ The TypeScript toolchain (in Zig)

A parse → check → emit pipeline, built as independent, composable libraries:

| Project | What it does | Highlights |
|---------|--------------|------------|
| **[es-parser](https://github.com/ericsssan/es-parser)** | JS/TS/JSX parser | 3,966/3,966 test262 · 19,120/19,136 TypeScript compiler tests · SIMD lexer, struct-of-arrays AST |
| **[ez-checker](https://github.com/ericsssan/ez-checker)** | TypeScript type checker | Full inference, control-flow narrowing, conditional/mapped types, cross-file resolution |
| **[ez-compiler](https://github.com/ericsssan/ez-compiler)** | TS → JS compiler | Emits JS, `.d.ts`, source maps & diagnostics — built on the two above |
| **[ez](https://github.com/ericsssan/ez)** | High-performance linter | Zero-copy ESLint plugin runner — run any ESLint plugin against the Zig AST, no reimplementation |

### 🌐 Networking

| Project | What it does |
|---------|--------------|
| **[zquic](https://github.com/ericsssan/zquic)** | Sans-I/O QUIC library — RFC 9000/9001/9002, TLS 1.3 handshake, CUBIC + BBRv3, 0-RTT, zero dependencies |
| **[zhttp3](https://github.com/ericsssan/zhttp3)** | HTTP/3 framing, QPACK compression, and a server layer built on zquic |

### 🔬 Tooling & deep dives

| Project | What it does |
|---------|--------------|
| **[zbc](https://github.com/ericsssan/zbc)** | Static analyzer that infers Zig lifetime/ownership/cleanup bugs — no annotations |
| **[zcov](https://github.com/ericsssan/zcov)** | Cross-platform code coverage for Zig — one command, no dependencies |
| **[zig-bindgen](https://github.com/ericsssan/zig-bindgen)** | WIT bindings generator for Zig targeting the WebAssembly Component Model |
| **[ic-fuzzer](https://github.com/ericsssan/ic-fuzzer)** | Diagnosing & fixing V8 megamorphic deopts in Node — with a [full writeup](https://github.com/ericsssan/ic-fuzzer/blob/main/ARTICLE.md) |

---

### 🧰 Tech I reach for

![Zig](https://img.shields.io/badge/Zig-F7A41D?style=flat&logo=zig&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat&logo=webassembly&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

Interests: compilers, parsers, type systems, network protocols, performance engineering, and low-level systems work.

---

📫 **Open to work.** Reach me at **ericsssan@gmail.com** — happy to talk compilers, systems, or performance.
