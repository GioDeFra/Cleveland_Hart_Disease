# Cleveland_Hart_Disease
The goal of this analysis is to create a linear regression model and a non-linear method that detects if a patient has a heart disease.

The data comes from the UC Irvine Machine Learning Repository.

https://archive.ics.uci.edu/dataset/45/heart+disease

The dataset consists of 14 variables and 303 units related to a heart disease in Cleveland. The goal is to develop a classification model capable of accurately determining whether a patient is affected by the disease.
When the dataset is uploaded, the notebook initially interprets all variables as numeric, which leads to incorrect
data types for some of them. After correcting these data types, we can provide a clear explanation of
each variable to better understand the context and problem at hand. 

Categorical Variables:

• Sex: Indicates the gender of the patient (1 = Male, 0 = Female).

• Cp: Chest pain type, categorized into four levels (values 1 to 4).

• Fbs: Fasting blood sugar status, where 1 indicates levels greater than 120 mg/dl and 0 indicates
normal levels.

• Restecg: Results of the resting electrocardiogram (0 to 2).

• Exang: Indicates whether exercise-induced angina is present (1 = Yes, 0 = No).

• Slope: The slope of the ST segment during exercise (values 1 to 3).

• Thal: Thalassemia diagnosis, with three categories (3.0, 6.0, 7.0).

Integer Variables:

• Age: The patient’s age in years.

• Trestbps: Resting blood pressure measured in mmHg at hospital admission.

• Chol: Serum cholesterol level in mg/dl.

• Thalach: Maximum heart rate achieved during the test.

• Oldpeak: ST depression level induced by exercise relative to rest.
Ciao ciao ciao 
• Ca: Number of major vessels colored during fluoroscopy.

• Num: The target variable, representing the diagnosis of heart disease. It goes from to 0 to 4.
