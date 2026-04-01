# 🚀 Expense Validator

## 🧩 Problem Statement
Manually reviewing thousands of expense claims (especially when split across multiple vendors and dates) makes it difficult for finance teams to spot duplicate claims or policy violations.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Financial Auditor and AI Automation Architect building automated internal audit tools.

### 🔹 Task Definition
Create a Python application for Google Colab that validates expense reports. The tool should take a CSV of expense claims (Employee Name, Date, Category, Amount, Receipt Description) and use AI to check for policy violations like duplicate claims, exceeded limits, and weekend expenses.

### 🔹 Context
OPG Power's finance teams need to audit thousands of employee travel and operational expense claims monthly. The tool should flag suspicious entries such as "Multiple meals on the same day" or "Excessive local travel."

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `pandas`, `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with a file upload component for the CSV.
3. Python logic using `Pandas` to identify exact and near-duplicates based on date and amount.
4. An LLM prompt using `llama-3.1-8b-instant` to analyze the "Receipt Description" and flag policy-violating or unusual patterns.
5. A dynamic table output in the Gradio UI showing a "Validation Report."

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
A color-coded dashboard where finance teams can see which expense claims are safe to approve and which need closer inspection.

---

## 💡 Example Use Case
Analyzing an expense file: "Two entries of 4500 INR for 'Site Visit Taxi' on the same date by the same employee. AI Result: Flagged as 'Potential Duplicate'. Recommended action: Reject one entry."
