# Vestige on LobeHub
Local-first Rust MCP memory. See lhm.plugin.json.

Product: https://github.com/samvallad33/vestige
Package: vestige-mcp-server
Command: vestige-mcp
Identifier: samvallad33-vestige
Version: 2.8.0
Transport: stdio / local only. No hosted HTTP endpoint.
This is not production.

GUI clients should set command to the absolute path of vestige-mcp.
Prebuilt 2.8.0 binaries cover macOS (Apple Silicon and Intel), Linux x86_64, and Windows x86_64.

Tools: recall, smart_ingest, backfill (Causal Backfill).
Also: receipt, memory, graph, maintain, dedup, suppress, memory_status, codebase, intention, source_sync, session_start.

lhm.plugin.json is the owner declaration. Do not set cloudEndpoint.
