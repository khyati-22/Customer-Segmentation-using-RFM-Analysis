# Customer Segmentation using RFM Analysis

## Project Overview

Customer retention and customer value optimization are critical challenges for modern businesses. Understanding customer purchasing behavior enables organizations to design targeted marketing campaigns, improve customer satisfaction, and maximize revenue.

This project applies RFM (Recency, Frequency, Monetary) Analysis to segment customers into meaningful groups based on their purchasing patterns. The analysis helps identify high-value customers, loyal customers, new customers, and customers at risk of churn.

The project demonstrates the practical application of customer analytics, data cleaning, exploratory data analysis, business intelligence, and data visualization using Python.

---

## Business Problem

Businesses often have thousands of customers with varying purchasing behaviors. Treating all customers the same can result in ineffective marketing strategies and reduced customer engagement.

The objective of this project is to:

* Identify the most valuable customers.
* Detect customers who may stop purchasing.
* Recognize newly acquired customers.
* Support data-driven marketing and retention strategies.
* Improve customer relationship management through segmentation.

---

## Project Objectives

The primary objectives of this project are:

* Perform customer segmentation using RFM Analysis.
* Calculate Recency, Frequency, and Monetary metrics for each customer.
* Classify customers into different business segments.
* Visualize customer distribution across segments.
* Generate actionable business recommendations.
* Demonstrate analytical and problem-solving skills using Python.

---

## Dataset Information

The dataset contains transactional retail data including:

| Feature     | Description                   |
| ----------- | ----------------------------- |
| InvoiceNo   | Unique transaction identifier |
| StockCode   | Product identifier            |
| Description | Product description           |
| Quantity    | Number of items purchased     |
| InvoiceDate | Transaction date and time     |
| UnitPrice   | Price per unit                |
| CustomerID  | Unique customer identifier    |
| Country     | Customer country              |

The dataset is used to evaluate customer purchasing behavior and generate segmentation insights.

---

## Methodology

### 1. Data Collection

The retail transaction dataset is imported into Python for analysis.

### 2. Data Cleaning

* Removal of missing customer records
* Removal of cancelled transactions
* Removal of invalid quantities and prices
* Data type corrections

### 3. Feature Engineering

A new revenue metric is created:

Revenue = Quantity × Unit Price

### 4. RFM Analysis

#### Recency (R)

Measures how recently a customer made a purchase.

#### Frequency (F)

Measures how often a customer makes purchases.

#### Monetary (M)

Measures the total amount spent by a customer.

### 5. Customer Segmentation

Customers are grouped into categories such as:

* High Value Customers
* Loyal Customers
* New Customers
* Regular Customers
* At-Risk Customers

### 6. Data Visualization

Charts and visualizations are generated to understand customer distribution and revenue contribution across segments.


### Customer Segment Distribution

![Customer Distribution](images/Customer%20segment%20distribution.png)

### Revenue by Segment

![Revenue by Segment](images/Revenue_by_segment.png)


### 7. Business Recommendations

Insights are translated into practical marketing and customer retention strategies.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

Customer-Segmentation-RFM

├── data/

├── notebook/

│ └── customer_segmentation.ipynb

├── images/

├── README.md

├── requirements.txt

└──.gitignore

---

## Key Insights

The analysis helps businesses:

* Identify high-value customers for loyalty programs.
* Detect customers likely to churn.
* Improve customer retention strategies.
* Personalize marketing campaigns.
* Increase customer lifetime value.

---

## Business Recommendations

### High-Value Customers

* Provide exclusive rewards and loyalty benefits.
* Offer early access to products and promotions.
* Maintain personalized engagement.

### At-Risk Customers

* Launch targeted reactivation campaigns.
* Offer limited-time discounts and incentives.
* Send personalized product recommendations.

### New Customers

* Implement onboarding campaigns.
* Offer welcome discounts.
* Encourage repeat purchases through loyalty programs.

---

## Future Enhancements

Future versions of this project may include:

* Machine Learning-based customer clustering using K-Means.
* Customer Lifetime Value (CLV) prediction.
* Customer Churn Prediction.
* Interactive dashboards using Power BI or Tableau.
* Real-time customer segmentation.

---

## Key Results

* Total Transactions Analyzed: 397,924
* Total Unique Customers: 4,339
* Customer Segments Identified:

  * Loyal Customers: 2,051
  * New Customers: 1,474
  * Regular Customers: 383
  * High Value Customers: 346
  * At Risk Customers: 85

---

### Key Findings

* High Value Customers generated the highest average revenue (£12,318.05).
* Loyal Customers formed the largest customer segment.
* New Customers represented a significant growth opportunity.
* At Risk Customers required targeted retention strategies.
* RFM Analysis successfully identified customer groups for personalized marketing initiatives.

---

## Author

Khyati Kukreja

MBA Candidate | Finance Analytics & Marketing Analytics

Passionate about transforming data into actionable business insights through analytics, visualization, and strategic decision-making.
