🧠 Stroke Prediction System

A machine learning project that predicts the likelihood of a person having a stroke based on health, lifestyle, and demographic factors.
This project demonstrates how data preprocessing, feature engineering, and ML models can be applied to solve healthcare-related problems.

📌 Features

Takes patient health data as input (age, gender, hypertension, BMI, smoking status, etc.).

Encodes categorical variables and scales numerical features.

Predicts whether a person is at risk of stroke using a trained machine learning model.

Supports dynamic user input (comma-separated values).

📊 Dataset


Columns:

id, gender, age, hypertension, heart_disease, ever_married, work_type, Residence_type, avg_glucose_level, bmi, smoking_status

Target variable: stroke (0 = No stroke, 1 = Stroke)

⚙️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

🛠️ Steps Involved

Data Preprocessing

Handled missing values in BMI.

Encoded categorical variables using OneHotEncoding.

Standardized numerical columns with StandardScaler.

Model Training

Trained by Logistic Regression model

Selected the best-performing model for deployment.

Evaluation

Used accuracy, precision, recall, F1-score, and confusion matrix.

Prediction System

Accepts user input dynamically.

Converts raw input → encoded + scaled → prediction.

Returns result:

"Stroke not predicted"

"Stroke predicted"
