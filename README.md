<p align="center">
  <img src="https://github.com/MilenaBaldeva/Codes/blob/32a2a570c3ded66f5ff4c8a76ab741324186a8f8/Slides.jpg" width="600px" />
</p>

<h1 align="center">E-Commerce Sales Performance and Forecast</h1>

## 📌 Overview
This project simulates a real-world data analytics case where an e-commerce company aims to improve **customer retention** by analyzing user behavior and sales data. The analysis focuses on **data cleaning, exploratory analysis, customer segmentation, and sales forecasting**, culminating in a **Tableau dashboard** and a **business recommendations report**.

## 📖 Table of Contents
1. [Key Insights](#-key-insights)
2. [Customer Segmentation](#-customer-segmentation)
3. [Sales Forecast Insights](#-sales-forecast-insights)
4. [Business Recommendations](#-business-recommendations)
5. [Project Workflow](#-project-workflow)
6. [Project Structure](#-project-structure)
7. [Explore the Dashboard and the Report](#-explore-the-dashboard-and-the-report)
8. [Tools and Technologies Used](#-tools-and-technologies-used)
9. [Data Source](#-data-source)
10. [Author](#-author)

## 📊 Key Insights
- **Total Revenue:** £9.7M (2010-2011)
- **Total Quantity Sold:** 5.16M items
- **Best Sales Day:** **Thursday** (highest sales), **Sunday** (lowest). No sales on Saturdays.
- **Top-Selling Products:** Dotcom Postage, Regency Cake Stand 3-Tier
- **Top-Spending Customers:** A small segment of high-value customers drives a significant portion of revenue.
- **Regional Performance:** The UK leads with £8.16M in sales, while Germany and France show growth potential.
- **Seasonality:** Sales peak in November-December, with mid-year dips.

## 🎯 Customer Segmentation
- **Low-Value Customers (🔴 Red):** Majority of buyers, opportunity for upselling.
- **Mid-Value Customers (🟡 Yellow):** Moderate engagement, potential for growth.
- **High-Value Customers (🟢 Green):** Small segment but major revenue contributors.

📌 **Approach:**  
- Used **K-Means Clustering** to segment customers based on **Recency, Frequency, and Monetary (RFM) analysis**.
- Identified patterns in customer purchasing behavior.

## 🔮 Sales Forecast Insights
- **Predicted Growth:** Sales expected to rise over time.
- **Holiday Spikes:** Critical for promotional strategies.
- **Inventory Planning:** Forecasting helps optimize stock replenishment.

📌 **Approach:**  
- Applied **Time-Series Forecasting** using **Prophet model**.
- Focused on generating a general forecast trend rather than detailed model evaluation.

## 📌 Business Recommendations
1. **Increase High-Value Customers:** Implement loyalty programs and personalized discounts.
2. **Optimize Pricing Strategies:** Adjust prices for low-margin items and introduce bundle deals.
3. **Leverage Best Sales Days:** Target Thursday for promotions and plan early holiday sales.
4. **Expand Internationally:** Focus on Germany & France with localized marketing campaigns.
5. **Improve Forecasting:** Automate stock replenishment and use dynamic pricing.
6. **Introduce Saturday Sales:** If feasible, explore launching weekend sales to capture additional revenue.

## 🔄 Project Workflow
### 1️⃣ **Data Collection & Cleaning**
- Imported the **Online Retail dataset**.
- Handled **missing values, duplicates, and anomalies**.
- Standardized **data types** and formatted **date columns**.

✅ **Tools Used:** Python (pandas, NumPy)

---

### 2️⃣ **Exploratory Data Analysis (EDA)**
- Conducted **sales trends analysis and customer segmentation**.
- Visualized **daily, monthly, and yearly sales performance**.
- Examined **repeat purchases and revenue drivers**.

✅ **Tools Used:** Tableau

---

### 3️⃣ **Customer Segmentation**
- Applied **K-Means clustering** to segment customers.
- Used **RFM (Recency, Frequency, Monetary) analysis**.
- Identified **high-value customers and sales patterns**.

✅ **Tools Used:** Python (scikit-learn, pandas)

---

### 4️⃣ **Sales Forecasting**
- Built a **Time-Series Forecasting Model (Prophet)**.
- Generated **future sales trends & demand projections**.
- Focused on **trend visualization** rather than evaluation.

✅ **Tools Used:** Python (Prophet)

---

### 5️⃣ **Reporting & Visualization**
- Created **interactive Tableau Dashboards** with **filtering options**.
- Built a **Google Slides report** summarizing insights & recommendations.

✅ **Tools Used:** Tableau, Google Slides

---

## 📂 Project Structure
- **📁 Data:** Contains the Online Retail dataset.
- **📊 Tableau Dashboards:** 
  - **Sales Performance Analysis**: Overview of key metrics and insights.
  - **Sales Forecast & Insights**: Predictive sales trends and business recommendations.
- **📄 Google Colab Notebook:**
  - **Data Cleaning**
  - **Customer Segmentation**
  - **Sales Forecasting**
- **📄 Reports:** Insights and business recommendations in **Google Slides**.

## 🚀 Explore the Dashboard and the Report

<p align="center">
  <img src="https://github.com/MilenaBaldeva/Codes/blob/32a2a570c3ded66f5ff4c8a76ab741324186a8f8/Dashboard1.jpg" width="400px" />
  <img src="https://github.com/MilenaBaldeva/Codes/blob/32a2a570c3ded66f5ff4c8a76ab741324186a8f8/Dashboard2.jpg" width="400px" />
</p>


🔗 [Click Here to View the Tableau Dashboard](https://public.tableau.com/views/Sales_Analysis_17423026047060/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) 

The project includes **two interactive Tableau dashboards**:  
- **Sales Performance Dashboard** – Analyzes total sales, profit, and quantity sold, with filters for deeper insights.  
- **Sales Forecast & Insights Dashboard** – Displays future sales trends.

### 🔄 Navigation Features:  
- **Navigation buttons** allow seamless switching between dashboards.  
- **Reset All Filters** button available on the first dashboard.  
- **Insights & Recommendations Button** on the second dashboard opens the final business recommendations presentation.

  📄 [Click Here to View the Full Insights & Recommendations Report](https://docs.google.com/presentation/d/1kUNrs8M3zGCLMPObR5IAs6XRNsZrOVJVxaW-hXv_8sY/present?slide=id.g34471732842_0_0)

---

### 🛠️ Tools and Technologies Used
- **Python** (pandas, NumPy, scikit-learn, Prophet)
- **Google Colab** (Code execution & modeling)
- **Tableau** (Interactive Dashboards)
- **Google Slides** (Business Recommendations Report)
- **GitHub** (Version Control)

---

### 📊 Data Source
The data used in this analysis is from [Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail), which can be accessed at the provided link.

## 📌 Author
**Milena Baldeva**  
📍 Easton, PA, USA  
📧 [milena.baldeva@gmail.com](mailto:milena.baldeva@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/milena-baldeva-051b01100/)  


Feel free to contribute, provide feedback, or explore the insights for your own business strategies! 🚀
