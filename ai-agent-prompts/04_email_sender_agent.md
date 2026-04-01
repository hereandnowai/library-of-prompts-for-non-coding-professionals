# 🚀 Email Sender Agent

## 🧩 Problem Statement
Manually writing and sending individual emails to different stakeholders is a repetitive and time-consuming task for account managers and project coordinators. An email sender agent can automate the generation of personalized messages and send them securely using SMTP or a provided API.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Communications Automation Architect who excels in building secure, context-aware AI agents for personal and professional outreach.

### 🔹 Task Definition
Develop a Google Colab Python script that uses `llama-3.1-8b-instant` to draft a professional email based on a brief description. The script should then use `smtplib` or a similar tool to send the email from a user-provided Gmail/Outlook account through a Gradio UI.

### 🔹 Context
Useful for sales professionals sending follow-ups or HR managers reaching out to candidates. The agent should intelligently suggest an appropriate tone (e.g., formal, friendly, urgent) based on the recipient's role.

### 🔹 Output Format
- **Python Code**: Modular functions for email drafting and SMTP-based sending.
- **Tool Usage**: `smtplib`, `email.mime`, and LangChain's PromptTemplate for high-quality drafting.
- **Gradio UI**: Inputs for the recipient's email, subject, brief context, and a "Send Email" button. Include a "Draft Preview" area.
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
- **Production-ready code**: Must handle authentication errors and use secure SMTP settings (TLS).
- **No placeholders**

---

## ✅ Expected Outcome
A powerful outreach tool that drafts and sends personalized, high-quality emails in seconds with just a few keywords from the user.

---

## 💡 Example Use Case
"Draft and send a follow-up email to Mr. Sharma regarding the HVAC maintenance contract renewal, emphasizing the 10% early-bird discount."
