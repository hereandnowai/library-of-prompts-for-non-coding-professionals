# 🚀 Cash Flow Forecaster

## 🧩 Problem Statement
Plant operations rely on a steady flow of cash for coal procurement and maintenance. Manually forecasting future cash availability based on historical data reaches limits when dealing with volatile prices and payment cycles.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Financial Planning and Analysis (FP&A) specialist and AI Data Scientist.

### 🔹 Task Definition
Develop a Python tool for Google Colab that forecasts future cash flow. The tool should accept a historical CSV file of monthly income and expenses (Date, Income, Expense, Category) and use simple trend analysis and AI to predict the next 3 months of cash availability.

### 🔹 Context
OPG Power's finance leadership needs to plan for coal procurement and revenue cycles. The tool should highlight potential "Cash Crunch" months based on historical peaks and troughs.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `pandas`, `matplotlib`, `langchain`, `langchain-groq`, and `gradio`.
2. Logic to perform a linear trend projection on the CSV data using `Pandas`.
3. Matplotlib code to generate a "3-Month Cash Flow Forecast" line chart.
4. An LLM prompt using `llama-3.1-8b-instant` to analyze the trend data and generate management commentary on working capital needs.
5. A Gradio interface with a file uploader and a combined forecast dashboard.

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
A professional cash flow forecast within seconds that shows a trend chart and provides AI-powered strategic advice.

---

## 💡 Example Use Case
Analyzing a years's data: "Forecast shows a 15% revenue drop in May due to summer peak PPA adjustments. Recommendation: Preserve cash in March and April for high coal procurement."
