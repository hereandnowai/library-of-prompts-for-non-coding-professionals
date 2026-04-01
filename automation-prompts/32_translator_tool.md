# 🚀 Translator Tool

## 🧩 Problem Statement
Manually translating technical manuals, safety protocols, or legal contracts into multiple regional languages is slow and expensive. An automated translator can bridge the language gap for OPG Power's multi-state operations instantly.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Linguistic Localization Expert and AI Translation Engineer focused on technical and industrial sectors.

### 🔹 Task Definition
Develop a Python tool for Google Colab that performs high-quality translations for any text or an uploaded PDF. The tool should use AI to translate from English to any major Indian language (e.g., Tamil, Hindi, Telugu, Kannada) and vice versa.

### 🔹 Context
OPG Power's engineering and operations teams need to translate equipment manuals or safety signs for local plant technicians in Tamil Nadu or other states. The translation should maintain technical context (e.g., "Boiler" should not be translated as a household kitchen item).

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `pypdf`, `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with a textbox or file uploader and a target language selection.
3. An LLM prompt using `llama-3.1-8b-instant` to perform the translation with "Technical Context Awareness."
4. Logic to show the final translated text in a markdown-formatted block in the Gradio UI.
5. Clear comments explaining the translation logic.

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
A professional-grade translator for OPG Power that is ready for plant operation teams.

---

## 💡 Example Use Case
Input: "Wear helmet and safety boots at all times." Target: Tamil. AI Result: "எல்லா நேரங்களிலும் தலைக்கவசம் மற்றும் பாதுகாப்பு காலணிகளை அணியுங்கள்."
