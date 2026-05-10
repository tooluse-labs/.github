## Active projects

<table>
  <tr>
    <td width="72" align="center"><a href="https://github.com/tooluse-labs/perfetto-desktop"><img src="https://raw.githubusercontent.com/tooluse-labs/perfetto-desktop/main/desktop/branding/github-repo-logo.png" width="56" height="56" alt=""></a></td>
    <td><a href="https://github.com/tooluse-labs/perfetto-desktop"><strong>perfetto-desktop</strong></a><br>Tauri 2 desktop wrapper for the upstream Perfetto UI with AI-assisted trace analysis. Packages Perfetto as a native app and adds CLI Agent, a local MCP bridge that lets Codex, Claude Code, and other MCP clients analyze the trace currently open in the GUI.</td>
  </tr>
  <tr>
    <td width="72" align="center"><a href="https://github.com/tooluse-labs/perfetto-mcp-rs"><img src="https://raw.githubusercontent.com/tooluse-labs/perfetto-mcp-rs/main/assets/brand/logo-avatar.svg" width="56" height="56" alt=""></a></td>
    <td><a href="https://github.com/tooluse-labs/perfetto-mcp-rs"><strong>perfetto-mcp-rs</strong></a><br>MCP server for Perfetto trace analysis. PerfettoSQL queries on <code>.pftrace</code> / <code>.perfetto-trace</code> / <code>.bin</code> files plus dedicated Chrome tools for scroll jank, page loads, main-thread hotspots, and stdlib module discovery. Available via <code>cargo install perfetto-mcp-rs</code>, <code>brew install</code>, or <code>curl ... | sh</code>.</td>
  </tr>
  <tr>
    <td width="72" align="center"><a href="https://github.com/tooluse-labs/wpa-mcp"><img src="https://raw.githubusercontent.com/tooluse-labs/wpa-mcp/main/assets/wpa-mcp-avatar.svg" width="56" height="56" alt=""></a></td>
    <td><a href="https://github.com/tooluse-labs/wpa-mcp"><strong>wpa-mcp</strong></a><br>MCP server for Windows ETW (<code>.etl</code>) trace analysis. 54 tools spanning CPU, wait, image-load, file/disk/mmap I/O, virtual+heap memory, network, ALPC, registry, interrupts, CLR (GC/JIT/alloc/exception/contention), and any user-mode ETW provider — each top-N view paired with a caller-callee drill-down. Built on the official <code>Microsoft.Diagnostics.Tracing.TraceEvent</code> library. Windows-only. Install via PowerShell one-liner (<code>irm ... | iex</code>) or Git Bash (<code>curl ... | bash</code>).</td>
  </tr>
</table>

## Distribution

- [**homebrew-tap**](https://github.com/tooluse-labs/homebrew-tap) — Homebrew formula distribution for Tooluse Labs releases (`brew tap tooluse-labs/tap`).

## Why "Tooluse"

LLM agents pick which tool to call from a list at every turn. Tool quality — what the tool *says* it does, when *not* to use it, what its empty result means — has measurable impact on agent task success (see Glama's [Tool Definition Quality Score](https://glama.ai/blog/2026-04-03-tool-definition-quality-score-tdqs) framework). This org builds tools whose descriptions are calibrated for that selection problem, not just for human readers of API docs.
