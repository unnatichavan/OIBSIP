# 🛍️ EDA on Retail Sales Dataset

### Oasis Infobyte – Data Analytics Internship  
**Task 1: Exploratory Data Analysis (EDA)**

---

## 📌 Project Overview

This project involves performing a comprehensive **Exploratory Data Analysis (EDA)** on a retail sales dataset. The goal is to uncover hidden patterns, understand customer behaviour, identify sales trends, and generate **actionable business insights** that can help drive data-driven decision-making.

The analysis covers:
- Data cleaning and preprocessing
- Statistical summary (mean, median, mode, standard deviation)
- Time series analysis (monthly and quarterly trends)
- Customer demographics (age and gender distribution)
- Product category performance
- Correlation analysis
- Actionable business recommendations

---

## 📊 Dataset Information

| Attribute | Details |
|-----------|---------|
| **Source** | Kaggle – Retail Sales Dataset |
| **Rows** | 1,000 |
| **Columns** | 9 |
| **Format** | CSV |

### Column Description

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| Transaction ID | Integer | Unique identifier for each transaction |
| Date | DateTime | Date of purchase (DD-MM-YYYY) |
| Customer ID | String | Unique identifier for each customer |
| Gender | String | Customer gender (Male / Female) |
| Age | Integer | Customer age in years |
| Product Category | String | Category of the product purchased |
| Quantity | Integer | Number of units purchased in the transaction |
| Price per Unit | Integer | Price of one unit of the product |
| Total Amount | Integer | Total transaction value (Quantity × Price per Unit) |

---

## 🔍 Key Analyses Performed

| Analysis | Description |
|----------|-------------|
| Data Cleaning | Handled missing values, converted data types, extracted date features |
| Descriptive Statistics | Computed mean, median, mode, and standard deviation for numerical columns |
| Monthly Sales Trends | Line chart showing sales fluctuations across months |
| Quarterly Sales Trends | Bar chart comparing sales across Q1–Q4 |
| Age Distribution | Histogram showing customer age concentration |
| Gender Breakdown | Pie chart showing male vs female customer ratio |
| Top Product Categories | Bar chart of top-performing categories by sales |
| Revenue by Category | Bar chart of total revenue generated per category |
| Correlation Heatmap | Matrix showing relationships between numerical variables |
| Sales by Age Group | Bar chart showing which age groups contribute most to revenue |

---

## 📈 Key Insights

| Insight | Observation |
|---------|-------------|
| Seasonal Trends | Sales peak in Month 5 (May) and Month 10 (October) |
| Top Categories | Electronics and Clothing are the highest revenue generators |
| Target Demographic | Customers aged 26–35 contribute the highest sales |
| Gender Split | Fairly balanced: 54% Female, 46% Male |
| Revenue Drivers | Price per Unit (0.85) and Quantity (0.37) are most correlated with Total Amount |
| Age vs Spending | Weak negative correlation (-0.06) — age does not significantly influence spending |

---

## 🛠️ Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| Jupyter Notebook | Interactive development environment |
| Google Colab | Cloud-based notebook execution |

---

## 📂 Repository Structure
DataAnalytics-L1-EDARetailSales/
├── OIBSIP_EDA_Retail_Sales.ipynb # Jupyter Notebook with full analysis
├── retail_sales_dataset.csv # Dataset used for analysis
└── README.md # Project documentation (this file)

---

## 📝 Actionable Recommendations

Based on the insights derived from the analysis, the following recommendations are proposed:

| # | Recommendation |
|---|----------------|
| 1 | Focus Marketing on High-Performing Categories – Allocate 40% of budget to Electronics and Clothing |
| 2 | Target the 26–35 Age Group – Create loyalty programs and personalized offers for this demographic |
| 3 | Prepare Inventory for Seasonal Peaks – Increase stock for top categories before Month 5 and Month 10 |
| 4 | Balance Gender Marketing – Since the customer base is 54% female and 46% male, use gender-neutral campaigns |
| 5 | Leverage Price-Volume Strategy – Offer bundle deals and bulk discounts to increase quantity per transaction |

---

## 🚀 How to Run This Notebook

1. **Clone this repository**
   ```bash
   git clone https://github.com/unnatichavan/OIBSIP.git
   Navigate to the project folder

bash
cd OIBSIP/DataAnalytics-L1-EDARetailSales
Open the Jupyter Notebook

Using Jupyter Notebook:

bash
jupyter notebook OIBSIP_EDA_Retail_Sales.ipynb
Or upload to Google Colab and run all cells

Run all cells sequentially to reproduce the analysis