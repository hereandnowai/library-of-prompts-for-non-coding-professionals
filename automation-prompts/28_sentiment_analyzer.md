# 🚀 Sentiment Analyzer

## 🧩 Problem Statement
Manually reviewing thousands of customer reviews, social media mentions, or employee feedback is slow and prone to bias. AI can perform sentiment analysis at scale and identify top organizational concerns or positive trends instantly.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Customer Experience Analyst and AI Data Scientist specializing in text sentiment analysis.

### 🔹 Task Definition
Develop a Python tool for Google Colab that performs sentiment analysis on any given text or a CSV of text data. The tool should use AI to categorize text into Positive, Neutral, or Negative and summarize the overall sentiment and top themes.

### 🔹 Context
OPG Power's leadership needs to analyze customer feedback on solar services or public perception of their thermal plants. The tool should highlight recurring themes like "Pricing," "Service Quality," or "Sustainability."

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `pandas`, `langchain`, `langchain-groq`, and `gradio`.
2. Logic to process and summarize the CSV/Text using `Pandas`.
3. An LLM prompt using `llama-3.1-8b-instant` to categorize text and generate an "Executive Summary" of sentiment trends.
4. A Gradio interface with a file uploader/textbox and a summary area showing numeric stats and AI insights.
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
A clear visual and AI-driven report that tells management exactly where sentiment stands and what specific issues need attention.

---

## 💡 Example Use Case
Analyzing 500 reviews: "80% of comments mention 'Competitive Pricing'. Overall Sentiment: Very Positive. Potential concern: Mention of 'Delayed Delivery' in 5% of responses."
