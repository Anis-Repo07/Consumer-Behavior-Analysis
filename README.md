# Consumer-Behavior-Analysis
The project explores the impact of food taste, convenience, pricing, and payment methods on customer satisfaction and purchase behavior, providing actionable insights to optimize DIG’s market strategy.

## Background and Overview
DIG is a locally farm-sourced healthy restaurant chain founded in 2011, offering high-quality, nutritious meals. The University City location, which serves both Drexel and UPenn students, presents an opportunity to analyze student lunch preferences and optimize business strategies.

This study explores Drexel students’ lunch decision-making process using survey data and Choice-Based Conjoint (CBC) experiments. The goal is to uncover which factors influence students' meal choices and provide data-driven recommendations to improve DIG’s market positioning.

## Data Structure Overview
The dataset consists of two primary sources:

Survey Data: Capturing consumer perceptions of food quality, convenience, pricing, and purchase behavior.

Choice-Based Conjoint (CBC) Data: Simulating trade-off decisions to measure the importance of different meal attributes.

### Key Variables:
Consumer Perceptions: Food taste, value for money, wait time, convenience, variety of payment options.

Consumer Behavior: Number of meals purchased, overall experience.

Demographics: Age, gender.

Decision Influencers: Payment methods, price sensitivity, location proximity.

![image](https://github.com/user-attachments/assets/e1a3dc21-92c2-4e20-8afa-45fd227f5200)


## Executive Summary
DIG operates in a highly competitive food service market, where Drexel students make lunch decisions based on multiple factors, including price, convenience, and food quality. This project examines how these factors influence their choices and what DIG can do to enhance its appeal.

Through survey analysis and Choice-Based Conjoint (CBC) experiments, we identify key customer segments and preferences. The findings reveal that while food quality is critical for customer satisfaction, convenience and payment flexibility drive actual purchasing decisions. Price remains a major factor, with students favoring meal options under $15.

Our analysis suggests that DIG can improve its market position by optimizing operational efficiency, reducing wait times, and expanding digital payment options. Implementing a targeted loyalty program and increasing brand visibility on Drexel’s campus can further enhance customer retention and engagement.

## Insights Deep Dive
### Choice-Based Conjoint (CBC) Experiment Findings:
Importance Score Analysis:

Price and Payment Methods were the most influential factors in student decision-making.

Students preferred meal prices up to $15 and favored restaurants that offered multiple payment options.

![image](https://github.com/user-attachments/assets/262509f5-ec9c-43fd-adbf-0b8b4d7e78ed)



Market Segmentation:

Cluster 0: Non-target customers (excluded from further analysis).

Cluster 1 (Price-Sensitive): Students who prioritize affordability over other factors.

Cluster 2 (Payment-Sensitive): Students who value flexible payment methods over price reductions.

![image](https://github.com/user-attachments/assets/01ead37f-8adb-493f-a100-1f8248a7f544)

Price-sensitive students prefer restaurants that offer meals under $15 and will switch if prices exceed this threshold.

Payment-sensitive students prioritize restaurants that accept Dragon Dollars, credit cards, and mobile payments.

Convenience and short wait times are crucial in highly competitive areas like University City.

## Survey-Based Mixed-Regression Analysis:
### Overall Experience Model (Marginal R² = 0.347):
Food taste was the most influential factor in shaping overall experience (coefficient = 0.555, p < 0.001).

Convenience also contributed positively (coefficient = 0.107, p < 0.001).

Longer wait times negatively impacted satisfaction (coefficient = -0.036, p = 0.055), emphasizing the need for faster service.

![image](https://github.com/user-attachments/assets/3316e54b-a573-43c4-92bc-4e525406c203)


### Number of Meals Model (Marginal R² = 0.307):

Convenience was the strongest predictor of purchase frequency (coefficient = 0.654, p < 0.001), meaning students are more likely to return if the buying process is simple and efficient.

Food taste did not significantly impact purchase frequency, suggesting students care more about efficiency when deciding how often to buy meals.

Wait time did not significantly impact the number of meals purchased, indicating that students expect some waiting but do not let it deter repeat purchases.

![image](https://github.com/user-attachments/assets/365cd287-36f0-4c4b-a428-3f8f8b03eb77)


## Recommendations
### For DIG’s Business Strategy:

Enhance Convenience: Reduce wait times by optimizing ordering systems and offering real-time queue tracking in the DIG app.

Leverage Payment Flexibility: Promote digital payments and mobile wallets to cater to payment-sensitive customers.

Increase Brand Visibility: Partner with Drexel-affiliated stores (e.g., Heirloom Grocery) for promotions and food tastings.

Incentivize Repeat Purchases: Introduce an app-based rewards program offering points redeemable for discounts.

## Learnings
### Industry Learnings:
Students prioritize convenience and pricing over food quality when selecting lunch spots.

Payment flexibility is crucial—businesses that offer diverse options retain more customers.

## Future Improvements:
Refine Payment Option Categorization: The CBC experiment results varied due to inconsistencies in how payment options were presented. Future studies should consolidate payment categories to ensure a more realistic and comparable analysis.

Expand Data Collection for Better Segmentation: Increasing the sample size and refining segmentation methods can lead to more targeted insights into different customer behaviors.

Incorporate Real-Time Pricing Adjustments: Consider how dynamic pricing strategies (e.g., off-peak discounts) could influence customer behavior and loyalty.

## Key Takeaways:
Convenience and payment flexibility are as crucial as food quality. While great food contributes to satisfaction, students prioritize easy purchasing experiences when making repeat purchases.

Pricing remains a key decision driver, but strategic payment flexibility can offset price sensitivity. Offering digital and campus-linked payment options ensures stronger customer retention.

DIG should optimize its operational efficiency. Reducing wait times and streamlining ordering can increase meal purchases without major menu changes.

Brand presence and student engagement drive long-term success. Targeted promotions, campus partnerships, and digital marketing can help DIG solidify its position among Drexel students.

