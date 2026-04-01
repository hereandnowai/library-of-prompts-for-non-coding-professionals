# 🚀 Browser Agent

## 🧩 Problem Statement
Many non-technical professionals spend hours manually searching for information across multiple websites and summarizing findings for reports. A browser agent can automate this by navigating the web, identifying relevant data, and providing a synthesized answer.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an expert AI Web Automation Engineer specializing in building LangChain agents that utilize search tools to interact with the web and extract high-quality information.

### 🔹 Task Definition
Create a Google Colab-compatible Python script that launches a Gradio UI. The app should take a user query, use a search tool (like DuckDuckGo via LangChain) to browse the web, and use the Groq `llama-3.1-8b-instant` model to summarize the findings.

### 🔹 Context
This agent is designed for business researchers who need to stay updated on industry trends or competitor news without manually visiting dozens of sites. It should be able to handle complex queries like "What are the latest developments in hydrogen fuel cell technology for 2024?"

### 🔹 Output Format
- **Python Code**: A single, clean, and well-commented cell for Google Colab.
- **Modular Structure**: Define tools, initialize the agent with memory, and wrap it in a Gradio interface.
- **Tool Usage**: Use `DuckDuckGoSearchRun` or similar LangChain-integrated search tools.
- **Gradio UI**: A simple text input for the query and a large text area for the agent's summarized response.

### 🔹 Constraints
- **Python only**
- **LangChain (langchain-groq)**
- **Groq API**
- **Model**: `llama-3.1-8b-instant`
- **Gradio UI**
- **Google Colab compatible**: Use `google.colab` for secret handling if needed, or simple input.
- **Include pip installs**: `!pip install langchain-groq duckduckgo-search gradio`
- **Use GROQ_API_KEY**: Retrieve from environment or user input.
- **Single runnable script**: No external dependencies beyond pip.
- **Production-ready code**: Solid error handling for search failures.
- **No placeholders**: Ensure all logic is complete.

---

## ✅ Expected Outcome
A fully functional web search agent that can autonomously browse the internet and provide a consolidated answer to any query provided through a sleek Gradio interface.

---

## 💡 Example Use Case
"Research the current market share of top 5 renewable energy companies in India and summarize their 2023 performance."
