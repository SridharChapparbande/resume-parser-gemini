# resume-parser-gemini
AI-powered resume parser using Gemini and Python

This project uses a Jupyter notebook to extract structured resume data using Google Gemini API (`models/gemini-1.5-flash`) from PDF or DOCX resumes.

---

## Notebook Included

- `ResumeParser.ipynb` – All code and logic to:
  - Read `.pdf` or `.docx` resumes
  - Extract text
  - Prompt Gemini API
  - Parse and print structured JSON

---

## Requirements
```bash
pip install google-generativeai pdfplumber python-docx
