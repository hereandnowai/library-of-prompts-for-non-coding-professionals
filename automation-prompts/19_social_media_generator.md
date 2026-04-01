# 🚀 Social Media Post Generator

## 🧩 Problem Statement
Creating consistent, high-quality social media content for LinkedIn, Twitter, and Instagram for a power generation company takes a lot of marketing team hours. A standardized generator can automate post creation while maintaining a professional tone.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Digital Marketing Specialist and AI Copywriter focusing on the power and infrastructure sectors.

### 🔹 Task Definition
Create a Python chatbot for Google Colab that generates platform-optimized social media posts. The tool should take inputs for Platform (LinkedIn, Twitter, Instagram), Topic/News, and Tone (Professional, Casual, Celebratory), and output a complete post with hashtags and emojis.

### 🔹 Context
OPG Power's marketing team needs to create posts for plant milestone anniversaries, PPA announcements, or environmental initiatives. The tool should understand different character limits for each platform.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with a dropdown for platforms, a large text box for topic, and a Tone selection.
3. An LLM prompt using `llama-3.1-8b-instant` to generate a platform-specific post (e.g., shorter for Twitter, more technical for LinkedIn).
4. Logic to show the final post text and a "Character Count" in the Gradio UI.
5. Clear comments explaining the post generation logic.

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
A customized social media post for OPG Power, ready to be copied and pasted to any major platform.

---

## 💡 Example Use Case
Inputs: "Platform: LinkedIn, Topic: Unit 2 100% PLF achieved for 30 consecutive days, Tone: Professional." AI generates: "Thrilled to announce that OPG Power's Unit 2 has reached a milestone—100% Plant Load Factor for the last 30 days! 🚀 #EnergyEfficiency #PowerGeneration"
