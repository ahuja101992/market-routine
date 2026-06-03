# Methodology — Scoring & Time-Bucketing

## Time buckets (applied to every event-based signal)

- **Fresh:** <4h since event → potentially actionable
- **Recent:** 4–48h → continuation / second-leg watch
- **Stale:** >48h → context only, not a primary signal

Tag every event signal with its time bucket. A stale signal cannot drive a name into the top setups.

---

## Signal types — each scored on the indicated scale

### 1. Event signal (catalyst proximity) — 0 to 3
- **3**: Hard catalyst in <5 days (earnings, FDA decision, scheduled event); OR fresh executive / political mention (<4h)
- **2**: Hard catalyst in 5–14 days; OR recent mention (4–48h)
- **1**: Soft catalyst — analyst day, rumor, M&A speculation
- **0**: No identifiable catalyst

### 2. Sentiment delta (24–72h narrative shift) — −3 to +3
- **+3 / −3**: Major shift — tier-1 bank upgrade/downgrade, high-profile mention
- **+2 / −2**: Notable — multiple aligned headlines
- **+1 / −1**: Mild directional shift
- **0**: Neutral

Absolute value matters. Strong negative sentiment on a fundamentally strong name can be a contrarian signal.

### 3. Valuation signal — −3 to +3
- **+3**: Trading at clear discount vs sector and own history (z-score < −1.5 on P/E or EV/EBITDA)
- **+2**: Below historical average
- **0**: In-line
- **−2 / −3**: Premium or stretched

### 4. Technical signal — −3 to +3
- **+3**: Clear inflection (RSI <30 on quality name, golden cross, volume spike with price hold)
- **+2**: Constructive setup (above key MA, basing pattern)
- **0**: Neutral
- **−2 / −3**: Breaking down; RSI >70 with no fundamental backing

### 5. Crowding / positioning — −3 to +3
- **+3**: Under-owned, high short interest on improving fundamentals (squeeze potential)
- **0**: Neutral
- **−3**: Crowded long; everyone already in

---

## Composite scoring

Sum the five signals. Range: −15 to +15. Use absolute value for ranking.

- **Watch threshold:** |composite| ≥ 6
- **High conviction:** |composite| ≥ 10 AND at least one signal of 3 (no flat profiles)

A single 3 in **event signal** can carry an otherwise quiet name onto the brief, because event-driven is the strategy. High valuation score with no catalyst is not enough on its own — it's a setup looking for a trigger, and those can sit for months.

---

## Asymmetry framing (per name)

Every name on the brief must answer four questions:

1. **Catalyst** — what specific event, when, why it moves the stock
2. **Setup** — price relative to history; valuation snapshot; peer context
3. **Variance** — estimated move range based on implied vol or historical reaction to similar events
4. **Bear case** — single line: what would invalidate the thesis

**If the bear case cannot be articulated, the idea is not ready. Drop it.**

---

## Low-signal days

Some days, nothing important is happening. The honest response is to say so. Forcing 5 names every run manufactures noise and trains the user to act on it. Acceptable outputs: "1 name flagged, 2 watching, otherwise quiet" — or even "no high-conviction setups today."

---

## Journal scoring (for `journal.md`)

Each flagged name gets logged with:
- Date / time flagged
- Composite score at flag
- Price at flag
- Catalyst summary
- Bear case summary

In later runs, append:
- T+1d return (vs SPY)
- T+5d return (vs SPY)
- T+30d return (vs SPY)
- Whether the catalyst materialized

After ~90 days of journal data, signal-type hit rates can be evaluated and rubric weights revised.
