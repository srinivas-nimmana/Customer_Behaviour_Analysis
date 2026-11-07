# 🛍️ Customer Shopping Behavior Analysis

### Turning Customer Transaction Data into Actionable Business Insights

## 📌 Project Overview

This project focuses on analyzing customer shopping behavior to identify purchasing patterns, customer preferences, product performance, and business growth opportunities.

Using Python, SQL, and Power BI, the project transforms raw customer transaction data into meaningful insights that can support data-driven business decisions.

The analysis focuses on understanding customer loyalty, subscription behavior, product categories, discount usage, customer demographics, and purchasing trends.

## 🎯 Business Objectives

- Understand customer purchasing patterns and preferences.
- Identify loyal, returning, and new customer segments.
- Analyze revenue contribution across different customer demographics.
- Evaluate product category and product-level performance.
- Understand the relationship between discounts and purchasing behavior.
- Analyze subscription adoption and identify opportunities to improve customer retention.
- Build an interactive dashboard to communicate business insights.

## 📂 Dataset

The project uses the Customer Shopping Behavior dataset.

**Dataset Overview:**
- Total Records: 3,900
- Total Columns: 18
- Data Type: Customer shopping and transaction data

The dataset includes information related to:

- Customer demographics (Age, Gender, Location)
- Product details (Item Purchased, Category, Size, Color)
- Purchase information (Purchase Amount, Season, Review Rating)
- Shopping behavior (Subscription Status, Discount Applied, Promo Code)
- Purchase frequency and shipping preferences

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data cleaning and exploratory data analysis |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Data visualization |
| MySQL | Database management |
| SQL | Business queries and data analysis |
| Power BI | Interactive dashboard development |
| Jupyter Notebook | Python development environment |
| GitHub | Project documentation and version control |

## ⚙️ Project Workflow

### 1. Data Loading
- Imported the dataset into Python using Pandas.
- Examined dataset structure, dimensions, and data types.
- Identified missing values and duplicate records.

### 2. Data Cleaning & Preprocessing
- Handled missing review ratings using category-wise median imputation.
- Checked and validated data consistency.
- Standardized data formats.
- Created additional analytical features such as age groups and purchase frequency days.
- Removed redundant columns where appropriate.

### 3. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand:

- Customer demographic distribution.
- Purchase amount distribution.
- Product category performance.
- Customer loyalty patterns.
- Subscription behavior.
- Discount usage.
- Product ratings and preferences.

### 4. SQL Analysis

Loaded the cleaned dataset into MySQL and performed business-oriented analysis using:

- SELECT, WHERE and ORDER BY
- GROUP BY and HAVING
- Aggregate functions
- INNER JOIN and LEFT JOIN
- Common Table Expressions (CTEs)
- CASE statements
- Window functions
- Subqueries

**Key Business Questions:**
- Which customer segments contribute the most revenue?
- Which product categories perform best?
- How does subscription status relate to customer spending?
- Which products have the highest discount rates?
- Which products receive the highest customer ratings?
- How can returning customers be converted into loyal customers?

### 5. Power BI Dashboard

Developed an interactive Customer Shopping Behavior Dashboard to present key business metrics and insights.

**Dashboard Highlights:**
- Total Customers
- Average Purchase Amount
- Average Review Rating
- Customer Subscription Distribution
- Revenue by Product Category
- Sales by Product Category
- Revenue by Age Group
- Customer Segmentation
- Interactive filters and slicers

## 📊 Key Findings & Business Insights

The analysis revealed several important findings:

1. **Customer Loyalty:** 3,116 customers were classified as loyal, 701 as returning, and 83 as new customers.

2. **Subscription Opportunity:** Only 27% of customers were subscribers, indicating an opportunity to improve subscription adoption.

3. **Customer Spending:** The average purchase amount was approximately $59.76.

4. **Gender-Based Revenue:** Male customers contributed approximately $158K in revenue, compared with $75.2K from female customers.

5. **Discount Behavior:** 839 customers used discounts while spending above the average purchase amount.

6. **Product Performance:** Gloves, Sandals, Boots, Hat, and Skirt were among the highest-rated products.

7. **Category Performance:** Jewelry, Blouse, Sandals, and Jacket emerged as category leaders in the analysis.

## 💡 Business Recommendations

Based on the analysis:

- Introduce targeted subscription benefits to improve subscription adoption.
- Develop loyalty campaigns for returning customers.
- Focus marketing campaigns on high-performing product categories.
- Use customer ratings to identify products suitable for promotional campaigns.
- Optimize discount strategies by evaluating product-level discount dependence.
- Develop targeted marketing strategies based on customer demographics and purchasing behavior.

## 📁 Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── SQL/
│   └── customer_behavior_sql_queries.sql
│
├── PowerBI/
│   └── Customer_Shopping_Behavior_Dashboard.pbix
│
├── Presentation/
│   └── Customer_Shopping_Behavior_Presentation.pdf
│
├── Dashboard_Screenshots/
│
└── README.md
```

## 🚀 How to Run the Project

### Prerequisites
- Python 3.x
- Jupyter Notebook
- MySQL Server and MySQL Workbench
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### Step 2: Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Run Python Analysis

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook inside the Python folder.

### Step 4: Perform SQL Analysis

- Create a database in MySQL.
- Import the cleaned dataset.
- Execute the SQL queries provided in the SQL folder.

### Step 5: Explore the Power BI Dashboard

Open the `.pbix` file using Power BI Desktop and interact with the dashboard filters and visualizations.

## 🔮 Future Scope

- Develop advanced customer segmentation models.
- Perform customer lifetime value analysis.
- Build predictive sales forecasting models.
- Analyze customer churn and retention patterns.
- Develop automated business intelligence reporting.

## 👨‍💻 Author

  Nimmana Sri Gowrav Srinivas

Data Analytics | SQL | Python | Power BI

GitHub: https://github.com/srinivas-nimmana

---

⭐ If you find this project useful, consider giving the repository a star!
