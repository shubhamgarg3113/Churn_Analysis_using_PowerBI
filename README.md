# 📊 Customer Churn Analysis Dashboard (Power BI)

This project is a **Power BI dashboard** focused on analyzing customer churn behavior. It provides rich visual insights to help stakeholders understand why customers leave and what patterns contribute to churn.

## 🎯 Objective

To provide a data-driven overview of customer churn trends, identify high-risk segments, and empower decision-makers with actionable insights.

---

## 📁 File

* **Name**: `Churn_analysis.pbix`
* **Tool**: Microsoft Power BI
* **Type**: Interactive BI Dashboard

---

## 📌 Key Features of the Dashboard

### 1. **KPI Cards**

* Total Customers
* Churned Customers
* Churn Rate (%)
* Monthly Revenue Loss

### 2. **Churn Breakdown**

* Churn by Gender
* Churn by Senior Citizens
* Churn by Tenure
* Churn by Contract Type

### 3. **Customer Demographics**

* Age distribution
* Subscription services (Phone, Internet, Streaming)
* Payment methods

### 4. **Trend Analysis**

* Monthly churn rate over time
* New vs. Churned customers trend

### 5. **Interactive Filters**

* Segment by gender, contract type, or services used
* Drill-down capabilities by time period or customer groups

---

## 📊 Visualizations Used

* Bar and stacked column charts
* Pie and donut charts
* Line charts for churn trends
* Slicers for dynamic filtering
* Custom KPIs

---

## 🔍 Data Source

Typically used CSV or Excel-based telecom datasets with fields such as:

* `CustomerID`, `Gender`, `Tenure`, `Contract`, `Churn`
* `MonthlyCharges`, `TotalCharges`, `SeniorCitizen`
* Services like `OnlineBackup`, `StreamingTV`, `TechSupport`, etc.

---

## 📌 Insights Provided

* Customers with **month-to-month** contracts are more likely to churn.
* **Senior citizens** tend to have higher churn rates.
* Lower tenure correlates with higher churn.
* Certain services (e.g., lack of tech support or online security) influence churn.

---

## 🧠 Potential Extensions

* Integration with real-time datasets.
* Predictive modeling using Python or R within Power BI.
* Export alerts for high-risk churn customers.

---

## 💻 Requirements

* Microsoft Power BI Desktop (free from Microsoft Store)
* Optional: Power BI Service for publishing and sharing reports
