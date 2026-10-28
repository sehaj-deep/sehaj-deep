<h1 align="center">Hi, I'm Sehajdeep</h1>

<p align="center">
AI Engineer &nbsp;·&nbsp; LLM agents, RAG and evaluation &nbsp;·&nbsp; Python, FastAPI, LangGraph, AWS
</p>

<p align="center">
<a href="https://www.linkedin.com/in/singh-sehaj-deep/" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
&nbsp;
<a href="mailto:sehajdeep490@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
</p>

---

I build LLM agents and search systems for work that has to be checked: financial-crime investigations, compliance documents and research data. Master of Applied Computer Science, Concordia University (GPA 4.17/4.3). My machine learning research on zero-shot vision-language models was accepted for IEEE. Based in the Greater Toronto Area.

---

### Featured project

#### [Anti-Money Laundering (AML) Investigation Agent](https://github.com/sehaj-deep/aml-investigation-agent)
[Live demo](https://aml-investigation-agent.onrender.com) · [Project page](https://aml-agent-home.onrender.com) · [Source](https://github.com/sehaj-deep/aml-investigation-agent)

A sandbox case manager for anti-money laundering analysts. Transaction monitoring raises alerts, a LangGraph agent drafts an investigation using read-only MCP data tools, and a human analyst makes every decision.

- **49-second median** to draft a case, measured over 150 alerts.
- **Hybrid search** (pgvector plus keyword) ranked the right guidance document first on 88.9% of 18 test questions, up from 77.8% with keyword search alone.
- **Citation check** dropped 94 of 280 quoted passages (33.6%) that failed a word-for-word check against the source.
- Synthetic data only. The repo's scorecard lists the limitations next to the results.

`Python` `FastAPI` `LangGraph` `MCP` `pgvector` `PostgreSQL` `React` `Docker`

---

### Other projects

**[Personal Finance Dashboard](https://github.com/sehaj-deep/finance-dashboard)**: FastAPI and Vue.js app where an LLM categorizes financial documents, behind a data-sanitization pipeline (95%+ accuracy on categorization).

**[Trade Stream Service](https://github.com/sehaj-deep/trade-stream-service)**: Java 17 and Spring Boot pipeline that streams simulated commodity trades through Kafka into MySQL, with per-instrument race conditions removed (checked by a 10-thread test) and failed messages retried 3 times before a dead-letter log.

**[AuthBridge](https://github.com/sehaj-deep/authbridge)**: Java and Spring Boot identity provider with Spring Security, stateless JWT and LDAP. Authentication latency 97.3% lower (0.15 ms vs 5.5 ms), containerized with Docker.

**[Multilingual Tweet Intimacy Analysis](https://github.com/sehaj-deep/Multilingual_Intimacy_Analysis)**: fine-tuned XLM-T beat mBERT by 20% and XLM-R by 13% on sentiment-intensity correlation.

---

### Research

Machine Learning Research Assistant at Concordia's PaInt Lab: zero-shot CLIP and LLaVA classifiers eliminated 15,000 manual annotations (60.5% accuracy). Accepted for IEEE.

---

### Tech stack

**Languages:** Python, Java, TypeScript, JavaScript, SQL
**AI:** LangGraph, LangChain, MCP, RAG, PyTorch, Hugging Face
**Backend and cloud:** FastAPI, Spring Boot, PostgreSQL, Docker, AWS

---

<p align="center">
<i>Open to AI engineer, applied ML and software engineer roles in Canada.</i>
</p>
