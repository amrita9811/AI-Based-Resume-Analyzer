# 🧠 AI-Based Resume Analyzer

An intelligent resume analysis tool that parses resumes using NLP techniques, identifies key skills and information, and provides job role predictions, resume feedback, and detailed analytics for both users and admins.

---

## 📌 About the Project

This tool leverages Natural Language Processing (NLP) to extract, classify, and analyze information from resumes. It helps both applicants and recruiters by identifying skills, predicting job roles, and offering data-driven insights.

Key highlights include:
- Resume parsing and keyword extraction
- Skill recommendations based on job roles
- Resume score and feedback
- Role-based predictions using rule-based logic
- Admin panel with visual analytics and CSV exports

---

## 🎯 Scope

- Convert uploaded resumes into structured tabular data for storage or analysis
- Allow users to improve their resumes based on real-time recommendations and feedback
- Provide institutions with resume insights before placements
- Enable recruiters to visualize trends in applicant data such as popular job roles, resume quality, and experience levels

---

## ⚙️ Tech Stack

**Frontend:**
- Streamlit
- HTML / CSS
- JavaScript

**Backend:**
- Python
- Streamlit

**Database:**
- MySQL

**Libraries Used:**
- `pandas`
- `nltk`
- `pyresparser`
- `pdfminer.six`
- `plotly`

---

## 🚀 Features

### 👤 For Users:
- Resume Parsing (Location, Contact Info, etc.)
- Extraction of:
  - Basic Information
  - Skills
  - Keywords
- Resume Enhancement:
  - Skill Recommendations
  - Predicted Job Role
  - Resume Tips
  - Resume Score

### 🛠️ For Admins:
- Dashboard of Uploaded Resumes
- Tabular View of All User Data
- Export All Data to CSV
- Resume Storage System
- Visual Analytics:
  - Pie charts for Resume Ratings
  - Field/Role Predictions
  - Experience Distribution
  - Resume Scores

---

## 💾 Requirements

- Python >= 3.8
- MySQL Server
- Visual Studio Code
- Visual Studio Build Tools for C++ (for compiling certain Python packages)

---

## ⚡ Getting Started

### 1. Clone the Repository
(on your terminal) 
git clone https://github.com/your-username/AI-Resume-Analyzer-Amrita.git
cd AI-Resume-Analyzer-Amrita

### 2. Install Dependencies
pip install -r requirements.txt

### 3. Run the application 
streamlit run app.py
