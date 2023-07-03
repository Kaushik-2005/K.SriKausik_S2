# K.SriKausik_S2

This task demonstrates the process of loading a dataset, selecting a target column, splitting it into training and testing sets, and using various classifiers to create a machine learning model for predicting the target.

**DataSet :**

 - The given dataset was [heart-disease-prediction](https://www.kaggle.com/datasets/ritwikb3/heart-disease-statlog).
 - This database contains 13 attributes and a target variable. It has 8 nominal values and 5 numeric values. The detailed description of all these features are as follows:
        &emsp;&emsp;&emsp;1)Age: Patients Age in years (Numeric) <br>
        &emsp;&emsp;&emsp;2)Sex: Gender (Male : 1; Female : 0) (Nominal)<br>
        &emsp;&emsp;&emsp;3)cp: Type of chest pain experienced by patient.This term categorized into 4 category.<br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;0: typical angina<br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;1: atypical angina<br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2: non- anginal pain<br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;3: asymptomatic (Nominal)<br>
        &emsp;&emsp;&emsp;4)trestbps: patient's level of blood pressure at resting mode in mm/HG (Numerical)<br>
        &emsp;&emsp;&emsp;5)chol: Serum cholesterol in mg/dl (Numeric)<br>
        &emsp;&emsp;&emsp;6)fbs: Blood sugar levels on fasting > 120 mg/dl represents as 1 in case of true and 0 as false (Nominal)<br>
        &emsp;&emsp;&emsp;7)restecg: Result of electrocardiogram while at rest are represented in 3 distinct values<br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;0: Normal <br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;1: having ST-T wave abnormality  <br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2: showing probable or definite left ventricular hypertrophyby Estes' criteria.<br>
        &emsp;&emsp;&emsp;8)thalach: Maximum heart rate achieved (Numeric)<br>
        &emsp;&emsp;&emsp;9)exang: Angina induced by exercise 0 depicting NO 1 depicting Yes (Nominal)<br>
        &emsp;&emsp;&emsp;10)oldpeak: Exercise induced ST-depression in relative with the state of rest (Numeric)<br>
        &emsp;&emsp;&emsp;11)slope: ST segment measured in terms of slope during peak exercise<br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;0: up sloping <br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;1: flat<br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2: down sloping(Nominal)<br>
        &emsp;&emsp;&emsp;12)ca: The number of major vessels (0–3)(nominal)<br>
        &emsp;&emsp;&emsp;13)thal: A blood disorder called thalassemia<br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;0: NULL <br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;1: normal blood flow <br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2: fixed defect (no blood flow in some part of the heart) <br>
                &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;3: reversible defect (a blood flow is observedbut it is not normal)(nominal)<br>
        &emsp;&emsp;&emsp;14)target: It is the target variable which we have to predict 1 means patient is suffering from heart disease and 0 means patient is normal.<br>
 - Target should be predicted by the model.<br>