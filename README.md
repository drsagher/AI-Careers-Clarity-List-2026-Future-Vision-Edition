# AI Careers Clarity List 2026 — Future Vision Edition

> **Verified, Corrected & Future-Vision Edition**  
> Original compilation: **Abubakar Siddique**  
> AI Engineer | SaaS Builder | Full-Stack Developer (Next.js, Python, LLM Agents) | MSCS Computer Networks  
> Helping US, UK, DE startups build AI-powered SaaS | 15+ Yrs Exp  
> Verified and future-vision edition revised **14 October 2026**

---

## Table of Contents

1. [Objective, Scope and How to Read This List](#1-objective-scope-and-how-to-read-this-list)
2. [What the Evidence Says (Market Summary)](#2-what-the-evidence-says-market-summary)
3. [What We Corrected from the Previous List](#3-what-we-corrected-from-the-previous-list)
4. [Career Map at a Glance and Path Chooser](#4-career-map-at-a-glance-and-path-chooser)
5. [Career 1: AI/ML Engineer](#career-1-aiml-engineer)
6. [Career 2: GenAI Engineer](#career-2-genai-engineer)
7. [Career 3: MLOps / LLMOps Engineer](#career-3-mlops--llmops-engineer)
8. [Career 4: AI Research Scientist](#career-4-ai-research-scientist)
9. [Career 5: Agentic AI Engineer](#career-5-agentic-ai-engineer)
10. [Career 6: Data Scientist](#career-6-data-scientist)
11. [Career 7: ML Engineer](#career-7-ml-engineer)
12. [Emerging Adjacent Careers](#12-emerging-adjacent-careers)
13. [Cross-Career Foundations](#13-cross-career-foundations)
14. [Future Vision 2026 to 2030](#14-future-vision-2026-to-2030)
15. [Regional Lens: Pakistan and Emerging Markets](#15-regional-lens-pakistan-and-emerging-markets)
16. [12-Month Roadmap and Portfolio Rules](#1612-month-roadmap-and-portfolio-rules)
17. [Keeping This List Current](#17-keeping-this-list-current)
18. [Sources and Verification Notes](#18-sources-and-verification-notes)
19. [Master Learning Links](#19-master-learning-links)

---

## 1. Objective, Scope and How to Read This List

This document gives a verified, up-to-date clarity map of seven core AI career paths in 2026: **AI/ML Engineer, GenAI Engineer, MLOps/LLMOps Engineer, AI Research Scientist, Agentic AI Engineer, Data Scientist and ML Engineer**. It corrects common misconceptions from scattered roadmaps, separates tools from platforms and concepts, and gives official learning links for each technology. Its goal is to help students and career-changers pick the right track, avoid learning outdated tools, and follow a focused, industry-aligned path for building real AI products.

This edition goes further than a tool list. It adds market evidence from labour-market and statistics bodies, flags tools that have been retired or demoted, adds the tools practitioners now use, and offers a realistic view of where each career is heading to 2030.

### How to Read the Tables

| Label | Meaning |
|-------|---------|
| **Core** | Learn first. Almost every employer in this track expects it. |
| **Recommended** | Learn after the core. Strongly valued and common in job descriptions. |
| **Optional** | Situational. Learn if your target employer or project needs it. |
| **Watch** | Emerging. Follow it, but do not build your plan around it yet. |
| **Kept / Updated / New** | Kept = unchanged from the previous list. Updated = link or guidance changed. New = added in this edition. New rows are shaded green, Updated rows amber. |
| **[S1], [S2] ...** | Source references. Full details are in Section 18. Statements marked 'our outlook' are editorial judgement, not sourced fact. |

### Where Industry Meets Education

**MVIT** represents a unique fusion of software development expertise and educational innovation. We operate at the intersection of industry demands and academic excellence, creating a powerful ecosystem for technology advancement and career development.

- **Industry-Driven Development:** Our software division delivers enterprise solutions while informing our curriculum with real-world challenges and emerging technologies.
- **Career-Focused Education:** Certification programs designed by industry experts to ensure graduates are job-ready with the most in-demand skills.

---

## 2. What the Evidence Says (Market Summary)

Seven findings frame the rest of this document. Each is drawn from a named source in Section 18; where a figure comes from a secondary summary rather than the original report, Section 18 says so.

| Finding | Evidence (paraphrased) | Source |
|---------|------------------------|--------|
| 1. AI engineering is the fastest-growing US job family | LinkedIn's Jobs on the Rise 2026 ranks AI engineer first, AI consultant/strategist second and AI/ML researcher fifth. | [S1] |
| 2. AI skills carry a growing pay premium | PwC analysed over one billion job ads in 27 countries: jobs requiring AI skills grew 69% against 9% for all jobs, and the average wage premium reached 62% (57% a year earlier). | [S2] |
| 3. Jobs are created and displaced at scale | The WEF expects 170 million jobs created and 92 million displaced by 2030 (net +78 million). Big-data specialists, fintech engineers and AI/ML specialists lead percentage growth. | [S3] |
| 4. The entry-level door is narrowing | Stanford found a 13% relative employment decline for 22 to 25 year-olds in the most AI-exposed occupations since late 2022. PwC finds AI-exposed junior roles are seven times more likely to demand traditionally senior skills. Pakistani press reports junior tech hiring down about 25%. | [S4] [S2] [S16] |
| 5. Data science stays strong in official statistics | US BLS projects 34% growth for data scientists from 2024 to 2034, median pay of $112,590 (May 2024) and about 23,400 openings a year. | [S5] |
| 6. Agentic AI is real but over-hyped in places | Gartner expects over 40% of agentic AI projects to be cancelled by end-2027, yet one third of enterprise software to include agentic AI by 2028. | [S6] |
| 7. Tools churn faster than careers | In roughly 15 months AutoGen, Papers with Code, OpenAI fine-tuning, the Assistants API, Agent Builder, hosted Evals and the LangChain 0.x line all changed status, and TorchServe is no longer maintained (Section 3). | [S7]-[S12] |

### What This Means for a Learner

- **Learn concepts first, tools second.** Retrieval, evaluation, serving, security and experimentation outlast any framework.
- **Prove skill with deployed, measured projects.** The entry-level data above says employers want evidence of senior-style judgement early.
- **Pair AI fluency with domain depth.** PwC's findings and the WEF skills outlook both reward the combination, not tool knowledge alone.

---

## 3. What We Corrected from the Previous List

The previous list was mostly sound but contained items that have since been retired, demoted or superseded. These corrections matter because learners follow the links they are given.

### 3.1 Removed or Replaced

| Item | Career | What Happened | Replaced By |
|------|--------|---------------|-------------|
| AutoGen | Agentic | Microsoft put the repository into maintenance mode (bug and security fixes only) and directs new projects to Microsoft Agent Framework, which reached 1.0 in early April 2026 [S7]. | Microsoft Agent Framework, LangGraph, OpenAI Agents SDK, Google ADK |
| TorchServe | MLOps | Official docs state the project is no longer actively maintained and security patches are not planned [S10]. | vLLM, KServe, BentoML, Ray Serve |
| Papers with Code | Research | Shut down in July 2025; the address redirects to Hugging Face's Trending Papers [S11]. | Hugging Face Papers, arXiv, OpenReview |
| OpenAI fine-tuning guide | GenAI | OpenAI is winding down its self-serve fine-tuning platform; it was closed to new users from May 2026 [S9]. | Hugging Face PEFT and TRL, Unsloth |
| W3Schools SQL | Data Scientist | A general tutorial site, not an official or authoritative learning source. | PostgreSQL docs, SQLBolt |
| Optimizely A/B blog | Data Scientist | Vendor marketing content rather than a learning resource. | Kohavi et al. experimentation text |
| AutoGen docs as 'multi-agent' link | Agentic | Pointed to a maintenance-mode project. | Anthropic multi-agent engineering write-up |
| TensorFlow as core tool | ML Engineer | Still maintained and used, but PyTorch leads new work and Google's investment has shifted to JAX [S21]. | Demoted to Optional; PyTorch stays Core |

### 3.2 Updated Links and Guidance

| Item | Change |
|------|--------|
| LangChain, LangGraph, LangSmith links | LangChain and LangGraph reached stable 1.0 with a redesigned docs site (docs.langchain.com). Older 0.3/0.4 releases are in maintenance until December 2026 [S12]. |
| OpenAI LLM API guidance | The Assistants API was scheduled to shut down on 26 August 2026; the Responses API is the recommended base [S8]. Agent Builder and the hosted Evals platform are scheduled to close on 30 November 2026, with evals read-only from 31 October [S8]. |
| 'Agentic AI Engineer (2026 Hottest Role)' | Re-labelled as a fast-growing specialisation. Evidence supports strong demand for agent skills but not a separately ranked job title, and Gartner warns of high project cancellation rates [S6]. |
| MLflow and DVC | MLflow now also covers GenAI tracing and evaluation. DVC moved from core to optional because data versioning has several alternatives. |
| Vector databases | Original named only Pinecone and Chroma. Added pgvector (sensible first choice for many teams) and Qdrant; stressed that retrieval quality depends on chunking, embeddings and reranking [S19]. |
| Role names | 'MLOps Engineer' is now 'MLOps / LLMOps Engineer' because LLM serving and tracing are part of the job. |

**Also added:** evaluation and observability tools (Langfuse, Promptfoo, Ragas, DeepEval, OpenTelemetry), security references (OWASP Top 10 for LLM and Agentic applications), protocols (A2A), inference tooling (vLLM, KServe), data tools (Polars, dbt, XGBoost/LightGBM, SHAP), and cross-career foundations.

---

## 4. Career Map at a Glance and Path Chooser

Ratings below are an editorial assessment to help comparison, not measured data.

| Career | Core Question | Main Output | Maths | Software | Typical Entry |
|--------|---------------|-------------|-------|----------|---------------|
| **AI/ML Engineer** | How do I ship an AI feature reliably? | Deployed AI services and APIs | Medium | High | Software developer or ML graduate |
| **GenAI Engineer** | How do I make an LLM app accurate, safe and affordable? | RAG apps, copilots, eval suites | Low-Med | High | Web or backend developer |
| **MLOps / LLMOps** | How do I keep models running, observable and cheap? | Pipelines, platforms, monitoring | Low | High (infra) | DevOps, SRE or backend engineer |
| **AI Research Scientist** | What new method works, and why? | Papers, novel models, open source | High | Medium | MS/PhD or strong research record |
| **Agentic AI Engineer** | How do I let AI act safely on tools and data? | Governed agents, tool/MCP servers | Low-Med | High | Backend or AI engineer |
| **Data Scientist** | What does the data say and what should we do? | Analyses, experiments, models, dashboards | Medium | Medium | Statistics, analytics or CS background |
| **ML Engineer** | How do I train and optimise a model that performs? | Trained, evaluated, optimised models | Medium | High | CS or engineering graduate |

### Which Path Fits You?

| If you enjoy... | Consider |
|-----------------|----------|
| Building products and APIs that users touch | AI/ML Engineer or GenAI Engineer |
| Infrastructure, automation and making things reliable | MLOps / LLMOps Engineer |
| Mathematics, proofs and new ideas | AI Research Scientist |
| Designing autonomous workflows and thinking about failure modes | Agentic AI Engineer (with strong security awareness) |
| Experiments, statistics and explaining findings | Data Scientist |
| Making models faster, smaller and more accurate | ML Engineer |
| Not sure yet | Spend three months on the shared core (Python, SQL, Git, Docker, one LLM API, one evaluation). It applies to all seven careers. |

---

## Career 1: AI/ML Engineer

**Builds and ships AI-powered features and services**

### The Role in Brief

The generalist who turns models into products. LinkedIn's Jobs on the Rise 2026 ranks AI engineer first [S1]. In practice the title stretches from calling model APIs to training models, so always read the job description, not just the title.

**Typical titles:** AI Engineer, Applied AI Engineer, LLM Application Engineer, Machine Learning Engineer (applied)

### 2026 Reality Check

Routine integration work is increasingly handled with AI coding assistants. What employers still struggle to find is the engineer who can evaluate an AI feature, keep it reliable, control its cost and explain its failures. PwC finds that AI-exposed junior roles now ask for skills once expected of seniors [S2], so a deployed, measured project counts for more than a certificate.

### Tools, Platforms and Concepts

| Tool / Platform / Concept | Priority | Change | What to Know in 2026 | Official Learn Link |
|---------------------------|----------|--------|----------------------|---------------------|
| Python | Core | Kept | Foundation for every track. Add type hints, async I/O and pytest. | docs.python.org/3/tutorial |
| uv (Python packaging) | Recommended | New | Fast, modern tool for environments and dependencies; reproducible setups matter in teams. | docs.astral.sh/uv |
| SQL and PostgreSQL | Core | New | Most AI products still sit on relational data, and Postgres also unlocks pgvector. | postgresql.org/docs/current/tutorial.html |
| Git and GitHub | Core | New | Version control and pull-request workflow are expected from day one. | git-scm.com/doc |
| PyTorch | Core | Kept | Default framework for new models and most research. Learn tensors, autograd and training loops. | pytorch.org/tutorials |
| Hugging Face | Core | Kept | Hub, Transformers, Datasets, PEFT and TRL cover most open-model work. | huggingface.co/learn |
| LLM APIs (OpenAI, Anthropic, Gemini) | Core | Updated | OpenAI's Assistants API was scheduled to shut down on 26 Aug 2026 [S8]; build on the Responses API and avoid old tutorials. Learn two providers to avoid lock-in. | platform.openai.com/docs, docs.claude.com, ai.google.dev/gemini-api/docs |
| Embeddings | Core | Updated | Learn embedding models, similarity search and how to compare them (MTEB). | platform.openai.com/docs/guides/embeddings, sbert.net, huggingface.co/spaces/mteb/leaderboard |
| RAG (concept) | Core | Updated | Production RAG = chunking + hybrid keyword/vector search + reranking + evaluation. Hybrid retrieval is widely reported as the biggest single quality gain [S19]. | docs.langchain.com/oss/python/langchain/rag |
| pgvector (vector search in Postgres) | Core | New | Practitioner guides suggest it as the sensible first choice up to roughly 10 million vectors [S19]. | github.com/pgvector/pgvector |
| Qdrant (vector database) | Recommended | New | Open-source engine known for fast filtered search; self-hostable. | qdrant.tech/documentation |
| Pinecone (vector database) | Optional | Kept | Fully managed; useful when you prefer not to operate infrastructure. | docs.pinecone.io |
| Chroma (vector database) | Optional | Kept | Quickest way to prototype locally; plan a move for production scale. | docs.trychroma.com |
| LangChain and LangGraph | Recommended | Updated | Both reached stable 1.0 (LTS). LangChain 0.3 and LangGraph 0.4 are maintenance-only until Dec 2026 [S12]; check tutorials against the 1.0 API. | docs.langchain.com |
| FastAPI | Core | Kept | Standard Python layer for serving models and AI endpoints. | fastapi.tiangolo.com/learn |
| Docker | Core | Kept | Package once, run anywhere; required for deployment work. | docs.docker.com/get-started |
| Evals and tracing (Langfuse, Promptfoo, Ragas) | Core | New | Treat evals as unit tests for AI behaviour and keep them in your repo. OpenAI's hosted Evals platform is scheduled to close on 30 Nov 2026 [S8]. | langfuse.com/docs, promptfoo.dev/docs/intro, docs.ragas.io |
| Cloud ML platform (pick one) | Recommended | New | Learn compute, storage, identity and one managed model service end to end. | cloud.google.com/vertex-ai/docs, docs.aws.amazon.com/bedrock, learn.microsoft.com/en-us/azure/ai-foundry |

### Future Vision 2026 to 2030

By 2030 expect this role to merge with general software engineering: a software engineer who ships and operates probabilistic systems. Differentiators will be evaluation, reliability, security, cost control and domain knowledge (our outlook, informed by [S1], [S2], [S6]).

### Proof-of-Skill Projects

- Production RAG app over a real document set: hybrid search, reranking, an evaluation suite and a trace dashboard.
- Fine-tuned small open model served behind FastAPI and Docker, with CI that runs your evals on every change.
- Cost, latency and quality comparison of two LLM providers on the same task, published as a short report.

---

## Career 2: GenAI Engineer

**Builds LLM-powered apps: chatbots, copilots, RAG systems**

### The Role in Brief

A specialisation of the AI engineer focused on language and multimodal models inside real products. A LinkedIn analysis cited by LATEAM reports transitions into generative-AI engineer roles rising roughly ninefold since 2021, from a small base [S23].

**Typical titles:** Generative AI Engineer, LLM Engineer, Conversational AI Engineer, AI Application Developer

### 2026 Reality Check

The work has moved from prompting a chatbot to engineering retrieval quality, evaluation, guardrails and cost. Practitioner guides stress that chunking, embeddings and reranking usually matter more than which vector database you pick [S19]. Fine-tuning has also shifted: OpenAI's self-serve fine-tuning platform closed to new users in May 2026 [S9], so the practical route is adapting open-weight models.

### Tools, Platforms and Concepts

| Tool / Platform / Concept | Priority | Change | What to Know in 2026 | Official Learn Link |
|---------------------------|----------|--------|----------------------|---------------------|
| LLM fundamentals (concept) | Core | Kept | Tokens, context windows, sampling, reasoning models and cost/latency trade-offs. | platform.openai.com/docs/models |
| Open-weight LLMs (Llama, Qwen, Mistral, Gemma) | Recommended | New | Models you can run and adapt yourself; matters for privacy, cost and local-language work. | huggingface.co/models, ollama.com |
| Prompt and context engineering | Core | Updated | Now a skill inside AI-engineer roles rather than a standalone career. Focus on what goes into the context window and why. | promptingguide.ai, anthropic.com/engineering/effective-context-engineering-for-ai-agents, docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview |
| LangChain | Recommended | Updated | The 1.0 release launched with a redesigned docs site; prefer docs.langchain.com and verify older tutorials. | docs.langchain.com |
| LlamaIndex | Recommended | New | Strong choice for retrieval-heavy, document-centric applications. | docs.llamaindex.ai |
| Hugging Face Transformers | Core | Kept | Load, run and adapt open models; the base for fine-tuning. | huggingface.co/docs/transformers |
| Retrieval stack (pgvector, Qdrant, Pinecone) | Core | Updated | Original listed only Pinecone's explainer. Start with what you already run (often Postgres); measure before adding a dedicated database [S19]. | pinecone.io/learn/retrieval-augmented-generation, github.com/pgvector/pgvector, qdrant.tech/documentation |
| FastAPI | Core | Kept | Serve your pipeline as a streaming API. | fastapi.tiangolo.com |
| Vercel AI SDK (TypeScript) | Optional | New | Toolkit for streaming chat interfaces and agents in Next.js and other TypeScript apps. | ai-sdk.dev |
| Fine-tuning open models (PEFT/LoRA, TRL) | Recommended | Updated | Try prompting and RAG first; fine-tune when you have a measured gap and good data. | huggingface.co/docs/peft, huggingface.co/docs/trl, docs.unsloth.ai |
| LLM evals | Core | Updated | Combine offline test sets, LLM-as-judge and human review. Tools: Promptfoo, Ragas, DeepEval, Langfuse [S20]. | promptfoo.dev/docs/intro, docs.ragas.io, deepeval.com/docs/getting-started |
| Observability and tracing | Core | New | Trace every prompt, tool call, token and cost. OpenTelemetry GenAI conventions are emerging as a vendor-neutral format [S20]. | langfuse.com/docs, phoenix.arize.com, opentelemetry.io/docs/specs/semconv/gen-ai |
| Guardrails and LLM security | Core | Updated | Guardrails AI (kept) plus the OWASP Top 10 for LLM Applications (2026 edition) for risks such as prompt injection [S15]. | guardrailsai.com/docs, genai.owasp.org, docs.nvidia.com/nemo/guardrails |
| MCP (Model Context Protocol) basics | Recommended | New | Open standard for connecting LLM apps to tools and data; now hosted by the Linux Foundation's Agentic AI Foundation [S13]. | modelcontextprotocol.io |
| Cloud AI platforms (Vertex AI, Bedrock, Azure AI Foundry) | Recommended | Updated | Pick one. Managed models, enterprise controls and compliance features. | cloud.google.com/vertex-ai/docs, docs.aws.amazon.com/bedrock, learn.microsoft.com/en-us/azure/ai-foundry |
| Local and self-hosted inference (Ollama, vLLM) | Optional | New | Run models locally to prototype, or privately at scale. | ollama.com, docs.vllm.ai |
| Responsible AI and regulation basics | Recommended | New | Know your transparency and risk duties if you serve EU users; NIST AI RMF is a widely used US framework. | digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai, nist.gov/itl/ai-risk-management-framework |

### Removed or Replaced in This Edition

- **OpenAI Fine-Tuning guide** (replaced by open-model fine-tuning with PEFT/TRL, because OpenAI closed self-serve fine-tuning to new users in May 2026 [S9]).

### Future Vision 2026 to 2030

Expect smaller specialised models, on-device and private deployments, voice and multimodal interfaces, and compliance as a design input: the EU AI Act's transparency duties (Article 50) have applied since 2 Aug 2026 [S14]. Builders who can show measured quality and safe behaviour will stand out (our outlook).

### Proof-of-Skill Projects

- Support copilot that answers with citations, refuses out-of-scope questions, and ships with an automated evaluation harness.
- Bilingual (Urdu/English) domain assistant with guardrails and a documented list of failure cases.
- LoRA fine-tune of a small open model compared honestly against a prompting-only baseline.

---

## Career 3: MLOps / LLMOps Engineer

**Deploys, scales, and monitors ML and LLM systems in production**

### The Role in Brief

The engineer who makes models run reliably, observably and affordably. MLOps and infrastructure roles feature among the fast-growing AI-related jobs in coverage of LinkedIn's 2026 ranking [S1]. The title now increasingly includes LLMOps: serving, tracing and evaluating language models.

**Typical titles:** MLOps Engineer, ML Platform Engineer, LLMOps Engineer, AI Infrastructure Engineer

### 2026 Reality Check

Serving is no longer only about classic models. For self-hosted LLMs, vLLM is described by project and practitioner sources as the most widely adopted open-source inference engine, with Kubernetes layers such as llm-d and KServe on top [S17]. One long-standing tool from the old list, TorchServe, is no longer maintained and should not be learned for new work [S10].

### Tools, Platforms and Concepts

| Tool / Platform / Concept | Priority | Change | What to Know in 2026 | Official Learn Link |
|---------------------------|----------|--------|----------------------|---------------------|
| Linux and shell | Core | Kept | Processes, permissions, networking and scripting; every production server speaks it. | linuxjourney.com |
| Git | Core | Kept | Branching, reviews and release tagging. | git-scm.com/doc |
| Docker | Core | Kept | Images, volumes, networking and image security basics. | docs.docker.com |
| Kubernetes | Core | Kept | Deployments, services, autoscaling and GPU scheduling basics. | kubernetes.io/docs/tutorials |
| CI/CD with GitHub Actions | Core | Kept | Automate tests, builds and deployments; add evaluation gates for AI changes. | docs.github.com/en/actions |
| Infrastructure as Code (Terraform / OpenTofu) | Recommended | New | Reproducible cloud environments. OpenTofu is an open-source fork of Terraform. | developer.hashicorp.com/terraform/tutorials, opentofu.org/docs |
| Cloud platform (AWS, GCP or Azure) | Core | New | Pick one: identity, networking, GPUs, registries and a managed ML service. | docs.aws.amazon.com/sagemaker, cloud.google.com/vertex-ai/docs |
| MLflow | Core | Updated | Experiment tracking and model registry; ecosystem also covers GenAI tracing and evaluation. | mlflow.org/docs/latest |
| DVC (data versioning) | Optional | Updated | Learn the concept first. Alternatives exist (lakehouse tables, object-store versioning); choose per team stack. | dvc.org/doc |
| Apache Airflow | Core | Kept | Standard workflow orchestrator for data and ML pipelines. | airflow.apache.org/docs |
| Prefect or Dagster | Optional | New | Modern Python-first orchestrators; useful alternatives to know. | docs.prefect.io, docs.dagster.io |
| BentoML (model serving) | Recommended | Updated | Packaging and serving for classic and LLM models. Replaces the BentoML/TorchServe pairing. | docs.bentoml.com |
| KServe | Recommended | New | Kubernetes-native model serving with autoscaling and versioning; can run vLLM. | kserve.github.io/website |
| vLLM (LLM serving) | Core | New | Most widely adopted open-source LLM serving engine; hosted by the PyTorch Foundation [S17]. | docs.vllm.ai |
| Ray Serve | Optional | New | Python-native scalable serving; often paired with vLLM. | docs.ray.io/en/latest/serve/index.html |
| llm-d | Watch | New | Kubernetes-native distributed inference stack built around vLLM; backed by several large vendors [S17]. | github.com/llm-d/llm-d |
| Evidently (model monitoring) | Recommended | Kept | Data drift, model quality and report generation. | docs.evidentlyai.com |
| Prometheus and Grafana | Core | New | Metrics, alerting and dashboards for latency, errors and GPU use. | prometheus.io/docs, grafana.com/docs |
| OpenTelemetry | Recommended | New | Vendor-neutral tracing and metrics; lowers the cost of switching tools. | opentelemetry.io/docs |
| LLM observability (Langfuse, Phoenix) | Recommended | New | Prompt, token, latency and cost tracing for LLM applications [S20]. | langfuse.com/docs, phoenix.arize.com |
| LiteLLM (LLM gateway) | Optional | New | One interface to many model providers with routing and budgets. | docs.litellm.ai |

### Removed or Replaced in This Edition

- **TorchServe:** its own documentation states the project is no longer actively maintained and security patches are not planned [S10]. Replaced by vLLM, KServe, BentoML and Ray Serve.

### Future Vision 2026 to 2030

Expect the role to absorb AgentOps and LLMOps: evaluation gates in CI, tracing, GPU scheduling, cost governance, policy-as-code and model supply-chain security. Engineers who can show cost per request and reliability numbers will be hard to replace (our outlook).

### Proof-of-Skill Projects

- CI/CD pipeline that retrains a model, logs it to a registry, runs tests and promotes with a canary release.
- Open LLM served with vLLM on Kubernetes with autoscaling, dashboards and a cost-per-1,000-requests report.
- Drift-monitoring report using Evidently with alert rules and a documented runbook.

---

## Career 4: AI Research Scientist

**Researches novel architectures and methods, and publishes papers**

### The Role in Brief

Invents and rigorously tests new methods. Researchers in AI and machine learning appear in LinkedIn's 2026 fastest-growing list [S1], but these roles are the most selective: they typically expect a postgraduate degree and a publication or open-source record (general hiring pattern).

**Typical titles:** AI Research Scientist, Research Engineer, Applied Scientist, Machine Learning Researcher

### 2026 Reality Check

Two resources in the old list had to change. Papers with Code shut down in July 2025 and now redirects to Hugging Face's Trending Papers [S11]. OpenAI's Spinning Up is an introductory 2018-era resource, so it is now paired with current courses. PyTorch dominates research code in 2026 comparisons, with sources putting its share of papers at roughly 80% or more [S21].

### Tools, Platforms and Concepts

| Tool / Platform / Concept | Priority | Change | What to Know in 2026 | Official Learn Link |
|---------------------------|----------|--------|----------------------|---------------------|
| Linear algebra, probability, optimisation | Core | Updated | Deep Learning Book (kept) plus a modern maths-for-ML text and MIT's linear algebra course. | deeplearningbook.org, mml-book.github.io, ocw.mit.edu/courses/18-06-linear-algebra-spring-2010 |
| Deep learning | Core | Updated | DeepLearning.AI (kept) plus Karpathy's build-from-scratch series for intuition. | deeplearning.ai, karpathy.ai/zero-to-hero.html |
| Language modelling from scratch | Recommended | New | Stanford CS336 covers building and training language models end to end. | cs336.stanford.edu |
| PyTorch | Core | Kept | Primary research framework; learn autograd, custom modules and profiling. | pytorch.org/docs/stable/index.html |
| JAX | Recommended | Kept | Strong for large-scale and TPU work; PyTorch remains more common in academic papers [S21]. | jax.readthedocs.io |
| Transformers | Core | Kept | Read the original paper and implement attention yourself. | huggingface.co/docs/transformers, arxiv.org/abs/1706.03762 |
| Reinforcement learning | Core | Updated | Classic RL plus RL-based post-training of language models. Spinning Up kept as an intro only. | huggingface.co/learn/deep-rl-course, incompleteideas.net/book/the-book-2nd.html, huggingface.co/docs/trl, spinningup.openai.com |
| Paper discovery and implementation | Core | Updated | Papers with Code is gone. Use Hugging Face Papers, arXiv, OpenReview and GitHub. | huggingface.co/papers/trending, arxiv.org, openreview.net |
| Experiment tracking (Weights & Biases, MLflow) | Recommended | New | Log every run so results are reproducible and comparable. | docs.wandb.ai, mlflow.org/docs/latest |
| Distributed training (FSDP, Accelerate, DeepSpeed) | Recommended | New | Needed once models or data outgrow one GPU. | pytorch.org/docs/stable/fsdp.html, huggingface.co/docs/accelerate, deepspeed.ai |
| Experiment design and statistics | Core | Updated | Replaces a personal homepage link with a full free statistics text. | stat.cmu.edu/~cshalizi/ADAfaEPoV |
| Evaluation and benchmarking | Recommended | New | Contamination, reproducibility and limits of LLM-as-judge; use a standard harness. | github.com/EleutherAI/lm-evaluation-harness |
| AI safety and interpretability | Recommended | New | Growing research area with open courses and fellowships. | bluedot.org, arena.education |
| Research writing | Core | Kept | Clear problem statements, honest limitations and strong figures. | cs.cmu.edu/~rsingh/advice-for-research, overleaf.com/learn |

### Removed or Replaced in This Edition

- **Papers with Code** (shut down July 2025; replaced by Hugging Face Papers, arXiv and OpenReview) [S11].

### Future Vision 2026 to 2030

Likely growth areas are post-training and reinforcement learning for reasoning, evaluation science, interpretability, efficient architectures and AI for science. Access to compute is the main gate, so open research communities and reproducible small-scale work are valuable entry points (our outlook).

### Proof-of-Skill Projects

- Reproduce a recent paper with ablations, then publish code and an honest report on what did and did not replicate.
- Implement a small transformer from scratch and train it on a public dataset with documented scaling experiments.
- Contribute a fix, benchmark or evaluation to an open-source research repository.

---

## Career 5: Agentic AI Engineer

**Builds autonomous agents that use tools, memory and collaborate**

### The Role in Brief

Designs systems where models plan, call tools and act with limited supervision. The original list called this the hottest role of 2026; the evidence supports strong growth in agent skills but not a standardised, separately ranked job title. Treat it as a specialisation of AI engineering.

**Typical titles:** Agentic AI Engineer, AI Agent Developer, AI Automation Engineer, Applied AI Engineer (agents)

### 2026 Reality Check

Enthusiasm and failure rates are both high. Gartner expects more than 40% of agentic AI projects to be cancelled by the end of 2027 because of cost, unclear value or weak risk controls, while still expecting a third of enterprise software to include agentic AI by 2028 [S6]. The winners will ship narrow, measurable and governed agents. Tooling is also consolidating: AutoGen is in maintenance mode, replaced by Microsoft Agent Framework [S7], and MCP and A2A now sit together under the Linux Foundation [S13].

### Tools, Platforms and Concepts

| Tool / Platform / Concept | Priority | Change | What to Know in 2026 | Official Learn Link |
|---------------------------|----------|--------|----------------------|---------------------|
| Agent design patterns (concept) | Core | New | Start with the simplest workflow that works; add autonomy only where it earns its cost. | anthropic.com/engineering/building-effective-agents |
| OpenAI Agents SDK | Core | Kept | Code-first SDK built on the Responses API; supports many model providers [S22]. | openai.github.io/openai-agents-python |
| LangGraph | Core | Updated | Stateful, auditable graphs with persistence; 1.0 is a long-term-support release [S12]. Docs moved to docs.langchain.com. | docs.langchain.com/oss/python/langgraph/overview |
| MCP (Model Context Protocol) | Core | Kept | Standard way to connect agents to tools and data; donated to the Linux Foundation's Agentic AI Foundation in Dec 2025 [S13]. | modelcontextprotocol.io |
| A2A (Agent2Agent protocol) | Recommended | New | Open standard for agents to discover and delegate to each other; v1.0 in 2026, joined the same foundation in Aug 2026 [S13]. | a2a-protocol.org |
| Microsoft Agent Framework | Recommended | New | Successor to AutoGen and Semantic Kernel; 1.0 released in early April 2026 for Python and .NET [S7]. | learn.microsoft.com/en-us/agent-framework |
| CrewAI | Recommended | Kept | Role-based multi-agent teams; fast to prototype. | docs.crewai.com |
| Google Agent Development Kit (ADK) | Recommended | New | Multi-language agent toolkit with A2A and MCP support; natural fit on Google Cloud [S18]. | google.github.io/adk-docs |
| Claude Agent SDK | Recommended | New | Agent loop with file, shell, MCP and sub-agent capabilities [S18]. | docs.claude.com/en/docs/agent-sdk/overview |
| Pydantic AI | Recommended | New | Type-safe Python agents with tool approval and OpenTelemetry support [S18]. | ai.pydantic.dev |
| Tool calling and structured outputs | Core | Kept | Reliable function calling, schemas and error handling are the heart of every agent. | platform.openai.com/docs/guides/function-calling |
| Agent memory | Core | Kept | Short-term state, long-term memory and what should never be stored. | docs.langchain.com/oss/python/langgraph/memory |
| Multi-agent systems (patterns) | Recommended | Updated | Replaces AutoGen docs link. Learn when multiple agents help and when they only add cost. | anthropic.com/engineering/multi-agent-research-system |
| Context engineering | Core | Updated | Curating what the model sees at each step; the 2026 successor to prompt tinkering. | philschmid.de/context-engineering, anthropic.com/engineering/effective-context-engineering-for-ai-agents |
| Agent evals and tracing | Core | Updated | LangSmith (kept) plus open options such as Langfuse and Phoenix. Test whole trajectories, not just final answers [S20]. | docs.langchain.com/langsmith/home, langfuse.com/docs, phoenix.arize.com |
| Guardrails and agent security | Core | Updated | CrewAI guardrails (kept) plus the OWASP Top 10 for Agentic Applications: goal hijacking, tool misuse, privilege abuse [S15]. | docs.crewai.com/concepts/guardrails, genai.owasp.org |
| Durable execution (Temporal) | Optional | New | Keeps long-running agent workflows alive through crashes and retries. | docs.temporal.io |
| Sandboxed code execution (E2B, Docker) | Optional | New | Run agent-written code in isolation, never on your host. | e2b.dev/docs, docs.docker.com |
| AGENTS.md convention | Optional | New | Plain-file instructions for coding agents; hosted by the same open foundation [S13]. | agents.md |

### Removed or Replaced in This Edition

- **AutoGen** (maintenance mode since Oct 2025; Microsoft directs new projects to Microsoft Agent Framework 1.0, released April 2026) [S7].
- The old **Multi-Agent Systems** link, which pointed to AutoGen docs (replaced by a current multi-agent engineering write-up).

### Future Vision 2026 to 2030

Expect standard protocols (MCP for tools, A2A for agent-to-agent), agent identity and least-privilege permissions, evaluation of long multi-step tasks, and human-approval designs to become baseline engineering. Security knowledge is a differentiator because agents widen the attack surface [S15] (our outlook).

### Proof-of-Skill Projects

- Tool-using assistant with its own MCP server, an evaluation set and a written list of what it must never do.
- LangGraph workflow with durable state and a human-approval step before any irreversible action.
- Threat model and red-team report for your own agent, mapped to the OWASP Agentic Top 10.

---

## Career 6: Data Scientist

**Turns data into decisions using statistics, experiments and models**

### The Role in Brief

The role sits between business and engineering: framing questions, designing experiments, building models and communicating findings. US BLS projects 34% growth for data scientists from 2024 to 2034, with a median wage of $112,590 in May 2024 and about 23,400 openings a year [S5]. The World Economic Forum also lists big-data specialists among the fastest-growing jobs to 2030 [S3].

**Typical titles:** Data Scientist, Decision Scientist, Product Data Scientist, Applied Scientist (analytics)

### 2026 Reality Check

Generative AI is automating routine analysis, so the valuable part of the job is shifting to framing the right question, designing experiments, causal reasoning, domain knowledge and persuading decision-makers. Two items in the old list were not authoritative learning sources: a general-purpose tutorial site for SQL and a vendor blog for A/B testing. Both are replaced.

### Tools, Platforms and Concepts

| Tool / Platform / Concept | Priority | Change | What to Know in 2026 | Official Learn Link |
|---------------------------|----------|--------|----------------------|---------------------|
| Python and NumPy | Core | Kept | Arrays, vectorisation and reproducible notebooks. | numpy.org/learn |
| Pandas | Core | Kept | Data cleaning and wrangling for tabular data. | pandas.pydata.org/docs/getting_started |
| Polars | Recommended | New | Fast DataFrame library gaining use for larger-than-comfortable datasets. | docs.pola.rs |
| SQL | Core | Updated | Joins, window functions and query tuning. Use the PostgreSQL docs and an interactive tutorial. | postgresql.org/docs/current/tutorial.html, sqlbolt.com |
| Jupyter notebooks | Core | New | Standard environment for exploration; learn to turn notebooks into clean code. | docs.jupyter.org |
| Statistics and probability | Core | Kept | Distributions, inference, regression and uncertainty. Add a free statistical-learning text. | khanacademy.org/math/statistics-probability, statlearning.com |
| Scikit-learn | Core | Kept | Pipelines, model selection and honest evaluation. | scikit-learn.org/stable/getting_started.html |
| Gradient boosting (XGBoost, LightGBM) | Core | New | Often the strongest baseline for tabular data. | xgboost.readthedocs.io, lightgbm.readthedocs.io |
| Feature engineering | Core | Kept | Turn raw data into signal; guard against leakage. | kaggle.com/learn/feature-engineering |
| Machine learning | Core | Kept | Andrew Ng's course (kept) plus Google's free crash course. | coursera.org/learn/machine-learning, developers.google.com/machine-learning/crash-course |
| Visualisation (Matplotlib, Seaborn, Plotly) | Core | Updated | Communicate findings clearly; interactive charts via Plotly. | matplotlib.org/stable/tutorials/index.html, plotly.com/python |
| Power BI | Recommended | Kept | Widely used business-intelligence tool; learn dashboard design, not just clicks. | learn.microsoft.com/en-us/power-bi |
| A/B testing and experimentation | Core | Updated | Replaces a vendor blog with the standard text on trustworthy online experiments. | experimentguide.com |
| Causal inference | Recommended | New | Move from correlation to decisions; free Python-based handbook. | matheusfacure.github.io/python-causality-handbook |
| dbt (analytics engineering) | Recommended | New | Version-controlled, tested SQL transformations; bridges data science and data engineering. | docs.getdbt.com |
| Cloud data warehouse (BigQuery or Snowflake) | Optional | New | Query large datasets without managing servers. | cloud.google.com/bigquery/docs |
| Explainability and fairness (SHAP, Fairlearn) | Recommended | New | Explain model decisions and test for unfair outcomes. | shap.readthedocs.io, fairlearn.org |

### Removed or Replaced in This Edition

- **W3Schools SQL tutorial** (not an official source; replaced by PostgreSQL documentation and SQLBolt).
- **Optimizely blog on A/B testing** (vendor marketing; replaced by the standard textbook on online experiments).

### Future Vision 2026 to 2030

Expect the data scientist to become a decision scientist: someone who combines statistics, experimentation and LLM-assisted analytics with strong communication. Governance (explainability, fairness, privacy) becomes part of the job description (our outlook).

### Proof-of-Skill Projects

- End-to-end tabular project: gradient-boosting model, SHAP explanations and a dashboard a manager can use.
- A/B test written up properly: hypothesis, power analysis, results, limits and a business recommendation.
- Causal-inference case study that shows when a correlation should not drive a decision.

---

## Career 7: ML Engineer

**Trains, evaluates and optimises ML models for performance and cost**

### The Role in Brief

Focuses on getting models to train well, evaluate honestly and run efficiently. Coverage of LinkedIn's ranking treats AI engineers and machine-learning engineers as one fast-growing family [S1], and the World Economic Forum places AI and machine-learning specialists among its three fastest-growing roles to 2030 [S3].

**Typical titles:** Machine Learning Engineer, Applied ML Engineer, Deep Learning Engineer, Model Optimisation Engineer

### 2026 Reality Check

The strongest ML engineers combine software discipline with statistical honesty: reproducible training, leak-free evaluation and measured optimisation. TensorFlow stays valuable where employers already run it, especially for mobile and edge deployment, but Google's own investment has shifted toward JAX and PyTorch leads new work [S21]. It moves from core to optional in this edition.

### Tools, Platforms and Concepts

| Tool / Platform / Concept | Priority | Change | What to Know in 2026 | Official Learn Link |
|---------------------------|----------|--------|----------------------|---------------------|
| NumPy and Pandas | Core | Kept | Data handling underpins every training pipeline. | numpy.org/learn |
| Scikit-learn | Core | Kept | Classical ML, pipelines and evaluation tools. | scikit-learn.org |
| Gradient boosting (XGBoost, LightGBM, CatBoost) | Core | New | Strong baselines on tabular data; often hard to beat. | xgboost.readthedocs.io, lightgbm.readthedocs.io |
| PyTorch | Core | Kept | Default for new deep-learning work. | pytorch.org/tutorials/beginner/basics/intro.html |
| TensorFlow and Keras | Optional | Updated | Demoted from core: learn it if your target employer uses it or you work on mobile/edge. Keras 3 supports several backends. | tensorflow.org/learn, keras.io |
| Feature engineering | Core | Updated | Updated to Google's current crash-course home page, since lesson URLs change. | developers.google.com/machine-learning/crash-course |
| Model training and evaluation | Core | Kept | Metrics, cross-validation and avoiding leakage. | scikit-learn.org/stable/modules/model_evaluation.html |
| Hyperparameter tuning (Optuna) | Recommended | New | Efficient, reproducible search instead of manual guessing. | optuna.readthedocs.io |
| Experiment tracking (MLflow, Weights & Biases) | Core | Updated | MLflow (kept) plus W&B; log data versions, parameters and metrics. | mlflow.org/docs/latest, docs.wandb.ai |
| Distributed training (DDP, FSDP, Accelerate) | Recommended | New | Scale training across GPUs with mixed precision. | pytorch.org/docs/stable/fsdp.html, huggingface.co/docs/accelerate |
| Model optimisation (ONNX Runtime, quantisation) | Recommended | New | Reduce latency and memory for deployment. | onnxruntime.ai/docs |
| Fine-tuning open LLMs (PEFT/LoRA) | Recommended | New | Increasingly part of the job as teams adapt open models. | huggingface.co/docs/peft |
| Docker | Core | Kept | Reproducible training and serving environments. | docs.docker.com |
| Cloud ML platforms (SageMaker, Vertex AI) | Recommended | Updated | Pick one; managed training, endpoints and pipelines. | docs.aws.amazon.com/sagemaker, cloud.google.com/vertex-ai/docs |
| Serving basics (FastAPI, vLLM for LLMs) | Recommended | New | Expose a model as an API; use vLLM when serving language models. | fastapi.tiangolo.com/learn, docs.vllm.ai |

### Future Vision 2026 to 2030

Expect demand for efficiency: quantisation, distillation, small specialised models, on-device inference and lower training cost. MLOps skills will increasingly be assumed (our outlook).

### Proof-of-Skill Projects

- Compare a gradient-boosting model with a neural network on the same data, with proper validation and experiment tracking.
- Optimise a model for latency using ONNX Runtime or quantisation, with a benchmark report.
- Reproducible multi-GPU training pipeline with configuration files, seeds and documented results.

---

## 12. Emerging Adjacent Careers

These roles sit next to the seven core paths. Several are growing because AI systems now need to be secured, governed, served efficiently and taught. Treat the less-standardised titles as emerging rather than settled.

| Role | What They Do | Why It Is Rising | Start With |
|------|--------------|------------------|------------|
| **AI Security Engineer / Red Teamer** | Tests and hardens LLM apps and agents against prompt injection, excessive agency and tool misuse. | OWASP published a 2026 LLM Top 10 (August 2026) and an Agentic Applications Top 10 (December 2025) [S15]. | genai.owasp.org; threat modelling; your own agent as a test target |
| **AI Governance, Risk and Compliance Specialist** | Maps AI systems to laws and standards, documents risk and supports audits. | EU AI Act: transparency duties apply from 2 Aug 2026; Annex III high-risk duties moved to 2 Dec 2027 by the Digital Omnibus [S14]. | EU AI Act overview; NIST AI RMF; ISO/IEC 42001 |
| **Data / Analytics Engineer** | Builds the reliable pipelines and warehouses AI depends on. | WEF lists big-data specialists as fastest-growing and data warehousing specialists in the top 15 [S3]. | SQL, dbt, Airflow, Spark, a cloud warehouse |
| **Forward-Deployed / AI Solutions Engineer** | Works at the customer's side to wire AI into real processes. | Described by market analysts as a fast-growing niche; less standardised, treat as emerging (secondary source). | LLM APIs, integrations, communication |
| **AI Consultant and Strategist** | Helps organisations pick and implement AI use cases. | Ranked second fastest-growing in LinkedIn's 2026 US list [S1]. | Business analysis plus AI literacy |
| **LLM Inference / Performance Engineer** | Makes model serving fast and cheap. | vLLM, SGLang and llm-d show serving has become its own specialism [S17]. | docs.vllm.ai; GPU basics; quantisation |
| **AI Educator / Learning Designer** | Trains teachers and workforces to use AI well. | Pakistan's National AI Policy sets a Train-the-Trainer target of 10,000 educators by 2027 (policy coverage) [S16]. | Prompt and context engineering plus pedagogy |

---

## 13. Cross-Career Foundations

Whichever career you choose, this shared base is where the first three months should go.

| Skill | Why It Matters | Learn With |
|-------|----------------|------------|
| Python | The working language of AI, data and most tooling. | docs.python.org/3/tutorial |
| SQL | Almost every real dataset lives in a database. | postgresql.org/docs/current/tutorial.html |
| Git and GitHub | Collaboration, review and deployment all start here. | git-scm.com/doc |
| Linux and command line | Servers, containers and cloud all assume it. | linuxjourney.com |
| Docker | Reproducible environments for training and serving. | docs.docker.com/get-started |
| One cloud platform | Employers deploy on AWS, Azure or GCP; pick one and go deep. | Vendor learning paths |
| APIs, JSON and HTTP | AI products are built by connecting services. | fastapi.tiangolo.com/learn |
| Testing and evaluation mindset | Unmeasured AI behaviour is unreliable behaviour. | pytest; Promptfoo; Ragas |
| AI-assisted coding | Use assistants to move faster, but be able to review, test and explain every line. Stanford found jobs that AI augments held up better than those it automates [S4]. | Claude Code, GitHub Copilot, Cursor, OpenAI Codex docs |
| Security basics | Prompt injection, secrets handling and least privilege apply to every AI app [S15]. | genai.owasp.org |
| Communication and domain knowledge | PwC finds the AI wage premium is tied to judgement and domain depth, not tool use alone [S2]. | Write project READMEs; study one industry |
| Responsible AI and regulation | Compliance is becoming a design input, not an afterthought [S14]. | NIST AI RMF; EU AI Act overview |

**AI coding assistants to know:** Claude Code, GitHub Copilot, Cursor and OpenAI Codex. Choose one, learn it well, and always review what it produces.

---

## 14. Future Vision 2026 to 2030

Forecasts are uncertain. The anchors below come from published sources and scheduled regulatory or industry dates; the interpretation is ours.

### Six Shifts Shaping Every AI Career

| Shift | What Is Happening | What to Do About It |
|-------|-------------------|---------------------|
| 1. From models to systems | Value is moving from calling a model to evaluating, securing and operating AI systems. Evaluation and observability tooling has become its own category [S20]. | Learn evals, tracing and cost control early. |
| 2. Open standards replace lock-in | MCP and A2A now share a neutral home in the Linux Foundation's Agentic AI Foundation, which reports more than 250 members [S13]. | Prefer open protocols; avoid building only on one vendor's proprietary builder. |
| 3. Regulation as a design input | EU AI Act duties are phasing in, and OWASP lists are becoming security baselines [S14] [S15]. | Know the basics of risk classification, transparency and threat modelling. |
| 4. A changing career ladder | Entry-level hiring is tighter in AI-exposed fields [S4] [S2] [S16]. | Show deployed projects, measurements and written judgement. |
| 5. AI fluency plus domain depth | The measured pay premium rose to 62% [S2]. | Pair your technical track with one industry you understand. |
| 6. Concepts outlast tools | Many tools in and around the old list changed status within about 15 months (Section 3). | Learn the idea first (retrieval, serving, evals), the framework second. |

### Timeline of Dated Anchors

| When | Anchor | Source |
|------|--------|--------|
| Aug 2026 | EU AI Act transparency (Article 50) duties apply; AI Office and national enforcement powers begin. | [S14] |
| 26 Aug 2026 | OpenAI Assistants API scheduled shutdown (now past; migrate to Responses API). | [S8] |
| 31 Oct 2026 | OpenAI Evals platform becomes read-only. | [S8] |
| 30 Nov 2026 | OpenAI Agent Builder, Evals dashboard/API and v1/prompts scheduled to shut down. | [S8] |
| Dec 2026 | LangChain 0.3 and LangGraph 0.4 maintenance support ends; EU content-marking grace period ends (2 Dec). | [S12] [S14] |
| By end of 2027 | Gartner expects over 40% of agentic AI projects to be cancelled. | [S6] |
| 2 Dec 2027 | EU AI Act Annex III high-risk obligations apply (moved from Aug 2026). | [S14] |
| 2028 | Gartner: a third of enterprise software includes agentic AI; EU Annex I (products) high-risk duties apply from 2 Aug 2028. | [S6] [S14] |
| 2030 | WEF horizon: 170M jobs created, 92M displaced. Pakistan's AI policy targets one million trained AI professionals. | [S3] [S16] |
| 2034 | BLS projection horizon: data scientist employment +34%. | [S5] |

### Skills Heading Up, According to the WEF

The WEF lists AI and big data, networks and cybersecurity, technological literacy, creative thinking and resilience among the fastest-rising skills, while clerical and administrative roles decline fastest [S3].

---

## 15. Regional Lens: Pakistan and Emerging Markets

Global data does not always match local conditions. This section gathers the Pakistan-specific facts found during verification; the guidance that follows is our interpretation.

| Fact | Detail | Source |
|------|--------|--------|
| National AI Policy 2025 | Federal cabinet approved it on 30 July 2025. Targets include training one million AI professionals, 3,000 scholarships a year, 1,000 local AI products and 50,000 AI-related projects by 2030. | [S16] |
| Public-sector and educator goals | Policy coverage reports AI training for all public servants by 2027, a Train-the-Trainer programme for 10,000 educators and 20,000 internship placements a year. | [S16] |
| IT exports growing | Pakistan's IT and telecom export remittances reached a record Rs 1.2 trillion in FY2025-26, up 20.6%. | [S16] |
| Junior hiring under pressure | Press reports about a 25% fall in hiring for junior developers and other entry-level tech roles; routine web, app, design and manual testing work is increasingly automated. | [S16] |
| Rising demand areas | The same report names AI engineering, cybersecurity, cloud computing and AI integration as growing. | [S16] |

### Practical Guidance (Our Interpretation)

- **Aim above the automatable layer.** Basic website and app work is where AI tools bite first; positions around AI integration, evaluation, security and cloud are growing.
- **Build deployed, measured portfolios.** Remote and freelance clients judge by shipped work and cost-quality evidence.
- **Use language as an advantage.** Urdu and regional-language assistants with proper evaluation are a credible niche, but must be measured, not assumed.
- **Use national programmes.** Look for policy-linked scholarships, internships and centres of excellence as they roll out.

---

## 16. 12-Month Roadmap and Portfolio Rules

| Phase | Goal | Output You Should Have |
|-------|------|------------------------|
| Months 0 to 3: Foundations | Python, SQL, Git, Linux, Docker, one LLM API, basic statistics. | A small FastAPI service in Docker, on GitHub, calling an LLM and returning structured output, with at least 10 automated tests. |
| Months 3 to 6: Track core | Learn the Core rows of your chosen career table. | One project that uses the track's core stack end to end (for example RAG with eval suite, or a trained model with tracking). |
| Months 6 to 9: Depth and production | Add Recommended rows, deploy to a cloud, add monitoring and cost tracking. | A live deployment with traces, a quality report and a short cost analysis. |
| Months 9 to 12: Proof and positioning | Security review, documentation, public write-up, mock interviews. | A portfolio of 2 or 3 projects, each with README, evaluation results, threat model and lessons learned. |

### Portfolio Rules That Employers Can Verify

- **Deploy it.** A running URL or reproducible container beats a notebook.
- **Measure it.** Include evaluation results, failure cases and what you changed because of them.
- **Secure it.** Add a short threat model; reference the OWASP lists for LLM and agent apps.
- **Price it.** Report cost and latency per request.
- **Explain trade-offs.** Say what you chose, what you rejected and why.
- **Date it.** Note library versions and the date, so readers know how current it is.

---

## 17. Keeping This List Current

The tool changes in Section 3 show that any tool list ages quickly. Use this routine every quarter.

| Check | How |
|-------|-----|
| Deprecation notices | Read vendor deprecation pages (for example OpenAI's) and release policies (for example LangChain's). |
| Maintenance banners | Open each project's repository README and look for maintenance-mode or archived notices. |
| Release cadence | A project with no releases for a year deserves a closer look. |
| Link health | Run a link checker across the document; vendor docs move often. |
| Standards | Prefer tools that support MCP, A2A and OpenTelemetry. |
| Evidence refresh | Update market figures when LinkedIn, PwC, WEF, BLS and Gartner publish new editions. |

### Watch List for the Next Review (January 2027)

- OpenAI Agent Builder, Evals dashboard/API and prompt-object shutdowns (30 Nov 2026) [S8].
- LangChain 0.3 and LangGraph 0.4 end of maintenance (Dec 2026) [S12].
- MCP and A2A specification updates under the Agentic AI Foundation [S13].
- Microsoft Agent Framework releases and AutoGen migration experience [S7].
- EU AI Act guidance and standards ahead of the December 2027 high-risk date [S14].
- Pakistan National AI Policy implementation milestones [S16].

---

## 18. Sources and Verification Notes

Research was carried out on **14 October 2026**. Sources are grouped by type. 'Primary' means the publisher or the data owner; 'Secondary' means journalism or analysis summarising it; 'Practitioner' means vendor or developer commentary. Where a figure was read from a secondary summary, treat it as indicative until checked against the original.

| Ref | Source | Type | Used For |
|-----|--------|------|----------|
| S1 | LinkedIn Jobs on the Rise 2026, as reported by Forbes and Dice | Secondary | Role rankings |
| S2 | PwC 2026 Global AI Jobs Barometer (15 Jun 2026) | Primary | Wage premium, job growth, junior roles |
| S3 | WEF Future of Jobs Report 2025 (figures cross-checked via press summaries) | Primary | Job creation, fastest-growing roles, skills |
| S4 | Stanford Digital Economy Lab, Canaries in the Coal Mine? | Primary | Early-career employment |
| S5 | US Bureau of Labor Statistics, Data Scientists | Primary | Data scientist outlook, pay |
| S6 | Gartner press release, 25 Jun 2025 | Primary | Agentic AI forecasts |
| S7 | Microsoft AutoGen repository; Microsoft Agent Framework; Intelligent Tools summary | Primary and secondary | AutoGen maintenance mode, Agent Framework 1.0 |
| S8 | OpenAI deprecations page; OpenAI community Assistants notice | Primary | Assistants, Agent Builder, Evals shutdowns |
| S9 | OpenAI fine-tuning update (8 May 2026) | Primary | Fine-tuning wind-down |
| S10 | PyTorch TorchServe documentation | Primary | TorchServe status |
| S11 | HyperAI report on Papers with Code shutdown | Secondary | Papers with Code shutdown |
| S12 | LangChain and LangGraph 1.0 announcement; LangChain versioning docs | Primary | 1.0 releases, maintenance dates |
| S13 | Linux Foundation A2A press release; Axios; FlowHunt summary | Primary and secondary | MCP, A2A, Agentic AI Foundation |
| S14 | Cloud Security Alliance note on the EU Digital Omnibus; DLA Piper briefing | Secondary (legal analysis) | EU AI Act dates |
| S15 | OWASP GenAI Security Project; CSA note on OWASP 2026 lists | Primary and secondary | LLM and Agentic Top 10 |
| S16 | Express Tribune on cabinet approval; ProPakistani, 7 Aug 2026 | Secondary | Pakistan policy and hiring |
| S17 | vLLM conference page; Fish Audio engine comparison | Project and practitioner | LLM inference landscape |
| S18 | Arize agent framework guide; VDF framework comparison (Oct 2026) | Practitioner | Agent framework capabilities |
| S19 | Chat2DB vector database guide; Noqta comparison | Practitioner | RAG and vector database guidance |
| S20 | MojoAuth platform roundup; FutureAGI eval tools | Practitioner | Evaluation and observability landscape |
| S21 | UVIK PyTorch vs TensorFlow; Tech Insider comparison | Practitioner | Framework adoption (figures vary by source) |
| S22 | DEV Community; OpenAI agent APIs in 2026 | Practitioner | Agents SDK provider support |
| S23 | LATEAM, most in-demand AI profiles 2026 | Secondary | Generative AI engineer transitions |

### Verification Limits (Please Read)

- Tool status was checked by searching official pages, repositories and recent coverage. Learning links were taken from the previous list or from official vendor domains, but not every link was click-tested from this environment. Run a link checker before publishing.
- Secondary and practitioner sources can contain errors or vendor bias. Dates and figures that matter to a decision should be confirmed at the original source.
- Salary figures are deliberately limited to official statistics (US BLS) because pay varies sharply by country, employer and seniority. Check local market data before making financial decisions.
- Forecasts (Gartner, WEF, BLS) are projections, not guarantees.

---

## 19. Master Learning Links

The most useful starting points across all seven careers.

- Python Official Tutorial — docs.python.org/3/tutorial
- PostgreSQL Tutorial — postgresql.org/docs/current/tutorial.html
- Git Documentation — git-scm.com/doc
- PyTorch Official Tutorials — pytorch.org/tutorials
- Hugging Face Learn — huggingface.co/learn
- LangChain and LangGraph Docs — docs.langchain.com
- OpenAI Agents SDK — openai.github.io/openai-agents-python
- Model Context Protocol — modelcontextprotocol.io
- A2A Protocol — a2a-protocol.org
- OWASP GenAI Security Project — genai.owasp.org
- FastAPI Learn — fastapi.tiangolo.com/learn
- Docker Get Started — docs.docker.com/get-started
- vLLM Documentation — docs.vllm.ai
- Langfuse Documentation — langfuse.com/docs
- Google Machine Learning Crash Course — developers.google.com/machine-learning/crash-course

---

*Original compilation: Abubakar Siddique — AI Engineer | SaaS Builder | Full-Stack Developer (Next.js, Python, LLM Agents) | MSCS Computer Networks | Helping US, UK, DE startups build AI-powered SaaS | 15+ Yrs Exp*  
*Verified and future-vision edition revised 14 October 2026.*
