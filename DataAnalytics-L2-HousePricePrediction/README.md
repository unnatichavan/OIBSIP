# Level 2- Task 1: Predicting House Prices with Linear Regression – Oasis Infobyte Internship

## 📌 Project Overview
This project involves building a **Linear Regression model** to predict house prices based on key features such as square footage, grade, number of bathrooms, and view. The goal is to develop end-to-end skills from data cleaning through model interpretation.

The dataset used is the **King County House Sales dataset**, which contains over 21,000 records of house sales in the King County area, USA.

---

## 📊 Dataset Information

| Attribute | Details |
|-----------|---------|
| **Source** | Kaggle – King County House Sales |
| **Rows** | 21,613 |
| **Columns** | 21 |
| **Target Variable** | `price` |

### Key Features Used

| Feature | Description |
|---------|-------------|
| `sqft_living` | Square footage of the living area |
| `grade` | Overall grade of the house (1–13) |
| `sqft_above` | Square footage above basement |
| `sqft_living15` | Average living area of nearest 15 neighbors |
| `bathrooms` | Number of bathrooms |
| `view` | View rating (0–4) |

---

## 🔍 Key Steps Performed

1. **Data Loading & Inspection** – Loaded dataset, checked shape, null values, and data types.
2. **Exploratory Data Analysis** – Visualized target variable distribution and analyzed correlations.
3. **Feature Selection** – Selected top 6 features most correlated with `price`.
4. **Train/Test Split** – Split data into 80% training and 20% testing sets.
5. **Model Training** – Trained a Linear Regression model using scikit-learn.
6. **Model Evaluation** – Evaluated using R² Score and RMSE.
7. **Residual Analysis** – Checked assumptions of linear regression.
8. **Coefficient Analysis** – Identified which features most influence price.
9. **Regularization** – Compared Linear Regression with Ridge and Lasso.

---

## 📈 Model Performance

| Metric | Value |
|--------|-------|
| **R² Score** | 0.579 |
| **RMSE** | 252,244 |

- The model explains approximately **58%** of the variance in house prices.
- On average, predictions are off by about **$252,000**.

---

## 📊 Visualizations

- **Distribution of House Prices** – Shows right-skewed distribution.
- **Correlation Heatmap** – Highlights features most correlated with price.
- **Actual vs Predicted Scatter Plot** – Shows model performance.
- **Residual Plot** – Checks linear regression assumptions.

---

## 🛠️ Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| **Python** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical data visualization |
| **Scikit-Learn** | Machine learning (Linear Regression, Ridge, Lasso) |
| **Jupyter Notebook** | Interactive development environment |

---

## 📂 Repository Structure
DataAnalytics-L2-HousePricePrediction/
├── DataAnalytics-L2-HousePricePrediction.ipynb # Jupyter Notebook
├── kc_house_data.csv # Dataset
└── README.md # Project documentation

text

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/unnatichavan/OIBSIP.git

2. Navigate to the project folder:

bash
cd OIBSIP/DataAnalytics-L2-HousePricePrediction

3. Open the notebook:

bash
jupyter notebook DataAnalytics-L2-HousePricePrediction.ipynb

4. Run all cells sequentially.


📄 License
This project is submitted as part of the Oasis Infobyte Data Analytics Internship program. All rights reserved.

Oasis Infobyte – Data Analytics Internship
Level 2 – Task 1: Predicting House Prices with Linear Regression
📍 Completed by Unnati Chavan