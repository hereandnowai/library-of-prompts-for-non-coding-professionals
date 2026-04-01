# 🚀 Training Needs Bot

## 🧩 Problem Statement
Manually identifying training gaps for technical engineers and operations staff is complex due to various skill sets. A personalized training bot can recommend the best certifications and upskilling paths based on an employee's current profile.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Learning & Development (L&D) Specialist and AI Education Consultant.

### 🔹 Task Definition
Create a Python chatbot for Google Colab that recommends personalized training programs. The tool should take inputs for Employee Role, Current Skills, Performance Rating, and Department, and use AI to output a suggested learning path with specific certifications.

### 🔹 Context
OPG Power's engineering and operations staff need power sector-specific certifications (e.g., Boiler Competency, HSE Certification). The bot should prioritize these based on the employee's career progression.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with text input fields (role, skills, rating, department).
3. An LLM prompt that takes these details and generates a "3-Level Training Roadmap" (Basic, Intermediate, Advanced).
4. Logic to show the final training recommendations in a clear markdown format.
5. Clear comments explaining the role-to-training mapping.

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
A customized training plan for any engineer or staff member at OPG Power, including specific Indian energy sector certifications.

---

## 💡 Example Use Case
Inputs: "Role: Junior Engineer, Skills: Mechanical Basics, Rating: Good, Department: Turbine Maintenance." AI generates: "Roadmap: 1. Advanced Turbine Hydraulics, 2. Vibration Analysis Level-1, 3. BOE (Boiler Operation Engineer) certification training."
