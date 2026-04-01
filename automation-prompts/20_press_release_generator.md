# 🚀 Press Release Generator

## 🧩 Problem Statement
Manually drafting press releases for news like financial results or PPA signings is a slow and repetitive process. A standard template and AI can generate professional-grade press releases in seconds.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a PR Manager and Corporate Communications Consultant specializing in industrial journalism.

### 🔹 Task Definition
Develop a Python tool for Google Colab that generates professional press releases. The tool should take inputs for Headline, Key Facts (bullet points), Quote (from CEO/Exec), and Company Name, and output a complete press release in standard AP format.

### 🔹 Context
OPG Power needs standard press releases for its Tamil Nadu plants and quarterly financial results. The tool should include a standard company boilerplate and a media contact section.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with four text input fields for Headline, Facts, Quote, and Company.
3. An LLM prompt using `llama-3.1-8b-instant` to generate a formatted press release (Headline, Subhead, Dateline, Body paragraphs, Media section).
4. Logic to display the final text in a markdown-formatted block in the Gradio UI.
5. Clear comments explaining the press release structure.

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
A professional-grade press release for OPG Power that is ready for distribution to media outlets.

---

## 💡 Example Use Case
Inputs: "Headline: OPG Power FY26 Q3 Profit Grwoth, Facts: 15% increase in generation, Quote: 'We are delighted with our record performance'." AI generates: "FOR IMMEDIATE RELEASE: OPG Power Reports Record Profits in Q3 FY2026..."
