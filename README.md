# Predictive Modeling for Health-Related Risk Assessment

## Research Topic
Our research focuses on developing predictive models for assessing health-related risks based on an individual's lifestyle, medical history, and demographic factors. Leveraging the Behavioral Risk Factor Surveillance System (BRFSS) dataset with 19 variables, including general health, exercise habits, and disease history, our goal is to predict the likelihood of various health conditions, notably heart disease.

## SMART Questions
1. Can accurate predictive models determine an individual's risk of developing heart disease based on demographic, lifestyle, and medical history factors?
2. How do factors like exercise habits, alcohol consumption, and BMI contribute to the prediction of health conditions?
3. What is the impact of gender, age, and general health status on the risk assessment of various health conditions?

## Data Source
We utilize the [BRFSS dataset](https://www.kaggle.com/datasets/alphiree/cardiovascular-diseases-risk-prediction-dataset/data), a comprehensive nationwide survey collecting health-related information from U.S. residents.

## Modeling Methods
We employ various machine learning and statistical methods, including:
- Logistic Regression
- Random Forest
- Gradient Boosting
- Support Vector Machines
- Naive Bayes

Evaluation metrics include accuracy, precision, recall, and F1-score.

## Expected Outcomes
Our project aims to create predictive models for personalized healthcare, identifying individuals at higher risk of conditions like heart disease. These models can revolutionize healthcare with targeted interventions, early prevention, and improved resource allocation.

## Conclusion

In conclusion, our exploration of various predictive models for heart disease prediction revealed distinct strengths and weaknesses in each approach:

- **Decision Tree:** Demonstrated balanced accuracy but tended to miss negative cases (low NPV).
- **Random Forest:** Achieved high overall accuracy and specificity but struggled in predicting positive cases (low PPV).
- **XGBoost:** Excelled in identifying positive cases but resulted in many false positives (low specificity).
- **Logistic Regression:** Provided a balanced approach with reasonable precision and recall.

The selection of the most suitable model depends on the specific requirements of the heart disease prediction task. If minimizing false negatives is crucial, XGBoost might be preferred despite its high false positive rate. For a more balanced approach, Logistic Regression could be a better choice. If overall accuracy and specificity are the focus, Random Forest may be suitable, even though it faces challenges in detecting positive cases effectively. Decision Tree offers a middle ground in terms of balanced accuracy.

Our modeling approach involved a comprehensive utilization of logistic regression, decision trees, random forests, XGBoost, upsampling techniques, and hyperparameter tuning. The results underscored the importance of a thoughtful and iterative modeling process. While initial models showcased high accuracy, addressing recall limitations through upsampling, feature selection, and hyperparameter tuning revealed a more nuanced understanding of the predictive factors. This nuanced approach enhances the reliability and effectiveness of our heart disease prediction models, providing valuable insights for real-world applications.
