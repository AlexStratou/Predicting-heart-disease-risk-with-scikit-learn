# Predicting Heart Disease risk using combined UCI data and machine learning
## Basic info
In this jupyter notebook (Predicting Heart Disease risk using combined UCI data and machine learning.ipynb
), we use scikit-learn to train and test classifiers that can decide if a person is at risk of (or has) heart disease, or not, based on patients' results on simple medical tests.
 
 ## Dataset
The data (heart.csv) was collected from https://www.kaggle.com/fedesoriano/heart-failure-prediction. They are the combination of 5 different datasets that had some overlaping classes. For more info click on the link. The labels are:

1. Age: age of the patient [years]
2. Sex: sex of the patient [M: Male, F: Female]
3. ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4. RestingBP: resting blood pressure [mm Hg]
5. Cholesterol: serum cholesterol [mm/dl]
6. FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7. RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
8. MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
9. ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
10. Oldpeak: oldpeak = ST [Numeric value measured in depression]
11. ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
12. HeartDisease: output class [1: heart disease, 0: Normal]

The dataset contains 918 (non-duplicate) observations. Notice that the target label is binary, for simplicity.

## Results
After training and testing, we conclude that many of the trained models are succesful in predicting the correct output label. This are some sample confusion matrices of some models:

![image](https://github.com/user-attachments/assets/7677eec4-c8e9-445d-9187-bab1799ca357)

![image](https://github.com/user-attachments/assets/1a4e3812-eabc-46eb-9ab5-5b69da56425a)




## References
1. fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [Date Retrieved] from https://www.kaggle.com/fedesoriano/heart-failure-prediction.
