# Blaque Baux Broaching

**Post-Event Volatility Bleed — STUB (blocked on data).**

Sell short-dated straddles/strangles the morning after a binary event (earnings, FDA) to harvest the IV collapse once uncertainty resolves, delta-hedged daily.

> **Status: STUB / DATA-BLOCKED.** This sleeve is specified and queued but **not yet built** — it needs an options chain plus an event calendar (earnings/FDA dates). Both are outside Alpaca's price-only daily bars.

> **Not investment advice.** Educational/research software. See [DISCLAIMER](DISCLAIMER.md) and [LICENSE](LICENSE).

## Honest null (to be tested once the feed exists)

Does echo volatility (guidance revisions, downgrades) cause enough realized movement to wipe out the premium — a hidden tail-risk strategy disguised as income?

## Why it's a stub

The Blaque Baux research stack runs on Alpaca SIP **daily OHLCV + crypto**. Post-Event Volatility Bleed cannot be tested faithfully on
price bars alone — it requires an options chain plus an event calendar (earnings/FDA dates). Both are outside Alpaca's price-only daily bars. When that feed is wired in, this becomes `broaching_1` with the family's standard
fat-tail scorecard (Sharpe / CAGR / maxDD / skew / Jensen's alpha / M-squared), causal signals, and an honest verdict.

## Status

**Stub.** Placeholder for a queued sleeve awaiting a data source beyond price. No code, no backtest, no live capital yet.
