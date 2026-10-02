# HiveStream Phase 1B — v12.4.2 Natural Swarm Diagnostic

Test-run directory for `HiveStream_Phase_1B_Natural_Swarm_Diagnostic_v12-4-2.html`, the P2P-only/custom-swarm diagnostic harness used to test real segment-level P2P transfer against `test-streams.mux.dev/x36xhzz`.

v12.4.2 fixes a critical bug in v12.4.1 (an undefined `now()` call that silently dropped every captured ICE candidate) plus several smaller correctness and instrumentation issues, verified against two independent LLM code audits. Full changelog and per-claim verification: see the companion docs below.

**Contents (as added):**
- `HiveStream_Phase_1B_Natural_Swarm_Diagnostic_v12-4-2.html` — the diagnostic harness
- `2026-09-25-1900_HIV_001_Phase1B-v12.4.1-Code-Review_OUTPUT.md` — line-by-line code review of v12.4.1
- `2026-09-25-2300_HIV_002_Phase1B-v12.4.2-Verification-and-Changelog_OUTPUT.md` — audit verification + full v12.4.2 changelog
- Exported run JSONs (as this test run produces them)

Authors: Elwood Edwards (Project Owner) + Claude (Anthropic, Claude Sonnet 5)
