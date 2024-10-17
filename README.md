Dataset Overview:

Source: UCI Machine Learning Repository - Heart Disease Dataset

Purpose: The primary goal is to predict the presence or absence of heart disease in a patient, based on a set of medical attributes.

Original Data: The dataset was originally collected by the Cleveland Clinic Foundation.

Key Characteristics of Cleveland Data:

Total Instances: 303 rows

Total Attributes: 14 columns (13 features and 1 target variable)

Missing Values: Some instances contain missing data, represented by ?.

Attribute Information:

The dataset contains 13 medical attributes (or features) and 1 target variable that indicates the presence of heart disease.

age: Age of the patient in years.

sex: Gender of the patient (1 = Male, 0 = Female).

cp (chest pain type): 1= Typical angina. 2= Atypical angina. 3= Non-anginal pain. 4= Asymptomatic.

trestbps: Resting blood pressure (in mm Hg) on admission to the hospital.

chol: Serum cholesterol level (in mg/dL).

fbs (fasting blood sugar):Whether the fasting blood sugar is greater than 120 mg/dL (1 = True, 0 = False).

restecg (resting electrocardiographic results): 0= Normal. 1= Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV). 2=Showing probable or definite left ventricular hypertrophy by Estes' criteria.

thalach: Maximum heart rate achieved during exercise.

exang: Exercise-induced angina (1 = Yes, 0 = No).

oldpeak: ST depression induced by exercise relative to rest (numeric value measured in mm).

slope:The slope of the peak exercise ST segment: 1= Upsloping. 2= Flat. 3= Downsloping.

ca: Number of major vessels (0-3) colored by fluoroscopy (higher values indicate more blocked vessels).

thal: A blood disorder called thalassemia: 3 = Normal. 6 = Fixed defect. 7 = Reversible defect.

num (target variable): Diagnosis of heart disease (angiographic disease status). Originally a categorical variable ranging from 0 to 4. 0= No heart disease. 1, 2, 3, 4= Different levels of heart disease severity. In this study, this is simplified into a binary classification (0 = No heart disease, 1 = Presence of heart disease).
