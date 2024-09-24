




## Project Background
Zenith Bank has observed a significant rise in customer churn, which refers to customers discontinuing their banking services with the institution. The bank needs a robust analysis to identify patterns and predict customer behavior, enabling proactive strategies to reduce churn and improve customer retention. The goal of this project is to analyze the historical customer data to detect the factors influencing customer churn and create a predictive model that helps target at-risk customers.

Insights and recommendations are provided on the following key areas:

1. **Identify High-Risk Customer Segments:**
Analyzed customer demographics, behavior, and financial data to identify segments (age, balance, credit score) most prone to churn.

2. **Determine Key Churn Drivers:**
Uncoverd the primary factors contributing to customer churn, such as inactivity, low credit scores, and specific product usage.

3. **Predict Churn Probability:**
Recommendadtion to develop a predictive model to estimate the likelihood of churn for individual customers, enabling proactive engagement.

4. **Improve Retention Strategies:**
Provided actionable insights for marketing and customer service teams to implement personalized retention strategies for high-risk customers.

5. **Optimize Customer Experience:**
Use churn insights to tailor product offerings, improve service satisfaction, and ensure long-term customer loyalty.






 An interactive PowerBI dashboard used to report and explore  trends can be found here 
 
 
 
 [link].

## Data Structure & Initial Checks
The data consists of a single fact table "Bank Customer Data" with a total row count of 10,000 records.This was divided into 3 dimension tables creating a star schema. Description of each table is as follows:


[photo]





## Executive Summary
#### Overview of Findings:
The customer churn analysis reveals a churn rate of 20.37%, indicating a notable portion of customers are leaving. Inactive customers and those with low credit scores are more likely to churn. The age group 51-60 has the highest churn rate, showing that older middle-aged customers need attention. Customers with balances between 100k-200k are also at higher churn risk, suggesting that balance alone does not guarantee retention. Finally, product usage patterns indicate that customers with fewer products may be more inclined to leave.

Below is the summary page from the PowerBI dashboard.


[link]



## Insights Deep Dive
High-Risk Customer Segments Insights:

**Age Group 51-60:**
This group has the highest churn rate, with approximately 60% of customers churning. Over time, this segment shows increasing churn compared to other age groups, suggesting a possible dissatisfaction or service misalignment with their needs.

**Customers with Credit Scores Below 400:**
Customers in the <400 credit score range have the highest churn rate, nearing 100%, even though they represent a smaller segment of the customer base. This shows a strong correlation between credit risk and churn likelihood, indicating the need for focused credit rehabilitation efforts.

**Balance Group 100k-200k:**
Customers with balances between 100k and 200k have a churn rate exceeding 50%, despite having significant assets. This trend indicates that higher balances do not equate to loyalty, and customers in this range may require more personalized engagement to prevent churn.


[KPI photo]




Key Churn Drivers Insights:

**Inactive Customers:**
Inactive customers make up 48.49% of the total base and exhibit a higher churn rate compared to active customers. Over time, the inactivity trend strongly correlates with customer churn, highlighting engagement as a crucial retention factor.

**Low Credit Score (<400):**
Customers with credit scores below 400 show a near 100% churn rate, making credit risk a key driver. This segment, while small, consistently contributes to churn, emphasizing the need for credit management support.

**Age Group 51-60:**
With over 60% churn, the 51-60 age group is a critical driver. This segment has seen a steady rise in churn over time, indicating dissatisfaction that could stem from unmet service needs or expectations.

[PHOTO]





Churn Probability Insights:

1. The churn probability for age group 51-60 exceeds 60%, making them the most at-risk over time. Given their steady increase in churn, future predictions should focus on addressing their specific needs to reduce this trend.
2. Customers with balances in the 100k-200k range have a churn probability of over 50%, indicating that high balances don’t ensure loyalty. Predictive models can prioritize this group for targeted retention efforts to avoid significant losses.

3. Inactive customers, representing 48.49% of the base, show a high likelihood of churn, with future predictions indicating continued disengagement if no proactive actions are taken. A targeted reactivation strategy could significantly lower this risk.


[CHARTS PHOTO ]

Improve Retention Strategies:
1. **Re-engage Inactive Customers:**
With 48.49% of customers classified as inactive, focusing retention efforts here is crucial. Immediate outreach and personalized reactivation campaigns could significantly reduce churn in this segment.

2. **Target Customers in Age Group 51-60:**
This age group has a 60% churn rate, and efforts over the next 6 months should focus on tailored financial products and improved communication. Addressing their needs could reverse the increasing churn trend in this demographic.

3. **Focus on Customers with Low Credit Scores (<400):**
Customers with <400 credit scores have a near 100% churn rate, so implementing financial coaching and credit-building programs within the next quarter can improve retention. This intervention could stabilize this high-risk segment.
## Recommendations:
Based on the insights and findings above, I would recommend to consider the following:

1. Offer exclusive wealth management and financial advisory services to enhance value for these high-balance customers for customers with balances between 100k and 200k.
2.  Launch a re-engagement campaign with incentives like rate discounts or bonus loyalty points to reactivate customer accounts.
3.  Develop age-specific programs, for the Customers aged 51-60 such as retirement planning or healthcare financing options, to cater to this group's unique needs.


