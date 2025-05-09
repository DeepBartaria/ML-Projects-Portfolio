# 🚢 Titanic Survival Prediction

This project uses machine learning to predict passenger survival on the Titanic dataset from Kaggle. It was built as my first classification project during my AI/ML learning journey.

## 📊 Project Overview

- **Competition**: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
- **Goal**: Predict which passengers survived the Titanic shipwreck
- **Score Achieved**: **0.7511** on the public leaderboard

## 🧠 Key Concepts Used

- Supervised Learning (Classification)
- Data Cleaning & Feature Engineering
- Model Training with Random Forest
- Evaluation and Submission

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## ✅ Project Steps

1. **Load Dataset**: Load train and test CSV files
2. **EDA**: Visualize missing data, survival rates by class, sex, age, etc.
3. **Data Cleaning**:
   - Fill missing Age/Fare values
   - Encode categorical variables like Sex, Embarked
   - Drop unnecessary columns like Name, Ticket
4. **Modeling**:
   - Use `RandomForestClassifier`
   - Tune hyperparameters (optional)
5. **Prediction & Submission**:
   - Predict survival on test set
   - Create `submission.csv` and submit to Kaggle

## 📌 Future Improvements

- Try other models: XGBoost, Logistic Regression
- Use feature selection and cross-validation
- Build a Streamlit app for live demo

---

> 🏁 This is part of my [ML Portfolio Repository](../) documenting my learning journey to become an AI/ML Engineer.
