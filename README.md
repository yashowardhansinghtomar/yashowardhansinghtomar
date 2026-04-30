# Yashowardhan Singh Tomar

**AI Engineer focused on LLM evaluation, RAG quality, voice AI, and applied AI systems**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-yashowardhansinghtomar-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yashowardhansinghtomar)
[![Email](https://img.shields.io/badge/Email-yashtomar10122%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:yashtomar10122@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-yashowardhansinghtomar.github.io-111827?style=flat-square&logo=githubpages&logoColor=white)](https://yashowardhansinghtomar.github.io/)

I work on practical AI systems where model behavior has to be measured: evaluation rubrics, prompt test sets, retrieval workflows, voice-agent pipelines, and local LLM applications.

My background combines hands-on LLM evaluation work, production voice AI integration, and business-facing product experience. I care about the gap between a demo and a workflow that remains useful when prompts, users, documents, and edge cases get messy.

## Current Focus

- LLM evaluation, RLHF workflows, pairwise response review, and rubric design
- RAG evaluation: retrieval recall, citation behavior, groundedness, and required-fact coverage
- Voice AI systems using STT, TTS, LLMs, conversational routing, and scenario testing
- Local AI apps using Ollama, LangChain, FAISS, Streamlit, and Gradio

## Public Proof Points

| Area | Evidence |
| --- | --- |
| LLM evaluation | [llm-evaluation-lab](https://github.com/yashowardhansinghtomar/llm-evaluation-lab) includes configurable rubrics, JSONL validation, computed-vs-human preference checks, optional multi-annotator agreement, disagreement cases, CI, and generated [Markdown reports](https://github.com/yashowardhansinghtomar/llm-evaluation-lab/blob/main/reports/sample_report.md). |
| RAG quality | [rag-evaluation-workbench](https://github.com/yashowardhansinghtomar/rag-evaluation-workbench) compares BM25, keyword, and hybrid retrievers with top-source checks, retrieval recall@k, groundedness metrics, failure tags, and a generated [retriever comparison report](https://github.com/yashowardhansinghtomar/rag-evaluation-workbench/blob/main/reports/retriever_comparison.md). |
| Voice-agent reliability | [voice-ai-agent-demo](https://github.com/yashowardhansinghtomar/voice-ai-agent-demo) models provider boundaries, latency tracing, silence timeout, low-confidence transcript clarification, barge-in handling, emergency escalation, batch scenarios, and generated [batch reports](https://github.com/yashowardhansinghtomar/voice-ai-agent-demo/blob/main/reports/batch_report.md). |

## Selected Public Work

| Project | What it demonstrates | Stack |
| --- | --- | --- |
| [llm-evaluation-lab](https://github.com/yashowardhansinghtomar/llm-evaluation-lab) | Config-driven LLM evaluation workbench with pairwise scoring, RLHF-style rubrics, dataset validation, multi-annotator agreement, disagreement analysis, CI, and Markdown/JSON reports | Python |
| [rag-evaluation-workbench](https://github.com/yashowardhansinghtomar/rag-evaluation-workbench) | RAG evaluation workbench for retrieval recall, citation coverage, required-fact coverage, groundedness checks, retriever comparison, top-source ranking, and failure tags | Python |
| [voice-ai-agent-demo](https://github.com/yashowardhansinghtomar/voice-ai-agent-demo) | Voice-agent framework with provider adapters, streaming-style artifacts, p50/p95 latency traces, silence timeout, low-confidence clarification, barge-in simulation, and batch reports | Python |
| [real_estate_chatbot_ollama](https://github.com/yashowardhansinghtomar/real_estate_chatbot_ollama) | Offline multi-agent real estate assistant with image routing, legal FAQ retrieval, and local LLM execution | Python, Gradio, LangChain, FAISS, Ollama |
| [PDF-Question-Answering-System](https://github.com/yashowardhansinghtomar/PDF-Question-Answering-System) | PDF ingestion, chunking, vector retrieval, and grounded question answering | Streamlit, LangChain, FAISS, Groq |
| [Text-to-SQL-model](https://github.com/yashowardhansinghtomar/Text-to-SQL-model) | Natural-language to SQL prototype with local LLM generation and read-only query guardrails | Streamlit, Ollama, MySQL |
| [Groq-chat-bot](https://github.com/yashowardhansinghtomar/Groq-chat-bot) | Lightweight Gradio interface for testing system/user prompt behavior with Groq chat models | Python, Gradio, Groq |

## Evaluation And RLHF Work

I have worked on LLM response evaluation workflows involving:

- Single-turn and multi-turn prompt design
- Side-by-side response comparison
- Rubric-based scoring for correctness, instruction following, reasoning, and clarity
- Ground-truth corrections and preference judgments
- Failure-mode analysis for coding and data-science prompts

The public [llm-evaluation-lab](https://github.com/yashowardhansinghtomar/llm-evaluation-lab) repo is a reusable version of this style of work, with configurable rubrics, dataset validation, scoring, annotator agreement checks, disagreement review signals, and generated reports.

## RAG Evaluation Work

I build retrieval workflows with attention to evidence quality, citation behavior, and answer grounding. The public [rag-evaluation-workbench](https://github.com/yashowardhansinghtomar/rag-evaluation-workbench) repo evaluates RAG outputs for retrieval recall, citation precision and recall, required-fact coverage, grounded answer rate, retriever comparisons, and failure-mode tags.

## Voice AI And Applied Systems

I have integrated TTS and STT models into a production AI calling workflow and continue to build small public prototypes around:

- Speech-to-text and text-to-speech pipelines
- Conversational routing
- Retrieval-backed assistants
- Local-first LLM applications

The public [voice-ai-agent-demo](https://github.com/yashowardhansinghtomar/voice-ai-agent-demo) repo shows this as a testable local framework with replaceable STT, assistant, and TTS provider boundaries, streaming-style artifacts, latency tracing, realistic edge cases, and batch scenario reports.

## Tooling

| Area | Tools |
| --- | --- |
| LLM apps | LangChain, OpenAI API, Groq, Ollama |
| Evaluation | Pairwise rubrics, prompt test sets, annotator agreement, failure tagging |
| Retrieval | FAISS, embeddings, document chunking, retriever comparison, citation checks |
| Interfaces | Streamlit, Gradio |
| Voice AI | STT/TTS integration, provider boundaries, latency tracing, transcription workflows |
| Core language | Python |

## Contact

- LinkedIn: [linkedin.com/in/yashowardhansinghtomar](https://www.linkedin.com/in/yashowardhansinghtomar)
- Email: [yashtomar10122@gmail.com](mailto:yashtomar10122@gmail.com)
