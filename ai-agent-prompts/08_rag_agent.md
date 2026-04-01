# 🚀 RAG Agent

## 🧩 Problem Statement
Business professionals need to find information across multiple related documents, ranging from project manuals to training guides. A Retrieval-Augmented Generation (RAG) agent can store and search through this knowledge base, providing accurate answers based directly on the provided context.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Knowledge Management Architect and AI Engineer specializing in building RAG systems that link unstructured documents with high-precision LLMs using vector databases.

### 🔹 Task Definition
Create a Python script for Google Colab that builds a full RAG pipeline: uploading multiple text/PDF files, encoding them into a FAISS or ChromaDB vector store, and using `llama-3.1-8b-instant` for context-aware Q&A through a Gradio interface.

### 🔹 Context
Useful for corporate libraries and training departments maintaining internal policy documents. The agent should cite the specific document or section where it found the answer.

### 🔹 Output Format
- **Python Code**: Modular functions for document loading, splitting, vectorization, and retrieval.
- **Tool Usage**: `langchain-community`, `faiss-cpu`, `sentence-transformers`, and `langchain-groq`.
- **Gradio UI**: Upload box for multiple files, text input for queries, and a large output area showing findings and sources.
- **Google Colab-ready**: Include `!pip install faiss-cpu sentence-transformers langchain-groq pypdf gradio`.

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
- **Production-ready code**: Solid error handling for empty files or non-existent info.
- **No placeholders**

---

## ✅ Expected Outcome
A high-accuracy document assistant that provides detailed answers derived exclusively from the uploaded business knowledge base.

---

## 💡 Example Use Case
"What is our company's policy on remote work for employees in the IT department, and who is the final approving authority?"
