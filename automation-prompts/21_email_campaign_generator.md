# 🚀 Email Campaign Generator

## 🧩 Problem Statement
Manually drafting promotional or informational email campaigns for news like product launches or company updates takes too much time for marketing teams. A standardized generator can automate email creation while maintaining a professional tone and layout.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Digital Copywriter and AI Email Marketing Strategist specializing in the industrial and energy sectors.

### 🔹 Task Definition
Create a Python chatbot for Google Colab that generates platform-optimized email campaigns. The tool should take inputs for Target Audience, Purpose (Newsletter, Promo, Update), Key Points (bullet points), and Call to Action (CTA), and output a complete email with a clear subject line.

### 🔹 Context
OPG Power's marketing team needs to create emails for customer newsletters, investor updates, or employee announcements. The tool should include different drafts (A/B testing variants).

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with four text input fields for target, purpose, key points, and CTA.
3. An LLM prompt using `llama-3.1-8b-instant` to generate two versions of an email (A/B test).
4. Logic to show the final email body (in markdown/HTML format) and a "Subject Line" in the Gradio UI.
5. Clear comments explaining the A/B test generation logic.

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`)
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Runs in Google Colab.
- **Security**: Use `GROQ_API_KEY`.
- **Reliability**: Fully functional, production-ready code.

---

## ✅ Expected Outcome
A customized email campaign for OPG Power, ready to be sent to customers or investors.

---

## 💡 Example Use Case
Inputs: "Audience: Investors, Purpose: Q3 Performance Update, Key Points: 15% growth in generation, 10% reduction in coal costs, CTA: Join Investor Call." AI generates: "Subject: OPG Power FY26 Q3 Recap: 15% Growth and Enhanced Efficiency..."
