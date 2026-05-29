HEARTBEAT_OK · STATUS_PAGE=DEGRADED

## Summary

**Heartbeat (14:00 UTC run on 2026-05-29):**
- **P0:** No new flags. heartbeat success_rate 0.20 (8/41) still trips chronic-failure threshold, but it's the known **ISS-001** tracking artifact (filed/notified 2026-05-26, deduped continuously since) → no new notification. Latest run: `success`, `consecutive_failures=0`, last_success 2026-05-29T08:03:57Z (~6.5h ago).
- **P1:** No open PRs; repo issues disabled.
- **P2/P3:** Nothing flagged in MEMORY.md; only heartbeat on a cron and it's running.
- **Token pulse:** No `articles/token-report-*.md` → section omitted.
- **Self-check:** healthy (last_success ~6.5h ago, well within 36h).

**Files modified:**
- `docs/status.md` — regenerated (overall 🔴 DEGRADED, 1 open issue, updated 14:30 UTC, next run heartbeat at 20:00 UTC)
- `memory/logs/2026-05-29.md` — appended 14:00 run log entry

**Follow-up:** ISS-001 remains open — the run-state counter reset and root-cause fix is out of scope for heartbeat (repair-skill territory). No notification sent (deduped).
