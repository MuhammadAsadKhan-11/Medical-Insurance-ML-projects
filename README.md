Medical Insurance Cost Prediction using ML (Linear Regression & KNN)
This project predicts individual medical insurance costs using machine learning algorithms — Linear Regression and K-Nearest Neighbors (KNN). It is designed to explore how different features such as age, BMI, smoking status, and more influence insurance charges and how accurately they can be predicted using regression techniques.

🎯 Objective
To build, train, and compare machine learning models that can predict medical insurance charges based on user demographic and health-related data.

📊 Dataset
The project uses the Medical Cost Personal Dataset, which includes the following attributes:

age: Age of the individual

sex: Gender

bmi: Body mass index

children: Number of dependents

smoker: Smoking status (yes/no)

region: Geographic location

charges: Medical insurance cost (target variable)

⚙️ Workflow
Data Preprocessing

Load and explore dataset

Encode categorical features (e.g., sex, smoker, region)

Normalize/scale features (for KNN)

Exploratory Data Analysis (EDA)

Visualizations to identify patterns and relationships

Correlation matrix and pair plots

Model Building

Apply Linear Regression to capture linear trends

Use K-Nearest Neighbors Regressor (KNN) to capture non-linear patterns

Tune K-value for optimal KNN performance

Model Evaluation

Evaluate both models using:

R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Compare model results for accuracy and interpretability

🧰 Tools & Libraries
Python

NumPy & Pandas

Scikit-learn

Matplotlib & Seaborn

📁 Files Included
insurance.csv – Dataset

medical_insurance_prediction.ipynb – Main notebook

README.md – Project description

