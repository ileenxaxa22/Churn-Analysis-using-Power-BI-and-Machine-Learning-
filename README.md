# 📊 Churn Analysis using SQL, Power BI & Machine Learning

This project is an **end-to-end churn prediction and business intelligence solution** that helps companies identify customers who are likely to leave (churn) and understand the factors driving their decision.  

It integrates **SQL + Power BI + Python (Machine Learning)** to provide:
- Clean and transformed customer data  
- Interactive dashboards  
- Predictive churn analytics  
- Actionable business insights  

---
## 🚀 Project Workflow

### **1. Data Extraction & Cleaning (SQL)**
- Loaded the raw customer churn dataset into SQL.
- Performed data cleaning:
  - Removed missing values  
  - Extracted important columns  
  - Standardized data types  
  - Fixed inconsistent entries  
- Exported the cleaned dataset for:
  - Power BI dashboard  
  - Machine Learning model  

---
### **2. Exploratory Data Analysis (Power BI)**
Created professional BI dashboards to understand customer behavior and churn patterns.

📌 Key Insights Identified:
- Month-to-month customers churn the most  
- Customers with high monthly charges are more likely to leave  
- Long-tenure customers rarely churn  
- Auto-pay and yearly contract customers have lowest churn  
  
![Churn Dashboard](images\summary.png)

---

## 🤖 3. Machine Learning Model (Python)
- Loaded the same SQL-cleaned dataset
- Performed:
  - Additional preprocessing  
  - One-hot encoding  
  - Train-test split  
- Trained predictive models (Logistic Regression / Random Forest)
- Generated churn predictions for each customer
- Exported results:  
  - `Predicted_Churn_Customers.csv`  
  - `Prediction_analysis.xlsx`

---

## 📊 4. Churn Prediction Dashboard (Power BI)
After generating predictions using Python, a **second dashboard** was created to visualize:

- High-risk churn customers  
- Probability of churn  
- Revenue at risk  
- Customer segmentation  
- Top churn-causing factors  

![Prediction Dashboard](images\churn_prediction.png)

---

## 🧩 Real-World Problem We Solved

Companies lose millions due to customer churn.  
Most businesses do not know:
- **Who is about to leave**
- **Why they are leaving**
- **How much revenue is at risk**

This project solves all three:

### ✔ Identify customers at risk  
The ML model flags customers who may churn next month.

### ✔ Understand why churn happens  
Power BI highlights the drivers (contract type, charges, tenure, etc.)

### ✔ Estimate revenue impact  
The dashboard shows potential revenue loss so companies can act.

---

## 📝 Conclusion

This project delivers a **complete churn prediction system** that combines data engineering, analytics, visualization, and machine learning.  

Using SQL, Power BI, and Python, we created a pipeline that helps businesses:
- Reduce customer churn  
- Improve customer satisfaction  
- Take targeted retention actions  
- Protect monthly revenue  

---

## 📂 Project Files

- `Churn Analysis.pbix` – Power BI dashboard  
- `cleandata`– data
- `prediction_churn_final.ipynb` – Machine learning notebook  
- `images` – Dashboards 
- `README.md` – Project documentation 

---

## 🛠 Tools & Technologies
- **SQL**
- **Power BI**
- **Python**
  - pandas  
  - scikit-learn  
  - matplotlib / seaborn  
- **Jupyter Notebook / VS Code**

---

## 🙌 Author  
**Ileen Xaxa**  
Data Analyst & Machine Learning Enthusiast
🔗 [LinkedIn](https://www.linkedin.com/in/ileen-xaxa-713625bt9/)  
💻 [GitHub](https://github.com/ileenxaxa22) 
---

