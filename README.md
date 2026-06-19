# Archived Project

⚠️ This repository contains the first version of my Resume Ranking System built using TF-IDF and Cosine Similarity.

This project was developed as an initial exploration of AI-powered resume screening and ranking.

The improved version is being rebuilt using:

- Sentence Transformers
- Semantic Search
- Resume Parsing
- Skill Extraction
- Recruiter Analytics
- Explainable AI Matching

🔗 New Repository: [Add New Repository Link Here]


# AI Resume Screening & Ranking System

This project is an AI-powered resume screening and ranking system built using Streamlit, scikit-learn, and PyPDF2. The application allows users to upload resumes in PDF format, compares them to a given job description, and ranks them based on cosine similarity using TF-IDF.

Project Link:
https://resumerankingapp-joguyugandar.streamlit.app/

## 🚀 Features

- Upload multiple PDF resumes.
- Enter a job description to compare.
- Uses TF-IDF & Cosine Similarity for ranking.
- Displays ranked resumes with similarity scores.

## 📂 Folder Structure

```
resume_ranking_app/
│── .venv/
│── app.py
│── requirements.txt
│── resume_ranking.ipynb
│── data/
│   ├── sample_resume.pdf
│── README.md
│── .gitignore
```

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/JoguYugandar/resume_ranking_app.git
cd resume_ranking_app
```

### 2️⃣ (Optional) Create a Virtual Environment

```sh
python -m venv .venv
```

Activate on Windows:
```sh
.\.venv\Scripts\Activate.ps1
```

Activate on Mac/Linux:
```sh
source .venv/bin/activate
```

### 3️⃣ Install Dependencies

```sh
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```sh
streamlit run app.py
```

The app will open in your default web browser.

## 📌 How It Works

1. Upload PDF resumes using the file uploader.
2. Enter a job description in the provided text area.
3. The system extracts text from the resumes and converts them into TF-IDF vectors.
4. The job description is compared against resumes using cosine similarity.
5. Ranked results are displayed with similarity scores.

## 📡 Deployment

### Deploy on Streamlit Cloud (Free)

1. Push your project to GitHub.
2. Go to [Streamlit Cloud](https://share.streamlit.io/) and log in.
3. Click **New App**, select your GitHub repo, and set the file path to `app.py`.
4. Click **Deploy 🚀**

## 🔧 Requirements

- `streamlit`
- `PyPDF2`
- `pandas`
- `scikit-learn`
- `numpy`

Install using:

```sh
pip install -r requirements.txt
```

## 🎯 End Users

- **HR & Recruiters** – Automates resume screening for faster hiring.
- **Hiring Managers** – Ranks resumes efficiently for job roles.
- **Job Portals** – Enhances resume-job matching accuracy.
- **AI Enthusiasts & Students** – Learn NLP-based resume analysis.

## 🔮 Project Evolution (Future Scope)

This project served as the foundation for a more advanced Resume Intelligence System. The next version focuses on:

- Semantic Search with Sentence Transformers
- Resume Parsing
- Skill Extraction
- Explainable AI Matching
- Recruiter Analytics Dashboard
- Production-Ready Architecture

## 🔚 Conclusion

This AI-powered Resume Screening & Ranking System addresses the challenge of manual resume screening, which is time-consuming and inefficient. By leveraging TF-IDF and Cosine Similarity, the system automates resume ranking, ensuring fast, objective, and accurate candidate shortlisting. With PDF text extraction, real-time ranking, and easy deployment via Streamlit, this project provides an efficient, scalable, and user-friendly solution for recruiters, hiring managers, and job portals. 🚀

