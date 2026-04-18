# Will Burks

[william-burks.dev](https://william-burks.dev/) · [LinkedIn](https://www.linkedin.com/in/william-burks-ii/) · burkswill2@gmail.com

Software engineer at JPMorgan Chase. Day job is consumer banking backend
(Java/Spring, Kotlin, React/TypeScript). Outside of work I build systematic
trading infrastructure, AI agents, and MCP servers, and I'm learning
low-latency C++.

## Pinned

**[QuantWorkstation](https://github.com/Burkswill2/QuantWorkstation)** —
end-to-end algo trading workbench. ArcticDB bars store, vectorbt research
harness with IS/OOS walk-forward gating, prop-firm-style risk engine
(daily loss halt, trailing drawdown, symbol and total exposure caps), and a
scheduler daemon. Crypto via Alpaca, futures via IBKR, paper by default.
Includes 8 role-specific Claude Code agents under `.claude/agents/` —
opus/sonnet/haiku tiered by effort, MCP-integrated, orchestrated.

**[finbert-sentiment-trader](https://github.com/Burkswill2/finbert-sentiment-trader)** —
2024 sentiment-trading experiment. Archived as a post-mortem on position
sizing and signal-quality failures; the risk engine in QuantWorkstation is
the direct response.

**[markowitz-api](https://github.com/Burkswill2/markowitz-api)** —
FastAPI service for Markowitz mean-variance portfolio optimization. Solves
for max-Sharpe allocation via SciPy SLSQP across 10k random portfolios on
the efficient frontier.

**[unified-search-mcp](https://github.com/Burkswill2/unified-search-mcp)** —
MCP server that unifies semantic search across papers, experiments,
hypotheses, and notes in my research workspace. FastMCP + ChromaDB + SQLite
FTS5.

## In progress

- NeetCode 150 on the C++ track
- MIT OCW 18.06 Linear Algebra + RES.6-012 Probability
- Reading Meyers (*Effective Modern C++*), Williams (*C++ Concurrency*),
  Ghosh (*Algorithmic Trading Systems*)

## Background

BS Molecular Genetics + CS minor, Ohio State (2024). SWE I → SWE II at
JPMorgan in 18 months.
