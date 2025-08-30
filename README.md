# 🛒 Retail Sales EDA (Mini Project)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a retail sales dataset (synthetic, India-based).  
The aim is to explore customer segments, product categories, and sales trends to generate actionable insights.  

## 📊 Dataset
- 1,500+ retail orders
- Features: order_date, delivery_date, city, state, segment, product_category, payment_method, price, discount, total_sales, returns, shipping_days, etc.
- Contains intentional issues: missing values, duplicates, and outliers (for cleaning practice).

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib
- Jupyter Notebook

## 🔑 Steps Followed
1. Data cleaning (duplicates, missing values, outliers)
2. Feature engineering (`delivery_delay`, `order_month`)
3. Univariate analysis (sales distribution, discount patterns)
4. Bivariate analysis (segment vs sales, discount vs sales)
5. Time series analysis (monthly orders & sales trends)
6. Segmentation deep-dive (categories, cities, returns)

## 📈 Sample Visualizations
- Distribution of sales  
- Monthly orders & sales trend  
- Top product categories by revenue  
- Discount vs total sales scatter plot  


## 💡 Key Insights
- Electronics & Fashion contribute the highest sales volume.
- Corporate segment spends more per order compared to Consumers.
- Discounts >15% do not increase sales significantly.
- Return rate is higher in Fashion category.
- Average delivery time is ~3–4 days, but some cities face >6 days.

## 🚀 Next Steps
- Cohort analysis for customer retention
- Customer lifetime value (CLV) prediction
- Build a sales forecast model

---
