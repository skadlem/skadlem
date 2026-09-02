# Hi, I'm Madiyar Yengsebek 👋

CS undergraduate at City University of Hong Kong (Year 3), previously on exchange at Vilnius University. I build low-latency systems, cross-platform mobile and AI-powered applications end to end, and developer tooling for multi-agent workflows.

## What I build

- **Low-latency systems** — [orderbook](https://github.com/skadlem/orderbook): C++23 limit order book and matching engine — bitmap ladder, zero-alloc intrusive pool, IOC/FOK/PostOnly/STP, incremental L2 + seqlock BBO, ITCH 5.0 engine-vs-feed validation (0 violations on full trading days), OUCH 4.2 order-entry gateway, honest min-of-N benchmarking vs 4 vendored rivals (~18 ns/op mixed)
- **Developer tooling** — [pm-agent-team](https://github.com/skadlem/pm-agent-team): PMOS, a host-portable multi-agent project-management template (jcode, Claude Code, Hermes, OpenHands SDK) — role agents with per-role hybrid-search knowledge bases (BM25 + vector, reciprocal rank fusion), graphify repo context, wave-based execution with human approval gates, a real-time spend ledger priced from Epoch AI benchmarks, and SPARQL-queryable artifact traceability
- **AI-powered apps** — [roof-bot](https://github.com/skadlem/roof-bot): a WhatsApp roofing sales manager — Gemini agent on LangGraph (tool-calling) running a full SPIN sales script, RAG knowledge base (ChromaDB), live pricing from a price list, voice-message transcription, and every confirmed lead delivered to Google Sheets + the owner's WhatsApp
- **Poker research** — [poKING](https://github.com/skadlem/poKING): a 6-max No-Limit Hold'em research project — rules engine, hand-tuned bot, a PPO agent (PyTorch) and an NFSP average-policy pipeline validated against exact exploitability on Kuhn poker, with seed-replicated, claim-disciplined benchmarking (found and fixed a rebuy bug that had inflated variance ~2,800x) — PPO beats the heuristic bot +604 bb/100 heads-up, NFSP's average policy comes out 2-4x less exploitable
- **Mobile** — [diary](https://github.com/skadlem/diary): React Native / Expo app — Firebase email/password auth, full task CRUD (thoughts, 30-day reviews, yearly goals, daily summaries), local AsyncStorage persistence, and a mini-game
- **Web** — [dostupnaya-sreda](https://github.com/skadlem/dostupnaya-sreda): Next.js 14 landing page with ru/kk i18n and dark mode, live on Vercel

## Stack

React Native, JavaScript, TypeScript, Python (FastAPI, numba, PyTorch, pytest), C++ (C++23, CMake, sanitizers), LangGraph / Gemini, RAG (ChromaDB), Firebase, SQLite (FTS5, hybrid search), Next.js, Java, C#

## Currently

Building PMOS — a host-portable multi-agent project-management template — and training RL poker agents (PPO, NFSP) in poKING.

## Languages

English (C1, IELTS 7.5) · Russian (fluent) · Kazakh (fluent)

## Contact

- 📧 myengsebe2-c@my.cityu.edu.hk
- 💼 [LinkedIn](https://www.linkedin.com/in/yengsebek/)
