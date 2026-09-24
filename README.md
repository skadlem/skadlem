# Madiyar Yengsebek

**AI-agent systems + low-latency C++**

CS @ City University of Hong Kong · Class of 2028 · Open to Summer 2027 SWE and AI-agent internships

I build AI-agent tools and performance-critical software, with an emphasis on measurable behavior, reproducibility, and failure handling.

[LinkedIn](https://www.linkedin.com/in/yengsebek/) · [Email](mailto:myengsebe2-c@my.cityu.edu.hk)

## Selected work

### [orderbook](https://github.com/skadlem/orderbook) — Low-latency C++23 matching engine

A price-time-priority limit order book and matching engine validated against real ITCH 5.0 market data, with an OUCH 4.2 order-entry gateway.

**16.6–18.5 ns/op mixed · 11M+ differential checks · zero violations on full NASDAQ ITCH replay**

`C++23` · `CMake` · `ASan/UBSan` · `ITCH/OUCH`

[Repository](https://github.com/skadlem/orderbook) · [Architecture and benchmarks](https://github.com/skadlem/orderbook#system-tour)

### [roof-bot](https://github.com/skadlem/roof-bot) — WhatsApp AI sales agent

A Russian-language sales agent that qualifies leads, quotes from live pricing data, transcribes voice messages, and exports confirmed orders to Google Sheets and the owner's WhatsApp.

**96% grounded · 92% correct on a 24-case evaluation set**

`Python` · `FastAPI` · `Gemini` · `LangGraph` · `RAG`

[Repository](https://github.com/skadlem/roof-bot) · [Evaluation](https://github.com/skadlem/roof-bot#evaluations)

### [PMOS](https://github.com/skadlem/pm-agent-team) — Multi-agent development framework

A host-portable framework for role-specialized agents with hybrid knowledge bases, human approval gates, spend tracking, and artifact traceability. Runs on Claude Code, jcode, Hermes, and OpenHands.

Used by a PMOS agent team to ship [cronx](https://github.com/skadlem/cronx), a DST-aware, standard-library-only cron explainer.

[Repository](https://github.com/skadlem/pm-agent-team)

## Current work

**[rof](https://github.com/skadlem/rof-harness)** — a local Rust agent runtime with deterministic context assembly, deny-by-default tool permissions, and reproducible evaluation traces. Its current 20-task suite averages **17/20 across three runs**.

## Research

**[poKING](https://github.com/skadlem/poKING)** — seeded PPO and NFSP research in a poker engine, built around honest measurement. Includes a write-up of a benchmark bug that inflated measured variance by approximately **2,800×**.

## Stack

- **Core:** Python · C++ · TypeScript/JavaScript
- **AI and agents:** Gemini · LangGraph · RAG · PyTorch · evaluation harnesses
- **Systems and product:** CMake · FastAPI · SQLite · Next.js · React Native · Firebase

English C1 (IELTS 7.5) · Russian · Kazakh
