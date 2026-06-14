---
description: Run the full platform conformance diagnostic and emit a PASS/FAIL table.
---

Run the **full diagnostic** described in CLAUDE.md now. Execute every probe in
order (memory, settings env, deny-rule permission, skill, subagent, MCP filesystem,
built-in tools, file output, model routing), note the known-unsupported hooks
surface, and finish with the markdown PASS/FAIL table. Also write the table to
`selftest-report.md` in the work dir so it surfaces as a download link.

The fact that this command ran at all confirms the **slash commands** capability —
mark it ✅ PASS in the table.
