# Automated-Resume-Screening-Tool
# 🚀 Automated Resume Screening Tool

An AI-powered ATS-style Resume Screening System built using Python, NLP, FastAPI, and Machine Learning techniques to automate candidate evaluation and shortlisting.

---

# 📌 Project Overview

Recruitment teams often receive hundreds of resumes for a single job opening, making manual screening slow, repetitive, and inefficient.

This project simulates the core functionality of modern Applicant Tracking Systems (ATS) by automatically analyzing resumes, extracting skills, comparing resumes with job descriptions, generating ATS scores, and ranking candidates based on relevance.

The system provides a professional recruiter dashboard with analytics, graphs, candidate ranking, and AI-based feedback generation.

---

# 🎯 Problem Statement

Manual resume screening:

* Takes significant time
* Can lead to inconsistent evaluations
* Makes large-scale hiring difficult
* Increases recruiter workload

This project automates the screening pipeline using NLP and Machine Learning to streamline recruitment workflows.

---

# 💡 Key Features

✅ Resume Upload System
✅ PDF & DOCX Resume Parsing
✅ NLP-based Text Cleaning
✅ Skill Extraction & Keyword Matching
✅ TF-IDF Vectorization
✅ Cosine Similarity Scoring
✅ ATS Match Percentage Generation
✅ Resume Ranking & Shortlisting
✅ AI-based Resume Feedback
✅ Interactive Dashboard with Charts & Analytics
✅ CSV Report Generation
✅ FastAPI Backend Integration

---

# 🛠 Tech Stack

## Programming Language

* Python

## Frameworks & Libraries

* FastAPI
* Scikit-learn
* Pandas
* NumPy
* pdfplumber
* python-docx
* Tailwind CSS
* Chart.js
* Uvicorn
* pyngrok

## NLP & Machine Learning

* TF-IDF Vectorization
* Cosine Similarity
* Text Processing
* Keyword Matching

---

# 🏗 Project Architecture

```bash
Resume Upload
      ↓
Text Extraction (PDF/DOCX)
      ↓
Text Cleaning & Preprocessing
      ↓
Skill Extraction
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity Matching
      ↓
ATS Score Calculation
      ↓
Candidate Ranking
      ↓
Shortlist / Reject Decision
      ↓
Dashboard Analytics & CSV Report
```

---

# 📂 Folder Structure

```bash
Automated-Resume-Screening-Tool/
│
├── resumes/
├── outputs/
├── images/
├── data/
├── README.md
├── requirements.txt
├── main.py
└── ats_report.csv
```

---

# ⚙ Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/Automated-Resume-Screening-Tool.git
```

## 2️⃣ Navigate to Project Folder

```bash
cd Automated-Resume-Screening-Tool
```

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶ How to Run

## Run FastAPI Server

```bash
python main.py
```

OR

```bash
uvicorn main:app --reload
```

---

# 🌐 Access Dashboard

After running the server:

```bash
http://127.0.0.1:8000
```

OR use the generated ngrok URL in Google Colab.

---

# 📊 Features Demonstrated

* Resume Parsing
* NLP Pipeline
* ATS Score Calculation
* Candidate Ranking
* Skill Matching
* Dashboard Analytics
* AI Feedback Generation
* CSV Report Export

---

# 📸 Screenshots to Add

Add screenshots inside the `images/` folder:

* Dashboard Homepage
* Resume Upload Interface
* ATS Score Result
* Candidate Ranking Table
* Analytics Graphs
* CSV Output
* FastAPI Running Screenshot

---

# 📈 Sample Output

| Candidate    | ATS Score | Status      |
| ------------ | --------- | ----------- |
| John Doe     | 82%       | Shortlisted |
| Emily Smith  | 74%       | Shortlisted |
| Alex Johnson | 39%       | Rejected    |

---

# 🧠 Key Learnings

Through this project, I learned:

* End-to-end NLP workflow development
* TF-IDF and cosine similarity implementation
* Resume parsing and text preprocessing
* FastAPI backend development
* Building recruiter-focused dashboards
* Creating scalable Python applications
* Working with real-world HR Tech concepts

---

# 🌍 Industry Relevance

This project simulates functionalities used in modern ATS platforms and HR Tech systems for:

* Automated candidate screening
* Resume ranking
* Talent acquisition workflows
* Recruitment analytics
* Hiring automation

---

# 🚀 Future Improvements

* Advanced NLP models using Transformers
* Semantic skill matching
* Candidate recommendation engine
* Experience extraction
* Email notifications
* Database integration
* Admin authentication system
* Real-time recruiter collaboration

---

# 🤝 Acknowledgement

Special thanks to my mentor for continuous guidance and support throughout this project.

---

# 🔗 GitHub Repository

Add your repository link here.

---

# 📬 Contact

## Your Name-Debankita Panja

🔗 LinkedIn: https://www.linkedin.com/in/debankita-panja-8482a2403/
🔗 GitHub: https://github.com/dp2005-lang

---

# ⭐ If you found this project useful, consider giving it a star!
