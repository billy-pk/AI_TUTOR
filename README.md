# 🧑‍🏫 AI Tutor – Agentic Educational Assistant

AI Tutor is an **agentic AI web app** that acts like a **teacher**, providing educational assistance across **all domains**.  
It can answer user queries directly or, when necessary, **search the web** for up-to-date information to provide accurate answers.  
Built with the **[OpenAI Agents SDK](https://openai.github.io/openai-agents-python/)** for agent orchestration and **[Chainlit](https://docs.chainlit.io/)** for the interactive user interface.


## ✨ Features

- 📚 **Domain-Agnostic Education** – Ask about science, technology, math, history, or any topic.  
- 🌐 **Web Search Integration** – Uses an agentic search tool to fetch live information from the internet.  
- 🤝 **Conversational UI** – Powered by Chainlit for a modern, chat-like experience.  
- 🧠 **OpenAI Agents SDK** – Handles reasoning, tool selection, and response generation.  


##  Installation

### Clone the repository
git clone https://github.com/billy-pk/ai_tutor.git

cd ai_tutor

### Create and activate a virtual environment
uv venv

Windows: .venv\Scripts\activate

### Install dependencies

uv sync

### Set Environment Variables

Create a .env file and set environment variables.

### Run Locally

uv run chainlit run study_mode_agent.py 

Open your browser at http://localhost:8000/





