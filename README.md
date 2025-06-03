# 🎓 Student Grade Prediction Using Machine Learning

This project builds a **Machine Learning model** to predict students' final grades (`G3`) based on various personal and academic factors. The dataset is based on real student performance data and is widely used for educational data mining.

---

## 📦 Features

- Data cleaning and preprocessing
- One-hot encoding of categorical variables
- Train/Test split (80/20)
- **Linear Regression** model for predicting grades
- Evaluation using **R² score** and **Mean Squared Error**
- **Visualization** of predictions vs actual values

---

## 🗂️ Project Structure
ML_Student_Grade_Predictor/
│
├── data/
│ └── student-mat.csv # Dataset (from UCI)
│
├── notebooks/
│ └── student_grade_model.ipynb # Main Jupyter notebook
│
├── .gitignore # Git ignore rules
├── README.md # This file
├── requirements.txt # Python dependencies
└── main.py # (Optional) Training script

---

## 📊 Dataset Overview

- **Source**: Kaggle
- **File Used**: `student-mat.csv`
- **Target**: `G3` (final grade)
- **Features**: 30+ attributes (age, study time, failures, absences, parental education, etc.)

---

## ⚙️ How to Run the Project

### 🔹 Step 1: Clone the Repository

```bash
git clone https://github.com/MuhammadAhmad60/Ml_projects.git
cd Ml_projects
