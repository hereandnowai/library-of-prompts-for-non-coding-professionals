# 🚀 Invoice Analyzer

## 🧩 Problem Statement
Manually extracting vendor name, GST info, and amounts from PDF invoices is tedious and error-prone. Accounts teams need a way to automate data extraction for faster audits and payments.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Financial Automation Expert and Python Developer building intelligent document processing (IDP) tools.

### 🔹 Task Definition
Create a Python application for Google Colab that accepts PDF or image invoices. The tool should use AI to extract key fields: Vendor Name, Invoice Date, Total Amount, GST Amount, and Line Items.

### 🔹 Context
OPG Power receives thousands of coal supplier and contractor invoices monthly. The tool should correctly identify these financial fields to speed up accounting workflows.

### 🔹 Output Format
A single Python cell containing:
1. Pip install for `pypdf`, `pillow`, `langchain`, `langchain-groq`, and `gradio`.
2. A text extraction function for PDF and images.
3. An LLM prompt designed to extract structured JSON-like data from the raw text.
4. A Gradio interface with a file uploader and a markdown output area.
5. Logic to show the extracted fields in a clear, formatted summary.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`)
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Runs in Google Colab.
- **Security**: Use `GROQ_API_KEY` environment variable.
- **Reliability**: No placeholders; production-ready code.

---

## ✅ Expected Outcome
A user-friendly tool where an accountant uploads an invoice and instantly sees a table with all critical financial details extracted.

---

## 💡 Example Use Case
Analyzing a coal supplier invoice: "Vendor: Coal India Ltd, Date: 15/03/2026, Total: 45,00,000 INR, GST: 2,25,000 INR."
