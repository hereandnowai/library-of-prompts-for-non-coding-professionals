# 🚀 SOP Generator

## 🧩 Problem Statement
Manually creating Standard Operating Procedures (SOPs) for new plant equipment, maintenance tasks, or safety drills is a slow and repetitive process. A standard template and AI can generate professional-grade SOPs in seconds.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an Operations Management Consultant and AI Workflow Architect specializing in industrial and energy sectors.

### 🔹 Task Definition
Develop a Python tool for Google Colab that generates professional SOPs. The tool should take inputs for Process Name, Objective, Rough Steps (bullet points), and Safety Precautions, and output a complete SOP in standard business format.

### 🔹 Context
OPG Power needs standard SOPs for its plant operations, maintenance, and administrative procedures. The tool should include a standard company header and a "Approval Section" boilerplate.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with four text input fields for process name, objective, steps, and safety.
3. An LLM prompt using `llama-3.1-8b-instant` to generate a formatted SOP (Header, Objective, Equipment Needed, Step-by-Step Procedure, Safety Rules, Record Keeping).
4. Logic to display the final text in a markdown-formatted block in the Gradio UI.
5. Clear comments explaining the SOP structure.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`)
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Optimized for Google Colab.
- **Security**: Use `GROQ_API_KEY`.
- **Reliability**: No placeholders; production-ready script.

---

## ✅ Expected Outcome
A professional-grade SOP for OPG Power that is ready for plant distribution.

---

## 💡 Example Use Case
Inputs: "Name: Boiler Cold Start, Objective: Safely start unit after 72-hour outage, Steps: 1. Open main steam valve, 2. Check feedwater pressure, 3. Ignite burners." AI generates: "SOP: Boiler Cold Start. Pre-requisites: Full PPE required. Step 1: Ensure all manual isolation valves are in 'Closed' position..."
