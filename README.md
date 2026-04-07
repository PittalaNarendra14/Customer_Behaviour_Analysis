# 🛍️ Customer Shopping Behavior Analysis

## 📌 Overview
This project focuses on analyzing customer shopping behavior using transactional data. The goal is to extract meaningful insights related to customer preferences, spending patterns, and business performance to support data-driven decision-making.

The project follows a complete data analytics workflow including data cleaning, exploratory data analysis (EDA), SQL-based querying, and dashboard visualization.

---

## 📊 Dataset
- Total Records: ~3,900 transactions  
- Features include:
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Item, Category, Amount, Season, Size, Color)
  - Shopping behavior (Discount Applied, Frequency, Review Rating, Shipping Type)

---

## 🛠️ Tools & Technologies
- **Python (Jupyter Notebook)** – Data cleaning & EDA  
- **SQL (PostgreSQL / MySQL / SQL Server)** – Data analysis  
- **Power BI** – Interactive dashboard  
- **Excel** – Dataset storage  
- **Gamma (PPT)** – Presentation creation  

---

## 🔄 Project Workflow

### 1. Data Loading & Cleaning (Python)
- Imported dataset using pandas  
- Handled missing values (Review Ratings)  
- Renamed columns for consistency  
- Performed feature engineering (age groups, purchase frequency)

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions and trends  
- Identified patterns in customer behavior  
- Checked relationships between variables  

### 3. SQL Analysis
Performed business-focused queries such as:
- Revenue by gender  
- Top-rated products  
- Customer segmentation (New, Returning, Loyal)  
- Discount impact on purchases  
- Subscription behavior analysis  

### 4. Dashboard Creation (Power BI)
- Built an interactive dashboard  
- Visualized sales, revenue, and customer insights  
- Enabled filtering by category and customer attributes  

### 5. Reporting & Presentation
- Created a detailed project report  
- Designed a presentation using Gamma for storytelling  

---

## 📈 Dashboard

![Dashboard](Dashboard.png)

---

## 🔍 Key Results & Insights
- Clothing category generates the highest sales and revenue  
- Majority of customers are non-subscribers  
- Repeat customers show higher likelihood of subscription  
- Discounts influence purchase behavior but need optimization  
- Certain age groups contribute more to overall revenue  

---

## ▶️ How to Run

### 🔹 Python (Jupyter Notebook)
1. Open the notebook file (`.ipynb`)
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
