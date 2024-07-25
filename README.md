# Navigating Telecom Customer Churn

## Project Overview
This project analyzes customer churn in the telecom industry using data analytics and predictive modeling techniques.

## Business Problem
Customer churn, or attrition, is a major challenge for the telecom industry. It occurs when customers discontinue using a company's services for any reason. This issue extends beyond mere customer loss, significantly impacting revenue, reputation, and market competitiveness.

## Research Questions
- What factors influence customer churn in the telecom industry?
- How effective are different modeling techniques in predicting customer churn?
- What role do customer demographics and usage patterns play in predicting churn?
- Can clustering algorithms effectively segment customers based on churn likelihood?
- Which classification algorithms are most effective in categorizing churners and non-churners?

## Data Analysis Approach
Our analysis utilized a comprehensive dataset from Kaggle, containing historical customer records. The approach involved:
- Exploratory Data Analysis (EDA) to visualize distributions, correlations, and segments.
- Data Preprocessing, including handling missing values and feature engineering.
- Model Selection, training predictive models like logistic regression and random forest.
- Model Evaluation using metrics such as accuracy, AUC-ROC, precision, and recall.
- Feature Importance analysis to identify key drivers of churn.

## Key Findings

### Descriptive Analysis
![Descriptive analysis](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Descriptive%20analysis.png?raw=true)
- Average customer age: 47 years
- Mean tenure: 34 months
- Average monthly download: 21 GB
- Mean monthly charge: $68

### Visualisations
![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Visualisations1.png?raw=true)
- Pie Chart of customer status by gender
- Histogram of tenure in months
- Histogram of age (with normal curve)
- Scatterplot of tenure in months vs total charges

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Visualisations2.png?raw=true)
- Bar chart showing contract vs count of subscribers
- Boxplot of total revenue
- Boxplot of tenure in months
- Scatterplot of churned v total refunds

### Clustering Analysis
K-means clustering revealed distinct customer segments based on value metrics like tenure, charges, and revenue.

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Final%20Cluster%20Centers.png?raw=true)

### Hierarchical Clustering:
![Hierarchical Clustering](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Dendogram%20using%20Average%20Linkage.png?raw=true)

### Classification Analysis
Decision tree and K-Nearest Neighbors models showed promise in predicting churn, with decision trees identifying key predictors like tenure, charges, and usage.

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Model%20Summary%20Decision%20Tree.png?raw=true)

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Classification.png?raw=true)

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Decision%20Tree-%20Training%20Sample.png?raw=true)

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Decision%20Tree-%20Test%20Sample.png?raw=true)

### K-nearest neighbors (KNN) Analysis
![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/KNN-%20Case%20Processing%20Summary.png?raw=true)

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Predictor%20Space.png?raw=true)

### Statistical Modeling
Logistic regression highlighted the significant role of tenure and service type in decreasing churn odds. Each month of tenure corresponded to a 6.3% increase in retention odds.

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Logistic%20Regression%20Analysis.png?raw=true)

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Block%200%20-Beginning%20Block.png?raw=true)

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Block%201-%20Method%20=%20Enter.png?raw=true)

![](https://github.com/NidhiD54/Customer-attrition-prediction-in-Telecom-industry/blob/main/images/Variables%20in%20the%20Equation.png?raw=true)

## Conclusions
- Long-tenured customers and those with specific services (e.g., fiber internet) showed lower churn risk.
- Predictive models demonstrated potential for early identification of at-risk customers.
- Customer segmentation revealed distinct groups with varying churn propensities.
- Targeted retention strategies based on tenure, usage, and service type could effectively mitigate churn.

## Tools Used
- SPSS
- Minitab
- Excel

## Acknowledgements
I would like to express my sincere gratitude to the following who have contributed to the successful completion of this project:

1. Dr. Hannan Amoozad Mahdiraji, my module tutor, for their guidance, expertise, and invaluable feedback throughout the course of this study.
2. The faculty and staff of the MSc Business Analytics program at the University of Birmingham, for providing the knowledge and resources necessary to undertake this research.
3. I would like to acknowledge the use of the Telecom Customer Churn Prediction from Kaggle, which was instrumental in conducting this analysis.

## References
Zhuang, S. (2022) Telecom Customer Churn Prediction. Available at: https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics (Accessed: 24 July 2024).


Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
