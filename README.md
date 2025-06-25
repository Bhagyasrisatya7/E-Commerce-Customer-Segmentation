# 🛒 E-Commerce Sales Analytics

An end-to-end E-Commerce analytics project using **Python (Pandas, Scikit-learn, Seaborn, Matplotlib)** and **Power BI** for customer segmentation, sales analysis, and business intelligence.

---

## 📊 Project Overview

This project provides detailed insights into e-commerce performance through:

- Customer behavior analysis
- Sales performance tracking
- Customer segmentation (KMeans, RFM)
- Power BI visualizations for stakeholders

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `e-commerce.csv` | Main dataset used for analysis |
| `dashboard_customer.png` | Power BI visualization - Customer Details |
| `dashboard_order.png` | Power BI visualization - Order Details |
| `dashboard_home.png` | Main dashboard interface |
| `main_analysis.ipynb` | Python script for data analysis and ML |
| `README.md` | Project documentation |

---

## 🧠 Key Python Tasks Performed

### ✅ Data Cleaning
- Removed missing values
- Renamed and standardized column names
- Converted date formats
- Added calculated fields (e.g., `total_price`)

### 📈 Feature Engineering
- Aggregated customer metrics (`orders`, `quantity`, `revenue`)
- Created a **customer segmentation** model using:
  - **KMeans clustering**
  - **Principal Component Analysis (PCA)**

### 🔍 RFM Analysis
- Recency = Days since last order
- Frequency = Number of orders
- Monetary = Total spend
- Created RFM scores and assigned customer segments (e.g., Champions, Loyal)

### 🤖 ML Model: High-Value Customer Prediction
- **Random Forest Classifier** to predict if a customer is high-value
- Evaluated with accuracy, confusion matrix, and feature importance

### 📅 Sales Trend Analysis
- Extracted `order_month`
- Analyzed monthly revenue trends using line plot

---

## 📊 Power BI Dashboards

A comprehensive **Power BI dashboard** built using e-commerce transaction data to analyze customer behavior, product performance, sales trends, and profitability across various regions and categories. This project helps in understanding how different segments and products contribute to overall business performance.

## 📊 Features

- 📆 Time-based analysis of orders, sales, and profits
- 👥 Customer segmentation by type and region
- 📦 Top-selling products and categories
- 🛍️ Discount vs Profitability visualization
- 🚚 Order shipping trends and cost analysis
- 🌎 Region and state-wise revenue performance
- 📌 KPIs:
  - Total Sales
  - Total Profit
  - Total Orders
  - Average Order Value
  - Profit Margin %

---

## 📁 Dataset Details

- **File Name:** `e-commerce.csv`
- **Total Columns:** 25
- **Key Columns Used:**
  - `Order ID`, `Order Date`, `Ship Date`
  - `Customer Name`, `Customer Segment`, `Region`
  - `Product Category`, `Sub-Category`, `Unit Price`, `Discount`
  - `Sales`, `Profit`, `Shipping Cost`, `Quantity Ordered`
    
---
    

### 1. **Home Screen**
- Navigation to "Customer Details" and "Order Details"

### 2. **Customer Details**
- Sum of customers, orders, city count
- Top 5 products sold
- High discount states
- Geographic distribution (Map visualization)

### 3. **Order Details**
- Total orders and quantity sold
- Sales by product and category
- Region-wise shipping cost
- Monthly order trends and shipping cost

---

## 📦 Technologies Used

- **Python** (Pandas, Scikit-learn, Matplotlib, Seaborn)
- **Power BI**
- **Jupyter Notebook / Google Colab**
- **KMeans, PCA, RandomForestClassifier**

---

## 📌 How to Run

### Python (Data Analysis):
1. Clone the repo and open `main_analysis.ipynb` or use Google Colab.
2. Upload `e-commerce.csv`.
3. Run each cell step-by-step to:
   - Clean data
   - Segment customers
   - Visualize results

### Power BI:
1. Open the Power BI `.pbix` file (if shared).
2. Link to the same `e-commerce.csv` or embed the data.
3. Explore the dashboards via navigation buttons.

---

## ✍️ Author

- **Koushika T** – Data Analyat
- **Bhagyasri** - Data Analyst

---

## 📬 Contact

For any queries or collaboration, feel free to connect via GitHub .

---

## 📘 License

This project is for educational and portfolio purposes only. Dataset used for demonstration was publicly available or anonymized.

