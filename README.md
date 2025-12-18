# Customer-Behaviour-Analysis
Data Analysis project showcasing customer behaviour usng Python, Sql, Power BI 

# 🛒 Customer Shopping Behaviour Analysis

An end-to-end **Data Analytics project** analyzing customer shopping behaviour using transactional data.  
This project demonstrates **Python, SQL, Power BI, and business storytelling** skills in a single workflow.

---

## 📌 Project Overview
This project analyzes customer shopping behaviour using **3,900 transactional records** across multiple product categories.  
The objective is to uncover insights into **spending patterns, customer segments, product performance, and subscription behaviour** to support data-driven business decisions.

---

## 📊 Dataset
- **Rows:** 3,900  
- **Columns:** 18  
- **Type:** Transactional customer data  

### Key Features
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Behavioural Data:** Discounts, Promo Usage, Purchase Frequency, Review Rating, Shipping Type  

### Data Quality
- Missing values identified in the **Review Rating** column  
- Missing values handled using **median rating per product category**

---

## 🧰 Tools & Technologies
- **Python** – Pandas, NumPy, Matplotlib, Seaborn  
- **SQL** – PostgreSQL / MySQL / SQL Server  
- **Power BI** – Interactive dashboard and KPIs  
- **Gamma** – Presentation (PPT)  
- **Jupyter Notebook** – Analysis and documentation  

---

## 🔄 Project Workflow
1. Load raw dataset using Python  
2. Perform Exploratory Data Analysis (EDA)  
3. Clean data (missing values, column standardization)  
4. Feature engineering:
   - Age groups  
   - Purchase frequency (in days)  
5. Load cleaned data into SQL database  
6. Run business-focused SQL queries  
7. Build Power BI dashboard  
8. Create report and presentation  

---

## 🧪 Exploratory Data Analysis (Python)
- Dataset structure and summary statistics  
- Missing value analysis and imputation  
- Column standardization (snake_case)  
- Feature engineering for deeper insights  

Notebook: `Customer_Behaviour_Analysis.ipynb`

---

## 🗄️ SQL Analysis (Business Questions)
The following business questions were answered using SQL:

1. Revenue by Gender  
2. High-spending customers who used discounts  
3. Top 5 products by average review rating  
4. Average purchase amount by shipping type  
5. Subscribers vs Non-Subscribers spending comparison  
6. Products most dependent on discounts  
7. Customer segmentation (New, Returning, Loyal)  
8. Top 3 products per category  
9. Relationship between repeat purchases and subscriptions  
10. Revenue contribution by age group  

---

## 📈 Power BI Dashboard
An interactive Power BI dashboard including:
- Total customers, average purchase amount, average rating  
- Revenue by category and gender  
- Subscription vs non-subscription comparison  
- Sales and revenue by age group  
- Filters for gender, category, and shipping type  

---

## 💡 Key Business Insights
- Subscription customers spend more on average  
- A small set of categories contributes most of the revenue  
- Discount usage does not always reduce purchase value  
- Loyal customers are more likely to subscribe  
- Certain age groups and shipping types generate higher revenue  

---

## 📌 Business Recommendations
- Promote subscription benefits to increase retention  
- Introduce loyalty programs for repeat buyers  
- Optimize discount strategy to protect margins  
- Highlight top-rated and best-selling products  
- Target high-revenue age groups and express-shipping users  

---

## ▶️ How to Run This Project
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn sqlalchemy

