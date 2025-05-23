# 🚢 Titanic Survival Prediction with Random Forest

This project is an end-to-end machine learning pipeline built on the iconic [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) dataset. It explores survival patterns and trains a predictive model using scikit-learn.

---

## 📊 Project Overview

- Performed detailed Exploratory Data Analysis (EDA)
- Handled missing data with strategic imputation
- Converted categorical features with encoding (binary + one-hot)
- Trained a Random Forest classifier to predict survival
- Achieved **0.75598 accuracy** on Kaggle's public leaderboard ✅

---

## 🧠 Techniques Used

- `pandas` for data wrangling
- `seaborn` and `matplotlib` for visualization
- `.isnull().sum()` and `.describe()` for dataset profiling
- Binary encoding for `Sex`, one-hot encoding for `Embarked`
- Model validation with `train_test_split` and `accuracy_score`
- Predictive modeling with `RandomForestClassifier`

---

## 📁 Dataset

- Source: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)
- Files used:
  - `train.csv` (labeled training data)
  - `test.csv` (unlabeled test data)
  - `submission.csv` (output file for leaderboard submission)

---

## 🚀 How to Run

1. Clone this repository
2. Open the notebook in Jupyter or Kaggle
3. Run all cells to reproduce results
4. Submit `submission.csv` to Kaggle if you want to join the leaderboard

---

## 📈 Final Result

- Public Leaderboard Score: **0.75598**
- Model: Random Forest with default parameters
- Features used: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, and `Embarked_*`

---

## 🔮 Future Improvements

- Feature engineering from `Name` (titles like Mr, Miss, etc.)
- Hyperparameter tuning using `GridSearchCV`
- Cross-validation with `KFold` for more robust evaluation
- Trying other classifiers like `XGBoost`, `LogisticRegression`, etc.

---

## ✍️ Author

- **Bakhshish Sethi**  
  Undergraduate CS Student | Data Science Enthusiast  

---

⭐ If you found this helpful or learned something, consider giving this repo a star!
