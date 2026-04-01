# 🚀 Employee Survey Analyzer

## 🧩 Problem Statement
Analyzing annual employee engagement survey responses (especially thousands of free-text comments) is slow and prone to bias. AI can perform sentiment analysis at scale and identify top organizational concerns instantly.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a People Experience Analyst and AI Data Scientist specializing in employee sentiment analysis.

### 🔹 Task Definition
Develop a Python tool for Google Colab that accepts a CSV file of survey responses (Likert scale 1-5 and free-text comments). The tool should use AI to perform sentiment analysis on comments, calculate overall engagement scores, and identify top concerns.

### 🔹 Context
OPG Power's HR leadership needs to analyze annual employee engagement surveys to improve morale across multiple plants. The tool should highlight recurring themes like "Safety Gear Quality" or "Shift Timing."

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `pandas`, `langchain`, `langchain-groq`, and `gradio`.
2. Logic to process and summarize the CSV using `Pandas`.
3. An LLM prompt using `llama-3.1-8b-instant` to categorize comments into Positive, Neutral, or Negative and summarize key themes.
4. A Gradio interface with a file uploader and a summary area showing numeric stats and an "Executive Summary" of employee sentiment.
5. Clear comments explaining the sentiment analysis logic.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`) + Pandas
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Optimized for Google Colab.
- **Security**: Use `GROQ_API_KEY`.
- **Reliability**: No placeholders; production-ready script.

---

## ✅ Expected Outcome
A clear visual and AI-driven report that tells HR leadership exactly where employee morale stands and what specific issues need attention.

---

## 💡 Example Use Case
Analyzing 500 responses: "Over 40% of comments mention 'Improvement in Plant HVAC'. Overall Sentiment: Slightly Positive. Primary Concern: Workspace Comfort."
