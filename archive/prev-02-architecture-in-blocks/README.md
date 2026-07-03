# Asmit Dash

**I design AI systems for a living.** AI Systems Architect Intern @ Deloitte · Mumbai, IN

---

## How my projects actually connect

```mermaid
flowchart TB
    subgraph Primitives["Primitives — libraries other systems compose"]
        direction LR
        PAL[palimpsest<br/>contradiction-aware memory]
        CHR[chronograph<br/>temporal KG]
        REP[replay-rag<br/>reasoning trace store]
        COR[corroborate<br/>answer grounding]
        CHA[chaffer<br/>RAG lint]
        STA[staleness<br/>freshness linter]
        REL[relapse<br/>self-correcting caller]
        MLG[dash-mlguard<br/>ML pipeline lint]
    end

    subgraph Retrieval["Retrieval platforms"]
        LEX[Lex-Rag<br/>hybrid+rerank+agent+GraphRAG]
        SEN[Sentinel<br/>citation-gated proxy]
        CDX[Codex-Prime<br/>codebase memory / MCP]
    end

    subgraph Apps["Applications"]
        TWIN[Twin<br/>voice-mimic PWA]
        RED[Redoubt<br/>prompt-injection scanner]
        DBI[Deathbed-Interview<br/>grounded conversation]
        IDC[IndicEval<br/>Indic LLM benchmark]
        CVS[CVS<br/>claim verification]
    end

    PAL --> TWIN
    CHR --> TWIN
    REP --> TWIN
    COR --> TWIN
    CHA --> TWIN
    COR --> SEN
    CHR --> CDX
    LEX --> IDC

    classDef primitive fill:#8957e5,stroke:#a371f7,color:#fff
    classDef platform fill:#1f6feb,stroke:#58a6ff,color:#fff
    classDef app fill:#238636,stroke:#3fb950,color:#fff
    class PAL,CHR,REP,COR,CHA,STA,REL,MLG primitive
    class LEX,SEN,CDX platform
    class TWIN,RED,DBI,IDC,CVS app
```

## The stack I default to

```mermaid
flowchart LR
    subgraph FE[Frontend]
        NX[Next.js App Router]
        PWA[PWA / Service Worker]
    end
    subgraph BE[Backend]
        API[Route Handlers]
        SID[Python Sidecar<br/>FastAPI]
    end
    subgraph Data[Data]
        PG[(Postgres / Neon)]
        VEC[(sqlite-vec / pgvector)]
        POC[(PocketBase)]
    end
    subgraph LLM[LLM Layer]
        BED[AWS Bedrock<br/>Opus 4.7]
        MCP[MCP Servers]
    end

    NX --> API
    PWA --> API
    API --> SID
    SID --> VEC
    API --> PG
    API --> POC
    API --> BED
    SID --> BED
    BED --> MCP

    classDef fe fill:#0969da,stroke:#58a6ff,color:#fff
    classDef be fill:#1f883d,stroke:#3fb950,color:#fff
    classDef data fill:#9a6700,stroke:#d29922,color:#fff
    classDef llm fill:#a475f9,stroke:#c297ff,color:#fff
    class NX,PWA fe
    class API,SID be
    class PG,VEC,POC data
    class BED,MCP llm
```

## How I split my time

```mermaid
flowchart LR
    A[Asmit] --> B[Design<br/>~50%]
    A --> C[Build<br/>~35%]
    A --> D[Write<br/>~15%]
    B --> B1[System diagrams]
    B --> B2[Data / retrieval flows]
    B --> B3[Team direction]
    C --> C1[Libraries]
    C --> C2[Applied projects]
    D --> D1[Papers]
    D --> D2[Blog / notes]

    classDef root fill:#0d1117,stroke:#58a6ff,color:#c9d1d9
    classDef leaf fill:#161b22,stroke:#30363d,color:#8b949e
    class A,B,C,D root
    class B1,B2,B3,C1,C2,D1,D2 leaf
```

---

## Publications · [ORCID 0009-0003-4247-9312](https://orcid.org/0009-0003-4247-9312) · [Google Scholar](https://scholar.google.com/citations?user=tyKozHwAAAAJ&hl=en)

- A Survey on Retrieval-Augmented Generation (RAG) Models: Recent Advances and Challenges
- Multimodal Emotion Recognition using Hierarchical Contrastive Residual Cross-Attention Fusion
- Facial Landmark-Based Face Shape Classification: A Lightweight Approach for Real-Time Applications
- A Bayesian Network to Model the Influence of Energy Consumption on Greenhouse Gases in Italy

---

Portfolio [asmit-dash.vercel.app](https://asmit-dash.vercel.app) · [LinkedIn](https://www.linkedin.com/in/asmitdash/) · [Twitter](https://twitter.com/AsmitDash007) · [Instagram](https://www.instagram.com/asmittdashh/) · asmitdash44@gmail.com
