# 🚀 PDF Summarizer

## 🧩 Problem Statement
Manually reading long PDF documents (annual reports, technical specifications, or compliance filings) is time-consuming. An automated summarizer can condense these documents into a 5-minute read while retaining all critical data points.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Document Knowledge Engineer and AI Information Specialist.

### 🔹 Task Definition
Create a Python application for Google Colab that summarizes long PDF documents. The tool should take an uploaded PDF file and output a concise summary including Key Highlights, Main Data Points, and Critical Risks.

### 🔹 Context
OPG Power's leadership team needs to quickly summarize annual reports, regulatory filings, or large-scale contract documents. The summary should prioritize financial or operational KPIs.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `pypdf`, `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with a file upload component for PDFs.
3. Python logic to extract text from the PDF using `pypdf`.
4. An LLM prompt using `llama-3.1-8b-instant` to generate a 3nd-level hierarchical summary (Executive, Technical, Risks).
5. Logic to show the final summary in a markdown-formatted area in the Gradio UI.

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
A concise and data-rich summary for any PDF document, ready to be reviewed in minutes.

---

## 💡 Example Use Case
Analyzing a 150-page annual report: "Revenue: 15,000 Cr, Operating Margin: 12%. Key Risk: Higher coal logistics costs detected in western region operations."
