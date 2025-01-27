# Zomato Dashboard

## 📖 Overview

The **Zomato Dashboard** is a powerful data visualization project designed to analyze Zomato's performance across various metrics. Built using **Power BI**, this dashboard offers a user-friendly interface for exploring insights into sales, user engagement, and city-level performance. This project is ideal for data analysts, business strategists, and decision-makers looking to leverage data for improved operational efficiency and growth.

---

## ✨ Features

### **1. Overview Page**
- **Purpose:** Provides a high-level summary of Zomato's overall performance.
- **Key Metrics:**
  - **Sales Amount:** `987M`
  - **Sale Quantity:** `2M`
  - **Overall Ratings:** `148K`
  - **Total Orders:** `150K`
- **Visuals:**
  - **Top 100 Cities by Sales Amount:** Highlights the top-performing cities (e.g., Tirupati, Baner, and Raipur).
  - **Sales Trend by Year:** Line chart showing annual sales growth.
  - **Category-Wise Insights:** Breakdown of Non-Veg, Veg, and Other food items in terms of sales and ratings.

---

### **2. User Performance Page**
- **Purpose:** Tracks user behavior, including active users, new customers, and churned customers.
- **Key Metrics:**
  - **Active Users:** `78K`
  - **New Users:** `12K` (segmented by gender)
  - **Lost Customers:** `33K` (segmented by gender)
  - **Ratings Count:** `148K`
- **Visuals:**
  - **Users by Age:** Bar chart showing user engagement based on age groups.
  - **Gain vs. Loss Analysis:** Bar charts to compare gained and lost users by gender.

---

### **3. City Performance Page**
- **Purpose:** Focuses on city-level performance metrics to identify opportunities and challenges in different regions.
- **Key Metrics:**
  - **Sales Amount:** `987M`
  - **Sale Quantity:** `2M`
  - **Total Orders:** `150K`
- **Visuals:**
  - **City-Wise Data Table:** Displays sales, orders, and gained users for each city.
  - **Sales by City:** Bar chart ranking cities based on their sales contribution.
  - **User and Ratings by City:** Visuals to analyze user count and average ratings in top cities.

---

## 🗂️ Dataset Description

The dataset used for this project includes the following key tables:
1. **Users:** Contains user demographics such as age, gender, and location.
2. **Orders:** Includes details of orders, such as order amount, date, and quantity.
3. **Food Categories:** Data on Non-Veg, Veg, and Other categories.
4. **Cities:** City-wise performance metrics, including sales and orders.
5. **Ratings:** User feedback and ratings for different food items and services.

### Sample Columns:
- `User_ID`
- `Order_ID`
- `City`
- `Sales_Amount`
- `Rating`
- `Category`

---

## 💻 Tools and Technologies Used

- **Power BI:** For creating interactive visualizations and dashboards.
- **SQL Server:** For data extraction, transformation, and loading (optional).
- **Excel:** Dataset preparation and formatting.
- **DAX (Data Analysis Expressions):** For custom calculations and measures.

---

## 📊 Use Cases

1. **Business Strategy:**
   - Identify high-performing cities and focus marketing efforts on underperforming regions.
2. **User Engagement Analysis:**
   - Track user churn rates and implement strategies to retain customers.
3. **Product Insights:**
   - Evaluate sales performance of Veg vs. Non-Veg categories.
4. **Operational Planning:**
   - Analyze yearly trends to prepare for peak seasons.

---

## 🚀 How to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/zomato-dashboard.git
   ```
2. **Open the Power BI File:**
   - Download and open the `.pbix` file in **Power BI Desktop**.
3. **Connect to the Dataset:**
   - Use the provided sample dataset or connect to your own database.
4. **Refresh Data:**
   - Click on `Refresh` to load the latest data into the dashboard.
5. **Explore the Dashboard:**
   - Navigate through the **Overview**, **User Performance**, and **City Performance** pages.

---

## 🛠️ Key Insights

### **Business Impact**
- Tirupati is the top-performing city with a sales amount of `43M`.
- Male users contribute more to orders compared to females, but customer retention is a challenge.
- Veg category outperforms Non-Veg in terms of sales and ratings.

### **Trends**
- Sales peaked in 2018 with a significant drop in subsequent years.
- Active users are concentrated in the 25–30 age group, suggesting a target demographic.

---

## 📷 Dashboard Screenshots

### **Overview Page**
![Overview Screenshot](Overview-Screenshot.PNG)

### **User Performance Page**
![User Performance Screenshot](path/to/user-performance-screenshot.png)

### **City Performance Page**
![City Performance Screenshot](path/to/city-performance-screenshot.png)

---

## 📈 Future Enhancements

1. **Real-Time Updates:**
   - Integrate live data sources for real-time analysis.
2. **Predictive Analytics:**
   - Use machine learning models to predict future trends in sales and user behavior.
3. **Advanced Filters:**
   - Add more interactive filters for deeper drill-down capabilities.
4. **Mobile Optimization:**
   - Design mobile-friendly layouts for better accessibility.

---
```
