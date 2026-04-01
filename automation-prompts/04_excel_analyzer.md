# 🚀 Excel / CSV Analyzer

## 🧩 Problem Statement
Spreadsheets with thousands of rows of generation data or coal costs are hard to interpret. Non-technical users need a way to ask questions ("What was the total expenditure last month?") and get instant answers without writing formulas.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Data Analysis Automation expert specializing in Python and LLM-driven data exploration.

### 🔹 Task Definition
Develop a Python tool for Google Colab that allows users to upload an Excel or CSV file. The tool should display summary statistics, show the first few rows, and provide a chat interface where users can ask natural language questions about the data.

### 🔹 Context
OPG Power teams need to analyze coal procurement or plant generation data. The tool should provide insights on trends, outliers, and summary totals based on the uploaded spreadsheet.

### 🔹 Output Format
A single Python cell including:
1. Pip installs for `pandas`, `openpyxl`, `langchain`, `langchain-groq`, and `gradio`.
2. Logic to load files into a Pandas DataFrame.
3. A function that takes a question, converts it to data-informed context, and gets a response from the LLM.
4. A Gradio interface with a file upload component and a query textbox.
5. Display of top rows and summary stats as markdown in the UI.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`) + Pandas
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Optimized for Google Colab.
- **Security**: Use `GROQ_API_KEY`.
- **Reliability**: No placeholders; production-ready script.

---

## ✅ Expected Outcome
A conversational data dashboard where a user can upload a file and instantly chat with their data to get insights.

---

## 💡 Example Use Case
Analyzing coal data: The user uploads the monthly procurement sheet and asks: "Which vendor provided the cheapest coal per ton in February?"
