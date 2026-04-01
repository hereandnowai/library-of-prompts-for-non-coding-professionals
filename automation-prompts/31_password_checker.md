# 🚀 Password Strength Checker

## 🧩 Problem Statement
Weak passwords are a significant security risk for plant control systems and corporate accounts. Employees need a fast, non-technical way to check their password strength and receive specific advice for improvement.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Cybersecurity Analyst and AI Security Consultant specializing in industrial IT/OT security.

### 🔹 Task Definition
Create a Python chatbot for Google Colab that evaluates password strength. The tool should take a text input and output a Strength Score (0-10), a list of detected weaknesses (e.g., "Too short," "No special characters"), and a specific recommendation.

### 🔹 Context
OPG Power employees need to ensure their access to SCADA systems, SAP, or personal company accounts is secure. The tool should NOT store or transmit the password, but analyze it locally in the browser/Colab environment.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with a single text box for password input (using `type='password'`).
3. Python logic or an LLM prompt using `llama-3.1-8b-instant` to evaluate the password quality without revealing it.
4. Logic to show the final "Strength Report" and an AI-generated suggestion for a more secure pattern.
5. Clear comments explaining the password evaluation logic.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`)
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Runs in Google Colab.
- **Security**: Use `GROQ_API_KEY`. NEVER print or log the original password input.
- **Reliability**: Fully functional, production-ready code.

---

## ✅ Expected Outcome
A customized and professional password strength report for OPG Power, providing actionable security advice.

---

## 💡 Example Use Case
Inputs: "Pass@123". AI generates: "Strength: 4/10. Weaknesses: Using common patterns, lack of complexity. Suggestion: 'Include more than 12 characters and avoid common words like 'Pass'."
