# Vestige on LobeHub
Local-first Rust MCP memory. See lhm.plugin.json.

Product: https://github.com/samvallad33/vestige
Package: vestige-mcp-server
Command: vestige-mcp
Identifier: samvallad33-vestige
Version: 2.3.0
Transport: stdio / local only. No hosted HTTP endpoint.
This is not production.

GUI clients should set command to the absolute path of vestige-mcp.
Linux Ubuntu 22.04 and Debian 12: wait for v2.4.0 because of glibc.

Tools: recall, smart_ingest, backfill (Causal Backfill).
Also: receipt, memory, graph, maintain, dedup, suppress, memory_status, codebase, intention, source_sync, session_start.

lhm.plugin.json is the owner declaration. Do not set cloudEndpoint.
