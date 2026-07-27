# Boris Zabavnikov

Software & research engineer building reliable AI, data and risk-control systems.
Python · reproducible evaluation · event-driven architectures.

---

### Selected projects

**[Research Intelligence Platform](https://github.com/zabor-crypto/research-intelligence-platform)**
A local-first pipeline that turns papers, repositories and notes into ranked, testable research
hypotheses. Eligibility rules are deterministic code kept *outside* the LLM prompt, so a rejection is
reproducible and auditable whether or not a model is in the loop. Runs fully offline with a mock
provider; the test suite needs no network and no API key.

**[zaBor](https://github.com/zabor-crypto/zaBor)**
Toolkit for market-data research, operational risk controls and reproducible analysis. Includes an
emergency risk-control engine with a fail-closed default, a wallet-tagged microstructure recorder, and
multi-venue research infrastructure that reports negative results as results.

---

### Engineering interests

- Reliable AI systems — deterministic guarantees around non-deterministic components
- Reproducible evaluation — offline test suites, pinned inputs, method published alongside findings
- Data pipelines — ingestion, normalization and storage that survive partial failure
- Event-driven architectures — append-only capture, replay, reconciliation
- Operational risk controls — fail-closed defaults, staged escalation, observable rollout

---

### Selected public activity

- Deterministic, code-enforced eligibility gating with machine-readable rejection reasons, wrapped in
  an offline-reproducible test suite.
- An emergency risk-control engine covering three exchanges, with staged closure and a portfolio-level
  guard for slow drawdowns that threshold-based logic does not detect.
- A microstructure recorder for venue data that publishes counterparty addresses, plus a
  standard-library toolkit that measures adverse selection per counterparty rather than assuming it.
- A multi-venue funding-arbitrage study concluding *no edge at current fee levels*, published together
  with the verdict tables and the engine that produced them.

---

### Technologies

`Python` · `pytest` · `SQLite` · `asyncio` · `httpx` · `pandas` / `numpy` · `GitHub Actions` ·
`WebSocket / REST integrations` · `Pine Script`

---

*Published repositories are sanitized: no private research corpus, no proprietary parameters,
no live configuration or account data.*
