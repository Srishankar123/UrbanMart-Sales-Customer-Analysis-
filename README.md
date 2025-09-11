# 🛒 UrbanMart Transaction Analysis

## 📌 Project Overview
This project analyzes **UrbanMart’s transaction dataset** to uncover customer behavior, product performance, and revenue drivers.  
It combines **Python-based exploratory data analysis (EDA)** with **RFM (Recency, Frequency, Monetary) analysis** for customer segmentation, and **Power BI dashboards** for interactive business insights.

---

## 📂 Project Files
- **UrbanMart_Transactions.csv** → Raw dataset containing transaction details.  
- **urbanmart_analysis.csv** → Cleaned dataset after preprocessing.  
- **UrbanMart_Transactions.ipynb** → Jupyter Notebook with Python-based data cleaning, EDA, and RFM analysis.  
- **UrbanMart.pbix** → Power BI dashboard for visual insights.  

---

## 🔑 Steps Performed in Python
1. **Data Cleaning**
   - Handled missing values and duplicates.  
   - Standardized date columns and categorical values.  
   - Converted transaction values into numeric format.  

2. **Univariate & Bivariate Analysis**
   - Distribution of transaction values.  
   - Most popular product categories.  
   - Payment method preferences.  
   - Category-wise revenue contribution.  

3. **Correlation Analysis**
   - Examined relationships among numerical fields.  
   - Identified strong revenue influencers.  

4. **RFM (Recency, Frequency, Monetary) Analysis**
   - **Recency** → Days since a customer’s last purchase.  
   - **Frequency** → Number of transactions made by a customer.  
   - **Monetary** → Total spending by each customer.  
   - Segmented customers into groups like **High-Value, Loyal, At-Risk, and New Customers**.  

5. **Visualization**
   - Bar charts, histograms, correlation heatmaps (Matplotlib & Seaborn).  
   - Power BI dashboards for interactive exploration.  

---

## 📊 Insights
- **Beauty, Home, and Electronics** are the highest revenue-generating categories.  
- **Digital payments** dominate compared to cash-based transactions.  
- Customer segmentation through **RFM** revealed:  
  - A small group of **loyal high-value customers** contributes a large share of revenue.  
  - **At-risk customers** require engagement strategies (discounts, offers).  
  - **New customers** are increasing but need retention strategies.  
- Transaction patterns show seasonal spikes during specific periods.  

---

## ⚙️ Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Power BI**: Interactive dashboards  
- **Dataset**: Transactional CSV files  

---

## 📂 Dashboard Preview
Here’s a snapshot of the **Power BI dashboard** built for UrbanMart:  

![UrbanMart Dashboard Preview](https://github.com/user-attachments/assets/ba867121-faa4-4694-937a-9b4642dedc33)
 

> 📌 To add your dashboard preview:  
> - Take a screenshot of your Power BI report.  
> - Save it in a folder named **`images`** inside your GitHub repo.  
> - Replace `images/powerbi_dashboard.png` with your actual file path.  
> - You can also embed a GIF if you want to show interactivity.

---

## 📓 Jupyter Notebook (View Online)

You can view the full Python analysis without downloading the repo using **nbviewer**:  

🔗 [Click here to view the UrbanMart_Transactions.ipynb](https://nbviewer.org/github/Srishankar123/UrbanMart-Sales-Customer-Analysis-/blob/main/UrbanMart_Transactions.ipynb)

---

## 👤 Author
**Srishankar Lokanath**  
_Data Analyst | Business Analytics Enthusiast_
