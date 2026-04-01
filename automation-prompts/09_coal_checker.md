# 🚀 Coal Quality Checker

## 🧩 Problem Statement
Manually grading coal based on GCV, moisture, and ash content is cumbersome and leads to inconsistent blending and poor plant heat rates. OPG Power needs an automated tool to instantly grade incoming coal shipments.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Power Plant Chemist and Fuel Management Automation Engineer.

### 🔹 Task Definition
Create a Python tool for Google Colab that takes inputs for Coal Parameters (GCV, Moisture %, Ash %, Volatile Matter %, Sulphur %) and automatically grades the coal (A-F) while recommending the best blending ratios for optimal combustion.

### 🔹 Context
OPG Power's fuel quality teams need to verify coal shipments at the point of receipt and decide how to blend them for the boiler. The tool should use AI to provide "Mixing Recommendations" for different coal grades.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with numerical input sliders for GCV, Moisture, etc.
3. Python logic to apply standard Indian coal grading rules (G1 to G17 or A-F scales).
4. An LLM prompt using `llama-3.1-8b-instant` to generate a report on combustion risks (e.g., slagging, corrosion).
5. Output of a Gradio dashboard showing the grade and the AI's advice.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`)
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Runs in Google Colab.
- **Security**: Use `GROQ_API_KEY` environment variable.
- **Reliability**: Fully functional, production-ready code.

---

## ✅ Expected Outcome
A precision fuel tool that tells a plant chemist exactly what quality of coal they have and how to use it safely.

---

## 💡 Example Use Case
Inputs: "GCV: 4200, Ash: 38%, Moisture: 12%." AI response: "Grade: E. Blending: Mix with Grade B coal (ratio 2:1) to maintain design heat rate and prevent slagging."
