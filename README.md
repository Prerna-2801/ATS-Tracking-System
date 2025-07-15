# A smart **AI-powered ATS Resume Tracker** built with **Streamlit** and **Google Gemini API**. This tool helps candidates and recruiters evaluate how well a resume matches a given job description.

## 🔍 Features

- ✅ Upload resume (PDF format)
- 🤖 Analyze resume content using Gemini (Google AI)
- 📈 Get a professional review of the resume
- 🧠 See ATS-style percentage match with job description
- 💡 Identify missing keywords and receive improvement suggestions

## 🚀 Tech Stack

- Python
- Streamlit (Web App Framework)
- Google Generative AI (Gemini 1.5 Flash)
- pdf2image + PIL (for PDF to image conversion)
- dotenv (for secure API key usage)

## 📂 How It Works

1. User enters a **job description**.
2. User uploads their **resume in PDF format**.
3. AI evaluates the resume based on:
   - Job fit analysis (HR perspective)
   - ATS match percentage with missing keywords
