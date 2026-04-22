# 👨🏻‍💻 Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data of **3,900 purchases** across multiple product categories.

The objective is to extract meaningful insights related to:
- Customer spending patterns  
- Product preferences  
- Customer segmentation  
- Subscription behavior  

and use these insights to support **data-driven business decisions**.

---

## 📊 Dataset Summary

- **Total Records:** 3,900  
- **Total Columns:** 18  

### Key Features:
- Customer Demographics → Age, Gender, Location, Subscription Status  
- Purchase Details → Item, Category, Amount, Season, Size, Color  
- Behavior Data → Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type  

- Missing values were present in the **Review Rating column** and handled during preprocessing :contentReference[oaicite:0]{index=0}  

---

## 🧰 Tools & Technologies Used

- **Python (Pandas, NumPy)** → Data Cleaning & EDA  
- **PostgreSQL / SQL** → Data Analysis  
- **Power BI** → Dashboard & Visualization  

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning & Preparation (Python)
- Loaded dataset using Pandas  
- Handled missing values using median imputation  
- Renamed columns for consistency (snake_case)  
- Created new features:
  - `age_group`
  - `purchase_frequency_days`  
- Removed redundant columns after validation  
- Loaded cleaned data into PostgreSQL database :contentReference[oaicite:1]{index=1}  

---

### 2️⃣ Data Analysis (SQL)

Performed analysis to answer key business questions:

- Revenue comparison by gender  
- High-spending customers using discounts  
- Top-rated products  
- Shipping type impact on purchase amount  
- Subscribers vs non-subscribers comparison  
- Discount-heavy products  
- Customer segmentation (New, Returning, Loyal)  
- Top products by category  
- Repeat buyers vs subscription behavior  
- Revenue contribution by age group :contentReference[oaicite:2]{index=2}  

---

### 3️⃣ Dashboard (Power BI)

- Built an interactive dashboard to visualize:
  - Total customers (~3.9K)  
  - Average purchase amount (~59.76)  
  - Revenue distribution  
  - Customer segmentation  
  - Sales trends by category and age group :contentReference[oaicite:3]{index=3}  

---

## 📈 Key Insights

- Female customers generated lower revenue compared to male customers  
- Certain products (like accessories and clothing items) had higher purchase frequency  
- Discount usage significantly influenced purchase behavior  
- Majority of customers fall under the **loyal segment**  
- Young adults contributed the highest revenue among age groups :contentReference[oaicite:4]{index=4}  

---

## 💡 Business Recommendations

- Increase subscription adoption by offering exclusive benefits  
- Introduce loyalty programs for repeat customers  
- Optimize discount strategies to balance profit and sales  
- Promote high-rated and high-selling products  
- Focus marketing on high-revenue customer segments :contentReference[oaicite:5]{index=5}  

---

## 📁 Project Files

- `Business_problem_document.pdf` → problem statement  
- `Customer_Shopping_Behavior_Dataset.csv` → raw dataset  
- `Customer_Shopping_Behavior_Analysis.ipynb` → Python analysis  
- `customer_behavior_sql_queries.sql` → SQL queries  
- `customer_behavior_dashboard.pbix` → Power BI dashboard  
- `customer_behavior_analysis_report.pdf` → Summary report  

---

## 🚀 How to Run the Project

```bash
git clone https://github.com/NaushadCodes/customer_behavior_analysis.git
cd customer_behavior_analysis
