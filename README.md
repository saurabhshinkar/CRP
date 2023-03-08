# Cardiovascular Risk prediction

## Abstract
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts.
The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes. Variables Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.
 We will analyze each feature and understand the different factors in the data which affect our target variable. We will apply different machine learning algorithms for classification to our data which will help to understand which model fits the best and then from that model we can estimate the target variable. 
ommute on arrival. According to our problem our main aim is to build a predictive model so as to find the number of bikes rented based on the given dataset.

## Problem Statement 
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham,Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD).

### Data Description:
#### Demographic:
- Sex: male or female ("M" or "F")
- Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous) Behavioral
- is smoking: whether or not the patient is a current smoker ("YES" or "NO")
- Cigs Per Day: the number of cigarettes that the person smoked on average in one day. (Can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

#### Medical(history):
• BP Meds: whether or not the patient was on blood pressure medication (Nominal)
• Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
• Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
• Diabetes: whether or not the patient had diabetes (Nominal)

#### Medical(current):
• Tot Chol: total cholesterol level (Continuous)
• Sys BP: systolic blood pressure (Continuous)
• Día BP: diastolic blood pressure (Continuous)
• BMI: Body Mass Index (Continuous)
• Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of a large number of possible values.)
• Glucose: glucose level (Continuous)









## Conclusion's
1. Logistic Model Has Accuracy Of 74%

2. Logistic with Hyperparameter Tuning Has Accuracy Of 74%

3. Decision Tree Has Accuracy Of 81%

4. Decision Tree with Hyperparameter Tuning Has Accuracy Of 81%

5. Random Forest Has Accuracy Of 91%

6. Random Forest with Hyperparameter Tuning Has Accuracy Of 92%

7. XG Boost Has Accuracy Of 86%

8. XG Boost with Hyperparameter Tuning Has Accuracy Of 91%

9. KNN Has Accuracy Of 84%

10. KNN with Hyperparameter Tuning Has Accuracy Of 84%

11. Naive Bayes Has Accuracy Of 62%

12. Naive Bayes with Hyperparameter Tuning Has Accuracy Of 62%

13. SVM Has Accuracy Of 77%
14. SVM with Hyperparameter Tuning Has Accuracy Of 85%
15. From Above We Can Conclude That Random Forest With Hyperparameter Tuning And XG Boost With Hyperparameter Tuning Is The Best Fitted Model To Our Data.

16. Random Forest With Hyperparameter Tuning has highest precision,recall and f1 score among all models.

17. According to Random Forest Model SysBP, Age And education are the most important features which affects our Target variable.


## References
1. GeekforGeeks
2. Kaggle
3. Analytics Vidya
