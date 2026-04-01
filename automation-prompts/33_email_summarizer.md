# 🚀 Email Summarizer

## 🧩 Problem Statement
Manually reading and processing hundreds of emails from vendors, clients, and partners is time-consuming for OPG Power's corporate teams. An automated summarizer can condense long email threads into a 1-minute read while retaining all critical action items.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an Executive Communication Specialist and AI Information Architect.

### 🔹 Task Definition
Create a Python application for Google Colab that summarizes long email text or uploaded email threads (.msg or .txt). The tool should output a concise "Inbox Report" including Sender Info, Primary Request, and 3-5 Key Action Items.

### 🔹 Context
OPG Power's leadership team needs to quickly summarize vendor negotiations, internal policy updates, or large-scale project coordination emails. The summary should prioritize "Who needs to do what by when."

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with a large text box or file upload for email text.
3. An LLM prompt using `llama-3.1-8b-instant` to generate a structured email summary (Sender, Purpose, Key Quotes, Action Items).
4. Logic to show the final summary in a markdown-formatted area in the Gradio UI.
5. Clear comments explaining the summarization logic.

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
A concise and strategic "Inbox Report" for any email, ready to be reviewed in seconds.

---

## 💡 Example Use Case
Analyzing a 10-email thread: "Summary: Coal supplier requesting 5-day delivery delay. Action Items: 1. Logistics head to confirm stock levels, 2. Finance to verify penalty clauses."
