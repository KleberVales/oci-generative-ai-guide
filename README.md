# oci-generative-ai-guide

---

```text

LLMs
  │
  ├──► Architectures
  │        │
  │        ├──► Transformer
  │        ├──► Decoder-Only
  │        ├──► Encoder-Decoder
  │        └──► Mixture-of-Experts (MoE)
  │
  ├──► Prompting
  │        │
  │        ├──► Zero-Shot
  │        ├──► Few-Shot
  │        ├──► Chain-of-Thought
  │        └──► Retrieval-Augmented Generation (RAG)
  │
  ├──► Training
  │        │
  │        ├──► Pretraining
  │        ├──► Supervised Fine-Tuning (SFT)
  │        ├──► PEFT (LoRA, T-Few)
  │        └──► RLHF
  │
  ├──► Hallucination
  │        │
  │        ├──► Causes
  │        └──► Mitigation (RAG, Guardrails, Model Constraints)
  │
  └──► LLM Applications
           │
           ├──► Chatbots
           ├──► Agents
           ├──► Document AI
           ├──► Code Assistants
           └──► Search & Summarization


```

---

OCI Generative AI  -->  Pre-Trained Foundational Models  |--> Flexible Fine-Tuning  -->  Dedicated AI Clusters  -->  Prompt Engineering  -->  Customize LLMs  --> OCI Generative AI Security


---

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

---

Oracle Generative AI Agent   -->  O que é o Serviço de Agentes?  -->  Arquitetura do Sistema  -->  conceitos centrais  -->  Data Source  -->  Criação de Agentes  -->  Session and Management Features

--- 

