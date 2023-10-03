# [Project 1: Customer Profiling Using Cluster Analysis]

This analytics project was imperative for stakeholders of ABC Telecomms to support their revenue drive and marketing effort. They wanted to have a better understanding of their customers, especially with regards to how they use their Internet Data Plans.
The company provided 6 months of customer data for profiling before further analysis.

First step:  I imported and cleaned the data collected in an excel workbook via power query editor in power bi. Unwanted columns, empty cells and redundant data were eliminated. Also, data types for each column were validated to maintain accuracy.

Second step: Normalized the data and established relationships between the fact and dimension tables using the customer number as the unique key.

Third step: Loyalty scores were assigned to each customer based on Data Subscribed and Bonus usage. Using on the customers final score, customers were classified into the following:
- Tier 1 Priority Service – Above 85% 
- Tier 2 Priority Service – Between 75% and 85%
- Tier 3 Priority Service + Incentives – Above 60% and less than 75%
- Tier 4 Priority Marketing + Incentives – Less than or equal to 60% 

In addition, key measures including Total number of customers, Total Assigned score, % Assigned score, Customer Group were created using Dax formulas.

Fourth step: A dynamic dashboard was created showing the 4 customer tiers with the aid of a bar chart, which is a great choice for visualizing data with less than 5 categories. A donut chart was also utilized to show the percentage of customers by city.

  ## ABC Telecomms Dashboard Showing Customer Tiers
![ABC DASHBOARD-1](https://user-images.githubusercontent.com/115559534/199286385-9512d81d-fbbd-4e5c-962e-951b3c7d4957.png)

## INSIGHTS

- **Tier 1 priority service & Tier 2 priority service** are the most valuable customer segments (based on data subscribed and bonus usage). Customers under this category contribute significantly to the company’s revenue. This category makes up 65% of the company’s customers.

- Customers under the **Tier 4 priority marketing + incentives** segment are at-risk and most likely to churn. This category makes up about 23% of the company’s customer base.


## RECOMMENDATIONS

- Premium data packages (e.g., discounted data plans, priority customer support, access to exclusive content) can be offered to customers under **Tier 1 & Tier 2 priority service**.

- Retention strategies should be implemented for customers under the **Tier 4 priority marketing + incentives** segment. A larger part of the marketing resources should be targeted towards customers under this category.

