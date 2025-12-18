Bank customer churn analysis
End-to-end customer churn analysis using SQL and Tableau

 Project Overview
This project analyzes customer churn for a retail bank using SQL and Tableau.
The goal is to identify patterns and risk factors associated with customer attrition
and provide actionable business recommendations.

Tools Used
- SQL (SQLite)
- Tableau Public

Dataset
The dataset contains 10,000 bank customers with demographic, financial,
and behavioral attributes such as credit score, balance, number of products,
and churn status.

Key Business Questions
- What is the overall customer churn rate?
- Which customer segments show the highest churn?
- How do engagement and financial behavior affect churn?

Key Insights
1. The overall churn rate is approximately 20%, indicating that one in five customers leaves the bank.
2. Customers with very low credit scores (300–399) exhibit extremely high churn (100%), although this segment represents a small sample size.
3. Customers holding only one product have significantly higher churn compared
   to those with two products, suggesting product diversification improves retention.
4. Although customers with three or four products show high churn rates, these segments are relatively small.
  As a result, their churn figures are more sensitive to individual customer behavior.
5. Inactive members are far more likely to churn than active members, highlighting engagement as a key retention driver.
6. Churn is higher among customers with zero or low account balances.
7. Estimated salary shows limited correlation with churn, indicating that behavioral factors are more important than income alone.
8. Churn tends to be higher in the early years of customer tenure and stabilizes as tenure increases.


Recommendations
1.	 Focus retention efforts on the early stages of the customer journey, where churn risk is highest.
2.	Strengthen product cross-selling strategies to move customers beyond a single-product relationship.
3.	Use credit score and balance information to identify high-risk customers and intervene proactively.
4.	Improve customer engagement, as inactive customers are significantly more likely to leave.

Tableau Dashboard
https://public.tableau.com/views/BankCustomerChurnDashboard_17660640628380/BankCustomerChurnDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
