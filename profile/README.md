# Sendra

**A terminal-native HTTP client for developers who want their requests to live with their code.**

Sendra lets you define HTTP requests as plain **YAML files** and run them directly from the shell.

```bash
sendra run examples/get-user.yaml
```

Requests are files — **reviewable, diffable, version-controlled, and shareable**.

### What Sendra does

*  **Requests as YAML** — method, URL, headers, body, and more.
*  **Collections** — group related requests into repeatable API workflows.
*  **Environments** — use the same requests across development, staging, and production.
*  **Assertions & testing** — define expectations and let `sendra test` pass or fail your build.
*  **Request chaining** — capture values from responses and use them in subsequent requests.
*  **Embedded scripting** — pre/post-request hooks powered by an embedded Rust-native scripting engine. No Node.js runtime required.
*  **Terminal-native** — built for the shell and designed to work naturally alongside your codebase.

Sendra is built with **Rust** and is designed to keep API workflows close to the code they exercise.

> **The request is the file.**

### Status

Sendra is actively being built.

An interactive TUI is planned for a future release. For now, Sendra is intentionally focused on its core CLI experience.

---

**Built with Rust.**
