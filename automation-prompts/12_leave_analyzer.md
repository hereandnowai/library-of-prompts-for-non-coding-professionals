# 🚀 Leave Management Analyzer

## 🧩 Problem Statement
Manually reviewing thousands of leave requests makes it difficult for HR to spot absenteeism trends or departmental leave imbalances that could affect plant operations.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a People Analytics Expert and Python Developer focusing on HR efficiency.

### 🔹 Task Definition
Develop a Python tool for Google Colab that accepts a CSV file of employee leave data (Employee ID, Name, Department, Leave Type, Dates). The tool should perform AI-powered analysis to identify absenteeism trends, calculate department-wise leave percentages, and flag unusual patterns.

### 🔹 Context
OPG Power's HR managers need to ensure critical plant units are adequately staffed during peak periods. The tool should identify if any specific technician groups have high concurrent leave rates.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `pandas`, `langchain`, `langchain-groq`, and `gradio`.
2. Logic to process the CSV data using `Pandas`.
3. An LLM prompt using `llama-3.1-8b-instant` to analyze the summarized data and detect potential policy violations or risks.
4. A Gradio interface with a file uploader and a summary area showing charts (using markdown-based table or simple bars) and AI insights.
5. Clear comments explaining the analytical logic.

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
A clear visual and AI-driven report that tells HR exactly which departments have high leave risks or attendance anomalies.

---

## 💡 Example Use Case
Analyzing a month's data: "Maintenance Dept shows 15% absenteeism on Fridays. Recommendation: Investigate shift rotations or review leave approval policies for the technical team."
