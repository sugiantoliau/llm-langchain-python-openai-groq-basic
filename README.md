# llm-langchain-python-basic


# LangChain & Agentic AI Exploration

A repository dedicated to learning and implementing LLM orchestration using LangChain. This project transitions from basic sequential chains to an autonomous Agentic AI framework.

## 🚀 Features & Milestones

* **Sequential Chains:** Built robust pipelines combining prompt templates and LLMs.
* **Multi-Provider Integration:** Swapped seamless integration between **OpenAI (GPT-4o-mini)** and **Groq (Llama 3.1)**.
* **Agentic Workflows:** Implemented ReAct agents capable of leveraging automated tools (e.g., Python REPL executor).
* **Database Integration Concept:** Explored foundational architecture for linking agentic tools to a MySQL database for live data insights.

## 🛠️ Tech Stack

* **Framework:** LangChain
* **LLM Providers:** OpenAI API, Groq Cloud API
* **Models Used:** `gpt-4o-mini`, `llama-3.1-8b-instant`
* **Language:** Python 3.11+

## 🔒 Security Note
This project utilizes `python-dotenv` to manage environments. All private API credentials (`OPENAI_API_KEY`, `GROQ_API_KEY`) are kept local and excluded from version control via `.gitignore`.