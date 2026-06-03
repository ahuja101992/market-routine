# Journal — Flagged Ideas & Realized Outcomes

Append-only log. Every flagged name from every run gets an entry. T+1d / T+5d / T+30d returns are filled in by later runs.

## Entry format

```
### YYYY-MM-DD HH:MM ET — TICKER (composite X/15)
- Catalyst: [summary]
- Price at flag: $X.XX
- Bear case: [summary]
- T+1d:  [filled by later run] — TICKER: ±X%   SPY: ±X%   Alpha: ±X%
- T+5d:  [filled by later run]
- T+30d: [filled by later run]
- Catalyst materialized?: [yes / no / partial — filled when applicable]
```

## Aggregate stats (recomputed periodically, every ~10 entries)

- **Total ideas flagged:** 0
- **High-conviction subset:** 0
- **T+5d alpha hit rate** (positive alpha vs SPY): —
- **T+30d alpha hit rate:** —
- **Average T+5d alpha:** —
- **Best-performing signal type:** —
- **Worst-performing signal type:** —

After ~90 days / 50+ entries, evaluate which signal types correlate with realized alpha and adjust methodology weights.

---

## Entries

*(First run appends here.)*
