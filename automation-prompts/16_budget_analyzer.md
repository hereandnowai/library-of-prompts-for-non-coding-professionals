# 🚀 Budget vs Actual Analyzer

## 🧩 Problem Statement
Monthly budget tracking is a complex task involving hundreds of line items. Manually calculating variances and explaining them in management reports takes too much time for plant accountants.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Management Accountant and AI Data Scientist specializing in financial variance analysis.

### 🔹 Task Definition
Develop a Python tool for Google Colab that accepts two files: a Budget Plan (CSV) and Actual Expenses (CSV). The tool should calculate variance percentages per category, identify top overspend areas, and use AI to generate management commentary explaining the likely reasons.

### 🔹 Context
OPG Power's plant operation managers need to track monthly expenditures for coal, maintenance, and administrative costs. The tool should compare current spending against the annual budget and highlight critical deviations.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `pandas`, `matplotlib`, `langchain`, `langchain-groq`, and `gradio`.
2. Logic to merge the budget and actual CSV data using `Pandas`.
3. Matplotlib code to generate a "Budget vs Actual" bar chart for the top 5 cost categories.
4. An LLM prompt using `llama-3.1-8b-instant` to analyze the variances and propose "Management Commentary" on cost-saving measures.
5. A Gradio interface with two file upload components and a combined analytical dashboard.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`) + Pandas + Matplotlib
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Optimized for Google Colab.
- **Security**: Use `GROQ_API_KEY`.
- **Reliability**: No placeholders; production-ready script.

---

## ✅ Expected Outcome
A professional variance report with charts and AI-driven insights that tell the plant manager exactly where the money went and why they are over budget.

---

## 💡 Example Use Case
Analyzing a month's performance: "Maintenance spares are 20% over budget. AI Insight: Likely due to unplanned outage of Unit 2. Recommendation: Review inventory levels for critical turbine components."
