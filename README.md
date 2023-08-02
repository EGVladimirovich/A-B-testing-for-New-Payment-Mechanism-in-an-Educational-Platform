# Pet project A/B testing for New Payment Mechanism in an Educational Platform
*Introduction

This project focused on conducting A/B testing to evaluate the impact of a new payment mechanism on user behavior and revenue metrics in an educational platform. The goal was to determine whether the new payment mechanism should be launched for all users based on the analysis of key metrics.

**Data Extraction and Preparation**

The first step involved extracting and preparing the necessary data for analysis. Four CSV files were used as input data, containing information about user group assignments, additional user data, user activity, and user payments during the experiment. Python libraries such as Pandas, Matplotlib, Seaborn, and NumPy were utilized for data manipulation and visualization.

**Analyzing Key Metrics**

Several key metrics were calculated to assess the impact of the new payment mechanism. These metrics included:

1. Conversion Rate (CR): The percentage of users who made purchases out of the total users.
2. Average Revenue per User (ARPU): The average revenue generated per user.
3. Average Revenue per Paying User (ARPPU): The average revenue generated per paying user.

**Insights and Findings**

The analysis revealed the following insights and findings:

1. Conversion Rate: The new payment mechanism resulted in a lower conversion rate compared to the existing payment mechanism. This suggested that the new mechanism might not be as effective in converting users into paying customers.
2. Revenue Metrics: Despite the lower conversion rate, the test group (using the new mechanism) exhibited higher revenue metrics (ARPU and ARPPU) than the control group (using the existing mechanism). This indicated that users in the test group, who made purchases, generated more revenue on average.
3. High-Value Payments: The new payment mechanism seemed to encourage high-value payments, which were observed predominantly in the test group. This suggested that the new mechanism might effectively promote specific price points or encourage users to spend more.

**Recommendations and Further Analysis**

Due to the sample size imbalance and the need to consider additional factors, it was not possible to make a definitive decision on whether to implement the new payment mechanism based solely on the analysis. Therefore, the following recommendations were made for further analysis:

1. Consider Sample Size Imbalance: The large difference in the number of users between the control and test groups should be taken into account when interpreting the results. Additional analysis with balanced samples could provide more robust conclusions.
2. User Surveys and Qualitative Feedback: Conduct user surveys and collect qualitative feedback to understand users' perspectives on the new payment mechanism and its impact on their behavior and decisions.
3. External Factors: Consider external factors, such as promotional offers, product availability, or changes in the market, that may have influenced the results.

**Conclusion**

The A/B testing analysis provided valuable insights into the impact of the new payment mechanism on user behavior and revenue metrics. While the test group showed higher revenue metrics, a lower conversion rate and sample size imbalances raised the need for further analysis. The project demonstrated skills in data extraction, cleaning, analysis, and visualization, providing valuable experience in data analytics and A/B testing methodologies.
