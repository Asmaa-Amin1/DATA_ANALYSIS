# 📊 Customer Behavior & Churn Analysis

An exploratory data analysis (EDA) and customer segmentation project using **Python**, **Pandas**, and data visualization tools to analyze customer demographics, spending patterns, and churn behavior.

---

## 📂 1. Dataset Overview
The dataset (`customer_behavior_eda.csv`) contains **532 rows** and **16 features** covering customer profiles and transactional data:
* **`customer_id`**: Unique identifier for each customer.
* **`signup_date`**: The date the customer registered.
* **`region`**: Geographic region/city (e.g., Cairo, Giza, Alexandria, Mansoura).
* **`acquisition_channel`**: Channel through which the customer was acquired (e.g., Web, Mobile App).
* **`segment`**: Customer tier/segment (e.g., Bronze, Silver, Gold).
* **`age`**: Customer age.
* **`annual_income_egp`**: Annual income in Egyptian Pounds (EGP).
* **`monthly_spend_egp`**: Average monthly spend in EGP.
* **`orders_last_6m`**: Number of orders placed in the last 6 months.
* **`avg_order_value_egp`**: Average order value in EGP.
* **`satisfaction_score`**: Customer satisfaction rating (out of 5.0).
* **`support_tickets`**: Number of support tickets raised.
* **`discount_rate`**: Average discount rate applied.
* **`website_visits_last_30d`**: Number of website visits in the last 30 days.
* **`is_active`**: Indicator of whether the customer account is active (Yes/No).
* **`churned`**: Indicator of whether the customer has churned (Yes/No).

---

## 🛠️ 2. Code & Data Cleaning Pipeline
The accompanying Jupyter Notebook (`after_analysis.ipynb`) performs the following data processing and analysis steps:
1. **Data Loading & Inspection**: Loads the CSV file using `pandas`, checking shape, data types, and missing values.
2. **Data Cleaning**: 
   * Handles missing values in columns like `signup_date`, `region`, `annual_income_egp`, and `satisfaction_score`.
   * Standardizes text fields and casts data types correctly (`datetime`, numeric formatting).
3. **Exploratory Data Analysis (EDA)**:
   * Generates descriptive statistics.
   * Analyzes customer segmentation and churn drivers.
4. **Visualizations**: Utilizes `Matplotlib` and `Seaborn` to plot distributions and relationships.

---

## 🛠️ Tech Stack
* **Language**: Python 3.x
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/Asmaa-Amin1/DATA_ANALYSIS.git](https://github.com/Asmaa-Amin1/DATA_ANALYSIS.git)
