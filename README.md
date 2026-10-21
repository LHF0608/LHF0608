## Hi there 👋, I'm Liu Hongfei

> Building things with LLMs, one commit at a time.

I love to talk on trending ⚡ AI / LLM technology ⚡, stay hungry stay foolish.

---

### 🚀 Projects

#### 👗 [衣智客服助手 (YiZhi-CS)](https://github.com/LHF0608/yizhi-cs)
**Intelligent E-Commerce Customer Service & RAG Policy QA System**

- Tiered Model Architecture: lightweight tasks (intent/slot/rerank/summary) on qwen3.7-flash (200~300ms), complex reasoning on qwen3.8-max; disabled deep thinking to cut latency from 69.8s to 3~10s
- Three-layer Memory Engine: Write-Through to MySQL + Redis, 12-turn incremental summary (≤250 chars), ~35% token reduction
- Anti-hallucination RAG: query rewrite → dual-mode embedding (DashScope / Feature Hashing fallback) → rerank Top-4 → forced [1][2] citation, hallucination rate 30% → <5%
- Stack: Python · FastAPI · LangChain · MySQL · Redis · Chroma · Streamlit · DashScope

#### 🎮 [sgame-smart-recorder](https://github.com/LHF0608/sgame-smart-recorder)
Automated screen recording & OCR-naming asset manager for mobile games, supports KernelSU / SukiSU / Magisk.

---

### 🛠️ Tech Stack

**AI / LLM**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6B6B?logo=openai&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen-FF8C00?logo=alibabacloud&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)

**Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?logo=visual-studio-code&logoColor=white)

---

### 📫 Connect

[![Email](https://img.shields.io/badge/Email-255235351@qq.com-D14836?logo=gmail&logoColor=white)](mailto:255235351@qq.com)
[![GitHub](https://img.shields.io/badge/GitHub-LHF0608-181717?logo=github&logoColor=white)](https://github.com/LHF0608)

---

<p align="center">
  <i>Stay hungry, stay foolish. Always learning, always building.</i>
</p>