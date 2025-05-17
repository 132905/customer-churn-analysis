# 🔁 Customer Churn Data Analysis – Case Study

This repository presents a comprehensive data analysis project focused on understanding customer churn behavior in a retail bank. The dataset contains information about 10,000 customers across France, Spain, and Germany, and explores demographic, financial, and behavioral factors influencing churn.

---

## 📂 Files in This Repository

- `Customer Churn Data Analysis Case Study.ipynb`: Full exploratory data analysis using Python.
- `churn.csv`: The dataset containing details of 10,000 customers.
- `Chrun Data Analysis Project Case Study.docx`: Detailed case study with insights and interpretations.
- `Churn Problem Statements.docx`: List of structured questions and tasks that guided the analysis.

---

## 🎯 Objective

The primary goal is to uncover insights behind why customers leave (churn) the bank, identify patterns in customer behavior, and suggest actionable steps to reduce churn. No machine learning is used in this analysis — the focus is entirely on statistical insights and visual exploration.

---

## 🧰 Tools & Technologies Used

- Python 🐍
- Pandas, NumPy
- Jupyter Notebook

---

## 🔍 Dataset Overview

- **Total Customers**: 10,000
- **Features**:
  - *Demographics*: Geography, Gender, Age
  - *Account Info*: CreditScore, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember
  - *Financials*: EstimatedSalary
  - *Target*: Exited (1 = churned, 0 = retained)

---

## 🧪 Key Analysis Performed

### 1. Churn Rate Analysis
- Overall churn rate: ~20.4%
- Highest churn by geography: **Germany** (32%)
- Churn highest among **older customers** (avg. age ~45)

### 2. Demographic & Behavioral Trends
- Customers **aged 45+** account for 50% of churners but only 30% of the total population
- **Inactive customers** churn at nearly **double** the rate of active ones
- Customers with **3+ products** have a **50%+ churn rate**

### 3. Credit & Finance Insights
- Churn increases sharply when **Credit Score < 600**
- Even customers with **Credit Score > 800** show some churn, likely due to offers from competitors
- No strong correlation between salary and churn found

---

## 📊 Sample Business Questions Answered

- What is the churn rate by geography, gender, or product usage?
- How does churn vary with age, credit score, and activity level?
- What percentage of churners are older than 45, and how does that compare to the overall population?
- Is having a credit card or zero account balance linked to churn?
- Which customer surnames appear most frequently among those who exited?

(Refer to `Churn Problem Statements.docx` for the full list of 17 analysis tasks.)

---

## 📈 Insights & Recommendations

- **Germany** shows disproportionately high churn → deeper market research needed
- **Older customers** (45+) are a flight risk → targeted retention plans advised
- **Inactive users** should be engaged through rewards or campaigns
- **Complex product bundles** (3+ products) may overwhelm → consider simplifying or tailoring offers
- Monitor customers with **low credit scores** for early signs of disengagement

---

## 🚀 Future Scope

- Develop predictive models (e.g., Logistic Regression, Decision Trees) to forecast churn
- Integrate customer feedback/survey data for qualitative insights
- Create an interactive dashboard for real-time churn monitoring

---

## 🧾 License

This project is for educational and analytical purposes. The dataset is publicly available, and any insights or results are independently derived.

