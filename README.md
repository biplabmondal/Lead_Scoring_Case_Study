**Predictive Lead Scoring Model for X Education**

**Project Overview**

This project aims to assist X Education, an online course provider for industry professionals, in identifying prospective leads with the highest likelihood of becoming paying customers. By developing a robust lead scoring model, the goal is to assign scores that distinguish high-conversion leads from those with lower conversion potential. The CEO has set an ambitious target of achieving an 80% lead conversion rate, and this project provides data-driven strategies to meet that goal.

**Objectives**

1. Identify High-Value Leads: Use historical lead data to predict the likelihood of conversion and assign scores to prioritize efforts.
2. Optimize Lead Conversion: Develop a data-driven model that accurately predicts conversion probabilities while aligning with the organization's goal of an 80% conversion rate.
3. Actionable Insights: Provide insights into the factors contributing most significantly to lead conversion to support strategic decision-making.

**Approach**

1. Data Preprocessing

* Data Familiarization: Thoroughly inspected the dataset to understand its structure and characteristics.
* Data Cleaning: Addressed missing values, eliminated redundancies, and balanced the dataset for effective modeling.
* Data Transformation: Created dummy variables for categorical attributes and removed irrelevant features.

2. Exploratory Data Analysis (EDA)

* Feature Selection: Utilized Recursive Feature Elimination (RFE) to identify the top 15 influential features. Further refined the selection to 12 key variables with low Variance Inflation Factors (VIFs).
* Correlation Analysis: Generated heatmaps to examine relationships between features and their impact on conversion rates.

3. Model Development

* Built a Logistic Regression model to predict lead conversion probabilities.
* Determined the optimal probability cutoff by analyzing metrics such as accuracy, sensitivity, and specificity.
* Evaluated the model's performance using the Receiver Operating Characteristic (ROC) Curve, achieving an AUC score of 88%.

4. Model Validation and Testing

* Tested the model on unseen data to validate its ability to predict conversions.
* Achieved an accuracy of 80.68%, with sensitivity at 79.55% and specificity at 81.39%.
* Identified 479 high-conversion leads with a predicted conversion probability of 80% or greater.

**Results and Insights**

1.Key Features: The features contributing most significantly to lead conversion include:

    * Welingak Website
    * Reference Source
    * Working Professional
    * Phone Conversation
    * SMS Interaction

2.Conversion Rate: The model achieved the desired conversion rate, providing actionable insights for prioritizing leads.
3.Strategic Value: A high sensitivity ensures that the model effectively identifies promising leads, minimizing the risk of missed opportunities.

**Tools and Techniques**

* Technologies: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.
* Concepts Used:
    * Logistic Regression
    * Recursive Feature Elimination (RFE)
    * Heatmaps for correlation analysis
    * ROC Curve and AUC Score
    * Metrics: Precision, Recall, Sensitivity, Specificity, Accuracy

**Conclusion**

This lead scoring model equips X Education with a powerful tool to optimize lead conversion rates. By identifying the most promising leads and providing actionable insights, the organization can streamline its marketing efforts, improve customer acquisition strategies, and achieve its conversion goals effectively.
