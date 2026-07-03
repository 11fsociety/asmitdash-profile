# Asmit Dash

AI Systems Architect Intern @ Deloitte. I think in diagrams before I think in code.

## How I split my work

```mermaid
flowchart LR
    A[Asmit] --> B[Design]
    A --> C[Build]
    A --> D[Teach]

    B --> B1[System diagrams]
    B --> B2[Data / retrieval flows]
    B --> B3[Agent orchestration]

    C --> C1[LLM apps]
    C --> C2[Eval pipelines]
    C --> C3[Infra glue]

    D --> D1[Blog posts]
    D --> D2[Team enablement]

    classDef root fill:#0d1117,stroke:#58a6ff,color:#c9d1d9
    classDef leaf fill:#161b22,stroke:#30363d,color:#8b949e
    class A root
    class B,C,D root
    class B1,B2,B3,C1,C2,C3,D1,D2 leaf
```

## How my current projects relate

```mermaid
flowchart TB
    LLMG[LLM Gateway<br/>Bedrock proxy] --> INDIC[IndicEval<br/>Indian-context benchmark]
    LLMG --> LEX[Lex-Rag<br/>advanced RAG platform]
    LEX --> JOLLY[Jolly<br/>CA / Lawyer vertical]
    LLMG --> SOP[SOP Maker<br/>multi-agent generator]
    LLMG --> TWIN[Twin<br/>digital-twin PWA]

    classDef infra fill:#1f6feb,stroke:#58a6ff,color:#ffffff
    classDef app fill:#238636,stroke:#3fb950,color:#ffffff
    classDef vertical fill:#8957e5,stroke:#a371f7,color:#ffffff
    class LLMG infra
    class INDIC,SOP,TWIN,LEX app
    class JOLLY vertical
```

## The stack I default to

```mermaid
flowchart LR
    subgraph Frontend
        NX[Next.js<br/>App Router]
    end
    subgraph Backend
        API[Route Handlers /<br/>Server Actions]
        DR[Drizzle ORM]
    end
    subgraph Data
        PG[(Postgres /<br/>Neon)]
        VEC[(sqlite-vec /<br/>pgvector)]
    end
    subgraph LLM
        BED[AWS Bedrock<br/>Opus 4.7]
    end

    NX --> API --> DR --> PG
    API --> BED
    API --> VEC

    classDef fe fill:#0969da,stroke:#58a6ff,color:#fff
    classDef be fill:#1f883d,stroke:#3fb950,color:#fff
    classDef data fill:#9a6700,stroke:#d29922,color:#fff
    classDef llm fill:#a475f9,stroke:#c297ff,color:#fff
    class NX fe
    class API,DR be
    class PG,VEC data
    class BED llm
```

## Contact

- LinkedIn — [asmitdash](https://www.linkedin.com/in/asmitdash)
- Twitter — [@AsmitDash007](https://twitter.com/AsmitDash007)
- Email — asmitdash44@gmail.com
