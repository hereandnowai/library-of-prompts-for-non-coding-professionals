# 🚀 Contract Clause Extractor

## 🧩 Problem Statement
Manually searching for specific clauses like "Termination," "Liability," or "Quality Bonus" in 100-page OPG Power contracts is slow and error-prone. A specialized extractor can find and summarize these clauses in seconds.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Legal Technology Specialist and AI Document Analyst specializing in industrial and energy sector contracts.

### 🔹 Task Definition
Create a Python application for Google Colab that extracts and summarizes specific legal clauses from PDF contracts. The tool should take an uploaded PDF and a list of target clause names, then output the verbatim text and a plain-English summary of each clause.

### 🔹 Context
OPG Power's legal and procurement teams need to verify PPA contracts, coal supply agreements, and contractor SLAs. Accuracy is critical, and the output should highlight specific financial penalties or timeframes mentioned in the clauses.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `pypdf`, `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with a PDF uploader and a checkbox list of common clauses (Termination, Indemnity, Force Majeure, etc.).
3. Python logic to extract PDF text and pass it to the LLM with a highly specific search prompt.
4. An LLM prompt using `llama-3.1-8b-instant` to find the exact clause and provide a non-legal summary.
5. A dynamic table output in the Gradio UI showing the results.

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
A powerful legal tool where a user uploads a contract and instantly extracts the most critical risk-related clauses.

---

## 💡 Example Use Case
Analyzing a coal supply agreement: "Termination Clause found on Page 45. Summary: Either party can terminate with 90 days notice if delivery fails for 3 consecutive months."
