# 🚀 Document Q&A Bot (RAG)

## 🧩 Problem Statement
Manually searching through long PDF reports, contracts, or technical manuals is time-consuming. This tool allows users to upload a document and ask natural language questions to get immediate, accurate answers based on the content.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an expert Python Developer and AI Automation Engineer specializing in building RAG (Retrieval Augmented Generation) applications for non-coding professionals in the power industry.

### 🔹 Task Definition
Create a complete, single-file Python script designed for Google Colab that implements a Document Q&A (RAG) Bot. The application must allow users to upload PDF or text files, process them into a vector store, and provide a chat interface for querying the document content.

### 🔹 Context
The tool is intended for OPG Power employees to analyze annual reports, PPA contracts, and plant safety manuals. Accuracy is critical, and the UI should be simple enough for non-technical staff to use.

### 🔹 Output Format
Generate a single Python code cell including:
1. Pip install commands for `langchain`, `langchain-groq`, `langchain-huggingface`, `faiss-cpu`, `gradio`, and `pypdf`.
2. Logic to load and split documents into chunks using `RecursiveCharacterTextSplitter`.
3. Vector store initialization using `FAISS` and `HuggingFaceEmbeddings`.
4. Integration with Groq LLM via `ChatGroq`.
5. A user-friendly Gradio interface with a file upload component and a chat window.
6. Clear comments for each functional block.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`)
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Must run flawlessly in Google Colab.
- **Security**: Use the environment variable `GROQ_API_KEY` for the API key.
- **Reliability**: No placeholders; provide fully functional production-ready code.

---

## ✅ Expected Outcome
A fully operational RAG chatbot where users can upload a file and receive instant AI-powered answers based on that file's specific data.

---

## 💡 Example Use Case
An engineer uploads a 200-page boiler maintenance manual and asks: "What is the recommended torque for the main flange bolts?"
