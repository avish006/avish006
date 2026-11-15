<p align="center">
  <img src="./assets/profile-header.svg" width="100%" alt="Avish Sinha · AI engineering and open source" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/avish-sinha/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" /></a>
  <a href="mailto:avishsinha10@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-613F57?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" /></a>
  <a href="https://www.kaggle.com/avish006"><img alt="Kaggle" src="https://img.shields.io/badge/Kaggle-156481?style=for-the-badge&amp;logo=kaggle&amp;logoColor=white" /></a>
  <a href="https://leetcode.com/u/avish006/"><img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-785119?style=for-the-badge&amp;logo=leetcode&amp;logoColor=white" /></a>
</p>

## About me

I’m Avish, a final-year B.Tech Computer Science student specializing in AI and ML at VIT Bhopal (2027). I build retrieval systems for long documents and tools for tracing and evaluating agent calls. I’m open to **AI engineering internships**.

## Tech stack

**Languages**  
![Python](https://img.shields.io/badge/Python-26342B?style=flat&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-26342B?style=flat&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-26342B?style=flat&logo=postgresql&logoColor=white)

**GenAI and agents**  
![LangChain](https://img.shields.io/badge/LangChain-26342B?style=flat&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-26342B?style=flat&logo=langgraph&logoColor=white) ![CrewAI](https://img.shields.io/badge/CrewAI-26342B?style=flat&logo=crewai&logoColor=white) ![Haystack](https://img.shields.io/badge/Haystack-26342B?style=flat) ![RAG](https://img.shields.io/badge/RAG-26342B?style=flat) ![MCP](https://img.shields.io/badge/MCP-26342B?style=flat&logo=modelcontextprotocol&logoColor=white) ![LoRA / PEFT](https://img.shields.io/badge/LoRA%20%2F%20PEFT-26342B?style=flat) ![Pydantic](https://img.shields.io/badge/Pydantic-26342B?style=flat&logo=pydantic&logoColor=white)

**LLM evaluation**  
![DeepEval](https://img.shields.io/badge/DeepEval-26342B?style=flat) ![LLM-as-a-Judge](https://img.shields.io/badge/LLM--as--a--Judge-26342B?style=flat) ![G-Eval](https://img.shields.io/badge/G--Eval-26342B?style=flat)

**ML and data tools**  
![PyTorch](https://img.shields.io/badge/PyTorch-26342B?style=flat&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-26342B?style=flat&logo=scikitlearn&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging%20Face-26342B?style=flat&logo=huggingface&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-26342B?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-26342B?style=flat&logo=numpy&logoColor=white)

**Backend and deployment**  
![FastAPI](https://img.shields.io/badge/FastAPI-26342B?style=flat&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-26342B?style=flat&logo=docker&logoColor=white) ![FAISS](https://img.shields.io/badge/FAISS-26342B?style=flat) ![Upstash Vector](https://img.shields.io/badge/Upstash%20Vector-26342B?style=flat&logo=upstash&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-26342B?style=flat&logo=postgresql&logoColor=white) ![Git](https://img.shields.io/badge/Git-26342B?style=flat&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-26342B?style=flat&logo=githubactions&logoColor=white)

---

## Featured projects

### [Agent Lenz](https://github.com/avish006/Agent_Eval)

> An evaluation harness for tool-calling agents.

- Captures LangChain traces and uses DeepEval to score tool selection, arguments, plan adherence, task completion, and answer quality. The Gemma 4 judge validates structured output with Pydantic and backs off on rate limits.
- On seven scripted refund scenarios, tool correctness passed **7/7** and task completion passed **6/7**. [Evaluation output](https://github.com/avish006/Agent_Eval#empirical-benchmark-results)

### [DocuMind](https://github.com/avish006/Rag-Project)

> A PDF reader and document chat in the same window.

- Combines BM25 and FAISS for text retrieval, with CLIP and on-demand OCR for figures.
- Tested on **10+ PDFs**, including books of **700–900 pages**. PyMuPDF handles ingestion, and repeat uploads reuse the cached index. [Streamlit version](https://github.com/avish006/Streamlit-Rag-Deployment)

### [upstash-haystack](https://github.com/avish006/upstash_haystack)

> A Python integration for using Upstash Vector as a Haystack document store.

- Supports dense and hybrid retrieval, batch writes, and nested filter translation. Includes 37 unit and live integration tests, CI for Python 3.10–3.13, and automated PyPI releases.
- [Install from PyPI](https://pypi.org/project/upstash-haystack/) · [Haystack integration directory](https://haystack.deepset.ai/integrations/upstash/) · [Merged listing PR](https://github.com/deepset-ai/haystack-integrations/pull/560)

### More projects

- [**Job Hunt AI Agent**](https://github.com/avish006/job-hunt-agent) derives queries from a résumé, gathers listings in parallel, and ranks them by skill and text overlap. It has a FastAPI backend and an MCP entry point.
- [**Deep Research Agent**](https://github.com/avish006/deep-research-agent) uses LangGraph to plan searches, collect sources, and stream a report with citations.
- **Pathwise** is a CodeVerse team project that turns topics into study roadmaps and checks generated content against web sources. Built with Abhay Tyagi, Ashish Vishwakarma, and Vaibhav Arora.

---

## GitHub statistics

<p align="center">
  <a href="https://github.com/avish006">
    <img src="./assets/profile-stats.svg" width="100%" alt="17 public repositories and 7 followers as of 15 November 2026. Core languages: Python, C++, and SQL." />
  </a>
</p>

---

## Repository showcase

<table width="100%">
  <tr>
    <td width="50%" valign="top"><a href="https://github.com/avish006/Agent_Eval"><strong>Agent Lenz</strong></a><br />Tool call traces and refund agent benchmarks<br /><sub>LangChain · DeepEval</sub></td>
    <td width="50%" valign="top"><a href="https://github.com/avish006/Rag-Project"><strong>DocuMind</strong></a><br />Read and query long PDFs side by side<br /><sub>Flask · FAISS</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="https://github.com/avish006/upstash_haystack"><strong>upstash-haystack</strong></a><br />Upstash Vector for Haystack pipelines<br /><sub>Python · Haystack</sub></td>
    <td width="50%" valign="top"><a href="https://github.com/avish006/job-hunt-agent"><strong>Job Hunt AI Agent</strong></a><br />Resume-aware job search and ranking<br /><sub>FastAPI · MCP</sub></td>
  </tr>
</table>

## Hackathons & Achievements

| Achievement | Result |
| --- | --- |
| **Kaggle Expert** | Peak rank **1,429 / 60,000+** (Top 3%) · 1 Silver + 5 Bronze medals · 100+ forks · 150+ upvotes |
| **Flipkart Gridlock 2.0** | Ranked **42 / 6,912** — national-level engineering challenge |
| **Shell AI Hackathon** | Ranked **181 / 1,500+** — fuel blend property prediction (ML) |
| **CodeVerse Hackathon** | **Finalist, Top 50 / 300+** teams — built *Pathwise*, an AI-powered EdTech study platform |
| **DSA / Competitive Programming** | **500+ problems** solved across LeetCode, GeeksforGeeks & Codeforces |

<details>
<summary>Dashboards and credentials</summary>

- [Indian Startup Funding](https://github.com/avish006/Startup-Analysis) · [Crypto Trading Analysis](https://github.com/avish006/Crypto-Trading-Data-Analysis) · [Bank Loan Dashboard](https://github.com/avish006/Power-BI-Bank-Loan-Dashboard)

- [OCI Certified Generative AI Professional](https://catalog-education.oracle.com/ords/certview/sharebadge?id=B5989130D2866FAEA5F7AAF2E6B72AACE90BC608CCF3513AFEFF9CC8AF76799A)
- [Deep Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/1DE22K271YAV)

</details>

---

## Let’s connect

I’m happy to talk about document retrieval, agent evaluation, or internship opportunities. [LinkedIn](https://www.linkedin.com/in/avish-sinha/) · [Email](mailto:avishsinha10@gmail.com)
