# 🚀 Excel Agent

## 🧩 Problem Statement
Manipulating large, complex Excel spreadsheets using formulas can be difficult for non-technical users. An Excel agent can intelligently perform data analysis, cleanup, and even complex pivot-table-like operations using simple natural language requests.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Principal Data Analyst and Python Automation Specialist specializing in building Excel-aware AI agents for complex business reporting and data cleanup.

### 🔹 Task Definition
Develop a Google Colab Python script that uploads an Excel or CSV file, reads it into `pandas`, and uses `llama-3.1-8b-instant` to analyze the data and generate a summary or performing cleaning operations based on a user's natural language request (e.g., "Find the top 5 regions by sales and calculate the average growth rate for 2023").

### 🔹 Context
Useful for finance managers, operations leads, and project coordinators who need deep data insights without writing Excel macros or complex `pandas` code. It should provide both a summary and a "Modified Data" download.

### 🔹 Output Format
- **Python Code**: Modular functions for file handling, LLM-based analysis, and data export.
- **Tool Usage**: `pandas`, `openpyxl`, and LangChain's PromptTemplate for high-accuracy analysis.
- **Gradio UI**: File Upload box, text input for natural language commands, a "Run Analysis" button, and a download link for the updated file.
- **Google Colab-ready**: Include `!pip install openpyxl pandas langchain-groq gradio`.

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
- **Production-ready code**: Must handle large files and common Excel formatting issues.
- **No placeholders**

---

## ✅ Expected Outcome
A powerful data assistant that functions like a dedicated data analyst who can read and manipulate your Excel files for you.

---

## 💡 Example Use Case
"Analyze this sales report for 2023 and tell me which product categories had the highest decline in profit margins, and list the top 3 contributing factors."
