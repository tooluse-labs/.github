<p align="center">
  <img src="https://raw.githubusercontent.com/tooluse-labs/.github/main/assets/brand/logo-lockup.svg" width="720" alt="Tooluse Labs — Open-source tools for AI agents: MCP servers, skills, and supporting tooling.">
</p>

---

## Active projects

- [**perfetto-mcp-rs**](https://github.com/tooluse-labs/perfetto-mcp-rs) — MCP server for Perfetto trace analysis. PerfettoSQL queries on `.pftrace` / `.perfetto-trace` / `.bin` files plus dedicated Chrome tools for scroll jank, page loads, main-thread hotspots, and stdlib module discovery. Available via `cargo install perfetto-mcp-rs`, `brew install`, or `curl … | sh`.
- [**wpa-mcp**](https://github.com/tooluse-labs/wpa-mcp) — MCP server for Windows ETW (`.etl`) trace analysis. ~17 tools across CPU / wait / image-load / file-disk-mmap I/O, each with a matching caller-callee drill-down; built on the official `Microsoft.Diagnostics.Tracing.TraceEvent` library. Windows-only. Install via PowerShell one-liner (`irm … | iex`) or Git Bash (`curl … | bash`).

## Distribution

- [**homebrew-tap**](https://github.com/tooluse-labs/homebrew-tap) — Homebrew formula distribution for Tooluse Labs releases (`brew tap tooluse-labs/tap`).

## Why "Tooluse"

LLM agents pick which tool to call from a list at every turn. Tool quality — what the tool *says* it does, when *not* to use it, what its empty result means — has measurable impact on agent task success (see Glama's [Tool Definition Quality Score](https://glama.ai/blog/2026-04-03-tool-definition-quality-score-tdqs) framework). This org builds tools whose descriptions are calibrated for that selection problem, not just for human readers of API docs.
