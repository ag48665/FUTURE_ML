# 📄 Resume Screening System

An AI-powered Resume Screening System built with **Natural Language Processing (NLP)** and **Machine Learning** techniques. The project automatically compares resumes with a given job description and ranks candidates based on their relevance.

---

## 📌 Project Overview

Recruiters often receive hundreds of resumes for a single job opening. Reviewing each application manually is time-consuming and inefficient.

This project automates the initial screening process by:

- Cleaning and preprocessing resume text
- Converting text into numerical features using **TF-IDF**
- Comparing resumes with a job description using **Cosine Similarity**
- Ranking candidates according to their match score
- Visualizing the results

---

## 🚀 Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- TF-IDF Vectorization
- Cosine Similarity
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains **962 resumes** from **25 different job categories**, including:

- Data Science
- Python Developer
- Java Developer
- DevOps Engineer
- Business Analyst
- HR
- Web Designing
- Testing
- Network Security
- Database
- and many more.

---

## ⚙️ Project Workflow

1. Load the resume dataset
2. Explore the dataset
3. Clean and preprocess resume text
4. Remove duplicate resumes
5. Convert resumes into TF-IDF vectors
6. Transform the job description into TF-IDF representation
7. Calculate cosine similarity scores
8. Rank candidates by similarity score
9. Visualize the top matching candidates

---

## 📊 Results

The system successfully ranked resumes according to their relevance for a **Data Scientist** position.

### Top Candidate Score

**41.48% Match**

The ranking demonstrates how NLP techniques can effectively identify resumes that best match a specific job description.

---

## 📈 Visualizations

The project includes several visualizations:

- Resume Category Distribution
- Resume Length Distribution
- Resume Similarity Matrix
- Top 10 Matching Candidates

---

## 📁 Project Structure

```
TASK_03_Resume_Screening_System/
│
├── data/
│   └── Resume Screening.csv
│
├── images/
│   ├── category_distribution.png
│   ├── resume_length_distribution.png
│   ├── resume_similarity_matrix.png
│   └── top_10_candidates.png
│
├── notebooks/
│   └── resume_screening.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/ag48665/FUTURE_ML.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🎯 Future Improvements

- Resume skill extraction
- Keyword highlighting
- Skill gap identification
- Support for PDF resumes
- Web application using Streamlit or Flask
- Deep Learning embeddings (BERT/Sentence Transformers)

---

## 👩‍💻 Author

**Agata Gabara**

Machine Learning Portfolio Project – Future ML
