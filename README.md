<div align="center">

<!-- BANNER:START -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=180&section=header&text=SIDDHESH%20BANSAL&fontSize=42&fontColor=2DD4BF&desc=AI%20%26%20ML%20Systems%20Engineer%20%C2%B7%20Autonomous%20Agents%20%C2%B7%20LangGraph%20Orchestration&descSize=14&descAlignY=68&descAlign=50&animation=fadeIn">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=rect&color=F6F8FA&height=180&section=header&text=SIDDHESH%20BANSAL&fontSize=42&fontColor=0F766E&desc=AI%20%26%20ML%20Systems%20Engineer%20%C2%B7%20Autonomous%20Agents%20%C2%B7%20LangGraph%20Orchestration&descSize=14&descAlignY=68&descAlign=50&animation=fadeIn">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=180&section=header&text=SIDDHESH%20BANSAL&fontSize=42&fontColor=2DD4BF" width="100%" alt="Siddhesh Bansal"/>
</picture>
<!-- BANNER:END -->

<p align="center">
  <a href="https://linkedin.com/in/siddhesh-bansal"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://siddheshbansal.github.io"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=flat-square&logo=googlechrome&logoColor=2DD4BF" alt="Portfolio"/></a>
  <a href="mailto:siddheshb@iitbhilai.ac.in"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/siddheshbansal"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://huggingface.co/siddheshbansal"><img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HuggingFace"/></a>
</p>

```
STATUS   : PRODUCTION_ACTIVE
ROLE     : AI & Machine Learning Systems Engineer · Autonomous Agent Architect
BASE     : IIT Bhilai — B.Tech, Data Science & AI (2024–2028, CPI 9.15/10)
SPECIALTY: Multi-Agent State Machines (LangGraph) · Production RAG · Low-Latency LLM Serving
CONTACT  : siddheshb@iitbhilai.ac.in · +91 73107 98730
```

</div>

---

### `$ whoami`

Undergrad in Data Science & Artificial Intelligence at **IIT Bhilai** focused on **agentic AI architectures, multi-agent state machines, and production RAG pipelines**. I build resilient supervisor-orchestrated agent DAGs, structured tool-execution engines, and fine-tuned transformer microservices.

- **Current**: Coordinator @ **DSAI Club, IIT Bhilai** · Developing autonomous agent swarms with dynamic fallback routing & local LLM inference.
- **Core Focus**: LangGraph multi-agent DAGs, hybrid vector search (Chroma + SentenceTransformers), MCP tool-calling protocols, and model fine-tuning (LoRA/PEFT).

---

### `$ ps aux --agentic-systems`

| System | Architecture & Engineering Highlights | Stack | Status |
|:---|:---|:---|:---:|
| [**`TravelMind-AI`**](https://github.com/siddheshbansal/TravelMind-AI) | **4-Agent LangGraph Supervisor Workflow** (Orchestrator $\to$ Research $\to$ Planner $\to$ Writer) with conditional routing, dynamic retry loops, 6 live tool APIs, and dual-model inference (Groq in cloud + local Ollama Qwen 2.5 7B) | LangGraph · Groq · Ollama · FastAPI · SerpApi · LangSmith | `active` |
| [**`MedQuery-RAG`**](https://github.com/siddheshbansal/MedQuery) | **Clinical RAG & Document Intelligence Pipeline** featuring semantic chunking, Sentence-Transformers vector embeddings, ChromaDB similarity retrieval, and Groq streaming endpoints with React interface | FastAPI · ChromaDB · Sentence-Transformers · Groq · React | `active` |
| [**`TweetSense`**](https://github.com/siddheshbansal/TweetSense) | **Transformer NLP & Inference Platform**; fine-tuned DistilBERT on 7,600+ disaster tweets on a T4 GPU (**84% Accuracy & F1 score**), containerized with Docker Compose on AWS EC2 | DistilBERT · PyTorch · FastAPI · React + Vite · Docker · AWS EC2 | `prod` |
| [**`Inter-IIT-Quant-Engine`**](https://github.com/siddheshbansal/inter-iit-quant) | High-throughput intraday trading system on 1-second Limit Order Book data; Ridge Regression Z-score model + ADX/ATR regime classifier (**Ranked 10th All-IITs**, 35.0% & 36.35% ann. returns) | Python · NumPy · pandas · scikit-learn · Market Microstructure | `active` |

<details>
<summary><b>Additional Systems & Tooling</b></summary>

| System | Overview | Stack |
|:---|:---|:---|
| [**`agent-mcp-hub`**](https://github.com/siddheshbansal) | Model Context Protocol server exposing deterministic tool execution layers for LLM swarms | Python · MCP · FastAPI · Pydantic |
| [**`doc-embed-stream`**](https://github.com/siddheshbansal) | High-speed batch PDF text parser with semantic sliding window chunking | Python · PyPDF · FAISS · Transformers |

</details>

---

### `$ cat agent_state_machine.yaml`

```yaml
orchestrator_pattern: Supervisor-Worker State Machine
graph_topology      :
  - node: supervisor_router    # Intent classification & task decomposition
  - node: research_agent       # Tool execution (SerpApi, Tavily, Indian Railways)
  - node: planner_agent        # Constraint satisfaction & itinerary synthesis
  - node: writer_agent         # Pydantic v2 validated structured output formatting
execution_guarantees:
  - deterministic_fallback    # Automatic switch from cloud Groq to local Ollama on failure
  - loop_prevention           # State-tracked recursion limits & dynamic retry logic
  - full_observability        # Real-time token latency & trace tracking with LangSmith
```

---

### `$ cat routing_table.yaml`

```yaml
agentic_orchestration : [LangGraph, LangChain, Multi-Agent DAGs, Tool-Calling, MCP, LangSmith, Structured Outputs]
machine_learning_nlp  : [PyTorch, Hugging Face, DistilBERT, Sentence-Transformers, LoRA/PEFT, scikit-learn]
retrieval_and_storage : [ChromaDB, FAISS, Vector Search, Semantic Chunking, PostgreSQL, NumPy, pandas]
backend_and_devops    : [FastAPI, Pydantic v2, Docker, Docker Compose, AWS EC2, REST APIs, Git, Ollama]
languages             : [Python, C, SQL, JavaScript, HTML/CSS]
```

---

### `$ cat leadership_and_org.log`

- **Coordinator**, *Data Science & AI (DSAI) Club, IIT Bhilai* (Apr 2026 – Present)
  - Leading institute-wide workshops on Transformer architectures and Multi-Agent LLM workflows; directed selections across 2 phases for 50+ members.
- **Convenor**, *Fintech Society, IIT Bhilai* (Aug 2025 – May 2026)
  - Organized algorithmic trading hackathons and statistical modeling bootcamps.
- **Certified Mentor**, *Student Mentorship Program (SMP), IIT Bhilai*

---

### `$ cat activity_graph`

<p align="center">
  <img src="https://raw.githubusercontent.com/siddheshbansal/siddheshbansal/main/assets/github-contribution-grid-snake.svg" width="100%" alt="GitHub Contribution Graph"/>
</p>

---

### `$ connect`

```
email    : siddheshb@iitbhilai.ac.in
web      : https://siddheshbansal.github.io
github   : https://github.com/siddheshbansal
linkedin : https://linkedin.com/in/siddhesh-bansal
terminal : siddhesh@iitbhilai:~$ exit
```
