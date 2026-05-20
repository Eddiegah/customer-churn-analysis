<div align="center">

# 📉🔥 CUSTOMER CHURN ANALYSIS & PREDICTION 🔥📉

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=1000&color=FF6B35&center=true&vCenter=true&width=750&lines=Why+Are+Customers+Leaving%3F+Let+ML+Answer!;Telco+Customer+Churn+Dataset+Analyzed+%F0%9F%93%8A;Powered+by+Python+%2B+Scikit-Learn+%F0%9F%90%8D;Predict+Churn+Before+It+Happens+%F0%9F%9A%A8" alt="Typing SVG" />

---

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Sklearn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed%20✅-brightgreen?style=for-the-badge)

</div>

---

## 🌟 What Is This Project About?

> **"Acquiring a new customer costs 5x more than retaining an existing one. Knowing WHO will leave — before they do — is worth millions."**

This project builds a **Machine Learning model** that predicts whether a telecom customer is likely to **churn (cancel their subscription)** — giving businesses the power to act before it's too late. Using the **Telco Customer Churn dataset**, we analyze customer demographics, services, and account data to identify churn patterns and train a classifier.

---

## 🎯 Problem Statement

| 💬 Challenge | 📊 Detail |
|---|---|
| Dataset | Telco Customer Churn (Kaggle) |
| Target Variable | `Churn` — Yes / No |
| Features | Demographics, Services, Contract, Billing |
| Key Challenge | Understanding **which features drive churn** |
| Business Goal | Reduce churn rate by enabling early intervention |

---

## 🧰 Tech Stack

```python
import numpy as np          # ➜ Numerical computing
import pandas as pd         # ➜ Data loading & manipulation
import matplotlib.pyplot    # ➜ Visualizations
import seaborn as sns       # ➜ Statistical plots
from sklearn import *       # ➜ ML models, preprocessing, evaluation
```

---

## 📁 Project Structure

```
📦 customer-churn-analysis/
 ┣ 📓 Customer_Churn_Analysis_&_Prediction.ipynb   ← Main Notebook
 ┣ 📊 Telco-Customer-Churn.csv                     ← Dataset (from Kaggle)
 ┣ 📄 README.md                                    ← You're reading it!
 ┗ 📸 images/                                      ← Output plots & charts
```

---

## 🔄 Project Workflow

```
📥 Load Data  ──►  🔍 EDA & Visualization  ──►  🧹 Data Cleaning
                                                        │
                                                        ▼
📈 Evaluate  ◄──  🤖 Train Models  ◄──  ⚙️ Feature Engineering & Encoding
```

---

## 📊 Exploratory Data Analysis Highlights

- 👥 Analyzed **customer demographics** — gender, senior citizen status, dependents
- 📡 Explored **service usage** — phone, internet, streaming, tech support
- 📋 Investigated **contract types** — month-to-month vs long-term contracts
- 💳 Studied **payment methods** and their correlation to churn
- 🔥 Built **correlation heatmaps** to identify the strongest churn predictors

---

## 🔑 Key Churn Drivers Found

| 🚩 Factor | 📌 Insight |
|---|---|
| Contract Type | Month-to-month customers churn the most |
| Tenure | New customers (low tenure) have highest churn |
| Internet Service | Fiber optic users churn more than DSL |
| Tech Support | Customers without tech support churn more |
| Monthly Charges | Higher charges correlate with higher churn |

---

## 🤖 Models Used

| 🧠 Model | 🎯 Purpose |
|---|---|
| Logistic Regression | Fast, interpretable baseline |
| Random Forest | Handles non-linearity, feature importance |
| Decision Tree | Transparent rules for churn prediction |
| K-Nearest Neighbors | Similarity-based classification |

---

## 📈 Evaluation Metrics

> ⚠️ We care about **catching churners** — missing a churner is more costly than a false alarm!

| 📐 Metric | 📌 Why It Matters |
|---|---|
| **Precision** | Of predicted churners, how many actually churned? |
| **Recall** | Of actual churners, how many did we catch? |
| **F1-Score** | Harmonic balance of Precision & Recall |
| **ROC-AUC** | Overall discriminative power of the model |
| **Confusion Matrix** | Full breakdown of TP, TN, FP, FN |

---

## 💡 Key Takeaways & Learnings

- 🏆 Learned how to perform **full EDA on business data**
- 🔍 Understood how **contract terms, tenure, and services** drive churn
- 📊 Practiced **encoding categorical variables** for ML models
- 🧪 Compared multiple classifiers and selected the best performer
- 💼 Built a project that mirrors real **CRM and telecom analytics workflows**

---

## 🚀 How to Run This Project

```bash
# 1️⃣ Clone the repository
git clone https://github.com/YOUR_USERNAME/customer-churn-analysis.git

# 2️⃣ Navigate into the folder
cd customer-churn-analysis

# 3️⃣ Install required libraries
pip install numpy pandas matplotlib seaborn scikit-learn

# 4️⃣ Download the dataset from Kaggle
# https://www.kaggle.com/datasets/blastchar/telco-customer-churn
# Place Telco-Customer-Churn.csv in the project folder

# 5️⃣ Launch Jupyter Notebook
jupyter notebook "Customer_Churn_Analysis_&_Prediction.ipynb"
```

---

## 📚 Dataset Source

> 📎 [Kaggle — Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The dataset contains 7,043 customer records from a telecom company, with 21 features covering demographics, account info, and subscribed services. Target: whether the customer churned within the last month.

---

## 🙋‍♂️ Author

<div align="center">

**Made with 💻 + ☕ + 🔥 by Edmund Eric Gah**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/in/edmund-eric-gah-7432a7213/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Eddiegah)

⭐ *If you found this project helpful, drop a star!* ⭐

</div>

---

<div align="center">
<sub>Built as part of a Machine Learning portfolio | 2025</sub>
</div>
