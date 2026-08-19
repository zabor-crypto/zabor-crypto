# Boris Zabavnikov

**Systematic trading professional combining quantitative research, production trading engineering,
and portfolio/risk ownership — from hypothesis to live capital.**

Digital-asset markets since 2013. Independent systematic trading and quant research: I take a
strategy from hypothesis and data through validation, simulation, portfolio construction, execution
and monitoring into live operation — and through attribution and retirement when it stops working.

`Research rigor · Production realism · Portfolio ownership`

---

### What I do

- **Quant research.** Preregistration, matched-null controls, placebo tests, walk-forward validation,
  era splits, block bootstrap, sample gates, explicit PASS / WATCH / KILL decisions.
- **Systematic trading development.** Python research-to-production stack — exchange APIs, order
  lifecycle, partial fills, reconciliation against venue truth, deterministic replay, event stores,
  monitoring.
- **Portfolio and risk ownership.** Capital allocation, correlated exposure, regime dependence,
  portfolio heat, leverage, drawdown control, capacity, strategy overlap.

Scope of the independent track: managed systematic trading capital across proprietary/owned capital and
external/prop trading allocations, with peak capital under management up to $25M; 10+ live strategies
at peak across BTC, ETH and liquid altcoin perpetuals; 50+ documented strategy lines researched,
validated, deployed, parked or rejected.

---

### Public code

**[zaBor](https://github.com/zabor-crypto/zaBor)** — trading engineering toolkit.
An emergency risk-control engine with account-level drawdown protection: PnL attribution decides
*which side* caused a loss, positions are ranked and closed surgically, and a portfolio-level Regime
Guard covers the slow bleed that no threshold on a 15-minute window ever catches. Fail-closed by
design — 153 offline tests, no credentials needed to run any of it. Alongside it: a wallet-tagged
Hyperliquid microstructure recorder that turns adverse selection from an assumption into a
per-counterparty measurement, and a multi-venue funding-carry research stack.

**[Research Intelligence Platform](https://github.com/zabor-crypto/research-intelligence-platform)** —
research-to-hypothesis pipeline.
Turns papers, repositories and notes into ranked, backtest-ready strategy hypotheses. The eligibility
rules are deterministic code kept *outside* the model prompt, so a rejection is reproducible and
auditable whether or not an LLM is in the loop. 324 tests, fully offline, no API key required.

Both install and run from a clean clone with no exchange account and no keys.

---

### Technical focus

Python · pandas / NumPy / SciPy · pytest · asyncio · SQLite and event stores · Parquet / DuckDB ·
exchange REST and WebSocket integrations · deterministic replay and backtest parity · Linux, systemd,
multi-VPS operation

---

### Public / private boundary

The public repositories are the engineering and methodology layer, published deliberately. Live
strategy logic and parameters, private research corpora, account data, positions and trading records
are not published, and results that depend on private datasets are labelled as such rather than
presented as reproducible.

Where a figure here comes from a reconstruction or a shadow test rather than realised live trading,
it says so.

---

[LinkedIn](https://www.linkedin.com/in/boris-zabavnikov)
