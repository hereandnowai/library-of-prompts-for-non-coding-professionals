# 🚀 CV Analyzer & Shortlister

## 🧩 Problem Statement
Reviewing hundreds of resumes for technical roles like plant engineers is a manual, error-prone, and slow process. HR needs a fast way to rank candidates based on their alignment with specific job descriptions.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an expert AI HR Automation Specialist and Python Engineer building intelligent recruitment tools.

### 🔹 Task Definition
Create a Python application for HR that accepts a Job Description (text) and multiple PDF resumes. The tool should use AI to analyze each resume, score it against the JD (0-100), and present a ranked summary table of candidates.

### 🔹 Context
OPG Power's HR team is hiring for thermal power station roles. The tool should identify specific skills like thermal power experience, boiler operation, or safety certifications.

### 🔹 Output Format
A single Python cell for Google Colab containing:
1. Pip install for `pypdf`, `langchain`, `langchain-groq`, and `gradio`.
2. A function to extract text from multiple PDF uploads.
3. An LLM-powered scoring function using a prompt that evaluates relevance to the JD.
4. A Gradio interface with two inputs: Job Description (textbox) and Resumes (file uploader for multiple files).
5. Output of a structured summary table showing candidate names, scores, and key skill highlights.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`)
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Works in Google Colab.
- **Security**: Use `GROQ_API_KEY` environment variable.
- **Reliability**: Fully functional, production-ready code.

---

## ✅ Expected Outcome
A ranking system where HR can see at a glance which 5 candidates out of 50 are best suited for the role.

---

## 💡 Example Use Case
Hiring for a "Senior Maintenance Engineer" role. AI scans 50 resumes and identifies 3 candidates with over 10 years of specific boiler turbine experience.
