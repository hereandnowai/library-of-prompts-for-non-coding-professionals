# 🚀 Search Agent

## 🧩 Problem Statement
Finding precise answers to business questions across the depth of the web is time-consuming when using standard search engines. A search agent can intelligently query multiple sources (like Google, Bing, or specialized business databases), synthesize the findings, and provide a single, verified answer.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Lead Business Researcher and Intelligence Analyst who builds high-accuracy, multi-source AI agents that find and verify data across the internet.

### 🔹 Task Definition
Create a Google Colab Python script that uses `llama-3.1-8b-instant` to analyze a business query (e.g., "What is the 2024 pricing strategy for Tesla in Southeast Asia?"), uses a search tool (like SerpAPI or DuckDuckGo) to fetch multiple current sources, and consolidates the best data into a summary in a Gradio UI.

### 🔹 Context
Useful for startup founders, market researchers, and executives who need high-signal business intelligence without the noise of search results. It should provide citations for all claims.

### 🔹 Output Format
- **Python Code**: Modular functions for querying, summarizing, and citation extraction.
- **Tool Usage**: `langchain-community`, `duckduckgo-search`, or `google-search-results`.
- **Gradio UI**: Input for the business query, a "Search and Summarize" button, and a large formatted output area for findings with links.
- **Google Colab-ready**: Include all `pip install` commands.

### 🔹 Constraints
- **Python only**
- **LangChain (langchain-groq)**
- **Groq API**
- **Model**: `llama-3.1-8b-instant`
- **Gradio UI**
- **Google Colab compatible**
- **Include pip installs**
- **Use GROQ_API_KEY**
- **Single runnable script**
- **Production-ready code**: Solid error handling for search failures or no-data scenarios.
- **No placeholders**

---

## ✅ Expected Outcome
A high-accuracy research tool that functions like a dedicated business analyst who has thoroughly researched any topic on the web for you.

---

## 💡 Example Use Case
"Research the current market developments in the Indian green hydrogen sector and provide a list of the top 3 emerging startups with their latest funding details."
