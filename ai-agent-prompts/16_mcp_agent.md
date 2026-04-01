# 🚀 MCP Agent

## 🧩 Problem Statement
Many AI agents are limited to silos—they can either browse the web or read files, but rarely both at the same time or with custom tools. A Model Context Protocol (MCP) agent can dynamically discover and use specialized "MCP Tools" (like a local calculator, a database connector, or a weather tool) to solve complex, multi-step tasks.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Lead AI Architect specializing in the Model Context Protocol (MCP) and building interoperable agents that can use any external tool or service to perform complex tasks.

### 🔹 Task Definition
Develop a Google Colab Python script that simulates an MCP server (with 2-3 mock tools like `get_weather`, `calculate_loan_emi`, and `search_internal_kb`) and uses `llama-3.1-8b-instant` as the orchestrator to dynamically choose and use these tools to answer a user's complex query.

### 🔹 Context
Useful for advanced operations teams and data scientists who need to connect AI with proprietary internal tools. The agent should intelligently sequence tool calls.

### 🔹 Output Format
- **Python Code**: Modular structure for tool definitions, the MCP orchestrator, and LangChain's AgentExecutor.
- **Tool Usage**: Use LangChain's `@tool` decorator or `StructuredTool` classes.
- **Gradio UI**: Input for the complex query and a "Thought Trace" area showing which tools were called and why.
- **Google Colab-ready**: Include `!pip install langchain-groq gradio`.

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
- **Production-ready code**: Must handle tool failures and provide a clear, unified answer.
- **No placeholders**

---

## ✅ Expected Outcome
A high-accuracy, tool-using assistant that turns a multi-step problem into a series of logical tool calls and a single, verified response.

---

## 💡 Example Use Case
"Calculate the monthly EMI for a 50 lakh loan at 8.5% for 20 years, then check the current Pune weather and tell me if it's a good time to visit a property for inspection."
