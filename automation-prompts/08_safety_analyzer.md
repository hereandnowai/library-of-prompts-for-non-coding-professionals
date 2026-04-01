# 🚀 Safety Incident Analyzer

## 🧩 Problem Statement
Large power plants capture thousands of safety incident logs, but manual review fails to identify hidden patterns and high-risk zones. OPG Power needs an automated way to analyze these logs and predict where the next incident might occur.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Health, Safety, and Environment (HSE) Specialist and AI Data Scientist.

### 🔹 Task Definition
Develop a Python tool for Google Colab that accepts a CSV file of safety incidents (Date, Location, Incident Type, Severity, Description). The tool should perform AI-powered pattern analysis to identify high-risk areas, frequent peak times, and generate preventive recommendations.

### 🔹 Context
OPG Power's safety managers need to analyze trends across multiple plant facilities. The tool should help in identifying which units need more safety training or equipment upgrades.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `pandas`, `matplotlib`, `langchain`, `langchain-groq`, and `gradio`.
2. Logic to process and visualize data using `Pandas` and `Matplotlib` (bar charts for incident types/locations).
3. An LLM prompt that analyzes the incident descriptions to detect systemic safety issues.
4. A Gradio interface with a file uploader and a combined output of charts and an AI report.
5. Clear comments explaining each analytical section.

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
A visual and AI-driven report that highlights safety "hotspots" and suggests specific corrective measures.

---

## 💡 Example Use Case
Analyzing a year's worth of data: "Coal Handling Plant (CHP) shows a 25% increase in near-miss incidents on night shifts. Recommendation: Improve lighting and increase supervisor rounds."
