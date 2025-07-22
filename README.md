# 📊 Personal Loan Acceptance Prediction

## 🔍 Objective
Predict which customers are likely to accept a personal loan offer using the **Bank Marketing Dataset** from UCI Machine Learning Repository.

## 📁 Dataset
- **Source:** [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- We used the `bank-additional-full.csv` file for this analysis.

## 🧰 Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## ✅ Steps Performed

### 1. Data Loading & Exploration
- Loaded dataset using `pandas`
- Checked `.shape`, `.info()`, and `.describe()`
- Explored features like `age`, `job`, `marital`, `duration`, etc.

### 2. Data Visualization
- Created histograms and countplots for key features
- Explored correlations using heatmaps

### 3. Model Building
- Trained both:
  - Logistic Regression (with feature scaling)
  - Decision Tree Classifier
- Used `train_test_split` for data split

### 4. Model Evaluation
- Confusion Matrix
- Classification Report
- Accuracy score

### 5. Business Insights
- Customers who had longer last contact duration or had success in previous campaigns were more likely to accept the offer.
- Marital status and job type showed varying loan acceptance behavior.

## 📈 Results
- **Logistic Regression Accuracy:** ~91%
- **Decision Tree Accuracy:** ~89%
- Best performance observed with logistic model after scaling

## 📌 Conclusion
Machine learning models can help banks predict which customers are more likely to accept personal loans, enabling more targeted marketing strategies.

## 📎 Project Notebook
You can view the full project in the Jupyter/Colab notebook: `internship_new_project01.ipynb`

---

## 🔖 License
This project is for educational purposes under an open license.
