# Sendra

**A terminal-native HTTP client for developers who want their requests to live with their code.**

Sendra lets you define HTTP requests as plain **YAML files** and run them directly from the shell, or browse and run them from a full interactive terminal UI. Same binary, same requests, your choice of interface.

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
*  **Embedded scripting** — pre/post-request hooks powered by an embedded scripting engine (Rhai). No Node.js runtime required.
*  **A full interactive TUI** — browse collections, edit requests, switch environments, and review run history without leaving the terminal. Bare `sendra` or `sendra tui` launches it.
*  **Terminal-native** — built for the shell and designed to work naturally alongside your codebase.

Sendra is built with **Rust** and is designed to keep API workflows close to the code they exercise.

> **The request is the file.**

### Install

```bash
# Shell (macOS/Linux)
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/sendra-lab/Sendra/releases/latest/download/sendra-cli-installer.sh | sh

# npm / pnpm / bun
npm install @sendra-lab/sendra

# Homebrew
brew install sendra-lab/tap/sendra-cli

# cargo
cargo install sendra-cli
```

See the [releases page](https://github.com/sendra-lab/Sendra/releases) for Windows and manual binary downloads.

### Docs

Full reference documentation, design decisions, and the changelog live at the [Sendra website](https://sendra-web.vercel.app) *(placeholder — swap for the real domain once it's live)*.

### Status

**v0.1.0 is out** — core CLI (`run`, `test`, assertions, chaining, environments, scripting, OAuth) and the full TUI are both shipped, in the same binary, available via GitHub Releases, npm, Homebrew, and crates.io.

---

**Built with Rust.**
