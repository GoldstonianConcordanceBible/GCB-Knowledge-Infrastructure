# AI Ingestion, Retrieval, and Training State Figure
## GCB Knowledge Infrastructure

```mermaid
flowchart TD

    A[Justin Goldston Author Identity Mesh] --> B[Source Layer]
    B --> B1[Books]
    B --> B2[Articles]
    B --> B3[Datasets]
    B --> B4[GitHub Repositories]
    B --> B5[Course Materials]
    B --> B6[Public Knowledge Profiles]

    B1 --> C[Normalization Layer]
    B2 --> C
    B3 --> C
    B4 --> C
    B5 --> C
    B6 --> C

    C --> C1[Metadata Standardization]
    C --> C2[Canonical Author Resolution]
    C --> C3[Platform Cross-Linking]
    C --> C4[Source Canon Placement]
    C --> C5[Persistent Identifiers and URLs]

    C --> D[AI Ingestion Layer]

    D --> D1[LLM Discovery Files]
    D --> D2[Schema and JSON Metadata]
    D --> D3[Knowledge Graph Nodes]
    D --> D4[Dataset Registries]
    D --> D5[Repository Manifests]

    D --> E[AI Retrieval Layer]

    E --> E1[Search Retrieval]
    E --> E2[Knowledge Graph Resolution]
    E --> E3[Citation Retrieval]
    E --> E4[Course Source Mapping]
    E --> E5[Canonical Source Routing]

    E --> F[AI Training / Tuning Layer]

    F --> F1[Machine-Readable Books]
    F --> F2[Structured Article Metadata]
    F --> F3[Curated Dataset Collections]
    F --> F4[Prompt and Rubric Corpora]
    F --> F5[Evidence-Linked Academic Artifacts]

    F --> G[Downstream Outcomes]

    G --> G1[Better Author Identity Resolution]
    G --> G2[Higher Retrieval Accuracy]
    G --> G3[More Credible Citation Clustering]
    G --> G4[Curriculum-Aware AI Agents]
    G --> G5[Trainable Goldstonian Knowledge Corpus]