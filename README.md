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

- **Pinpoints where a tool-calling agent goes wrong.** On seven scripted refund cases, tool correctness passed **7/7** and task completion passed **6/7**. The traces surfaced an unnecessary pricing lookup before the refund eligibility check. [Benchmark results](https://github.com/avish006/Agent_Eval#empirical-benchmark-results)
- Captures LangChain traces and scores tool selection, call arguments, plan adherence, step efficiency, task completion, and answer quality with DeepEval. The Gemma 4 judge validates structured output with Pydantic and uses exponential backoff on rate limits.

### [DocuMind](https://github.com/avish006/Rag-Project)

- **Lets readers ask about text and figures while keeping the original PDF in view.** Tested on **10+ PDFs**, including books of **700–900 pages**. A content-hash cache reuses the index on repeat uploads. [Streamlit version](https://github.com/avish006/Streamlit-Rag-Deployment)
- Extracts text and images with PyMuPDF, ranks text chunks by combining BM25 with BGE embeddings indexed in FAISS, and uses CLIP and on-demand OCR to add context when users ask about a figure.

### [upstash-haystack](https://github.com/avish006/upstash_haystack)

- **Lets Haystack users add serverless vector search to a retrieval pipeline.** The package is installable from PyPI and listed in the Haystack integration directory. [PyPI](https://pypi.org/project/upstash-haystack/) · [Haystack directory](https://haystack.deepset.ai/integrations/upstash/) · [Merged PR](https://github.com/deepset-ai/haystack-integrations/pull/560)
- Implements a document store with batch writes and nested metadata-filter translation. The retrievers support dense search and hybrid dense/sparse search via Reciprocal Rank Fusion. GitHub Actions runs unit tests across Python 3.10–3.13 and live integration tests on 3.12.

### [Job Hunt AI Agent](https://github.com/avish006/job-hunt-agent)

- **Gives candidates a single ranked shortlist across job boards.** Results include matched skills and links to the original postings, so candidates can see where their résumé fits and decide which openings to review first.
- Gemma 4 extracts search terms from a PDF résumé and chat prompt. A CrewAI workflow combines results from JobSpy, RSS feeds, and SearXNG/Crawl4AI. It deduplicates by title and company, ranks with equally weighted skill overlap and TF-IDF cosine similarity, and exposes search through FastAPI and an optional MCP tool.

### [Deep Research Agent](https://github.com/avish006/deep-research-agent)

- **Turns a broad question into a source-linked research brief.** Readers can watch the search and drafting stages in React, then follow citations in the Markdown report to check the evidence behind its findings.
- LangGraph coordinates a Gemma 4 planner, a search node that scores URLs using credibility heuristics and extracts page text without LLM calls, and a writer that drafts the report section by section. An Express API streams progress through server-sent events.

### [Pathwise](https://github.com/crowaltz24/pathwise)

- **Gives students a step-by-step study plan, topic-specific Q&A, and notes in one place.** Our team used it to revise for end-of-term exams and reached the CodeVerse finals. [Team demo](https://www.linkedin.com/posts/abhay-tyagi-61329a28a_hackathon-ai-webdevelopment-activity-7351263617926782978-T5me)
- A React frontend calls Flask endpoints to generate roadmaps and lesson content. The backend adds Google Search results as context for generation, and Supabase handles authentication and stores users’ learning paths. Built with Abhay Tyagi, Ashish Vishwakarma, and Vaibhav Arora.

### [Indian Startup Funding](https://github.com/avish006/Startup-Analysis)

- **Lets readers compare where funding went and how deal activity changed over time.** The dashboard shows funding by industry and city, surfaces investors by deal count, and exports the filtered records as CSV for further analysis.
- Standardizes industry and city names with pandas, aggregates deal amounts by month and year, and presents the results in Streamlit with filters for year, industry, and startup.

### [Crypto Trading Analysis](https://github.com/avish006/Crypto-Trading-Data-Analysis)

- **Shows how trading performance varied across market sentiment regimes.** Few of the **32 accounts** in the sample showed consistent profits during Extreme Fear. The analysis reports drawdown alongside returns so readers can compare the risk taken across accounts.
- Uses pandas in a Jupyter notebook to align trade-level profit and loss with Fear & Greed Index data. Compares accounts using Sharpe and Sortino ratios, maximum drawdown, win rate, and profit factor.

### [Bank Loan Dashboard](https://github.com/avish006/Power-BI-Bank-Loan-Dashboard)

- **Makes it easier to see where lending volume and charge-offs are concentrated.** The Power BI dashboard lets readers compare funded and repaid amounts, loan status, and borrower segments to identify patterns worth investigating.
- Uses PostgreSQL to aggregate applications, funded amounts, receipts, interest rates, and debt-to-income ratios by month and state. Calculates the portfolio’s charge-off rate from recorded loan statuses.

---

## Hackathons & Achievements

| Achievement | Result |
| --- | --- |
| **Kaggle Expert** | Peak rank **1,429 / 60,000+** (Top 3%) · 1 Silver + 5 Bronze medals · 100+ forks · 150+ upvotes |
| **Flipkart Gridlock 2.0** | Ranked **42 / 6,912** — national-level engineering challenge |
| **Shell AI Hackathon** | Ranked **181 / 1,500+** — fuel blend property prediction (ML) |
| **CodeVerse Hackathon** | **Finalist** — built *Pathwise*, an AI-powered EdTech study platform |
| **DSA / Competitive Programming** | **500+ problems** solved across LeetCode, GeeksforGeeks & Codeforces |

<details>
<summary>Credentials</summary>

- [OCI Certified Generative AI Professional](https://catalog-education.oracle.com/ords/certview/sharebadge?id=B5989130D2866FAEA5F7AAF2E6B72AACE90BC608CCF3513AFEFF9CC8AF76799A)
- [Deep Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/1DE22K271YAV)

</details>

---

## Let’s connect

I’m happy to talk about document retrieval, agent evaluation, or internship opportunities. [LinkedIn](https://www.linkedin.com/in/avish-sinha/) · [Email](mailto:avishsinha10@gmail.com)
