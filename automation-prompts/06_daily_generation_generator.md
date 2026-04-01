# 🚀 Daily Generation Report Generator

## 🧩 Problem Statement
Plant engineers spend hours manually compiling daily generation data (MW, hours, coal burnt) into formatted reports. Automating this report creation saves time and reduces calculation errors.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Power Plant Operations Specialist and Python Analyst.

### 🔹 Task Definition
Develop a Python tool for Google Colab that takes generation inputs (MW, hours, coal energy, coal weight) via a Gradio form and automatically calculates PLF (Plant Load Factor), heat rate, and specific coal consumption, generating a formatted daily report.

### 🔹 Context
OPG Power's Tamil Nadu plants need standard daily reports. The tool should use AI to provide a summary of performance trends based on the day's numbers.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with number-entry fields for data input.
3. Python logic for engineering calculations (PLF, Heat Rate).
4. An LLM prompt that takes these values and generates an "Executive Insight" on plant health.
5. A final button to "Generate Report" that displays the full formatted markdown.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`)
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Optimized for Google Colab.
- **Security**: Use `GROQ_API_KEY` environment variable.
- **Reliability**: Fully functional code.

---

## ✅ Expected Outcome
A professional plant generation report generated in seconds with zero manual calculation.

---

## 💡 Example Use Case
An engineer enters: "Unit 1: 520 MW, 24 Hours, 8500 Tons of Coal." The tool calculates 94% PLF and generates an AI summary: "Excellent plant health observed; sustained high-load operations."
