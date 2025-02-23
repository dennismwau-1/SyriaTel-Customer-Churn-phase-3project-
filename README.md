# SyriaTel-Customer-Churn-phase-3project-
Name: Dennis Mwania
![Image Alt](https://github.com/dennismwau-1/SyriaTel-Customer-Churn-phase-3project-/blob/26fee9251397eefbef6ae08ef923e51b5e63d106/customerchurn.png)
# Overview
In this project, we focus on the analysis of customer churn data from SyriaTel, a leading telecommunications provider. Customer churn refers to the phenomenon of customers discontinuing their services, and understanding the factors behind churn is critical for telecom companies like SyriaTel. By predicting churn, companies can take proactive measures to retain customers, improve customer satisfaction, and optimize resources.

The SyriaTel Customer Churn dataset contains information about the usage, demographic, and service-related details of customers. The main objective of this project is to identify the key factors influencing customer churn and to build a predictive model to forecast the likelihood of customer attrition.
# Business Understanding
SyriaTel, a prominent telecommunications company, seeks to minimize customer churn—the rate at which customers stop doing business with them. High churn rates can be costly, as acquiring new customers is more expensive than retaining existing ones. This project aims to develop a predictive model to identify customers who are at high risk of discontinuing their services (churning) in the near future. By predicting churn, SyriaTel can implement proactive strategies to retain these customers and reduce revenue loss.
# Data Understanding
In this project, we will work with a customer churn dataset from the telecom industry sourced from Kaggle. The dataset contains information about customers, their usage patterns, and whether they have churned or not. The dataset contains 3,333 records and spans 21 columns. 
# Modeling
 The dataset is imbalanced, with only 14.5% of the data being classified as "churn" and 85.5% being classified as "not churn."

My baseline model was LogisticRegression , just to test how my chosen attributes would perform on a basic level. I then  used models like the RandomForest and Decision trees
# Evaluation
AUC (Area Under the Curve) Scores:
Logistic Regression (AUC = 0.83): Performs well but is outperformed by tree-based models. Decision Tree (AUC = 0.86): Better than logistic regression but still not the best. Random Forest (AUC = 0.93): The best-performing model, with the highest AUC, meaning it has the strongest ability to differentiate between classes![image](https://github.com/user-attachments/assets/211861ea-d892-49aa-b86f-3825ba4c761f)
