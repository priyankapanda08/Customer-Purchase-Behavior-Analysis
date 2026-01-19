# Customer-Purchase-Behavior-Analysis


## 📌 Overview

This project focuses on analyzing customer shopping behavior using transactional retail data. The goal is to uncover meaningful insights related to customer demographics, purchasing patterns, product performance, discounts, and subscriptions to support data-driven business decisions.

The analysis follows an end-to-end data analytics workflow, including data loading, cleaning, exploratory analysis, SQL querying, and dashboard visualization.

---

## 📁 Dataset

* **Total Records:** 3,900
* **Total Features:** 18

### Key Data Fields

* **Customer Information:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
* **Behavioral Attributes:** Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

### Data Quality

* Missing values identified in the **Review Rating** column
* Missing data handled using **median imputation by product category**

---

## 🛠 Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **SQL:** PostgreSQL / MySQL / SQL Server
* **Visualization:** Power BI
* **Reporting:** PowerPoint (Gamma)
* **Environment:** Jupyter Notebook

---

## 🔍 Steps Performed

1. **Data Loading**

   * Imported dataset into Python using Pandas

2. **Data Cleaning**

   * Handled missing values
   * Standardized column names (snake_case)
   * Removed redundant columns

3. **Exploratory Data Analysis (EDA)**

   * Descriptive statistics and data distributions
   * Customer segmentation and purchase trends
   * Feature engineering (age groups, purchase frequency)

4. **SQL Analysis**

   * Loaded cleaned data into a relational database
   * Executed business-focused SQL queries for insights

5. **Dashboard & Reporting**

   * Built interactive Power BI dashboards
   * Created summary report and presentation

---

## 📈 SQL Analysis Highlights

* Revenue comparison by **gender**
* Average spending: **subscribers vs non-subscribers**
* **Top 5 products** by average review rating
* Products with highest **discount dependency**
* Customer segmentation: New, Returning, Loyal
* Revenue contribution by **age group**
* Shipping type vs purchase amount analysis

---

## 📊 Power BI Dashboard

The dashboard provides interactive visual insights on:

* Customer demographics
* Revenue and sales trends
* Product performance
* Discount and subscription impact
* Customer segmentation

Designed for easy interpretation by business stakeholders.

---

## 📌 Results & Insights

* Subscribers generate higher average revenue
* Loyal customers show consistent high spending
* Certain products heavily rely on discounts
* Specific age groups contribute significantly to revenue
* Express shipping users tend to spend more

---

## ▶️ How to Run

1. Clone the repository
2. Open the Jupyter Notebook
3. Install required Python libraries
4. Run the notebook cells sequentially
5. Load the cleaned dataset into SQL database
6. Execute SQL queries
7. Open the Power BI file to view the dashboard

---

## 📄 Deliverables

* Cleaned dataset
* Python EDA notebook
* SQL queries
* Power BI dashboard
* Business report & presentation



