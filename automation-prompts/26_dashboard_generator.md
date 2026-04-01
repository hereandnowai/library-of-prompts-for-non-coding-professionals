# 🚀 Dashboard Generator

## 🧩 Problem Statement
Manually creating dashboards for plant performance or financial metrics in Excel or BI tools takes too much effort for non-technical managers. A standardized dashboard generator can automate the creation of a visual summary from a CSV.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Business Intelligence (BI) Analyst and AI Dashboard Architect specializing in industrial performance metrics.

### 🔹 Task Definition
Develop a Python tool for Google Colab that generates a visual dashboard from a CSV file. The tool should take a CSV of Performance Indicators (Metric, Value, Previous, Trend) and output a clean, formatted dashboard with color-coded trend indicators.

### 🔹 Context
OPG Power's plant managers need to visualize daily KPIs for generation, coal stock, and safety. The dashboard should use green for positive trends and red for negative ones.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `pandas`, `langchain`, `langchain-groq`, and `gradio`.
2. Logic to process and summarize the CSV using `Pandas`.
3. An LLM prompt using `llama-3.1-8b-instant` to analyze the KPIs and generate an "Executive Summary" on plant performance.
4. A Gradio interface with a file uploader and a combined analytical dashboard displaying charts (if applicable) and a summary table.
5. Clear comments explaining the trend analysis logic.

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
A professional-grade dashboard for OPG Power that is ready for management review.

---

## 💡 Example Use Case
Analyzing a daily KPI file: "Generation: 1200 MW (Trend: ⏫ Up), Coal Stock: 15 Days (Trend: ⏬ Down). AI Insight: Generation is stable but coal stock needs urgent replenishment."
