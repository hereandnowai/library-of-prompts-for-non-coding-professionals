# 🚀 WhatsApp Agent

## 🧩 Problem Statement
Many small businesses and independent contractors find it difficult to manage constant customer inquiries on WhatsApp while performing their daily tasks. A WhatsApp agent can automatically draft and send messages (via Twilio or a similar API) or respond to incoming messages based on predefined rules.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Social Media Automation Engineer and Chatbot Architect specializing in building AI-powered customer engagement agents for mobile messaging platforms.

### 🔹 Task Definition
Create a Python script for Google Colab that uses `llama-3.1-8b-instant` to generate a WhatsApp response based on a user's prompt (or a mock conversation). The script should then send the message using a WhatsApp-compatible API like Twilio.

### 🔹 Context
This agent is for solar panel installers or local vendors dealing with repetitive customer questions about pricing and availability. It should maintain a professional and helpful tone.

### 🔹 Output Format
- **Python Code**: Modular structure for message drafting and API-based sending.
- **Tool Usage**: Use `twilio` or `pywhatkit` for the messaging logic and LangChain for the AI generation.
- **Gradio UI**: Input for the customer's phone number, their message, and a button to respond.
- **Google Colab-ready**: Include `!pip install twilio langchain-groq gradio`.

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
- **Production-ready code**: Must handle common API errors and use secure credentials.
- **No placeholders**

---

## ✅ Expected Outcome
A messaging assistant that creates and sends professional, context-aware WhatsApp messages, saving time and improving customer response rates.

---

## 💡 Example Use Case
"Respond to a customer asking about the availability of high-efficiency solar panels for their 10kW home installation."
