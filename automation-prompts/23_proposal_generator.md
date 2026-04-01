# 🚀 Project Proposal Generator

## 🧩 Problem Statement
Plant engineers and managers spend too much time manually drafting project proposals for plant upgrades, maintenance, or new technology adoptions. A standardized proposal generator can automate this process while maintaining a professional and technical tone.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Project Management Professional (PMP) and AI Solutions Architect specializing in industrial infrastructure proposals.

### 🔹 Task Definition
Create a Python chatbot for Google Colab that generates a professional project proposal. The tool should take inputs for Project Name, Problem Statement, Proposed Solution, Estimated Budget, and Timeline, and output a complete project proposal in standard business format.

### 🔹 Context
OPG Power's engineering team needs to create proposals for boiler overhauls, turbine upgrades, or new solar installations. The tool should include technical risk assessments and ROI calculations.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with five text input fields for project name, problem, solution, budget, and timeline.
3. An LLM prompt using `llama-3.1-8b-instant` to generate a formatted project proposal (Project Name, Executive Summary, Scope, Timeline, Budget, Risks, ROI).
4. Logic to show the final proposal (in markdown format) and a "Key Highlights" summary in the Gradio UI.
5. Clear comments explaining the proposal structure.

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
A customized project proposal for OPG Power, including technical risk assessments and ROI calculations.

---

## 💡 Example Use Case
Inputs: "Name: Unit 1 Boiler Efficiency Upgrade, Problem: High coal consumption, Solution: New Low-NOx burners, Budget: 5 Cr, Timeline: 6 months." AI generates: "Executive Summary: OPG Power's Unit 1 is experiencing higher than average heat rates. We propose the installation of..."
