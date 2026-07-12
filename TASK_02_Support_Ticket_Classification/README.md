# Support Ticket Classification

## Project Description

This project presents a machine learning solution for automatically classifying customer support tickets based on their priority. The model was developed using Python and Scikit-learn and predicts ticket priority from ticket information.

## Dataset

The dataset contains customer support tickets with features such as:

- Ticket Type
- Ticket Subject
- Ticket Description
- Ticket Status
- Ticket Priority (target variable)

## Project Structure

```
TASK_02_Support_Ticket_Classification/
│
├── data/
│   └── customer_support_tickets.csv
│
├── images/
│   ├── confusion_matrix.png
│   ├── model_accuracy.png
│   ├── ticket_priority_distribution.png
│   ├── ticket_status_distribution.png
│   └── ticket_type_distribution.png
│
├── models/
│   └── support_ticket_classifier.pkl
│
├── support_ticket_classification.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

## Project Workflow

1. Load the dataset.
2. Explore and clean the data.
3. Encode categorical features.
4. Split the dataset into training and testing sets.
5. Train the machine learning model.
6. Evaluate the model using accuracy and confusion matrix.
7. Save the trained model.

## Model Performance

The model was evaluated using:

- Accuracy Score
- Confusion Matrix

Evaluation plots are available in the `images` directory.

## Installation

Clone the repository:

```bash
git clone https://github.com/ag48665/FUTURE_ML.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Project

Open the notebook:

```bash
jupyter notebook support_ticket_classification.ipynb
```

or

```bash
jupyter lab
```

Run all notebook cells to reproduce the analysis and train the model.

## Requirements

Install all required libraries:

```bash
pip install -r requirements.txt
```

## Author

Agata Gabara
