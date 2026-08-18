# brand-nanorevive

Per-brand context repo for **NanoRevive**. Refreshed automatically every Monday
by the shared `context-tooling` reusable workflow.

## Read this first

1. `INDEX.md` — the map of where each source's data lives and whether it's fresh.
2. `CONTEXT.md` — the human/agent-readable summary of the latest week.
3. `RUNS.md` — append-only log of when each source last succeeded or failed.

## Data

```
data/<source>/<period>.json   schema-validated rollup per source per ISO week
data/latest.json              pointer to each source's latest period
```

No PII is stored anywhere in this repo. Reddit is rollups + links only.

## Manual refresh

From the Actions tab, run `refresh-context` with `workflow_dispatch`, or set
`fixture_all=true` to run everything against mock data with no live keys.
