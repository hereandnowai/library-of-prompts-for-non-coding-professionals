# 🚀 Employee Onboarding Checklist Generator

## 🧩 Problem Statement
Manually creating onboarding checklists for new hires in different departments is inconsistent and time-consuming. HR needs a way to standardize the experience for every new employee.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an HR Automation Specialist and Python Engineer building intelligent onboarding workflows.

### 🔹 Task Definition
Create a Python application for Google Colab that generates a professional onboarding checklist for new hires. The tool should take inputs for Employee Name, Department, Role, and Joining Date, then use AI to create a complete, role-specific onboarding plan with milestones and a "Welcome Email" draft.

### 🔹 Context
OPG Power's HR team is onboarding for technical plant roles (Shift Engineer, Maintenance) and corporate roles. The tool should include technical safety inductions for plant positions.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with text input fields (name, department, role, date).
3. An LLM prompt that takes these details and generates a structured checklist for the first 30 days.
4. Logic to show the final checklist and welcome email draft in a markdown-formatted area.
5. Clear comments for each functional block.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`)
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Runs in Google Colab.
- **Security**: Use `GROQ_API_KEY`.
- **Reliability**: Fully functional, production-ready code.

---

## ✅ Expected Outcome
A customized onboarding plan for any new hire at OPG Power, including specific training requirements like "Plant Safety Protocols."

---

## 💡 Example Use Case
HR inputs: "Name: Rajesh, Department: Operations, Role: Shift Engineer." AI generates: "Checklist: 1. Safety Gear Issued, 2. Plant Control Room Induction, 3. Emergency Evacuation Walkthrough..."
