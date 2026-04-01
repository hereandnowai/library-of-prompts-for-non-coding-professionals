# 🚀 Equipment Maintenance Scheduler

## 🧩 Problem Statement
Manually tracking maintenance intervals for hundreds of plant components often leads to missed schedules and equipment downtime. A centralized tool is needed to ensure every critical part is serviced on time.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an Industrial Maintenance Engineer and Python Developer specializing in asset management automation.

### 🔹 Task Definition
Create a Python application for Google Colab that tracks equipment maintenance schedules. The tool should take inputs for equipment name, last maintenance date, maintenance interval (in days), and criticality level, and output a sorted table showing upcoming, due, and overdue maintenance tasks.

### 🔹 Context
OPG Power's maintenance teams track boilers, turbines, and coal handling units. The tool should use AI to provide "Maintenance Priority Recommendations" based on the age and criticality of the equipment.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `pandas`, `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with input fields (name, date, days, criticality).
3. Python logic using `datetime` and `pandas` to calculate next service dates and highlight overdue items.
4. An LLM prompt using `llama-3.1-8b-instant` to generate a priority list of maintenance tasks.
5. A dynamic table output in the Gradio UI showing the schedule.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`) + Pandas
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Runs in Google Colab.
- **Security**: Use `GROQ_API_KEY`.
- **Reliability**: Fully functional, production-ready code.

---

## ✅ Expected Outcome
A color-coded dashboard where maintenance teams can see what needs immediate attention and what is scheduled for the next week.

---

## 💡 Example Use Case
Tracking a boiler pump: "Unit 1 Boiler Feed Pump, Last Serviced: 01/01/2026, Frequency: 90 days." The tool flags this as "Due in 5 days" and AI recommends "Inspect for seal wear before summer peak."
