# Cardiovascular-Risk-Prediction
**Project Summary**
*   Cardiovascular diseases (CVDs) are the leading cause of death globally.
*   An estimated 17.9 million people died from CVDs in 2019, representing 32% of 
all global deaths. Of these deaths, 85% were due to heart attack and stroke.

*   Most cardiovascular diseases can be prevented by addressing behavioural risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity and harmful use of alcohol.
*   It is important to detect cardiovascular disease as early as possible so that management with counselling and medicines can begin.

Cardiovascular diseases (CVDs) are a group of disorders of the heart and blood vessels. They include:
1. coronary heart disease – a disease of the blood vessels supplying the heart muscle;
2. cerebrovascular disease – a disease of the blood vessels supplying the brain;
3. peripheral arterial disease – a disease of blood vessels supplying the arms and legs;
4. rheumatic heart disease – damage to the heart muscle and heart valves from rheumatic fever, caused by streptococcal bacteria;
5. congenital heart disease – birth defects that affect the normal development and functioning of the heart caused by malformations of the heart structure from birth; and
6. deep vein thrombosis and pulmonary embolism – blood clots in the leg veins, which can dislodge and move to the heart and lungs.

This project is based upon a medical domain dataset, and it has been collected from various patients. It includes entries of over 3000 patients and has 16 different attributes for the prediction of Coronary Heart Diseases in patients for the next 10 years.
In this project we try to predict whether the patient has a 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 3390 records and 17 attributes. Variables Each attribute is a potential risk factor. There are both demographic, behavioural, and medical risk factors

**Problem Statement**
*  Cardiovascular disease(CVDs) are a group of life threatening disease which takes millions of lives worldwide
*  Early diagnosis can help in saving lives as it is said that prevention is better than cure. If our model is able to identify persons, who are at most risk of getting CVD's then it would greatly help doctors to save lives by starting early diagnosis and reduce the chances of death 
*  Our project aims at building ML models to detect high risk persons who are most vunerable towards suffering from CVD's 

**Conclusion**
* We trained 7 machine learning models using the training dataset, and hyperparameter tuning was used in some models to improve the model's performance.
* Missing values were handled, feature engineering and feature selection were carried out, and the training dataset was oversampled using SMOTE to reduce bias on one outcome.
* We chose recall as the model evaluation metric because it was critical that we reduce false negatives.
* Predicting the risk of coronary heart disease is critical for reducing fatalities caused by this illness. We can avert deaths by taking the required medications and precautions if we can foresee the danger of this sickness ahead of time.
* It is critical that the model we develop has a high recall score. It is OK if the model incorrectly identifies a healthy patient as a high risk patient because it will not result in death, but if a high risk patient is incorrectly labelled as healthy, it may result in fatality.
* We were able to create a model with a recall of just 0.81 because of limitated data available and limited computational power availabe.**Logistic Regression** is the model that we have selected for deployment.
* A recall score of 0.81 indicates that out of 100 individuals with the illness, our model will be able to classify only 81 as high risk patients, while the remaining  19 will be misclassified.
* Future developments must include a strategy to improve the model recall score, enabling us to save even more lives from this disease. This includes involving more people in the study, and include people with different medical history, etc build an application with better recall score.
* From our analysis, it is also found that the age of a person was the most important feature in determining the risk of a patient getting infected with CHD, followed by cigs_per_day,pulse pressure and prevalent hypertension
* BMI, prevalent stroke and BP medication were the least important features in determining the risk of CHD.
