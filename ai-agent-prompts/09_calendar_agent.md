# 🚀 Calendar Agent

## 🧩 Problem Statement
Coordinating multiple meetings, checking availability across calendars, and manually entering events into Google Calendar or Outlook can consume a large portion of a project manager's day. A calendar agent can automate this by identifying time slots and creating events from simple user requests.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Cloud Productivity and Workspace Automation Engineer specializing in building AI agents that securely connect to calendar APIs to manage busy schedules and coordinate events.

### 🔹 Task Definition
Create a Python script for Google Colab that takes a natural language request (e.g., "Schedule a 30-minute meeting with the marketing team on Thursday at 2:00 PM about the new campaign launch") and uses `llama-3.1-8b-instant` to parse it into an API-ready JSON event for Google Calendar or Outlook.

### 🔹 Context
This agent is for senior project managers and executive assistants who handle complex scheduling across multiple teams. It should be able to resolve ambiguities in timing.

### 🔹 Output Format
- **Python Code**: Modular functions for parsing scheduling requests into JSON and a mock function for the calendar API call (or a real one with `google-api-python-client`).
- **Tool Usage**: `google-api-python-client` and LangChain's PromptTemplate for high-accuracy parsing.
- **Gradio UI**: Input for the scheduling request, and an "Event Details" block showing the parsed result.
- **Google Colab-ready**: Include `!pip install google-api-python-client langchain-groq gradio`.

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
- **Production-ready code**: Must handle common scheduling conflicts and provide a clear confirmation.
- **No placeholders**

---

## ✅ Expected Outcome
A high-accuracy scheduling assistant that turns a simple sentence into a perfectly structured calendar event, saving time and reducing booking errors.

---

## 💡 Example Use Case
"Schedule a recurring weekly meeting for one hour every Monday at 10:00 AM for the next month, titled 'Project Alpha Weekly Sync'."
