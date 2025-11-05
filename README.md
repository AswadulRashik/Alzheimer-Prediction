# Alzheimer-Prediction using ML 
# Introduction 
Alzheimer’s disease is a progressive neurodegenerative disorder that affects memory, thinking ability, and behavior. Early prediction of Alzheimer’s is crucial, as timely diagnosis can help individuals seek medical intervention and adopt treatment strategies that may slow disease progression. Machine learning offers the capability to identify subtle patterns in patient health data that may not be easily detectable by traditional diagnostic methods.

In this project, we aim to build a predictive system that classifies whether a patient is likely to have Alzheimer's disease based on lifestyle, medical history, and cognitive assessments. The objective is to evaluate several machine learning models and identify the approach that produces the most reliable predictive performance.

# Dataset Description
Dataset Source: [Alzheimer's Disease Dataset](https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset) (Kaggle)

The dataset contains 2149 patient records and includes variables spanning demographics, lifestyle habits, cognitive symptoms, and medical conditions. The dataset consists of 35 features consists of Patient ID, Demographic Details, Lifestyle Factors, Medical History, Clinical Measurements, Cognitive and Functional Assessments, Symptoms, Diagnosis Information and some Confidential Information. 

# Data Preprocessing

Removing Irrelevant Features

PatientID and DoctorInCharge were dropped as they do not convey predictive information.

Handling Data Types & Missing Values

The dataset does not contain missing values, so no imputation was required.

Encoding Categorical Variables

Several features such as Gender, Ethnicity, and Medical Conditions were already in numerical form. Therefore, no encoding step was necessary.

Feature Scaling

Numerical features like Age, BMI, SleepQuality, etc., were standardized to improve model convergence and stability.

Train-Test Split

Data was split into 70% training and 30% testing to evaluate model generalization performance.
