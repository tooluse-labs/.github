<p align="center">
  <img src="https://raw.githubusercontent.com/tooluse-labs/.github/main/assets/brand/logo-lockup.svg" width="720" alt="Tooluse Labs — Open-source tools for AI agents: MCP servers, skills, and supporting tooling.">
</p>

---

## Active projects

<table>
  <tr>
    <td width="72" align="center"><a href="https://github.com/tooluse-labs/perfetto-mcp-rs"><img src="https://raw.githubusercontent.com/tooluse-labs/perfetto-mcp-rs/main/assets/brand/logo-avatar.svg" width="56" height="56" alt=""></a></td>
    <td><a href="https://github.com/tooluse-labs/perfetto-mcp-rs"><strong>perfetto-mcp-rs</strong></a><br>MCP server for Perfetto trace analysis. PerfettoSQL queries on <code>.pftrace</code> / <code>.perfetto-trace</code> / <code>.bin</code> files plus dedicated Chrome tools for scroll jank, page loads, main-thread hotspots, and stdlib module discovery. Available via <code>cargo install perfetto-mcp-rs</code>, <code>brew install</code>, or <code>curl ... | sh</code>.</td>
  </tr>
  <tr>
    <td width="72" align="center"><a href="https://github.com/tooluse-labs/wpa-mcp"><img src="https://raw.githubusercontent.com/tooluse-labs/wpa-mcp/main/assets/wpa-mcp-mark.svg" width="61" height="61" alt=""></a></td>
    <td><a href="https://github.com/tooluse-labs/wpa-mcp"><strong>wpa-mcp</strong></a><br>MCP server for Windows ETW (<code>.etl</code>) trace analysis. ~17 tools across CPU / wait / image-load / file-disk-mmap I/O, each with a matching caller-callee drill-down; built on the official <code>Microsoft.Diagnostics.Tracing.TraceEvent</code> library. Windows-only. Install via PowerShell one-liner (<code>irm ... | iex</code>) or Git Bash (<code>curl ... | bash</code>).</td>
  </tr>
</table>

## Distribution

- [**homebrew-tap**](https://github.com/tooluse-labs/homebrew-tap) — Homebrew formula distribution for Tooluse Labs releases (`brew tap tooluse-labs/tap`).

## Why "Tooluse"

LLM agents pick which tool to call from a list at every turn. Tool quality — what the tool *says* it does, when *not* to use it, what its empty result means — has measurable impact on agent task success (see Glama's [Tool Definition Quality Score](https://glama.ai/blog/2026-04-03-tool-definition-quality-score-tdqs) framework). This org builds tools whose descriptions are calibrated for that selection problem, not just for human readers of API docs.
