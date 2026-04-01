# 🚀 Attendance Logger (OCR-based)

## 🧩 Problem Statement
Manually entering daily attendance from handwritten sign-in sheets or physical register photos is slow and error-prone. OPG Power's site managers need a way to automate attendance recording via photo uploads.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Computer Vision Engineer and AI HR Automation Expert specializing in industrial site attendance systems.

### 🔹 Task Definition
Create a Python application for Google Colab that extracts attendance data from images of sign-in sheets. The tool should take an uploaded photo (using OCR) or a text capture, then use AI to identify Employee Name, ID, In-Time, and Out-Time, and output a structured attendance table.

### 🔹 Context
OPG Power's security and HR teams need to record daily attendance at remote plant units or during site shutdowns. The tool should use AI to resolve common OCR errors like "S" vs "5" or "I" vs "1" based on employee context.

### 🔹 Output Format
A single Python cell containing:
1. Pip installs for `pytesseract`, `pillow`, `langchain`, `langchain-groq`, and `gradio`.
2. A Gradio interface with an image upload component for photos of the register.
3. Python logic using `Tesseract` or an LLM-based OCR prompt for text extraction.
4. An LLM prompt using `llama-3.1-8b-instant` to clean and structure the raw OCR text into a formatted table.
5. A dynamic table output in the Gradio UI showing the "Attendance Log."

### 🔹 Constraints
- **Language**: Python
- **Framework**: LangChain (`langchain-groq`) + OCR via Tesseract/LLM
- **Inference**: Groq API
- **Model**: `llama-3.1-8b-instant`
- **UI**: Gradio
- **Compatibility**: Runs in Google Colab.
- **Security**: Use `GROQ_API_KEY`.
- **Reliability**: Fully functional, production-ready code.

---

## ✅ Expected Outcome
A customized attendance report for OPG Power, ready to be reviewed by HR based on a single photo of a register.

---

## 💡 Example Use Case
Photo Uploaded: A handwritten sign-in sheet image. AI Result Table: "Employee: Rajesh, ID: 105, IN: 09:00, OUT: 18:30. Note: Handwritten '5' in ID resolved via context."
