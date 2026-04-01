# 🚀 CRM Agent

## 🧩 Problem Statement
Manually updating CRM details across multiple platforms or trying to pull a quick customer history for a client meeting is a major bottleneck for sales professionals and account managers. A CRM agent can automatically find, update, or summarize customer records from a provided data source.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Cloud Sales Automation Architect and CRM Specialist who builds AI-powered agents for high-accuracy customer data management and history summarization.

### 🔹 Task Definition
Create a Python script for Google Colab that simulates a CRM (using a simple JSON or CSV backend) and uses `llama-3.1-8b-instant` to handle natural language requests (e.g., "Summarize the last 3 call logs for Mr. Advani and update his status to 'Negotiation'").

### 🔹 Context
Useful for sales representatives and account managers who need a quick, natural interface for complex customer data systems. It should be able to resolve name ambiguities.

### 🔹 Output Format
- **Python Code**: Modular functions for searching, updating, and summarizing.
- **Tool Usage**: `langchain-groq`, `json`, `pandas`, and LangChain's PromptTemplate for intent mapping.
- **Gradio UI**: Input for the request, and a structured output area for the customer summary and a log of all updates.
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
- **Production-ready code**: Must handle common CRM issues like duplicate records or missing fields.
- **No placeholders**

---

## ✅ Expected Outcome
A high-accuracy customer service assistant that turns a simple sentence into a perfectly managed customer record, saving time and improving CRM data quality.

---

## 💡 Example Use Case
"What is the current status and latest activity for ABC Corp, and can you update the 'Last Contacted' date to today?"
