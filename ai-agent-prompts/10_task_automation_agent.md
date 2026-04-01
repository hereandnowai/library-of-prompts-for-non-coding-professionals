# 🚀 Task Automation Agent

## 🧩 Problem Statement
Manually tracking long to-do lists across emails, Slack, and handwritten notes leads to missed deadlines and disorganized project management for busy professionals. A task automation agent can automatically identify new tasks from raw text and organize them into a structured database or Trello-like board.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Personal Productivity and Workflow Automation Expert who specializes in using LLMs to extract actionable tasks and deadlines from unstructured text for non-technical users.

### 🔹 Task Definition
Create a Python script for Google Colab that takes a raw text input (e.g., meeting transcript or a collection of emails) and uses `llama-3.1-8b-instant` to identify all mentioned tasks, assigns priority, and extracts due dates into a clean table in a Gradio UI.

### 🔹 Context
Useful for administrative staff and project managers who need to synthesize action items from long meetings. The agent should intelligently detect the "owner" of each task if mentioned.

### 🔹 Output Format
- **Python Code**: Modular functions for extraction, prioritization, and formatting.
- **Tool Usage**: `langchain-groq`, `pandas`, and Gradio's DataFrame or Table output.
- **Gradio UI**: A large text box for the source text and a tabular view of the extracted tasks.
- **Google Colab-ready**: Include `!pip install langchain-groq pandas gradio`.

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
- **Production-ready code**: Must handle multiple tasks in one request and provide a clear, logical priority level (High, Medium, Low).
- **No placeholders**

---

## ✅ Expected Outcome
A high-accuracy task manager that turns chaotic meeting notes or emails into a perfectly structured project board in seconds.

---

## 💡 Example Use Case
"Extract all the tasks from this project kickoff transcript and tell me who is responsible for each one and when they are due."
