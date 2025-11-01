# 🛍️ Customer Shopping Behaviour Analysis  

## 🧠 Project Overview  
This project analyzes **customer shopping behaviour** using transactional data from **3,900 purchases** across multiple product categories.  
The objective was to understand **spending patterns, customer segments, product preferences, and subscription behaviour** — and to translate raw data into actionable business insights through a full data analytics pipeline.  

The workflow involved **Excel**, **Python**, **MySQL**, **Power BI**, and **AI-assisted reporting tools**, integrating multiple technologies to produce a complete end-to-end analytics solution.  

---

## 📂 Dataset Summary   
- **Key Features:**  
  - Customer demographics → Age, Gender, Location, Subscription Status  
  - Purchase details → Item Purchased, Category, Purchase Amount, Season, Size, Colour  
  - Shopping behaviour → Discount Applied, Promo Code Used, Frequency, Review Rating, Shipping Type  
- **Missing Data:** 37 missing values in `Review Rating` column (handled during data cleaning)

---

## ⚙️ Tools & Technologies  
| Tool | Purpose |
|------|----------|
| 📊 Excel | Dataset review, exploration, and understanding |
| 🐍 Python (Pandas, NumPy, Matplotlib, Seaborn) | Data cleaning, preprocessing, EDA, and MySQL integration |
| 🛢️ MySQL | Querying, analysis, and data modeling |
| 📈 Power BI | Interactive dashboard creation and visualization |
| 🧠 Gamma AI | Presentation creation (PPT) |
| 📝 Microsoft Word / PDF | Detailed report documentation |

---

## 🧩 Project Workflow  

### 1️⃣ Excel — Data Review & Understanding  
- Imported and inspected the dataset to check for structure, missing values, and data distribution.  
- Reviewed key variables like purchase amount, gender, subscription, and product category.  

---

### 2️⃣ Python — Data Cleaning & Exploratory Data Analysis (EDA)  
- **Loaded dataset** into a Pandas DataFrame for transformation.  
- **Missing Data:** Imputed missing `Review Rating` values using median rating per product category.  
- **Column Standardization:** Renamed columns to snake_case for readability.  
- **Feature Engineering:**  
  - Created `age_group` column by binning customer ages.  
  - Calculated `purchase_frequency_days` for behavioural segmentation.  
- **Consistency Checks:** Compared `discount_applied` vs `promo_code_used` to remove redundant fields.  
- **Database Integration:** Loaded cleaned DataFrame directly into a **MySQL database** for further analysis.  

---

### 3️⃣ MySQL — Data Analysis & Business Insights  
Performed structured SQL analysis to answer key business questions:  

1. **Revenue by Gender** → Compared total revenue by male vs female customers.  
2. **High-Spending Discount Users** → Identified customers using discounts but spending above average.  
3. **Top 5 Products by Rating** → Highlighted products with the highest review scores.  
4. **Shipping Type Analysis** → Compared average spend between Standard and Express delivery.  
5. **Subscribers vs Non-Subscribers** → Analyzed spending patterns across customer types.  
6. **Discount-Dependent Products** → Found top 5 products with high discount usage.  
7. **Customer Segmentation** → Classified into *New*, *Returning*, and *Loyal* customers.  
8. **Top 3 Products per Category** → Ranked top sellers by category.  
9. **Repeat Buyers & Subscriptions** → Correlated purchase frequency with subscription rates.  
10. **Revenue by Age Group** → Measured contribution by demographic groups.  

---

### 4️⃣ Power BI — Interactive Dashboard  
Created a dynamic and interactive **Power BI dashboard** integrating MySQL data to visualize key findings:  
- 🧍‍♂️ Customer demographics and segmentation  
- 💰 Revenue and purchase analysis by category, gender, and region  
- 🏷️ Impact of discounts and promotions on sales  
- 🚚 Shipping preferences and profitability  
- ⭐ Product performance by rating and purchase frequency  

The dashboard helps stakeholders explore metrics interactively and identify performance drivers at a glance.  

---

### 5️⃣ Reporting & Presentation  
- 📘 **Detailed Report (Word → PDF):** Summarized all analytical steps, SQL results, and Power BI insights into a professional document.  
- 🪄 **Presentation (Gamma AI):** Created an engaging visual presentation of key findings, trends, and recommendations for business stakeholders.  

---

## 📸 Dashboard & Visuals

<img width="1587" height="866" alt="Dashboard" src="https://github.com/user-attachments/assets/18f5afe7-9ce6-4f0c-a773-15a026878691" />

---
## 📈 Business Insights & Recommendations  
- **Boost Subscriptions:** Encourage sign-ups by promoting exclusive subscriber benefits.  
- **Customer Loyalty Programs:** Incentivize repeat buyers to convert them into loyal customers.  
- **Review Discount Strategy:** Optimize discount offers to maintain profitability while driving sales.  
- **Highlight Top Products:** Promote best-selling and top-rated items in marketing campaigns.  
- **Targeted Marketing:** Focus marketing spend on high-revenue age groups and express-shipping users.  

---

## 🧠 Skills Demonstrated  
- Data Cleaning & Preprocessing (Python, Pandas)  
- Data Integration (MySQL Database Management)  
- Business Analysis using SQL Queries  
- Power BI Dashboard Design & Storytelling  
- Report Writing & Documentation (Word/PDF)  
- Presentation Design using AI Tools (Gamma AI)  
- End-to-End Data Analytics Workflow  

---

## 🚀 Conclusion  
This project demonstrates a complete **Data Analytics Lifecycle** — from raw data to business intelligence and communication.  
By combining **Excel, Python, MySQL, Power BI, and AI-powered storytelling**, I successfully built a system to understand **customer behaviour patterns**, derive **actionable insights**, and communicate them effectively to decision-makers.  

---

## 📫 Connect With Me  
🔗 [LinkedIn](https://www.linkedin.com/in/ayaan-gavandi-a16202218/)  
📧 [Email](mailto:ayaangavandi33@gmail.com)
