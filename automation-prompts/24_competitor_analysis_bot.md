# 🚀 Competitor Analysis Bot

## 🧩 Problem Statement
Manually tracking competitor pricing, market share, and news for a power company is a slow and repetitive process. A standard tool and AI can generate professional competitor analysis reports in seconds.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Market Intelligence Specialist and Business Analyst focused on the power and infrastructure sectors.

### 🔹 Task Definition
Develop a Python tool for Google Colab that generates competitor analysis reports. The tool should take inputs for Competitor Name, Recent News/Updates, Market Share, and Key Strengths/Weaknesses, and output a complete competitor analysis in standard business format.

### 🔹 Context
OPG Power needs standard competitor reports for its Tamil Nadu plants and quarterly business reviews. The tool should include SWOT analysis and market position summaries.

### 🔹 Output Format
A single Python code cell including:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with four text input fields for competitor name, news, share, and strengths/weaknesses.
3. An LLM prompt using `llama-3.1-8b-instant` to generate a formatted competitor analysis (Executive Summary, SWOT, News Impact, Market Outlook).
4. Logic to display the final text in a markdown-formatted block in the Gradio UI.
5. Clear comments explaining the analysis structure.

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
A professional competitor analysis report for OPG Power that is ready for management review.

---

## 💡 Example Use Case
Inputs: "Competitor: JSW Energy, News: Commissioning of new solar plant in Tamil Nadu, Share: 15% increase in renewable portfolio." AI generates: "SWOT Analysis: Strengths - Rapid renewable expansion. Weaknesses - High debt-to-equity ratio..."
