# 🚀 Data Entry Agent

## 🧩 Problem Statement
Manually entering thousands of line items from paper or digital forms into a CRM or specialized software is error-prone and time-consuming for administrative staff. A data entry agent can intelligently read the data from any source and format it into a clean, ready-to-import CSV or JSON file.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Cloud Automation Architect and Data Engineer specializing in building AI agents that reliably perform text-to-structured-data transformations using LLMs.

### 🔹 Task Definition
Develop a Python script for Google Colab that takes a raw, messy text input (e.g., a digitized form or an email with customer details) and uses `llama-3.1-8b-instant` to create a clean, exportable CSV or JSON format in a Gradio UI.

### 🔹 Context
Useful for administrative staff, HR, and sales professionals who need to move and clean data between platforms. The agent should intelligently detect and fix common data entry errors (like missing @ symbols in emails).

### 🔹 Output Format
- **Python Code**: Modular functions for extraction, formatting, and export.
- **Tool Usage**: `langchain-groq`, `pandas`, and Gradio's "Download File" functionality.
- **Gradio UI**: Input for the raw text, the desired fields (e.g., "Full Name, Email, Address, Phone"), and a "Generate CSV" button.
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
- **Production-ready code**: Must handle common data issues and provide a "Cleaned Data" preview before download.
- **No placeholders**

---

## ✅ Expected Outcome
A high-accuracy data entry assistant that turns hours of manual typing into seconds of automated text-to-data mapping.

---

## 💡 Example Use Case
"Extract the customer names, phone numbers, and addresses from this list of 50 new registrations in this email and create a clean CSV for our CRM import."
