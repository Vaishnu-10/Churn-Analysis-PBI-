 Churn Analysis Project Report

 Overview

This report looks at why some customers are leaving (churning) and what we can do to keep them. We have data on 7043 customers and found a few key things that can help reduce the number of customers who leave. The main recommendations are to improve tech support for Fiber Optic users, get more people to sign longer contracts, and encourage more automatic payments.

 Key Findings and Recommendations

 1. Improve Tech Support for Fiber Optic Customers
Finding: Fiber Optic customers are reporting more technical issues.
Explanation: Fiber Optic users have more tech tickets than others, meaning they face more issues with their service.
Recommendation:
- Action: Add more tech support for Fiber Optic customers to reduce their tech tickets to an average of 0.5 per customer.
- Result: Better support will make these customers happier and less likely to leave.

 2. Increase Sales of 1 and 2 Year Contracts
Finding: Most customers (89%) are on month-to-month contracts, which have higher churn rates.
Explanation: Month-to-month customers can leave anytime, so they tend to leave more often.
Recommendation:
- Action: Encourage more customers to sign 1-year and 2-year contracts by increasing sales of these by 5%.
- Result: Longer contracts mean customers stay longer, reducing churn.

 3. Promote Automatic Payment Methods
Finding: Only 25.09% of customers use automatic payments.
Explanation: Many customers are not using automatic payments, which can be easier and more reliable.
Recommendation:
- Action: Increase the number of customers using automatic payments by 5% each year.
- Result: Automatic payments help ensure bills are paid on time, reducing the chances of customers leaving due to payment issues.


Steps Taken, Visuals Used, and DAX Queries

Steps Taken
Data Collection: Gathered data including their demographics, account information, services used, and churn status.
Data Cleaning: Cleaned the data to ensure accuracy, such as handling missing values and correcting inconsistencies.
Data Analysis: Analyzed the data to find key trends and patterns related to customer churn.
Dashboard Creation: Created dashboards in Power BI to visualize the data and make insights easily understandable.

Visuals Used
Pie Charts: For gender distribution, payment methods, and contract types.
Bar Charts: For monthly and total charges, number of tech and admin tickets.
Line Charts: To show churn rates over time and by different services.
Tables: To display detailed customer information and summary statistics.

DAX Queries
Sum of Monthly Charges: SUM('Customer Data'[MonthlyCharges])
Average Monthly Charges: AVERAGE('Customer Data'[MonthlyCharges])
Churn Rate Calculation: CALCULATE(DIVIDE(COUNTROWS(FILTER('Customer Data', 'Customer Data'[Churn] = "Yes")), COUNTROWS('Customer Data')), 0)
Count of Tech Tickets: SUM('Customer Data'[numTechTickets])
Count of Admin Tickets: SUM('Customer Data'[numAdminTickets])
Dax to get the % of billing type,online backup, online security, yes, no, etc.

 Churn Dashboard Summary

 Customer Overview

Total Customers: 7043

Customers at Risk of Leaving: 1869

Total Yearly Charges: $16.06 million

Total Monthly Charges: $2.86 million

Churn Rate: 26.54%

 Customer Demographics

- Gender Distribution: 49.8% male, 50.2% female
- Senior Citizens: 25%
- Partners (those who have a partner): 36%
- Dependents (those who have dependents): 17%

 Subscription Length

- Less than 1 year: 53%
- 1-2 years: 17%
- 2-3 years: 10%
- 3-4 years: 8%
- 4-5 years: 7%
- 5-6 years: 5%

 Payment Methods

- Electronic Check: 57%
- Mailed Check: 16%
- Bank Transfer: 14%
- Credit Card: 12%
- Paperless Billing: 74.91% yes, 25.09% no
- Average Monthly Charges: $74.44
- Average Total Charges: $1513.80

 Contract Types

- Month-to-Month: 89%
- One Year: 9%
- Two Year: 3%

 Services Used

- Phone Service: 91%
  - Multiple Lines: 50.03% yes, 49.97% no
- Streaming TV: 44%
- Streaming Movies: 44%
- Device Protection: 29%
- Online Backup: 28%
- Tech Support: 17%
- Online Security: 16%
- Internet Services:
  - Fiber Optic: 69%
  - DSL: 25%
  - No Internet Service: 6%

 Customer Risk Analysis Dashboard

This dashboard shows the risk of customers leaving based on different factors.

Key Metrics:
- Total Tech Tickets: 2955
- Total Admin Tickets: 3632

 Churn by Internet Service

- Fiber Optic: Higher churn rate
- DSL: Moderate churn rate
- No Internet Service: Lowest churn rate

 Churn by Contract Type

- Month-to-Month: Highest churn rate
- One Year: Lower churn rate
- Two Year: Lowest churn rate

 Churn by Payment Method

- Electronic Check: Higher churn rate
- Bank Transfer and Credit Card: Lower churn rates

 Detailed Recommendations

 A. Enhance Technical Support

Action: 
- Increase resources for the tech support team, especially for Fiber Optic customers.
- Set up proactive monitoring and automated troubleshooting to fix issues before customers notice them.

Result: This will reduce the number of tech tickets and improve customer satisfaction, leading to lower churn rates.

 B. Promote Longer-Term Contracts

Action:
- Offer incentives like discounts or extra features to encourage customers to switch from month-to-month to 1-year or 2-year contracts.
- Launch targeted marketing campaigns to highlight the benefits of longer-term contracts.

Result: This will help lock in customers for a longer period, reducing the churn rate.

 C. Increase Adoption of Automatic Payments

Action:
- Provide incentives such as discounts or rewards for customers who set up automatic payments.
- Make it easier to set up automatic payments through user-friendly processes and customer support.

Result: More customers using automatic payments will lead to fewer missed payments and a lower churn rate.

 Conclusion

This churn analysis project has identified key areas where improvements can significantly reduce the number of customers leaving. By focusing on better technical support, promoting longer contracts, and increasing the use of automatic payments, the company can improve customer retention and satisfaction. Implementing these recommendations will require effort across various teams but will result in long-term benefits.

