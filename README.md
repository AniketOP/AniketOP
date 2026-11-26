<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" width="100%" alt="Aniket Kumar, AI engineer. I build LLM systems that answer from real data, then evaluate them until they hold up.">
</picture>

**I build LLM systems that answer from real data, then evaluate them until they hold up.** Retrieval that cites its sources, agents that stay inside their guardrails, and the Python and Java backends that keep both fast.

At **Amdocs** my LangGraph agents cut a 4-hour security compliance audit to 35 minutes. At **Vogueish** I shipped production RAG to 5,000+ users with responses under 200 ms.

**→ [aniketop.github.io](https://aniketop.github.io)**: ask my résumé a question. It answers only from what's on it, with citations, and says so when it doesn't know.

## How I work

- **Grounding first.** An answer should point at the chunk it came from, and refuse when retrieval comes back empty. Prompt tweaks come after retrieval quality, not before.
- **Evaluate against real tasks.** I review model output the way a user would hit it: wrong but confident answers, invented numbers, missing context, tool calls that wander. A demo that works once isn't a result.
- **Agents with guardrails.** Explicit graphs, typed tool calls and human checkpoints. An agent auditing production servers should be boring and predictable.
- **Latency is part of correctness.** Async Python, caching and lean services. 180 ms and 800 ms are different products.

## Projects

| Project | What it does | Built with |
| --- | --- | --- |
| [**Echo-RAG**](https://github.com/AniketOP/Echo-RAG) | Chat with your own PDFs: upload, chunk, embed and query without restarting, with answers grounded in the retrieved passages. **Start here for RAG.** | LangChain · FAISS · Llama 3 / Mistral on Groq · Streamlit |
| [**MeetAI**](https://github.com/AniketOP/MeetAI-The-Intelligent-Meeting-Platform) | Video meetings where AI agents join the call; every meeting gets a transcript, a summary and Q&A afterwards. | Next.js 15 · Stream Video & Chat · OpenAI · Inngest |
| [**WebhookRelay**](https://github.com/AniketOP/Webhook-Relay) | Fault-tolerant webhook delivery: exponential backoff, `SKIP LOCKED` retry pollers, circuit breakers, a dead-letter queue with replay, HMAC-signed payloads. | Java 21 · Spring Boot · Kafka · PostgreSQL |
| [**Multi-tenant billing**](https://github.com/AniketOP/Multi-Tenant-Billing-Platform) | Billing for housing societies with three layers of tenant isolation, Kafka-driven invoicing and 100 automated tests. | Java 21 · Spring Boot · Couchbase · React |
| [**Return-risk model**](https://github.com/AniketOP/Hackathon_HCL_ALVERSE) | Hackathon classifier that flags e-commerce returns before they ship, judged on recall and ROC-AUC rather than accuracy. | Python · XGBoost · Streamlit |
| [**This portfolio**](https://github.com/AniketOP/AniketOP.github.io) | BM25 retrieval over my résumé in the browser, with spelling correction, cited answers and refusals. No API calls. | HTML · CSS · JavaScript |

## Experience

- **Software Engineer Intern, Amdocs** · Feb–Jun 2026 · LangGraph and Azure OpenAI compliance agents, Java/Spring Boot services, Kubernetes and Jenkins
- **ML / Backend Developer Intern, Vogueish** · May–Jul 2025 · production RAG with LangChain and Gemini, async Python APIs at 99.9% uptime
- **B.Tech, Computer Engineering, Delhi Technological University** · 2022–2026

**Stack:** Python, Java, TypeScript, SQL · LangChain, LangGraph, Azure OpenAI, vector databases · FastAPI, Spring Boot · PostgreSQL, Redis, Kafka · Docker, Kubernetes, Jenkins

## Next

Planned, not started yet: open-source tooling for evaluating RAG pipelines and agents, covering retrieval quality, citation faithfulness and suites of known failure cases. I'll link it here when there's code to read.

## Get in touch

Open to full-time AI engineering roles, on-site or hybrid. The fastest route is **[aniketsinghkumar11@gmail.com](mailto:aniketsinghkumar11@gmail.com)**.

Elsewhere: [Portfolio](https://aniketop.github.io) · [LinkedIn](https://www.linkedin.com/in/aniket-k-13287a256)

<!--
  Owner: Aniket. Last reviewed: 2026-11-27.
  Review when: a new project ships, the "Next" project gets its first commit, a role changes, or a job search starts or ends.
-->
