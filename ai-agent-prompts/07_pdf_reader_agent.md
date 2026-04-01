# 🚀 PDF Reader Agent

## 🧩 Problem Statement
Manually reading and summarizing 50-page PDFs to find a single clause or data point is time-consuming for non-technical professionals. A PDF reader agent can quickly scan the entire document, identify the required information, and provide a direct answer with context.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Document Analysis Expert and AI Engineer who builds high-performance agents for reading complex PDF files, including text and simple tables, using Python and LLMs.

### 🔹 Task Definition
Develop a Google Colab Python script that uploads a PDF, extracts its text using `PyPDF2` or `pdfminer.six`, and uses `llama-3.1-8b-instant` to answer questions about the document in a Gradio UI.

### 🔹 Context
Useful for lawyers reviewing contracts or project managers analyzing vendor specifications. It should be able to handle dense, technical language and summarize key sections.

### 🔹 Output Format
- **Python Code**: Modular functions for file upload, text extraction, and question answering.
- **Tool Usage**: `PyPDF2`, `pdfminer.six`, and LangChain's PDF loading utilities.
- **Gradio UI**: A "File Upload" box for the PDF, a text input for the user's question, and a response area.
- **Google Colab-ready**: Include `!pip install pypdf2 langchain-groq gradio`.

### 🔹 Constraints
- **Python only**
- **LangChain (langchain-groq)**
- **Groq API**
- **Model**: `llama-3.1-8b-instant`
- **Gradio UI**
- **Google Colab compatible**
- **Include pip installs**
- **Use GROQ_API_KEY**
- **Single runnable script**
- **Production-ready code**: Must handle large PDFs by clever chunking and summarization.
- **No placeholders**

---

## ✅ Expected Outcome
A document assistant that behaves like an expert researcher who has read the PDF and can provide precise answers and summaries instantly.

---

## 💡 Example Use Case
"Summarize the limitation of liability clause in this 40-page maintenance contract and list the top 3 risks."
