# 🤖 Agentic AI 

Welcome to the **Agentic AI** repository by **Shantanu Patil**. This repository showcases real-world applications, research experiments, and demos built using **Agentic AI** principles powered by frameworks like **CrewAI**, **LangChain**, **Neo4j**, and **LLM APIs (Mistral, OpenAI, Claude)**.

> 🚀 Our goal: Build autonomous, goal-driven agents that solve complex tasks with reasoning, memory, and collaboration.

---

## 🧠 What is Agentic AI?

**Agentic AI** refers to systems that behave like intelligent agents — capable of perception, reasoning, planning, and decision-making — often working in teams or with other agents to complete complex goals autonomously.

These systems often involve:
- Autonomous decision-making
- Multi-agent orchestration
- Knowledge graphs
- Memory and reasoning
- Tool use (APIs, search, DBs)

---


## 🛠️ Tech Stack

- 🧠 **LLMs**: OpenAI, Mistral, Claude
- 🤖 **CrewAI**: Multi-agent task orchestration
- 🔗 **LangChain**: LLM orchestration, tools, memory
- 🕸️ **Neo4j**: Knowledge graph DB for reasoning
- 🐍 **Python**: Backend and scripting
- 🌐 **FastAPI / Flask**: Lightweight APIs (where applicable)

---

## 🧪 How to Run (Basic Setup)

```bash
# Clone the repo
git clone https://github.com/Shantanu-9901/Agentic-AI-Projects.git
cd agentic-ai-projects

# (Recommended) Create a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Set your API keys in .env
cp .env.example .env
# Edit .env with OpenAI / Mistral / Neo4j creds

# Run a specific project
cd domain-explorer
python app.py
