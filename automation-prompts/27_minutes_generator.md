# 🚀 Meeting Minutes Generator

## 🧩 Problem Statement
Manually recording meeting minutes, action items, and decisions from rough notes or recordings is time-consuming and prone to missing key points. A standardized generator can automate this task while maintaining a professional and structured tone.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an Executive Assistant and AI Business Analyst focused on meeting productivity.

### 🔹 Task Definition
Create a Python chatbot for Google Colab that generates structured meeting minutes. The tool should take inputs for Meeting Title, Attendee Names, Main Topics Discussed (rough notes), and Decisions Made, and output a complete meeting minutes document in standard business format.

### 🔹 Context
OPG Power's leadership team needs to create meeting minutes for board meetings, vendor negotiations, or safety audits. The document should include a "Next Steps" section with clear owner assignments.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with four text input fields for title, attendees, topics, and decisions.
3. An LLM prompt using `llama-3.1-8b-instant` to generate a formatted meeting minutes document (Meeting Details, Attendee List, Discussion Points, Decisions, Action Items).
4. Logic to show the final minutes (in markdown format) and a "Summary" in the Gradio UI.
5. Clear comments explaining the document structure.

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
A customized and professional meeting minutes document for OPG Power, including technical action items and decisions.

---

## 💡 Example Use Case
Inputs: "Title: Monthly Safety Audit Recap, Attendees: Plant Manager, Safety Officer, Maintenance Head, Topics: Recent near-miss incidents, new safety gear deployment, Decisions: Replacement of aging harness systems." AI generates: "MEETING MINUTES: Monthly Safety Audit Recap. Action Item: Procurement to order 50 new safety harnesses by EO Month."
