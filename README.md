# AI Resume Analyzer

This project is an AI-powered tool designed to evaluate resumes for specific job roles and provide actionable feedback.  
It uses natural language processing (NLP) techniques to parse resumes, extract key information, match them against job descriptions, and generate compatibility scores.  
The tool helps candidates improve their resumes and assists recruiters or institutions in screening them more efficiently.

---

## Project Overview
The AI Resume Analyzer is built as a standalone application with the following goals:
- Automate resume parsing and keyword matching.  
- Provide scoring and suggestions for improvement.  
- Support multiple file formats such as PDF, DOCX, and TXT.  
- Deliver analysis results quickly (within 2–3 seconds per resume).  
- Maintain privacy through data anonymization.  

---

## Features
- Extract relevant details such as name, education, skills, and work experience.  
- Keyword matching against job descriptions.  
- Compatibility scoring using weighted algorithms.  
- Personalized feedback and suggestions for missing skills or formatting improvements.  
- Report generation with analysis results.  
- Support for bulk resume processing and CSV export.  

---

## System Workflow
1. User uploads a resume file.  
2. System validates the format and parses the content.  
3. NLP modules extract skills, education, and experience.  
4. Resume content is compared against job descriptions.  
5. A compatibility score is calculated.  
6. A structured report is generated and displayed to the user.  

---

## Tech Stack
- **Programming Language**: Python  
- **Libraries**: NLTK, spaCy, scikit-learn, Pandas, NumPy  
- **Document Parsing**: PDFMiner, PyResparser  
- **Frontend**: Streamlit (for UI and dashboards)  
- **Database**: MySQL (for structured storage and reporting)  

---
