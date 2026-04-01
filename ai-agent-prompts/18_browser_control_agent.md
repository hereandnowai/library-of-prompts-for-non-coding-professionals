# 🚀 Browser Control Agent

## 🧩 Problem Statement
Manually clicking through 20 websites, filling out forms, or checking for specific updates on dynamic web pages is repetitive and tedious behavior. A browser control agent can intelligently navigate a browser (via Playwright or a similar library) and perform complex, multi-step actions on the user's behalf.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Lead Web Automation Architect and AI Specialist who builds "UI-aware" agents that can interact with the DOM, fill forms, and navigate complex web architectures using Python and LLMs.

### 🔹 Task Definition
Create a Google Colab Python script that uses `playwright-python` or a similar tool and `llama-3.1-8b-instant` to take a natural language command (e.g., "Go to OPG Power's website, find the 'Contact Us' page, and extract all their location addresses and emails").

### 🔹 Context
Useful for administrative staff, sales teams, and marketing researchers who need to interact with websites that don't provide a public API. The agent should intelligently sequence the clicks and navigation.

### 🔹 Output Format
- **Python Code**: Modular functions for browser control (using `playwright`), UI-aware navigation, and LLM-based parsing.
- **Tool Usage**: `playwright`, `langchain-groq`, and LangChain's PromptTemplate for intent mapping.
- **Gradio UI**: Input for the web task, and a large formatted output area for extracted info and a status log.
- **Google Colab-ready**: Include `!pip install playwright langchain-groq gradio && playwright install-deps chromium`.

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
- **Production-ready code**: Must handle common browser issues like slow loading or missing elements.
- **No placeholders**

---

## ✅ Expected Outcome
A powerful web automation assistant that turns a simple command into a perfectly navigated browser interaction and extractions.

---

## 💡 Example Use Case
"Open the IRCTC website, find the train availability from Chennai to Delhi for next Monday, and tell me the cheapest Sleeper class fare."
