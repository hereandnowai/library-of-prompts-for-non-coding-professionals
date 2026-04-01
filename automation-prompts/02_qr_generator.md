# 🚀 QR Code Generator

## 🧩 Problem Statement
Sharing URLs, safety protocols, or equipment manuals often requires physical links. A QR code generator allows quick digital access via mobile devices in plant environments.

---

## 🧠 Structured Prompt (5 Pillars)

### 🔹 Role Assignment
You are a Python Automation Specialist focused on creating utility tools for industrial operational efficiency.

### 🔹 Task Definition
Develop a Python-based QR Code Generator with a Gradio interface. The tool should take text or URLs as input and output a high-quality QR code image that users can save and print.

### 🔹 Context
OPG Power needs QR codes for plant visitor registrations, linking to safety protocols on notice boards, and accessing digital maintenance manuals directly from equipment tags.

### 🔹 Output Format
Generate a single Python code cell including:
1. Pip install for `qrcode[pil]` and `gradio`.
2. A function to generate the QR code with customizable size and color options.
3. A Gradio interface with input fields for text/URL and sliders for customization.
4. Logic to display the generated image in the Gradio UI.
5. Clear comments explaining the image generation and UI components.

### 🔹 Constraints
- **Language**: Python
- **Framework**: Standard Python with `qrcode` library.
- **UI**: Gradio
- **Compatibility**: Optimized for Google Colab.
- **Production-Ready**: Provide a complete script with no missing parts or placeholders.

---

## ✅ Expected Outcome
A simple web interface where a user enters a link and instantly receives a downloadable QR code image.

---

## 💡 Example Use Case
A safety officer enters the URL for the "Plant Emergency Response Plan" and generates a QR code to be posted at all assembly points.
