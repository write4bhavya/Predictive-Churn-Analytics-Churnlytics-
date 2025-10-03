# Predictive-Churn-Analytics-Churnlytics
Descriptive Analysis: Predictive Customer Churn Project

Overall Churn Rate & Revenue Risk

The platform exhibits an overall monthly churn rate of 18%, meaning nearly 1 in 5 customers leave each month.

With an average ARPU of ₹200, customer attrition represents significant ongoing revenue risk.

Modeling and Performance

A logistic regression model was built for churn prediction, achieving an ROC-AUC of 0.99, signaling excellent separation between churners and loyal customers.

Key predictive features include auto-renewal status, login frequency, billing cycle (monthly vs quarterly), subscription tier, content preferences, and primary device.

Top Churn Drivers

Customers without auto-renewal or with infrequent logins/watch frequency are much more likely to churn.

Monthly plans and standard subscriptions are riskier than longer billing cycles and premium tiers.

For example, enabling auto-renew or boosting user engagement can strongly reduce churn, while staying on monthly billing or standard plans increases risk.

Customer Segmentation: Risk & Value

Customers are classified by churn risk and revenue contribution into four strategic groups:

High-Risk, High-Value (critical retention targets): small in size but account for outsized revenue loss if they churn.

High-Risk, Low-Value (transients): often allowed to attrit or targeted with low-cost campaigns.

Low-Risk, High-Value (champions): prime candidates for upsell and nurture.

Low-Risk, Low-Value (base): reached with generic engagement efforts.

Retention Campaign Simulation

By targeting the High-Risk, High-Value group and reducing churn probability by 10 percentage points, the expected monthly revenue preserved is over ₹363, roughly equal to saving one customer-month for a group of 13.

This quantifies the disproportionate ROI of focused retention on high-value at-risk users.

Key Recommendations

Proactive personalized outreach for high-value, high-risk customers

Move monthly plan users to longer-term contracts and offer loyalty incentives

Use predictive scoring to trigger early intervention and automate win-back offers for lower-value segments

Identify top revenue contributors for premiums and special support

This integrated approach ensures StreamNow prioritizes resources where they deliver the greatest impact: retaining the most valuable users susceptible to churn, while cost-effectively engaging broader segments. Data-driven targeting and campaign simulation match best practices in subscription analytics and customer lifetime value maximization.
