# 🚀 Web Scraper Agent

## 🧩 Problem Statement
Extracting specific data from websites often requires coding complex scrapers or using expensive browser extensions. A web scraper agent can intelligently look at a page's HTML, find the relevant data points, and output them in a structured table or document.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Lead Data Scraper and Parsing Architect specializing in using LLMs to navigate and extract unstructured data from raw HTML/Web pages.

### 🔹 Task Definition
Create a Python script for Google Colab that takes a URL as input and a list of target data points (e.g., "Product Name, Price, Rating"). The agent should use `BeautifulSoup` to pull the page's HTML and `llama-3.1-8b-instant` to parse it into a clean CSV format within a Gradio interface.

### 🔹 Context
Useful for e-commerce managers tracking competitor prices or HR professionals gathering job posting data across multiple sites. Focus on high-accuracy data mapping rather than just text extraction.

### 🔹 Output Format
- **Python Code**: Modular functions for fetching HTML, parsing with AI, and exporting as CSV.
- **Tool Usage**: `requests`, `BeautifulSoup4`, and LangChain's LLM chain.
- **Gradio UI**: Input for a URL, a list of fields to extract, and a download button for the CSV.
- **Google Colab-ready**: Include `!pip install beautifulsoup4 lxml lxml_html_clean pandas` in the code.

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
- **Production-ready code**: Must handle common scraper issues like bot detection or malformed HTML.
- **No placeholders**

---

## ✅ Expected Outcome
A browser-based tool that functions like a "Swiss Army knife" for data extraction, turning any URL into structured data without writing a line of custom scraping logic.

---

## 💡 Example Use Case
"Scrape the top 10 articles from TechCrunch related to AI startups and create a CSV with the Title, Author, and a one-sentence summary."
