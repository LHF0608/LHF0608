## Hi there 👋, I'm Liu Hongfei

> 求职方向：**AI 大模型应用开发** | 坐标：江西景德镇 | 可 7 天内入职

I'm passionate about building LLM-powered applications with solid engineering practices.

---

### 🚀 Featured Projects

#### 👗 [衣智客服助手 (YiZhi-CS)](https://github.com/LHF0608/yizhi-cs)
**服装电商智能客服与规章问答系统** — 基于大模型分层架构 + 企业级 RAG

- **Tiered Model Architecture**：轻量任务（意图识别/槽位抽取/Rerank/摘要）走 qwen3.7-flash（200~300ms），复杂推理走 qwen3.8-max；关闭深度思考将延迟从 69.8s 压至 3~10s
- **三层记忆引擎**：Write-Through 双写 MySQL + Redis，12 轮触发 ≤250 字增量摘要，Token 消耗降低 ~35%
- **严谨防幻觉 RAG**：指代消解改写 → 双模向量召回（百炼 embedding / Feature Hashing 容灾降级）→ qwen3.7-flash 重排 Top-4 → 强制 [1][2] 原文页码角标溯源，幻觉率 30% → <5%
- **技术栈**：Python · FastAPI · LangChain · MySQL · Redis · Chroma · Streamlit · DashScope

#### 🎮 [sgame-smart-recorder](https://github.com/LHF0608/sgame-smart-recorder)
王者荣耀智能录屏素材管理 — 自动录屏/截图/OCR 命名，支持 KernelSU/SukiSU/Magisk

---

### 🛠️ Tech Stack

**AI / LLM**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6B6B?logo=openai&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen-FF8C00?logo=alibabacloud&logoColor=white)

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

### 📫 Contact

[![Email](https://img.shields.io/badge/Email-255235351@qq.com-D14836?logo=gmail&logoColor=white)](mailto:255235351@qq.com)
[![Phone](https://img.shields.io/badge/Phone-15607073967-25D366?logo=whatsapp&logoColor=white)](tel:15607073967)
[![GitHub](https://img.shields.io/badge/GitHub-LHF0608-181717?logo=github&logoColor=white)](https://github.com/LHF0608)

---

<p align="center">
  <i>Stay hungry, stay foolish. Always learning, always building.</i>
</p>