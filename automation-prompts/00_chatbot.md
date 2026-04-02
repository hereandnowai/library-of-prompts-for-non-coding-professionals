# 🚀 Simple Chatbot

## 🧩 Problem Statement
Non-coding professionals often need a quick, private, and customizable chatbot interface to interact with advanced LLMs like Llama 3 via Groq, without dealing with complex deployment or expensive subscriptions.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are an expert AI Full-Stack Engineer and Prompt Architect specializing in rapid prototyping with LangChain and Gradio.

### 🔹 Task Definition
Create a production-ready, single-cell Python script for Google Colab that launches a clean, interactive Chatbot UI.

### 🔹 Context
The user needs a reliable "entry-point" application to test the Groq `llama-3.1-8b-instant` model. This chatbot should handle conversation history and provide a professional interface for OPG Power employees to query general information.

### 🔹 Output Format
Generate a single Python code block including:
1. Necessary `pip install` commands for `langchain-groq` and `gradio`.
2. A `GROQ_API_KEY` input mechanism using `google.colab.userdata` or `getpass`.
3. A LangChain `ChatGroq` implementation with memory handling.
4. A Gradio `ChatInterface` for a modern, responsive user experience.
5. In-line documentation and professional comments.

### 🔹 Constraints
- **Framework**: LangChain (`ChatGroq`).
- **Inference**: Groq API.
- **Model**: `llama-3.1-8b-instant`.
- **UI**: Gradio (`gr.ChatInterface`).
- **Environment**: Google Colab compatible.
- **Safety**: Use environment variables or `getpass` for the API Key.
- **Reliability**: No placeholders; code must be 100% runnable.

---

## ✅ Expected Outcome
A fully functional web-based chatbot UI running directly from a Google Colab cell. Users can type messages and receive near-instant responses from the Llama 3.1 model with conversation memory.

---

## 💡 Example Use Case
An OPG Power manager uses the chatbot to quickly draft a memo, summarize a brief note, or ask for explanations of energy sector terminology during a meeting.
