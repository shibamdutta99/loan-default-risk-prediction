# 🏦 Loan Default Risk Prediction

This project analyzes key factors behind loan approvals and defaults using exploratory data analysis, visualization, and machine learning. The goal is to predict whether a loan application is likely to be approved or not.

---

## 📊 Objective

To identify key variables that impact loan approval and develop a predictive model using classification algorithms to assist financial institutions in decision-making.

---

## 📁 Dataset

- **Source**: [Analytics Vidhya - Loan Prediction Practice Problem](https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/)
- **Files**: `train.csv`, `test.csv`
- **Target Column**: `Loan_Status` (Y = 1, N = 0)

---

## 🔍 Key Steps

1. **Data Cleaning**
   - Treated missing values with median/mode strategies
   - Converted categorical features into numerical format

2. **EDA & Visualization**
   - Analyzed relationships between loan status and features like:
     - Credit History
     - Education
     - Property Area
     - Applicant & Coapplicant Income
   - Used: countplots, violin plots, scatterplots, stacked bar charts
   - Plots are saved in the `plot/` folder

3. **Feature Engineering**
   - Label Encoding (`Gender`, `Married`, `Self_Employed`, `Education`)
   - One-Hot Encoding (`Property_Area`)
   - Custom Mapping (`Dependents`)
   - Feature Scaling for numerical columns

4. **Model Building**
   - Logistic Regression
   - Decision Tree
   - Random Forest

5. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
   - Feature Importance Plot (Logistic Regression)

---

## 📊 Visualizations

All plots are saved in the `plot/` folder, including:

- 📌 Loan Status Distribution
- 📌 Loan Approval by Education
- 📌 Approval by Property Area
- 📌 Applicant Income vs Loan Amount
- 📌 Coapplicant Income by Loan Status
- 📌 Loan Status by Self Employed
- 📌 Loan Status by Credit History
- 📌 Feature Importance (Logistic Regression)

---

## ✅ Model Results

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | ✅ **78.9%** |
| Random Forest       | 76.4% |
| Decision Tree       | 69.9% |

---

## ⚙️ Tech Stack

- **Language**: Python 3.12
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Model Saving**: joblib
- **Notebook**: Jupyter (`.ipynb`)

---

## 📦 Setup Instructions

```bash
git clone https://github.com/shibamdutta99/loan-default-risk-prediction.git
cd loan-default-risk-prediction
pip install -r requirements.txt

Then open the Jupyter notebook:
jupyter notebook "Loan Default Risk Prediction.ipynb"
```


🚀 Future Work
Model tuning (GridSearchCV)

Cross-validation

Deploy model with Streamlit or Flask

Add feature selection pipeline

🙋‍♂️ About Me
Hi, I'm Shibam Dutta — a data analyst transitioning from photography and visual storytelling into the world of data.

📌 Open to Data Analyst and ML Associate roles
📬 Let’s connect on [LinkedIn](https://www.linkedin.com/in/shibam-dutta-6a644a43/)


⭐ Support This Project
If you found this helpful:

✅ Star the repo
📣 Share it with your network
🧠 Feedback and suggestions are always welcome!
