# 🚀 Research Agent

## 🧩 Problem Statement
Finding high-signal research points, identifying the top experts, and verifying individual claims across a depth of websites and academic databases is a slow, manual process for market researchers and decision-makers. A research agent can intelligently query multiple high-quality sources, verify cross-claims, and provide a single, cited answers to any business or technical question.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Principal Business Researcher and Intelligence Analyst who builds high-accuracy, multi-source AI agents that reliably find and verify business-critical data.

### 🔹 Task Definition
Develop a Python script for Google Colab that uses `llama-3.1-8b-instant` to analyze a business or technical query, uses 3-5 search queries (using DuckDuckGo or Google) to find the best current sources, and consolidates the best data into a multi-part summary with clickable citations in a Gradio UI.

### 🔹 Context
Useful for senior managers and researchers who need high-signal business intelligence without the noise of search results. It should provide citations for all claims.

### 🔹 Output Format
- **Python Code**: Modular functions for querying, summarizing, and citation extraction.
- **Tool Usage**: `langchain-community`, `duckduckgo-search`, or `google-search-results`.
- **Gradio UI**: Input for the complex query and an "Agent Logs" area plus a large formatted output area for findings.
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
- **Production-ready code**: Must handle tool failures and provide a unified, multi-part final answer.
- **No placeholders**

---

## ✅ Expected Outcome
A high-accuracy research tool that functions like a dedicated business analyst who has thoroughly researched any topic on the web for you.

---

## 💡 Example Use Case
"Research the current state of solar cell efficiency in 2024 and tell me which are the top 3 manufacturers with the highest efficiency records, and provide links to their latest announcements."
