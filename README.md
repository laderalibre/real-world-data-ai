# Real-world data & AI

**Prove it in prod.**

Data and AI patterns that ran in production at a real company, rebuilt here on public or synthetic data
so anyone can run them. Each folder goes with one post: the problem, what I tried, what shipped, the
numbers before and after, and where it falls short.

No demos built for the feed. If it didn't solve a real problem, it isn't here.

## Index

| # | Pattern | Stack | Status |
|---|---|---|---|
| 01 | Ranking as classification: a typed model picks the right table from a search shortlist | DuckDB · Jev · dbt | coming soon |

## How each folder works

- **Real problem, public data.** The production numbers are reported as percentages in the post. The
  code here runs on public or synthetic data with the same shape, so its numbers are from the
  experiment and labeled that way.
- **Run it yourself.** Every folder has a README with setup, the exact commands and the results of
  one run.
- **Your own keys.** Anything that calls a paid API reads the key from an environment variable. Nothing
  is committed.

## About

Aníbal Ladera, Data & AI engineer. I design data and AI platforms that hold up in production without
blowing up the bill: dbt semantic layers, MCP servers, RAG, agents, DuckDB and MotherDuck.

[LinkedIn](https://www.linkedin.com/in/ajladera) · `#ProveItInProd`
