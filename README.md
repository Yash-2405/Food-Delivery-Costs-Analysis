## Food-Delivery-Costs-Analysis
![image](https://github.com/user-attachments/assets/f6cfddb4-461e-4312-9cb6-3e9acad4230e)

# Overview

This repository contains an analysis of food delivery costs using a dataset with various details about each order, such as order value, delivery fee, discounts, and more. The analysis aims to provide insights into the cost structure and identify key trends and patterns.

# Contents

Food_delivery_costs_analysis.ipynb: Jupyter Notebook containing the code for data analysis.

Food delivery costs.csv: CSV file containing the raw data for the analysis.

README.md: Overview and documentation of the project.

# Data Description

![image](https://github.com/user-attachments/assets/ff04a1f4-5513-4575-a6b2-114ed6490f0e)


The dataset includes 1000 entries with the following columns:

Order ID: Unique identifier for each order.

Customer ID: Unique identifier for each customer.

Restaurant ID: Unique identifier for each restaurant.

Order Date and Time: Timestamp when the order was placed.

Delivery Date and Time: Timestamp when the order was delivered.

Order Value: Total value of the order.

Delivery Fee: Fee charged for delivering the order.

Payment Method: Method used for payment (Credit Card, Digital Wallet, Cash on Delivery).

Discounts and Offers: Discounts or offers applied to the order.

Commission Fee: Commission fee charged by the platform.

Payment Processing Fee: Fee for processing the payment.

Refunds/Chargebacks: Any refunds or chargebacks associated with the order.

# Analysis Summary

Data Cleaning

Initial data cleaning steps included:

Converting the Order Date and Time column to a datetime format for easier analysis.

# Summary Statistics

Basic statistical summaries of the data:

Order Value: Ranges from 104 to 1995 with a mean of approximately 1200.

Delivery Fee: Ranges from 0 to 50 with a mean of approximately 20.

Commission Fee: Ranges from 50 to 200 with a mean of approximately 120.

Payment Processing Fee: Ranges from 10 to 50 with a mean of approximately 30.

Refunds/Chargebacks: Mostly 0, indicating few refunds or chargebacks.

# Key Insights

Order Value Distribution:
Consistent spending patterns among customers with most orders within a certain range.

Delivery Fees:
Variability in delivery fees, with some orders having no delivery fee due to promotions or high-value orders.

Discounts and Offers:
Various types of discounts and offers applied, impacting the final order value.

Payment Methods:
A mix of payment methods used, with Digital Wallet and Cash on Delivery being popular choices.

# Next Steps

Further analysis steps include:

Detailed Time-Based Analysis:
Analyze trends over time to identify peak order times and potential seasonal effects.

Correlation Analysis:
Examine correlations between different cost components to understand their relationships.

Customer Segmentation:
Segment customers based on their order patterns to tailor marketing strategies.

Discount Effectiveness:
Evaluate the effectiveness of different discounts and offers in driving sales.

# Conclusion

The analysis provides valuable insights into the cost structure and customer behavior in food delivery. Key findings include consistent order values, variability in delivery fees, and diverse usage of payment methods. Further analysis, including time-based trends and customer segmentation, will deepen our understanding and help in making data-driven decisions to enhance business performance.

# Usage

Clone the repository:
```sh
git clone https://github.com/your-username/Food-Delivery-Costs-Analysis.git
```

Navigate to the project directory:
```sh
cd Food-Delivery-Costs-Analysis
```

Open the Jupyter Notebook:
```sh
jupyter notebook Food_delivery_costs_analysis.ipynb
```
