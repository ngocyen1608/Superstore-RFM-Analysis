# [PYTHON] Superstore RFM Analysis
## I. Introduction
### 1. About RFM Analysis
### What is RFM and why does it matter?
RFM is a customer segmentation approach that leverages three key metrics: Recency, Frequency, and Monetary value.
- Recency: When was the customer's last transaction?
- Frequency: How often does the customer make purchases?
- Monetary: What's the total value of the customer's spending?
This method allows businesses to categorize their customer base according to their buying patterns. By examining how recently and how often customers buy, as well as how much they spend, companies can gain valuable insights into customer behavior.
### Implementing RFM
The process involves assigning scores to customers for each of the three dimensions - Recency, Frequency, and Monetary value. These scores are then combined to create distinct customer segments, each with its own characteristics and potential strategies.

By employing RFM analysis, businesses can tailor their marketing efforts, improve customer retention, and maximize the value of their customer relationships.
### Reference
[RFM analysis (recency, frequency, monetary)](https://www.techtarget.com/searchdatamanagement/definition/RFM-analysis#:~:text=RFM%20analysis%20is%20a%20marketing,and%20perform%20targeted%20marketing%20campaigns.)
### 2. Business Questions
- The Marketing Department needs to classify the segments of each customer to deploy each marketing program suitable for each customer group.
- The Marketing Director also proposed a plan to use the RFM model in Python to segment customers, and then launch marketing campaigns to thank customers for supporting the company over the past time. As well as exploit potential customers to become loyal customers.
- Suggestions to the Marketing and Sales team with the company's retail model, which of the three indicators R, F, and M should be most interested in?
## II. Data Visualization with Python
- **Histogram distribution of each variable**
https://github.com/user-attachments/assets/dd049006-7eb2-4c51-bb00-bb636a7e251d
https://github.com/user-attachments/assets/208314f8-cede-408c-ae7a-3c5f2a825cca
https://github.com/user-attachments/assets/95ee1823-a35b-4e39-b71c-8d6ececde6b3
- **Treemap of RFM Segments of Customer Count**
https://github.com/user-attachments/assets/8e5d0300-79e7-4b33-99a7-b5b9e35d732b
- **Treemap of RFM Segments of Total Sales**
https://github.com/user-attachments/assets/0f351248-cfbe-459d-be98-755cddaceb36
## III. Insights
- **Focus on Champions Customers:**
Insight: The Champions group represents the highest percentage among all groups (19.22%) and contributes the most to revenue (62.92%).
Recommendation: Continue to maintain and develop relationships with this group through special promotion programs, high-quality customer care, and development of new products tailored to their needs.

- **Prioritize the At-Risk Customer Group:**
Insight: The At-Risk group accounts for 9% of customers but contributes 8% of revenue, higher than the Lost Customers group. They have high recency, indicating significant potential.
Recommendation: Create reactivation campaigns focused on this group, providing special offers and personalized experiences to prevent them from becoming Lost Customers

- **Reduce the Rate of Hibernating Customers:**
Insight: The Hibernating group is one of the two groups with the highest proportion, second only to the Champions group.
Recommendation: Analyze the reasons for customer inactivity and implement appropriate reactivation strategies, such as sending notifications about new products or special offers.

- **Reactivate Lost Customers:**
Insight: The Lost Customers group has the third-highest proportion, indicating the need for a re-engagement strategy.
Recommendation: Create win-back campaigns with attractive offers and personalized messages to restore relationships with these customers.

- **Analyze Correlations Between Groups:**
Insight: The Hibernating, Champion, and Lost Customers groups have three completely different indicators, showing clear segmentation and correlation between the indicators.
Recommendation: Use this analysis to optimize approach strategies for each group, focusing on converting customers from less effective groups to higher-value groups.

- **Monitor Changes in Group Proportions:**
Insight: The proportions of groups can change over time and reflect the business's status (e.g., a high proportion of the "Can Not Lose Them" group may indicate a downward trend).
Recommendation: Closely monitor changes in customer group proportions to quickly adjust strategies and identify potential business trends.
