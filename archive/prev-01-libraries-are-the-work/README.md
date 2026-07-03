# Asmit Dash

**I design AI systems for a living.**

AI Systems Architect Intern @ Deloitte. B.Tech Computer Engineering, University of Mumbai (graduated).

Most of what I build isn't an app — it's a **primitive** other systems compose. The libraries below are the RAG-and-agent-memory toolkit I keep reaching for. Each solves a silent-failure problem I got tired of watching people ship past.

---

## Libraries — the RAG & agent-memory toolkit

| Library | What silently breaks without it |
|---|---|
| [**palimpsest**](https://github.com/asmitdash/palimpsest) | Agent memory that quietly contradicts itself. Contradiction-aware memory with provenance-preserving forgetting. |
| [**chronograph**](https://github.com/asmitdash/chronograph) | RAG returning facts that were true in 2019 for a question about today. Temporally-aware knowledge graph — every edge has a validity window + confidence-decay curve. |
| [**replay-rag**](https://github.com/asmitdash/replay-rag) | Reasoning-heavy agents re-deriving the same chain-of-thought every call. Store, retrieve, splice past reasoning to cut tokens on repeat patterns. |
| [**corroborate**](https://github.com/asmitdash/corroborate) | Hallucinated numbers, dates, and quotes shipping to users. Deterministic answer-grounding without LLM-as-judge. |
| [**chaffer**](https://github.com/asmitdash/chaffer) | Duplicate chunks, dim mismatches, eval-set leakage rotting your retriever. Lint for RAG corpora + retrievers. |
| [**staleness**](https://github.com/asmitdash/staleness) | Stale chunks + missing timestamps + embed-model age degrading retrieval quietly. Freshness + drift linter. |
| [**relapse**](https://github.com/asmitdash/relapse) | LLMs hallucinating the same way twice. Self-correcting call wrapper: ground-check, restructure with explicit findings, retry. |
| [**dash-mlguard**](https://github.com/asmitdash/dash-mlguard) | Silent leakage/drift/schema mismatch in ML training pipelines. Lint before your model ruins itself. |

---

## Applied work built on top

- **[Twin](https://github.com/asmitdash/twin)** — Personal voice-mimic-with-retrieval PWA. Wraps 5 of the libraries above (palimpsest, chronograph, replay-rag, corroborate, chaffer) via a Python sidecar.
- **[Redoubt](https://github.com/asmitdash/redoubt)** — Static prompt-injection scanner for RAG corpora. Jailbreak signatures, encoded payloads, hidden instructions.
- **[Sentinel](https://github.com/asmitdash/sentinel)** — Drop-in LLM proxy that refuses to answer without citations from your Cognee memory. Every claim gets a receipt or gets redacted.
- **[Codex-Prime](https://github.com/asmitdash/codex-prime)** — Persistent memory for codebases via MCP + Cognee. Every AI-coding session becomes a queryable decision record.
- **[IndicEval](https://github.com/asmitdash/indic-eval)** — Eval harness + observability SDK + leaderboard for Indic LLMs (Hindi/Bengali/Tamil/Bhojpuri/Awadhi/Magahi). Code-mix, transliteration, dialect.
- **[Lex-Rag](https://github.com/asmitdash/lex-rag)** — Advanced RAG platform: hybrid + rerank + agent + GraphRAG.
- **[CVS](https://github.com/asmitdash/CVS)** — Generic claim verification with admin-configurable rules.

---

## Publications

- **A Survey on Retrieval-Augmented Generation (RAG) Models: Recent Advances and Challenges** — [Scholar](https://scholar.google.com/citations?user=tyKozHwAAAAJ&hl=en)
- **Multimodal Emotion Recognition using Hierarchical Contrastive Residual Cross-Attention Fusion**
- **Facial Landmark-Based Face Shape Classification: A Lightweight Approach for Real-Time Applications**
- **A Bayesian Network to Model the Influence of Energy Consumption on Greenhouse Gases in Italy**

ORCID: [0009-0003-4247-9312](https://orcid.org/0009-0003-4247-9312) · Scholar: [tyKozHwAAAAJ](https://scholar.google.com/citations?user=tyKozHwAAAAJ&hl=en)

---

## Elsewhere

Portfolio [asmit-dash.vercel.app](https://asmit-dash.vercel.app) · LinkedIn [asmitdash](https://www.linkedin.com/in/asmitdash/) · Twitter [@AsmitDash007](https://twitter.com/AsmitDash007) · Instagram [@asmittdashh](https://www.instagram.com/asmittdashh/) · asmitdash44@gmail.com
