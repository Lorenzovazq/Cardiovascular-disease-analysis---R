# Cardiovascular-disease-analysis---R
Exploring risk factors for cardiovascular diseases in adults

This dataset contains detailed information on the risk factors for cardiovascular disease. It includes information on age, gender, height, weight, blood pressure values, cholesterol levels, glucose levels, smoking habits and alcohol consumption of over 70 thousand individuals. Additionally it outlines if the person is active or not and if he or she has any cardiovascular diseases.

Source: https://www.kaggle.com/datasets/thedevastator/exploring-risk-factors-for-cardiovascular-diseas

In the dataset are:

- Numeric values for age, height, weight, systolic blood pressure (ap_hi) and diastolic blood pressure (ap_lo).
- Binary values for gender, alcohol consumption (alco), smoking habits (smoke), active person (active), cardiovascular diseases (cardio). In the gender variable it's not defined which value correspond to which gender. In the rest of the cases 0 = No and 1 = Yes. 
- Levels in the cholesterol and glucose (gluc) variables. In this cases I will consider that  1 = normal, 2 = above normal, 3 = well above normal. 


The aim of this analysis it's finding correlation between variables and determining which ones contributes to develop cardiovascular diseases.
Also build a predictive model using some variables.


