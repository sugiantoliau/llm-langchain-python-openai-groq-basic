# llm-langchain-python-openai-groq-basic

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

## ⚙️ Setup Instructions

To run these notebooks locally, you need to configure your environment variables securely so the LangChain framework can authenticate with the LLM providers.


### 1. Create a `.env` File, then fill your key

```bash
OPENAI_API_KEY=sk-proj-your_actual_openai_key_here
GROQ_API_KEY=gsk_your_actual_groq_key_here
```

### 2. Create a `.gitignore` File
To prevent your private API keys from accidentally being pushed to GitHub, ensure you have a `.gitignore` file in the root directory of your project containing the following line:
```
.env
.ipynb_checkpoints/
```


### 3. Open and Run the Notebooks

Launch your Jupyter environment (via VS Code, Jupyter Lab, or Jupyter Notebook) and select the pipeline execution style you want to explore:

- For OpenAI Workflows: Open and run all cells inside llm-langchain-python-openai-basic.ipynb

- For Groq Cloud Workflows: Open and run all cells inside llm-langchain-python-groq-basic.ipynb