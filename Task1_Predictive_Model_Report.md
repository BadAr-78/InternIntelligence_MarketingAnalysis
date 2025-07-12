
# 📊 Task 1 – Predictive Analytics Model  
**Project Title:** Predicting Customer Response to Marketing Campaigns  
**Internship Program:** Intern Intelligence – Data Analytics Track

---

## 🎯 Objective
Build a predictive analytics model to forecast whether a customer will respond to a marketing campaign, using historical customer and campaign data.

---

## 🗂️ Dataset
- **Source:** [Kaggle – Marketing Campaign Dataset](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign)
- **Size:** ~2,200 records and 29 columns
- **Key Features:**  
  - Customer demographics: age, education, marital status, income  
  - Spending habits on product categories  
  - Campaign engagement and recency  
  - Target variable: `Response` (0 = No, 1 = Yes)

---

## 🧹 Data Preprocessing
- Removed irrelevant columns like `ID`
- Converted `Dt_Customer` to datetime and dropped it from modeling features
- Encoded categorical variables using `LabelEncoder`
- Filled missing values in `Income` with mean
- Defined:
  - `X`: Features
  - `y`: Target (`Response`)

---

## 🤖 Model Building

### Logistic Regression
- **Used as baseline**
- Accuracy: `XX.XX%` *(replace with your result)*

### Random Forest Classifier
- **Best performing model**
- Accuracy: `YY.YY%` *(replace with your result)*

---

## 📈 Evaluation
- Confusion Matrix and Classification Report
- Compared first 20 actual vs predicted results using line plot
- Metrics: Precision, Recall, F1-Score

---

## 🔍 Insights
- Income and product spending patterns had strong influence on campaign response
- Random Forest model outperformed logistic regression due to better handling of nonlinearities and feature interaction

---

## 🧰 Tools Used
- Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
- Jupyter Notebook / Google Colab
- GitHub for project management

---

## ✅ Next Steps
- Hyperparameter tuning (`GridSearchCV`)
- Balance data using `SMOTE` if needed
- Deploy model as part of marketing dashboard

---

### 📎 Submission Notes
- Task 1 completed as part of Intern Intelligence internship
- GitHub Repo: `InternIntelligence_MarketingAnalysis`
- Shared results on LinkedIn with hashtag **#internintelligence**
