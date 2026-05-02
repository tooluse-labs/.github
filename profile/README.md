<p align="center">
  <img src="https://raw.githubusercontent.com/tooluse-labs/.github/main/assets/brand/avatar.svg" width="160" alt="Tooluse Labs">
</p>

<h1 align="center">Tooluse Labs</h1>

<p align="center">
  Open-source tools for AI agents — MCP servers, skills, and supporting tooling.
</p>

---

## Active projects

- [**perfetto-mcp-rs**](https://github.com/tooluse-labs/perfetto-mcp-rs) — MCP server for Perfetto trace analysis. PerfettoSQL queries on `.pftrace` / `.perfetto-trace` / `.bin` files plus dedicated Chrome tools for scroll jank, page loads, main-thread hotspots, and stdlib module discovery. Available via `cargo install perfetto-mcp-rs`, `brew install`, or `curl … | sh`.
- [**homebrew-tap**](https://github.com/tooluse-labs/homebrew-tap) — Homebrew formula distribution for the above (`brew tap tooluse-labs/tap`).

## Coming up

- **wpa-mcp-net** — sibling MCP server for Microsoft Windows Performance Analyzer / ETL trace files (`.etl`). Same shape as perfetto-mcp-rs, .NET implementation around the official `Microsoft.Windows.EventTracing.Processing` library.

## Why "Tooluse"

LLM agents pick which tool to call from a list at every turn. Tool quality — what the tool *says* it does, when *not* to use it, what its empty result means — has measurable impact on agent task success (see Glama's [Tool Definition Quality Score](https://glama.ai/blog/2026-04-03-tool-definition-quality-score-tdqs) framework). This org builds tools whose descriptions are calibrated for that selection problem, not just for human readers of API docs.
