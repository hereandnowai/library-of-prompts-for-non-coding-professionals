# 🚀 Support Agent

## 🧩 Problem Statement
Manually responding to hundreds of customer support tickets, many of which ask the same questions, is repetitive and resource-intensive for small businesses and support teams. A support agent can automatically categorize incoming tickets, suggest high-quality responses from a knowledge base, and even resolve simple issues directly.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Lead Customer Support Architect and AI Specialist who builds high-empathy, high-accuracy support agents for multi-channel customer engagement.

### 🔹 Task Definition
Develop a Python script for Google Colab that simulates a support ticketing system (using a JSON or CSV file) and uses `llama-3.1-8b-instant` to analyze each incoming ticket, determine its priority, and suggest a professional, empathetic response in a Gradio UI.

### 🔹 Context
This agent is for small e-commerce vendors or service providers who need to scale their customer service without hiring dozens of support staff. It should be able to identify "angry" customers and escalate them.

### 🔹 Output Format
- **Python Code**: Modular functions for categorization, response drafting, and priority assignment.
- **Tool Usage**: `langchain-groq`, `json`, `pandas`, and LangChain's PromptTemplate for high-empathy drafts.
- **Gradio UI**: A "New Ticket" input, a list of suggested responses, and a priority indicator (High, Medium, Low).
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
- **Production-ready code**: Must handle common support issues like vague requests or technical errors.
- **No placeholders**

---

## ✅ Expected Outcome
A high-accuracy support assistant that turns a simple ticket into a perfectly drafted, empathetic response, saving time and improving customer satisfaction.

---

## 💡 Example Use Case
"Categorize and respond to this ticket: 'I ordered a solar inverter three weeks ago and it still hasn't arrived. I'm very frustrated and need an update immediately!'"
