---
# Project Title
---
## Early Detection of Diabetes Using Machine Learning
---

## Project Overview
---
The goal of this project is to develop a machine learning model for the early detection of diabetes. 
By analyzing various symptoms and demographic information, the model aims to predict whether a patient is likely to be diagnosed with diabetes. 
This predictive tool could help healthcare providers identify at-risk patients and take preventive measures early on.

## Key Objectives

- Understand the Data: Perform Exploratory Data Analysis (EDA) to uncover insights and trends in the dataset.
- Preprocess the Data: Clean and prepare the data for machine learning tasks.
- Feature Selection and Engineering: Identify key features that contribute most to the prediction of diabetes.
- Model Development: Build, train, and evaluate machine learning models using supervised learning algorithms.
- Model Evaluation: Assess model performance using accuracy, precision, recall, F1-score, and ROC-AUC metrics.
- Insights and Recommendations: Provide actionable insights and recommendations based on the results

## Dataset Source
This dataset is sourced from the UCI Machine Learning Repository and contains clinical features such as age, gender, and various symptoms commonly associated with diabetes.

## Tools
- Python - for data mining, data cleaning, Analysis and visualization

## Exploratory Data Analysis (EDA) Questions
- What is the distribution of the target variable (class)?
![class_distribution](https://github.com/user-attachments/assets/6691fba7-682b-48d6-8d6c-7f7e55e63323)
This illustrates the distribution of diabetes diagnoses, categorizing cases as either Positive or Negative. The Positive class has a significantly higher count, with over 300 cases, compared to the Negative class, which has just over 200 cases. This relatively balanced distribution ensures that the dataset is suitable for training machine learning models without significant bias toward one class, allowing for effective prediction of both Positive and Negative outcomes

- What is the distribution of patients’ ages?
![age_distribution](https://github.com/user-attachments/assets/5268633c-2894-4783-9992-a7742accf7f3)
This represents the age distribution of patients in the dataset. The histogram shows that the majority of patients fall between the ages of 40 and 60, with a peak frequency around the late 40s and early 50s. There are fewer patients below 30 or above 70 years old, and the distribution follows a roughly normal shape with a slight right skew. This suggests that middle-aged individuals are the most represented demographic in the dataset, aligning with common trends where diabetes prevalence increases with age.

- Which symptoms are most commonly reported overall?
![symptom_frequency](https://github.com/user-attachments/assets/d3278cc7-00d5-47a5-a3fb-1a1bd2b563ac)

This displays the frequency of reported symptoms among patients in the dataset. The most commonly reported symptom is weakness, followed closely by polyuria (excessive urination) and itching. Other frequently reported symptoms include delayed healing, polyphagia (excessive hunger), and polydipsia (excessive thirst). Less commonly reported symptoms include alopecia (hair loss), irritability, genital thrush, and obesity. The variation in symptom frequency highlights the prominence of certain symptoms as potential predictors for diabetes

- How do symptoms differ between Positive and Negative diabetes cases?
![symptom_comparison](https://github.com/user-attachments/assets/6c8638ff-30d5-48c2-9ce3-8d03c58095fa)

This chart compares the proportion of reported symptoms between Positive and Negative diabetes cases. Symptoms like polyuria, polydipsia, weakness, and sudden_weight_loss are significantly more prevalent among Positive cases, making them strong indicators of diabetes. On the other hand, symptoms like alopecia, irritability, and obesity show a relatively higher prevalence among Negative cases, although they are less critical for distinguishing between the two classes. This comparison highlights the key symptoms that can be used to predict diabetes effectively

## Feature Selection and Engineering: 
Identify key features that contribute most to the prediction of diabetes.
![feature_importance](https://github.com/user-attachments/assets/f83a9174-87c5-4cbe-ac49-cf7a084b3415)

This chart highlights the importance of various features in predicting diabetes, as determined by a machine learning model. Polyuria (excessive urination) and polydipsia (excessive thirst) are the most influential features, followed by gender and age. Other notable contributors include sudden_weight_loss, partial_paresis, and alopecia. Features like muscle_stiffness and obesity have relatively low importance, indicating a lesser impact on the prediction. This ranking helps identify critical symptoms and demographic factors that can be prioritized for early diabetes detection and model optimization

## Model Development: 
Build, train, and evaluate machine learning models using supervised learning algorithms.
![model_performance_comparison](https://github.com/user-attachments/assets/1d033872-9601-48c6-8d45-0f71fa4da2ab)

This chart compares the performance of three machine learning models—Logistic Regression, Decision Tree, and Random Forest—based on their accuracy and AUC (Area Under the Curve) scores. The Random Forest model demonstrates the highest performance, achieving near-perfect scores in both accuracy and AUC. The Decision Tree model also performs well but slightly below the Random Forest. Logistic Regression has the lowest accuracy and AUC among the three, though it remains a competitive option for simpler use cases. Overall, Random Forest emerges as the most reliable model for diabetes prediction based on this evaluation

## Model Evaluation: 
Assess model performance using accuracy, precision, recall, F1-score, and ROC-AUC metrics.
![model_evaluation_comparison](https://github.com/user-attachments/assets/78e86e35-0c9b-4250-b79e-db4de6f7d281)

The evaluation compares Logistic Regression, Decision Tree, and Random Forest models using metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC. Random Forest performs the best across all metrics, making it the most reliable model for diabetes prediction. Decision Tree also performs well but slightly below Random Forest, while Logistic Regression shows competitive performance but is less effective overall. Random Forest is the top choice for this task.

## Insights and Recommendations: 
Provide actionable insights and recommendations based on the results








