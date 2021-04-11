# Motivation:
This project aims to help the company to predict the potential users who want to cancel their service. So, the company can offer discounts or promotion to avoid user cancellation.
Models were built by using three machine learning algorithms: Logistic Regression, Random Forest and Decision Tree, tuned via cross-validation with grid search of paramGrid for each model and evaluated via F1-score.

# Libraries Used:

- pyspark library version 2.4.3
- numpy library version 1.12.1
- pandas library version 0.23.3
- matplotlib library version 2.1.0

# Files in the repository:

- Mini_sparkify_event_data.json
   A subset of sparkify_event_data which record user information and activities
- Sparkify.ipynb
   This file explore, analysis the sparkify_event_data and build a user cancellation prediction model

# Results Summary and analysis:

![alt text](figure1.png)

![alt text](figure2.png)

By comparing the F1 score, I found logistic regression algorithm had the best performance (F1Score = 0.7229036295369211) than random forest (F1Score = 0.7145896656534955) and decision tree (F1Score = 0.7129959746981025).
The good performance of the logical regression model may be because the accuracy of the original data and the proper feature chosen.

# Medium post： 

https://czeng98.medium.com/sparkify-subscription-cancellation-analysis-d3b9a2a5c8f5

# Github link:  

https://github.com/JennyZ-hub/Capstone1
 
# Acknowledge:
[1] "Accuracy vs. F1-Score", Purva Huilgol, https://medium.com/analytics-vidhya/accuracy-vs-f1-score-6258237beca2
