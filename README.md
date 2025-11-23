# oci-generative-ai-guide

---

flowchart TD
    A[LLMs]
    A --> B[Architectures]
    B --> B1[Transformer]
    B --> B2[Decoder-Only]
    B --> B3[Encoder-Decoder]
    B --> B4[Mixture-of-Experts]

    A --> C[Prompting]
    C --> C1[Zero-Shot]
    C --> C2[Few-Shot]
    C --> C3[Chain-of-Thought]
    C --> C4[RAG]

    A --> D[Training]
    D --> D1[Pretraining]
    D --> D2[Supervised Fine-Tuning]
    D --> D3[PEFT (LoRA, T-Few)]
    D --> D4[RLHF]

    A --> E[Hallucination]
    E --> E1[Causes]
    E --> E2[Mitigation]

    A --> F[LLM Applications]
    F --> F1[Chatbots]
    F --> F2[Agents]
    F --> F3[Document AI]
    F --> F4[Code Assistants]
    F --> F5[Search & Summarization]



```text

                          ┌───────────────────────────────────────────┐
                          │          Retrieval Augmented Generation   │
                          └───────────────────────────────────────────┘
                                         │
                                         │
        ┌────────────────────────────────┼────────────────────────────────┐
        │                                │                                │
        ▼                                ▼                                ▼
┌────────────────────┐        ┌───────────────────────┐       ┌────────────────────┐
│     Estrutura      │        │       Benefícios       │       │     LangChain      │
│ (Architecture)     │        │    (Step-by-Step)      │       │                    │
└────────────────────┘        └───────────────────────┘       └────────────────────┘
        │                                │                                │
        ▼                                │                                ▼
┌──────────────────────────────┐          │                ┌──────────────────────────┐
│ Generative AI Service (OCI) │          │                │       Components         │
│ + Oracle 23ai Vector Search │          │                └──────────────────────────┘
└──────────────────────────────┘          │                                │
                                         │                                ▼
                                         │                ┌──────────────────────────┐
                                         │                │         Prompts          │
                                         │                └──────────────────────────┘
                                         │                                │
                                         │                                ▼
                                         │                ┌──────────────────────────┐
                                         │                │          Chains          │
                                         │                └──────────────────────────┘
                                         │                                │
                                         │                                ▼
                                         │                ┌──────────────────────────┐
                                         │                │         Memory           │
                                         │                └──────────────────────────┘
                                         │                                │
                                         │                                ▼
                                         │                ┌──────────────────────────┐
                                         │                │ Oracle 23ai as Vector DB │
                                         │                └──────────────────────────┘


```

