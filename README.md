# 🚀 NLP-Powered Resume Analyzer

An intelligent web application built with **Python & Flask** that analyzes resumes against job descriptions and provides a **data-driven match score** along with a **detailed breakdown of missing and matched skills**.

---

## 📸 Project Demo

![Project Screenshot](https://your-image-link-here.com)

> ⚠️ Replace the above link with an actual screenshot of your project UI.

---

## ✨ Key Features

### 🔹 Dual-Scoring System
- **Keyword Matching** → Detects direct overlap of skills  
- **Semantic Similarity** → Uses **TF-IDF + Cosine Similarity** to understand contextual meaning  

---

### 🔹 Detailed Skill Analysis
- Shows **matched skills**
-  Highlights **missing skills**
- Helps users improve resumes based on job requirements

---

### 🔹 Multi-Format Support
- Supports:
  - 📄 `.pdf` (via PyMuPDF)
  - 📝 `.docx` (via python-docx)

---

### 🔹 Responsive UI
- Clean and user-friendly interface  
- Works across **desktop, tablet, and mobile devices**

---

## 🧠 Tech Stack

### Backend
- Python
- Flask

### NLP & Machine Learning
- Scikit-learn
- spaCy
- NLTK

### File Processing
- PyMuPDF
- python-docx

### Frontend
- HTML5
- CSS3
- JavaScript

---

## ⚙️ How It Works

1. **Upload & Input**
   - User uploads resume  
   - Pastes job description  

2. **Text Extraction**
   - Extracts text from `.pdf` or `.docx` files  

3. **NLP Preprocessing**
   - Tokenization  
   - Stopword removal  
   - Lemmatization  

4. **Scoring Algorithm**
   - Converts text → **TF-IDF vectors**
   - Computes **Cosine Similarity**
   - Combines with keyword match score  

5. **Results Display**
   - Final match score (%)  
   - Matched skills  
   - Missing skills  

---

## 📊 Example Output

- Match Score: **78%**
- Matched Skills: Python, Machine Learning, SQL  
- Missing Skills: Deep Learning, NLP  

---

## 🚀 Getting Started

###  Prerequisites
- Python 3.8+
- pip

---

### 🔧 Installation

#### 1. Clone the Repository
```bash
git clone https://github.com/Balajiscientist/resume_analyzer.git
cd resume_analyzer
