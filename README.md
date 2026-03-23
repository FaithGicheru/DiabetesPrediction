# DiabetesPrediction
BUSINESS UNDERSTANDING

Objective

This project aims to create a machine learning model which detects clinical parameters that are most significant in predicting/detecting diabetes.

Key Questions 

1. Which parameter is the highest predictor of diabetes?

2. Which parameter is the lowest predictor of diabetes?

3. Which 2 parameters combined are likely to result in diabetes?

4. Which parameter is strongly correlated with diabetes outcome?

KEY STAKEHOLDERS

1.Physicians 

Responsible for screening, diagnosing and managing patients.

2.Nutritionists

Responsible for providing dietary advise to patients especially those having obesity

3.Public health professionals

Responsible for creating awareness on non communicable diseases like diabetes.

DATA UNDERSTANDING

The dataset used was obtained from Kaggle.

It contains data of female patients aged atleast 21yrs and of Pima Indian origin.

It contains 768 rows and 9 columns.

The column names of the dataset represent the following:

*Pregnancies: Number of times pregnant

*Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test

*BloodPressure: Diastolic blood pressure (mm Hg)

*SkinThickness: Triceps skin fold thickness (mm)

*Insulin: 2-Hour serum insulin (mu U/ml)

*BMI: Body mass index (weight in kg/(height in m)^2)

*DiabetesPedigreeFunction: Diabetes pedigree function

*Age: Age (years)

*Outcome: Class variable (0- No diabetes or 1-Diabetes)

This machine learning model:

  Has high recall to reduce missed diagnosis of diabetes.
  
  VISUALIZATIONS
  
  1.Rate of Diabetes for Higher-Risk Patients
  
  Patients with high levels of glucose and BMI>25 are at a higher risk of having diabetes as compared to having either 
  
  parameters singly.
  
  2.Level of Glucose by Diabetes Outcome
  
  Glucose levels is a key diagnostic feature for diabetes as most dabetic patients usually have high glucose levels
  
  3.BMI by Diabetes Outcome
  
  Obesity is a  major risk factor for diabetes
  
  4.Rate of Diabetes by Age Category
  
  People aged 40-60 yrs are at a higher risk of developing diabetes
  
  5.Rate of Diabetes by High Glucose Status
  
  Patients with high levels of glucose have high diabetes rates compared to others as observed in the bar chart above.
  
  6.Feature Correlation Matrix
  
  Glucose is strongly correlated with diabetes outcome.
  
  Conclusion
  
Key Findings

 Glucose is strongly correlated with diabetes outcome
 
• Glucose is the strongest predictor of diabetes

• Skin thickness is the least predictor of diabetes.

• BMI and Glucose combined have a high prevalence of diabetes 

outcome

Recommendations

1. Patients aged 40-60 should have their glucose levels checked routinely during hospital visits.
 
• Patients with a high BMI>25 should be put on weight reduction programs to prevent development of diabetes

Repository Structure

notebook/ – Jupyter Notebook containing analysis
https://github.com/FaithGicheru/DiabetesPrediction/blob/main/diabetes.ipynb

data/ – Diabetes dataset

presentation/ – Non-technical presentation slides
https://github.com/FaithGicheru/DiabetesPrediction/blob/main/Presentation3.pdf

dashboard/ – Interactive dashboard



