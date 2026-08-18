# Nanorevive — context index

Start here if you are an agent or human looking for this brand’s context.
Current reporting week: **2026-W34**.

## Where the data lives

| Source | Latest period | Fresh? | Data file |
|---|---|---|---|
| shopify | 2026-W34 | yes | `data/shopify/2026-W34.json` |
| reddit | 2026-W34 | yes | `data/reddit/2026-W34.json` |
| converge | 2026-W34 | yes | `data/converge/2026-W34.json` |
| richpanel | 2026-W34 | yes | `data/richpanel/2026-W34.json` |
| aircall | 2026-W34 | yes | `data/aircall/2026-W34.json` |

## Reading order for an agent

1. `CONTEXT.md` — human/agent-readable summary of the latest week.
2. `data/<source>/<period>.json` — schema-validated raw rollups.
3. `RUNS.md` — append-only log of when each source last succeeded or failed.

## Notes

- Sources marked "no" are stale: `CONTEXT.md` will show their last known period.
- No PII is stored anywhere in this repo (filtered at extraction time).
