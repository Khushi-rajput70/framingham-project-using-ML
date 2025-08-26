Framingham Heart Disease Prediction - Machine Learning Project

📌 Overview

This project uses the Framingham Heart Study dataset to predict the 10-year risk of developing coronary heart disease (CHD) using machine learning models.
The dataset contains demographic, behavioral, and medical risk factors such as age, sex, cholesterol levels, blood pressure, BMI, smoking habits, and diabetes status.

The goal is to analyze risk factors and build predictive models that can assist in early detection and prevention of cardiovascular disease.

⚙ Features

Data preprocessing and cleaning (handling null values, encoding categorical variables, etc.)

Exploratory Data Analysis (EDA) with visualizations

Feature engineering for improved prediction

Implementation of multiple ML models (Logistic Regression, Decision Tree, Random Forest, etc.)

Model evaluation using accuracy, precision, recall, F1-score, and ROC-AUC


📂 Dataset

The dataset comes from the Framingham Heart Study and includes the following features:

Age

Sex

Education

Current Smoker

Cigs Per Day

BPMeds (blood pressure meds)

Prevalent Stroke

Prevalent Hypertension

Diabetes

Total Cholesterol

Systolic & Diastolic Blood Pressure

diaBP

Body Mass Index (BMI)

Heart Rate

Glucose

TenYearCHD (Target: 1 = Yes, 0 = No)


🛠 Technologies Used

Python 🐍

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Data visualization

Scikit-learn – Machine learning models

Jupyter Notebook

Clone the repository:

git clone https://github.com/Khushi-rajput70/framingham-project-using-ML.git


2. Navigate to the project folder:

cd framingham-project-using-ML


3. Install required dependencies:

pip install -r requirements.txt


4. Open Jupyter Notebook:

jupyter notebook



📊 Results

The best performing model(Logistic Regression) achieved an accuracy of 85%(update after training).

Risk of CHD is highly influenced by age, smoking habits, blood pressure, cholesterol, and diabetes.


📜 License

This project is licensed under the MIT License – see the LICENSE file for details.
