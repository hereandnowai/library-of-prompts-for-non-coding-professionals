# 🚀 File Organizer Agent

## 🧩 Problem Statement
Manually sorting hundreds of downloaded files, invoices, and project documents into appropriate folders based on their content is a tedious daily task. A file organizer agent can intelligently read the content or properties of a file and move it to the correct folder.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Desktop Automation Specialist who builds high-efficiency AI agents that manage local and cloud files using Python's file system tools and LLMs for content classification.

### 🔹 Task Definition
Develop a Python script for Google Colab that scans a user-provided directory, reads each file's metadata and content, and uses `llama-3.1-8b-instant` to categorize and move files into dynamically created subfolders (e.g., /Invoices, /Contracts, /Personal).

### 🔹 Context
Useful for administrative staff and project managers who deal with thousands of miscellaneous documents. The agent should intelligently detect the document's type and intent from its file name or first few paragraphs.

### 🔹 Output Format
- **Python Code**: Modular functions for scanning, reading, categorizing, and moving files.
- **Tool Usage**: `os`, `shutil`, `pathlib`, and LangChain's LLM chain for categorization.
- **Gradio UI**: Input for the target directory and a "Start Organization" button. Show a log of all moved files.
- **Google Colab-ready**: Include all `pip install` commands.

### 🔹 Constraints
- **Python only**
- **LangChain (langchain-groq)**
- **Groq API**
- **Model**: `llama-3.1-8b-instant`
- **Gradio UI**
- **Google Colab compatible**
- **Include pip installs**: `!pip install langchain-groq gradio`
- **Use GROQ_API_KEY**
- **Single runnable script**
- **Production-ready code**: Must handle permissions errors and avoid overwriting existing files.
- **No placeholders**

---

## ✅ Expected Outcome
A clean, automated file system that sorts and organizes documents with zero manual effort, ensuring all project files are always where they belong.

---

## 💡 Example Use Case
"Organize my 'Downloads' folder by sorting all files containing 'contract' into a 'Legal' folder and all files with 'Receipt' or 'Invoice' into an 'Expenses' folder."
