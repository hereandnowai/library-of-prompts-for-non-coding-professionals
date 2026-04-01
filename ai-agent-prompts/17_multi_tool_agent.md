# 🚀 Multi-Tool Agent

## 🧩 Problem Statement
Simple AI agents can only perform one task at a time—they can't look at a spreadsheet while also checking the web or generating an email. A multi-tool agent can intelligently switch between different "modules" like file reading, search, and email generation to complete a complex business objective.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Lead Operations Automation Architect specializing in building "Universal AI Assistants" that use a suite of tools for file analysis, search, and business outreach.

### 🔹 Task Definition
Create a Google Colab Python script that initializes a multi-tool agent with 3 specific tools: `read_excel_summary`, `duckduckgo_search_run`, and `draft_email_response`. Use `llama-3.1-8b-instant` to analyze a user's goal (e.g., "Analyze this sales report, find the latest news for our top client, and draft a high-quality email update").

### 🔹 Context
Useful for senior executives and regional managers who need a single "command center" for multiple business operations. The agent should intelligently sequence the tools.

### 🔹 Output Format
- **Python Code**: Modular structure for tool definitions, the orchestrator, and LangChain's AgentExecutor.
- **Tool Usage**: `@tool` decorators for each capability and LangChain's LLM chain.
- **Gradio UI**: Input for the complex business objective and an "Agent Logs" area to show which tools were called.
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
- **Production-ready code**: Must handle tool errors and provide a unified, multi-part final answer.
- **No placeholders**

---

## ✅ Expected Outcome
A powerful multi-purpose assistant that turns a complex multi-step request into a sequence of tool-powered business actions in seconds.

---

## 💡 Example Use Case
"Summarize the main points of this 10-page contract, then search the web for any recent news about our partner company and draft a clear follow-up email."
