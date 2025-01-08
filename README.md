# Employee-Salary-Prediction
Salary Prediction Using Machine Learning
Overview
This project explores the development and evaluation of machine learning algorithms to predict employee salaries in an organization, using the Dangote Group, Nigeria, as a case study. The study aims to support data-driven decisions in human resource management by creating accurate and reliable salary prediction models.

**Dataset**
The dataset consists of 1,742 observations with 19 features, including:

Demographic Information: Gender, Age, Education Level, etc.
Performance Metrics: Performance Score, Projects Handled, Training Hours, etc.
Organizational Data: Job Title, Department, Years at Company, etc.
Target Variable: Monthly Salary
Objectives
- Develop and apply machine learning algorithms to forecast employee salaries based on historical data.
-  Assess the predictive accuracy of different machine learning modelsIdentify key variables influencing employee salaries.
- Build a web application to allow real-time salary predictions.

**Implemented Models**
The following machine learning algorithms were implemented and evaluated:

- Decision Tree Regression (DTR)
- Elastic Net Regression (ENR)
- K-Nearest Neighbors (KNN) Regression
- Linear Regression (OLS)
- Random Forest Regression (RFR)
- Support Vector Machine (SVM) Regression
- Gradient Boosting Regression (GBR)

**Key Findings**
Best Models for Deployment: Random Forest Regression (RFR), Decision Tree Regression (DTR), and Gradient Boosting Regression (GBR) were the most accurate but require careful tuning to avoid overfitting.
Alternative Model: Support Vector Machine (SVM) also showed competitive performance.
Less Suitable Models: Elastic Net Regression (ENR) and Linear Regression (OLS) performed poorly on this dataset.

**Web Application**
A web-based interface was developed to enable organizations to estimate employee salaries easily and efficiently. The app uses the trained machine learning models and provides predictions in real time.

**How to Run the Project**
Requirements
Python 3.8 or later
Required Libraries: pandas, numpy, sklearn, matplotlib, seaborn, streamlit
Steps
Clone this repository:
jupyter notebook Salary_Prediction.ipynb  
Launch the web application:
python app.py  

**Conclusion**
This project demonstrates the potential of machine learning for improving salary prediction accuracy and supporting fair and transparent compensation systems. Future work will focus on further optimizing the models and expanding their application to other domains.

**Acknowledgments**
This research was conducted using data provided by the Dangote Group, Nigeria.
