# Heart Disease Classification

This notebook focuses on classifying whether a patient has a heart disease or not. The classification process involves the following steps:

- Load the Data: The heart disease dataset is loaded and explored.

- Exploratory Data Analysis (EDA): Various data exploration techniques are used to gain insights into the dataset.

- Feature Engineering: Feature engineering is performed to transform raw data into meaningful features that can be used to train machine learning models.

- Model Training, Validation, and Prediction: Random Forest Classifier is used as the classification model. The dataset is split into training and testing sets. The model is trained on the training set and evaluated on the testing set. Predictions are made on the testing set.

# Heart Disease Data Dictionary

The dataset contains the following features (independent variables) used to predict the target variable (presence or absence of heart disease):

- age: Age of the patient in years.
- sex: Gender of the patient (1 = male, 0 = female).
- cp: Chest pain type (0: Typical angina, 1: Atypical angina, 2: Non-anginal pain, 3: Asymptomatic).
- trestbps: Resting blood pressure (in mm Hg on admission to the hospital).
- chol: Serum cholestoral in mg/dl.
- fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false).
- restecg: Resting electrocardiographic results (0: Nothing to note, 1: ST-T Wave abnormality, 2: Possible or definite left ventricular hypertrophy).
- thalach: Maximum heart rate achieved.
- exang: Exercise-induced angina (1 = yes, 0 = no).
- oldpeak: ST depression induced by exercise relative to rest.
- slope: The slope of the peak exercise ST segment (0: Upsloping, 1: Flatsloping, 2: Downsloping).
- ca: Number of major vessels (0-3) colored by fluoroscopy.
- thal: Thalium stress result (1, 3: Normal, 6: Fixed defect, 7: Reversible defect).
- target: Presence of heart disease (1 = yes, 0 = no) - the predicted attribute.
- Models

The Random Forest Classifier model is used for heart disease classification.

# Model Evaluation
The model's performance is evaluated using accuracy as the metric. The accuracy score on the training set is calculated, and predictions are made on the testing set. The accuracy score on the testing set is also calculated.

# Readme
The code provided in this notebook performs heart disease classification using a Random Forest Classifier. The data is loaded and explored, and feature engineering techniques are applied. The Random Forest model is trained, validated, and used for predictions. The notebook includes visualizations and explanations of the steps taken.

Keywords: heart disease, classification, random forest, feature engineering, data exploration, model evaluation.
