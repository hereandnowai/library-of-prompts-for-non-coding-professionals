# 🚀 API Call Agent

## 🧩 Problem Statement
Business professionals often need data from third-party services like weather, stock markets, or CRM tools but lack the technical skills to write API connectors. This agent can automatically fetch data from a provided API endpoint, process the JSON response, and present it in a readable format.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Cloud Integration Specialist who builds robust AI agents capable of connecting to RESTful APIs, parsing complex JSON structures, and generating human-readable insights.

### 🔹 Task Definition
Develop a Python-based AI agent that takes a generic API URL (or a specific one like OpenWeatherMap) as input, handles the requests, and uses `llama-3.1-8b-instant` to analyze and format the raw data.

### 🔹 Context
This tool is for analysts who need real-time data integration. The prompt should explain how to handle different response codes and structure the final report into logical sections (Data Point, Interpretation, Action Item).

### 🔹 Output Format
- **Python Code**: Modular structure with a clear function for API handling and another for the AI analysis.
- **Tool Usage**: Use LangChain's `RequestsWrapper` or a custom `PythonReplTool` approach for fetching data.
- **Gradio UI**: Inputs for the API URL, API Key (if needed), and a text box for the analysis.
- **Google Colab-ready**: Include all `pip install` commands.

### 🔹 Constraints
- **Python only**
- **LangChain (langchain-groq)**
- **Groq API**
- **Model**: `llama-3.1-8b-instant`
- **Gradio UI**
- **Google Colab compatible**
- **Include pip installs**: `!pip install requests langchain-groq gradio`
- **Use GROQ_API_KEY**
- **Single runnable script**
- **Production-ready code**: Must handle timeouts and invalid API keys gracefully.
- **No placeholders**

---

## ✅ Expected Outcome
An intelligent bridge that converts raw, technical API data into ready-to-use business intelligence via a simple web UI.

---

## 💡 Example Use Case
"Fetch the current stock price and financial ratios for Reliance Industries and explain what they mean for a long-term investor."
