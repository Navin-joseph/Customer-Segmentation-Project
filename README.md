# 📊 Customer Segmentation & Sales Prediction

## 🚀 Overview

This project is an end-to-end data analysis and machine learning solution designed to analyze customer behavior and sales trends. It integrates data preprocessing, SQL-based analysis, clustering, predictive modeling, and interactive visualization to generate meaningful business insights.

---

## 🛠️ Tools & Technologies

* 🐍 Python (Pandas, NumPy, Matplotlib)
* 🤖 Machine Learning (Scikit-learn)
* 🗄️ MySQL (SQL for data analysis)
* 📊 Power BI (Dashboard Visualization)
* 💻 Visual Studio Code
* 🌐 GitHub

---

## 📂 Project Structure

```
Customer-Segmentation-Project/
│
├── data/
│   ├── superstore.csv
│   ├── cleaned_sales.csv
│   └── customer_segments.csv
│
├── notebook/
│   └── segmentation.ipynb
│
├── sql/
│   └── queries.sql
│
├── dashboard/
│   └── dashboard.pbix
│
├── requirements.txt
│
└── README.md
```

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning & Preprocessing (Python)

* Handled missing values and cleaned dataset
* Converted date columns into proper format
* Standardized column names

---

### 2️⃣ SQL Data Analysis (MySQL)

* Imported dataset into MySQL
* Performed data aggregation using SQL queries:

  * Total Sales calculation
  * Region-wise performance analysis
  * Top customers identification
* Used SQL concepts like:

  * GROUP BY
  * ORDER BY
  * Aggregation functions (SUM, COUNT)

---

### 3️⃣ Feature Engineering

* Created customer-level features:

  * Total Spend
  * Purchase Frequency
* Generated time-based features (Month, Year)

---

### 4️⃣ Customer Segmentation (Clustering)

* Applied **K-Means Clustering** to group customers
* Segmented into:

  * High-value customers
  * Medium-value customers
  * Low-value customers

---

### 5️⃣ Sales Prediction

* Built a **Linear Regression model** to predict sales trends
* Evaluated model performance using:

  * Mean Squared Error (MSE)
  * R² Score

---

### 6️⃣ Data Visualization (Power BI)

* Developed an interactive dashboard including:

  * KPI Cards (Total Sales, Total Customers, Avg Spend)
  * Customer Segmentation (Scatter Plot)
  * Monthly Sales Trend
  * Customer Distribution by Segment
  * Top Customers Table

---

## 📊 Dashboard Preview
<img width="1374" height="790" alt="dashboard" src="https://github.com/user-attachments/assets/b8803f15-4334-4adc-8704-b3ab02903fe6" />

---

## 📈 Key Insights

* Majority of customers belong to the low-value segment, indicating growth opportunities
* High-value customers contribute significantly to total revenue
* Sales show an increasing trend in later months, suggesting seasonal demand patterns

---

## 💡 Business Impact

* Helps identify high-value customers for targeted marketing strategies
* Improves understanding of customer purchasing behavior
* Enables data-driven decision-making through predictive insights

---

## 🔮 Future Improvements

* Implement advanced ML models (Random Forest, XGBoost)
* Automate data pipeline
* Deploy dashboard using web applications (Streamlit)

---

## 👤 Author

**Navin Raja J**
📧 [navinrajajoseph@gmail.com](mailto:navinrajajoseph@gmail.com)

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
