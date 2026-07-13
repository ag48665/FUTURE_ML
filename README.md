# Machine Learning Portfolio — Future ML

This repository contains three end-to-end Machine Learning projects developed as part of the **Future ML Internship Portfolio**.

The projects demonstrate practical applications of:

* Machine Learning
* Data Analysis
* Natural Language Processing
* Regression and classification
* Feature engineering
* Model evaluation
* Data visualization
* Model serialization

Each project includes a Jupyter Notebook, dataset, visualizations, requirements file, saved model where applicable, and detailed documentation.

---

## Projects

### 1. Sales Forecasting

[View Project](./TASK_01_Sales_Forecasting)

A regression project focused on forecasting monthly sales using historical transaction data from the Sample Superstore dataset.

The project includes:

* Data cleaning and exploratory data analysis
* Monthly sales aggregation
* Time-based feature engineering
* Lag and rolling-average features
* Random Forest Regression
* Model evaluation using MAE and RMSE
* Actual versus predicted sales visualization
* Trained model serialization

**Main technologies:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Joblib and Jupyter Notebook.

---

### 2. Support Ticket Classification

[View Project](./TASK_02_Support_Ticket_Classification)

A classification project that automatically predicts the priority of customer support tickets.

The model uses ticket-related information such as ticket type, subject, description and status to classify each request into an appropriate priority category.

The project includes:

* Dataset exploration and cleaning
* Categorical feature encoding
* Training and test data preparation
* Machine Learning model training
* Accuracy evaluation
* Confusion matrix analysis
* Distribution visualizations
* Trained classifier serialization

**Main technologies:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn and Joblib.

---

### 3. Resume Screening System

[View Project](./TASK_03_Resume_Screening_System)

An NLP-based resume screening system that compares candidate resumes with a job description and ranks candidates according to their relevance.

The system automates the initial recruitment screening process by converting resume text and a job description into numerical representations.

The project includes:

* Resume text cleaning and preprocessing
* TF-IDF vectorization
* Job description processing
* Cosine similarity calculation
* Candidate ranking
* Resume category analysis
* Similarity matrix visualization
* Top candidate visualization

The dataset contains **962 resumes from 25 job categories**, including Data Science, Python Development, Java Development, DevOps, Business Analysis, HR and Network Security.

**Main technologies:** Python, Pandas, NumPy, Scikit-learn, NLTK, TF-IDF, Cosine Similarity, Matplotlib and Seaborn.

---

## Repository Structure

```text
FUTURE_ML/
│
├── TASK_01_Sales_Forecasting/
│   ├── data/
│   ├── images/
│   ├── models/
│   ├── sales_forecasting.ipynb
│   ├── requirements.txt
│   └── README.md
│
├── TASK_02_Support_Ticket_Classification/
│   ├── data/
│   ├── images/
│   ├── models/
│   ├── support_ticket_classification.ipynb
│   ├── requirements.txt
│   └── README.md
│
├── TASK_03_Resume_Screening_System/
│   ├── data/
│   ├── images/
│   ├── models/
│   ├── notebooks/
│   ├── requirements.txt
│   └── README.md
│
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/ag48665/FUTURE_ML.git
cd FUTURE_ML
```

Move to the selected project directory:

```bash
cd TASK_01_Sales_Forecasting
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the relevant notebook and run all cells to reproduce the analysis and results.

> Each project has its own `requirements.txt` file. Install dependencies from the directory of the project you want to run.

---

## Skills Demonstrated

* Exploratory Data Analysis
* Data cleaning and preprocessing
* Feature engineering
* Regression modelling
* Classification modelling
* Natural Language Processing
* TF-IDF text vectorization
* Cosine similarity
* Model evaluation
* Data visualization
* Saving trained Machine Learning models
* Organizing reproducible ML projects

---

## Future Development

Possible improvements across the portfolio include:

* Hyperparameter optimization
* Cross-validation
* Testing additional Machine Learning algorithms
* Building interactive applications with Streamlit
* Adding automated testing
* Creating inference pipelines
* Deploying trained models as web APIs
* Using advanced NLP embeddings such as BERT or Sentence Transformers

---

## Author

**Agata Gabara**

Machine Learning Internship Portfolio — Future ML

[GitHub Profile](https://github.com/ag48665)
