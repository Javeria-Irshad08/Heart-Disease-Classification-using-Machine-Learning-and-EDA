# Heart-Disease-Classification-using-Machine-Learning-and-EDA
**Introduction**
This project aims to develop a model that predicts whether a patient has heart disease based on various features. We utilize multiple machine learning algorithms, including Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Naive Bayes, Decision Tree, and Random Forest, to determine the most effective method. The dataset used is publicly available and consists of patient data, including age, sex, chest pain type, resting blood pressure, serum cholesterol, and more.

**Data Overview**
The dataset contains the following features:

age: Age of the patient in years
sex: Gender (1 = male; 0 = female)
cp: Chest pain type
trestbps: Resting blood pressure (in mm Hg)
chol: Serum cholesterol in mg/dl
fbs: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
restecg: Resting electrocardiographic results
thalach: Maximum heart rate achieved
exang: Exercise-induced angina (1 = yes; 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: Slope of the peak exercise ST segment
ca: Number of major vessels (0-3) colored by flourosopy
thal: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
target: Diagnosis of heart disease (1 = yes, 0 = no)
**Data Exploration**
Exploratory Data Analysis (EDA) revealed:

The dataset is relatively balanced with 54.46% of patients having heart disease and 45.54% not having heart disease.
There are more male patients (68.32%) than female patients (31.68%).
Various visualizations, such as bar plots and scatter plots, were used to understand the distribution and relationships of features concerning the target variable.
Data Preprocessing
Categorical variables cp, thal, and slope were transformed into dummy variables. The dataset was then normalized to prepare it for model training.

**Model Training and Evaluation**
Six different machine learning algorithms were applied to the dataset:

Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Naive Bayes
Decision Tree
Random Forest
Each model was trained using 80% of the data and tested on the remaining 20%. Accuracy scores were calculated for each model:

**Logistic Regression: 86.89%
KNN: 88.52%
SVM: 86.89%
Naive Bayes: 86.89%
Decision Tree: 80.33%
Random Forest: 88.52%**
The best-performing models were KNN and Random Forest, both achieving an accuracy of **88.52%.**


The project demonstrated the effectiveness of various machine learning algorithms in predicting heart disease, with KNN and Random Forest providing the highest accuracy. Further improvements can be made by fine-tuning the models, using cross-validation, and exploring more advanced techniques.







