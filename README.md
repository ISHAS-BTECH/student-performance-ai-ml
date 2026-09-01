# 🎓 Student Performance AI

An end-to-end Machine Learning project that predicts student academic performance and provides an early-warning risk indicator.

## 🚀 Overview

Student Performance AI analyzes academic and behavioral indicators such as study hours, attendance, previous scores and assignment completion.

The system predicts:

- Needs Improvement
- Average
- Good

It also provides:

- Low Risk
- Medium Risk
- High Risk

## 🧠 Machine Learning Workflow

Data
→ Preprocessing
→ Exploratory Analysis
→ Feature Engineering
→ Model Training
→ Evaluation
→ Prediction

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Streamlit
- Joblib

## 🤖 Machine Learning Model

The project uses a Random Forest Classifier with a Scikit-learn preprocessing pipeline.

Evaluation metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 📊 Features

| Feature | Description |
|---|---|
| Study Hours | Average study hours per day |
| Attendance | Attendance percentage |
| Previous Score | Previous academic score |
| Assignments | Completed assignments |
| Sleep Hours | Average sleep hours |
| Internet Access | Internet availability |
| Extracurricular | Activity participation |
## 📁 Project Structure

student-performance-ai-ml/
│
├── data/
│   └── student_performance.csv
│
├── src/
│   ├── preprocessing.py
│   ├── train_model.py
│   └── predict.py
│
├── models/
│   └── student_performance_model.pkl
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
