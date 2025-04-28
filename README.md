# Titanic Survival Prediction - EDA and Machine Learning

## 📚 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Machine Learning** on the famous **Titanic dataset** to predict passenger survival.

We analyzed the data, engineered new features, trained a classification model, and created a final submission file ready for evaluation.

---

## 📁 Dataset Files Used

- `train.csv` — training data (with known survival labels)
- `test.csv` — test data (survival to predict)
- `gender_submission.csv` — sample submission format

---

## 🛠 Tools and Libraries

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 🧹 Project Workflow

### 1. Data Cleaning
- Handled missing values (`Age`, `Fare`, `Embarked`).
- Dropped `Cabin` column due to excessive missing data.

### 2. Exploratory Data Analysis (EDA)
- Univariate analysis (Age distribution, survival counts).
- Bivariate analysis (Survival by Sex, Pclass).
- Correlation heatmaps and pairplots.
- Visual observations and insights written after each plot.

### 3. Feature Engineering
- Extracted `Title` from passenger `Name` (Mr, Miss, Mrs, etc.)
- Created new feature: `FamilySize` = SibSp + Parch + 1
- Encoded categorical features (`Sex`, `Embarked`, `Title`) into numbers.

### 4. Model Training
- Model used: **Random Forest Classifier** (100 estimators)
- Achieved validation accuracy of approximately **84%**.

### 5. Prediction and Submission
- Generated predictions on `test.csv`.
- Created final `submission_improved.csv` ready for evaluation.

### 6. Feature Importance Visualization
- Bar plot showing the most important features for survival prediction.
- Top features: `Sex`, `Title`, `Fare`, `Age`.

---

## 📊 Key Insights

- Females had a much higher survival rate compared to males.
- 1st Class passengers survived more than 2nd and 3rd Class.
- Higher Fare and lower Age increased survival chances.
- Titles like "Mrs", "Miss" strongly indicated survival probability.

---

## 📂 Files in Repository

| File | Description |
|:-----|:------------|
| `Titanic_EDA_ML.ipynb` | Full Colab Notebook with code and explanations |
| `submission_improved.csv` | Final prediction file for test data |
| `README.md` | This file explaining the project |

---

## 🚀 How to Run

1. Clone this repository.
2. Open `Titanic_EDA_ML.ipynb` in Google Colab or Jupyter Notebook.
3. Run all cells step-by-step.
4. Download the `submission_improved.csv` for submission.

---

## 📌 Note

This project was completed focusing on EDA, feature engineering, and predictive modeling.

---

## ✨ Credits

- Dataset: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
- Tools: Python, Scikit-Learn, Pandas, Matplotlib, Seaborn

---

## Credit 
-Parag
