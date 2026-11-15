# Avish Sinha

I’m a final-year Computer Science student specializing in AI and ML at VIT Bhopal, graduating in 2027. My projects cover retrieval for long documents, evaluation for tool-calling agents, and Python integrations for LLM applications. I’m looking for AI engineering internships and early-career roles in applied AI and ML systems.

[LinkedIn](https://www.linkedin.com/in/avish-sinha/) · [Email](mailto:avishsinha10@gmail.com) · [Kaggle](https://www.kaggle.com/avish006) · [LeetCode](https://leetcode.com/u/avish006/) · [Codeforces](https://codeforces.com/profile/avish006)

## Open source

### [upstash-haystack](https://github.com/avish006/upstash_haystack)

A community integration that adds Upstash Vector to Haystack as a document store. Published on PyPI under Apache 2.0 and listed in the Haystack integration directory through a merged listing PR.

- Provides a document store and two retrievers for dense and hybrid search. Hybrid retrieval combines dense and sparse results using Upstash’s native Reciprocal Rank Fusion.
- Supports batched writes, duplicate handling, and translation of nested Haystack filters to Upstash filter expressions.
- Includes unit and live integration tests, a GitHub Actions matrix for Python 3.10–3.13, and automated PyPI releases.

[PyPI](https://pypi.org/project/upstash-haystack/) · [Haystack listing](https://haystack.deepset.ai/integrations/upstash/) · [Merged PR](https://github.com/deepset-ai/haystack-integrations/pull/560)

## AI engineering projects

### [Agent Lenz](https://github.com/avish006/Agent_Eval) | Agent evaluation and tracing

An evaluation harness for a simulated customer refund agent built with LangChain and DeepEval.

- Captures tool calls and execution traces, then checks task completion, tool selection, arguments, plan quality, plan adherence, step efficiency, and answer correctness.
- On the repo’s seven scripted refund scenarios, tool correctness passed **7/7** and task completion passed **6/7**.
- The Gemma judge uses concurrency limits and retry backoff for HTTP 429 responses, with Pydantic validation for structured outputs.

### [DocuMind](https://github.com/avish006/Rag-Project) | Multimodal RAG for long PDFs

A PDF reader with chat alongside the document. Tested on more than ten PDFs, including books of 700–900 pages.

- Combines BM25 with FAISS retrieval over BGE embeddings. PyMuPDF handles ingestion, and a file hash lets repeat uploads reuse the cached index.
- Uses CLIP to select relevant figures and EasyOCR to extract text from them on demand.
- A [lighter Streamlit build](https://github.com/avish006/Streamlit-Rag-Deployment) supports deployment with fewer resources.

### [Job Hunt AI Agent](https://github.com/avish006/job-hunt-agent) | Search and ranking

A search tool that converts a resume and a prompt into queries, gathers listings from several sources in parallel, and presents ranked results in a React interface.

- Uses Gemma to extract role and location signals. Ranks listings using skill overlap and TF-IDF cosine similarity.
- Serves results through FastAPI and exposes the search pipeline as an optional MCP tool.

### [Deep Research Agent](https://github.com/avish006/deep-research-agent) | Research and synthesis

A LangGraph workflow that plans queries, extracts source material, and writes a sourced Markdown report.

- Uses a separate source collection stage and streams progress and report output to a React UI over Server-Sent Events.
- Includes retry handling for model rate limits and Docker configuration for deployment on Render.

### Pathwise | AI study and revision tool

A team project that generates study roadmaps and uses web sources to check generated content. Built with React, Flask, and Supabase for the CodeVerse Hackathon with Abhay Tyagi, Ashish Vishwakarma, and Vaibhav Arora.

## Applied ML, research, and experiments

| Work | Focus |
| --- | --- |
| [ARC Prize 2026 / ARC-AGI-3](https://www.kaggle.com/competitions/arc-prize-2026-arc-agi-3) | Agent experiments for interactive reasoning tasks. |
| [Kaggriculture](https://www.kaggle.com/competitions/kaggriculture) | Strategy evaluation for a competitive farming simulation agent. |
| Indian legal document classification | Exploration of hierarchical text classification for Indian legal documents. |
| [Multi-PDF RAG capstone](https://github.com/avish006/RAG_Streamlit) | Streamlit app with a history-aware LangChain retriever, ChromaDB, and Gemini. |
| [MPOnline ML projects](https://github.com/avish006/MPOnlineOldAssignment) and [computer vision notebooks](https://github.com/avish006/MPONLINE_ASSIGNMENT) | Census income classification, CIFAR-10 and Fashion-MNIST, face recognition, medical image classification, movie recommendations, CartPole and LunarLander, and model serving with FastAPI. |
| [Deep-ML](https://github.com/avish006/deep-ml) | Handwritten Python solutions for ML and linear algebra exercises. |

## Data analysis and dashboards

- [Indian Startup Funding](https://github.com/avish006/Startup-Analysis) — a Streamlit dashboard for exploring funding rounds, investors, industries, and cities.
- [Crypto Trading Analysis](https://github.com/avish006/Crypto-Trading-Data-Analysis) — comparison of 32 trading accounts across market sentiment regimes using drawdown, risk-adjusted returns, and other performance measures.
- [Bank Loan Dashboard](https://github.com/avish006/Power-BI-Bank-Loan-Dashboard) — loan portfolio analysis with PostgreSQL and Power BI.

## Technical toolkit

| Area | Tools |
| --- | --- |
| Languages | Python, C++, SQL, TypeScript |
| Agents and evaluation | LangChain, LangGraph, CrewAI, MCP, DeepEval, G-Eval, Pydantic |
| Retrieval and applied ML | Haystack, BM25, FAISS, Upstash Vector, ChromaDB, PyTorch, TensorFlow, scikit-learn, Hugging Face, LoRA/PEFT |
| APIs, deployment, and data | FastAPI, Flask, React, Streamlit, Docker, Git, GitHub Actions, PostgreSQL, pandas, NumPy |

## Hackathons & Achievements

| Achievement | Result |
| --- | --- |
| **Kaggle Expert** | Peak rank **1,429 / 60,000+** (Top 3%) · 1 Silver + 5 Bronze medals · 100+ forks · 150+ upvotes |
| **Flipkart Gridlock 2.0** | Ranked **42 / 6,912** — national-level engineering challenge |
| **Shell AI Hackathon** | Ranked **181 / 1,500+** — fuel blend property prediction (ML) |
| **CodeVerse Hackathon** | **Finalist, Top 50 / 300+** teams — built *Pathwise*, an AI-powered EdTech study platform |
| **DSA / Competitive Programming** | **500+ problems** solved across LeetCode, GeeksforGeeks & Codeforces |

## Certifications

- [OCI Certified Generative AI Professional](https://catalog-education.oracle.com/ords/certview/sharebadge?id=B5989130D2866FAEA5F7AAF2E6B72AACE90BC608CCF3513AFEFF9CC8AF76799A)
- [Deep Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/1DE22K271YAV)
