# 🚀 GST Helper

## 🧩 Problem Statement
Manually calculating Input Tax Credit (ITC) and Output GST from hundreds of purchase and sales invoices leads to errors and filing delays. Finance teams need a way to automate GST reconciliation and preparation.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Tax Technology Consultant and AI Automation Engineer building intelligent GST compliance tools.

### 🔹 Task Definition
Create a Python application for Google Colab that calculates and summarizes GST data. The tool should take two CSV files: Purchase Registry and Sales Registry, and perform calculations for Input GST, Output GST, and Net Payable/Refundable.

### 🔹 Context
OPG Power's finance teams need to simplify monthly GST filing. The tool should use AI to validate common errors like mismatched GSTINs or wrong HSN codes.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `pandas`, `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with two file upload components for the Purchase and Sales CSVs.
3. Python logic using `Pandas` to aggregate taxes by GST type (IGST, CGST, SGST).
4. An LLM prompt using `llama-3.1-8b-instant` to generate a summary report in the format of GSTR-1 and GSTR-3B filings.
5. A dynamic table output in the Gradio UI showing the reconciliation.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`) + Pandas
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Runs in Google Colab.
- **Security**: Use `GROQ_API_KEY`.
- **Reliability**: Fully functional, production-ready code.

---

## ✅ Expected Outcome
A user-friendly tool where a tax accountant uploads two files and instantly sees their GST liability and ITC status.

---

## 💡 Example Use Case
Analysis: "Sales: 5,00,00,000 INR (GST: 60,00,000), Purchases: 3,00,00,000 INR (GST: 36,00,000). Net Payable: 24,00,000 INR. AI Validation: No GSTIN mismatches found."
