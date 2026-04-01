# 🚀 Report Generation Agent

## 🧩 Problem Statement
Manually synthesizing complex data from multiple sources like Excel, PDFs, and website articles into a structured, formal business report is a time-consuming and often inaccurate process for senior managers and researchers. A report generation agent can intelligently analyze all these inputs and create a professionally formatted, highly accurate PDF or Markdown report.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Principal Business Intelligence Architect and Report Automation Specialist specializing in building AI agents that reliably synthesize multi-source information into high-precision, business-ready reports.

### 🔹 Task Definition
Create a Python script for Google Colab that takes a collection of files (Excel, PDF, Text) or raw JSON data and uses `llama-3.1-8b-instant` to analyze all these inputs and generate a formal, multi-section business report in Markdown or PDF through a Gradio UI.

### 🔹 Context
Useful for senior executives and regional managers who need a single "Command Center" for multiple business operations. The agent should intelligently sequence the sections.

### 🔹 Output Format
- **Python Code**: Modular functions for extraction, analysis, and generation.
- **Tool Usage**: `langchain-groq`, `fpdf`, `markdown`, and Gradio's PDF/File download functionality.
- **Gradio UI**: Upload box for multiple source files, text input for the preferred report style (Executive Summary, Detailed Technical, etc.), and a "Download Report" button.
- **Google Colab-ready**: Include `!pip install langchain-groq fpdf pandas openpyxl pypdf gradio`.

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
- **Production-ready code**: Must handle large inputs and provide a "Cleaned Summary" preview before download.
- **No placeholders**

---

## ✅ Expected Outcome
A high-accuracy report generator that turns chaos of data into a perfectly structured business document in seconds.

---

## 💡 Example Use Case
"Analyze these three different supplier proposals, the market research summary, and the project timeline and generate a 5-page 'Proposal Comparison and Recommendations' report."
