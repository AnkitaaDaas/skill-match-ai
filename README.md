
# 🚀 SkillMatch AI – Intelligent Resume Screening & Skill Gap Analyzer

ResumeIQ is an AI-powered Resume Screening System built using Natural Language Processing (NLP) and Machine Learning techniques to analyze resumes, calculate relevance scores, and identify skill gaps based on target job roles.

This system helps candidates optimize resumes and helps recruiters screen applicants efficiently.


## 📌 Project Overview

This application parses resumes (PDF/DOCX), extracts structured information using NLP, and:

- Computes a Resume Relevance Score  
- Identifies missing skills  
- Suggests skill improvements  
- Recommends learning resources  
- Stores applicant analytics in MySQL  

Built using Streamlit, spaCy, NLTK, and MySQL.

## 🧠 Core Features

### 🔎 Resume Parsing & NLP Processing
- Extracts:
  - Skills
  - Education
  - Experience
  - Contact Information
- Uses spaCy (en_core_web_sm) for Named Entity Recognition
- Uses NLTK for stopword removal and tokenization


### 📊 Resume Scoring Engine
- Calculates skill-match percentage
- Assigns a Resume Score based on:
  - Keyword relevance
  - Technical skills match
  - Content richness
  - Experience indicators

### 🎯 Skill Gap Detection
- Compares extracted skills with target job role
- Identifies missing competencies
- Suggests relevant skills to improve resume strength

### 📚 Smart Learning Recommendations
- Recommends:
  - YouTube tutorials
  - Online courses
  - Skill upgrade resources

### 📈 Admin Dashboard
- Stores applicant data in MySQL database
- Displays analytics using:
  - Matplotlib
  - Plotly visualizations

## 🛠 Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### NLP & ML
- spaCy  
- NLTK  
- pyresparser  

### Database
- MySQL  
- PyMySQL  

### Data Visualization
- Matplotlib  
- Plotly  


## 🏗 System Architecture

1. Resume Upload  
2. Text Extraction (PDFMiner / Docx2txt)  
3. NLP Preprocessing  
4. Skill Extraction  
5. Resume Scoring  
6. Skill Recommendation  
7. Database Storage  
8. Admin Analytics Dashboard  

## 🚀 How to Run Locally

```bash
git clone <your-repository-link>
cd ResumeIQ
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

## 💡 Enhancements Implemented

- Integrated MySQL backend for persistent storage
- Designed weighted resume scoring logic
- Implemented skill-gap analysis module
- Added recruiter analytics dashboard
- Resolved dependency compatibility issues across NLP libraries

## 📊 Future Improvements

- Deploy on Streamlit Cloud / AWS
- Add AI-based job role prediction
- Implement cosine similarity scoring
- Add ATS compatibility score
- Integrate embeddings for semantic matching

## 🎯 Key Learning Outcomes

- End-to-end NLP pipeline development
- Handling real-world PDF parsing challenges
- Database integration with Python
- Managing dependency conflicts in ML projects
- Building production-ready Streamlit applications


## 👩‍💻 About

Computer Science student passionate about:

- Artificial Intelligence  
- Natural Language Processing  
- Backend Development  
- Real-world ML applications  


## ⭐ Why This Project Stands Out

Unlike basic resume parsers, this system:

- Performs structured skill-gap analysis  
- Generates resume improvement suggestions  
- Stores applicant analytics  
- Provides recruiter-level dashboard insights  

# Authors

- [@Ankita](https://github.com/AnkitaaDaas)


# Hi, I'm Ankita! 👋


## 🚀 About Me
I'm a Full Stack Developer


## 🔗 Links
[![linkedin](https://www.linkedin.com/in/ankitaad)]


## 🛠 Skills
1. C, C++, Python
2. SQL
3. Machine Learning
4. Deep Learning
5. Data Science


## Summary of My Journey
👩‍💻 I'm a 2025 graudaute

🧠 Btech Computer Science, NIT Agartala
