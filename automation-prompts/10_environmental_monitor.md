# 🚀 Environmental Compliance Monitor

## 🧩 Problem Statement
Thermal power stations must strictly adhere to CPCB/SPCB emission norms. Manual data tracking for SO2, NOx, and particulate matter (PM) leads to delayed reporting and potential legal violations.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an Environmental Compliance Auditor and Sustainability Technologist specializing in industrial emission monitoring.

### 🔹 Task Definition
Build a Python-based Environmental Compliance Monitor for Google Colab. The tool should allow users to input emission readings (SO2, NOx, PM, CO2) and compare them against regulatory limits (e.g., CPCB/SPCB norms), flagging any violations and generating compliance summary text.

### 🔹 Context
OPG Power's environmental teams need to ensure their Tamil Nadu facilities are within legal limits. The tool should use AI to recommend "Corrective Operational Actions" if limits are exceeded.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with input number fields for SO2, NOx, and PM concentrations.
3. Logic that compares these to pre-configured regulatory limits.
4. An LLM prompt using `llama-3.1-8b-instant` to analyze the data and generate a professional compliance report summaries.
5. Display of "Compliance Status" indicators (Green/Yellow/Red) in the Gradio UI.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`)
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Optimized for Google Colab.
- **Security**: Use `GROQ_API_KEY`.
- **Reliability**: No placeholders; production-grade script.

---

## ✅ Expected Outcome
An instant compliance dashboard that tells the plant manager whether their unit is legally operating and what to adjust if not.

---

## 💡 Example Use Case
Reading: "SO2: 650 mg/Nm³ (Limit: 600)." AI result: "Violation Detected (115% of limit). Recommendation: Increase FGD (Flue Gas Desulfurization) unit efficiency and check limestone purity."
