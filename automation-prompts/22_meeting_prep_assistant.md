# 🚀 Meeting Prep Assistant

## 🧩 Problem Statement
Reviewing long documents (contracts, reports, resumes) before every meeting is time-consuming. An automated assistant can summarize these documents and generate a list of key questions for the meeting attendee.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an Executive Assistant and AI Knowledge Analyst focused on organizational efficiency.

### 🔹 Task Definition
Develop a Python tool for Google Colab that prepares a meeting summary. The tool should take an uploaded PDF or text file and output a one-page "Meeting Prep Sheet" including Main Summary, Key Stakeholders, and 5 Strategic Questions to ask.

### 🔹 Context
OPG Power managers need to quickly prep for board meetings, vendor negotiations, or safety audits. The tool should condense 50-page documents into a 5-minute read.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `pypdf`, `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with a file upload component.
3. An LLM prompt using `llama-3.1-8b-instant` to analyze the document and summarize it.
4. Logic to show the final "Meeting Prep Sheet" in a markdown-formatted block in the Gradio UI.
5. Clear comments explaining the summarization logic.

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
A concise and strategic "Meeting Prep Sheet" for any document, ready to be reviewed before a meeting.

---

## 💡 Example Use Case
Analyzing a coal supply contract: "Summary: 2-year contract with Coal India, 50,000 tons/month. Questions: 1. How is the quality bonus calculated? 2. What are the delivery penalty clauses?"
