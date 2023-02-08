# Cardiovascular-Risk-Prediction
Capstone Project on Cardiovascular Risk Prediction to predict 10-year risk of coronary heart disease.

Introduction
According to the World Health Organization, every year 12 million deaths occur worldwide due to Heart Disease. The load of cardiovascular disease is rapidly increasing all over the world from the past few years. Many researches have been conducted in an attempt to pinpoint the most influential factors of heart disease as well as accurately predict the overall risk. Heart Disease is even highlighted as a silent killer which leads to the death of the person without obvious symptoms.The early diagnosis of heart disease plays a vital role in making decisions on lifestyle changes in high-risk patients and in turn reducing the complications. This project aims to predict future Heart Disease by analyzing data of patients which classifies whether they have 10 Year risk of Coronary Hear Disease.

Problem Statement
The objective of the project is to come up with the machine learning model to predict whether a patient has 10-year risk of developing coronary heart disease (CHD) using the dataset collected by the residents of the town of Framingham, Massachusetts.

Data Summary
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

Attributes:

Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk factors.

Demographic:

Sex: male or female("M" or "F")
Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous) Behavioral
is_smoking: whether or not the patient is a current smoker ("YES" or "NO")
Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)
Medical( history):

BP Meds: whether or not the patient was on blood pressure medication (Nominal)
Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
Diabetes: whether or not the patient had diabetes (Nominal)
Medical(current):

Tot Chol: total cholesterol level (Continuous)
Sys BP: systolic blood pressure (Continuous)
Dia BP: diastolic blood pressure (Continuous)
BMI: Body Mass Index (Continuous)
Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
Glucose: glucose level (Continuous)
Target Variable:

10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) - DV
ML Classification Models
For modeling we tried various classification algorithms like:

Logistic Regression
Decision Trees
Random Forest
XG boost
Support Vector Machine

Conclusion
Based on our observations, the Support vector machine with the radial kernel is the best performing model in terms of accuracy and the F1 score and it's high AUC-score shows that it has a high true positive rate.

Balancing the dataset by using the SMOTE technique helped in improving the models sensitivity and improving the scores of all the models.
