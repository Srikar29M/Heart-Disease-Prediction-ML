# Heart Disease Prediction Project

## Overview
This project aims to predict the presence of heart disease in patients using various features from a dataset. It employs data preprocessing, exploratory data analysis (EDA), and machine learning algorithms for prediction.

## Dataset
The dataset used in this project is `heart.csv`, which contains the following features:

- `age`: Age of the patient
- `sex`: Gender (1 = male; 0 = female)
- `cp`: Chest pain type (0-3)
- `trestbps`: Resting blood pressure (in mm Hg)
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg`: Resting electrocardiographic results (0-2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment (0-2)
- `ca`: Number of major vessels (0-3) colored by fluoroscopy
- `thal`: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversable defect)
- `target`: Presence of heart disease (1 = disease; 0 = no disease)

---

- The heart disease prediction project uses machine learning techniques to identify individuals at risk of heart disease based on health-related factors.
- A comprehensive dataset is utilized, including attributes such as age, gender, blood pressure, cholesterol levels, and other clinical parameters.
- The project analyzes patterns and correlations within the data to understand the factors contributing to heart disease.
- Various machine learning models, such as Logistic Regression, Decision Trees, and Random Forests, are applied to predict the likelihood of heart disease occurrence.
- Data preprocessing and exploratory analysis are conducted to ensure that the models are trained on relevant and clean data.
- The effectiveness of each model is evaluated using metrics like accuracy and F1-score to provide insights into their predictive performance.
- The project aims to assist healthcare professionals in making informed decisions, leading to earlier interventions and better patient outcomes.
- The results highlight the potential of predictive analytics in healthcare, showcasing how technology can enhance medical diagnostics.
- This project contributes to improving patient care and emphasizes the importance of data-driven approaches in healthcare.
- Overall, the heart disease prediction project demonstrates the intersection of technology and healthcare, aiming for a positive impact on patient health.

## Heart Disease Prediction Data Visualization

- **Correlation Matrix:** A heatmap visualizing feature relationships, indicating correlation strength with the target variable (heart disease presence).

- **Target Variable Distribution:** A countplot showing the distribution of patients with and without heart disease to assess class imbalance.

- **Gender Distribution:** A countplot providing insights into the dataset's demographic makeup, exploring potential gender disparities in heart disease.

- **Chest Pain Type vs. Target:** This countplot examines the relationship between chest pain types and heart disease presence, identifying risk correlations.

- **Fasting Blood Sugar vs. Target:** A countplot illustrating how fasting blood sugar levels relate to heart disease outcomes and associated risk factors.

- **Resting ECG Results vs. Target:** A countplot exploring the relationship between resting ECG results and heart disease for diagnostic insights.

- **Exercise-induced Angina vs. Target:** This visualization assesses the impact of exercise-induced angina on heart disease outcomes, revealing possible associations.

- **Age Distribution by Target:** A boxplot highlighting age distributions based on heart disease status, showing age-related patterns and central tendencies.

- **Resting Blood Pressure by Target:** A boxplot presenting resting blood pressure distributions to identify significant differences between patient groups.

- **ST Depression by Target:** This plot highlights differences in ST depression levels, a key indicator in diagnosing heart disease.

- **Feature Correlations with Target:** A focused heatmap on correlations between features and the target variable, identifying significant heart disease predictors.

- **Age Distribution by Target (Histogram):** A histogram detailing age distribution with density estimates for both classes (with and without heart disease).

- **Max Heart Rate Achieved Distribution by Target (Histogram):** This visualization focuses on max heart rate achievements and their correlation with heart disease.

- **Average Age of Patients with and without Heart Disease (Line Plot):** A line plot tracking average age trends for each heart disease category.

- **Gender Distribution by Heart Disease (Stacked Bar Plot):** This visualization illustrates the relationship between gender and heart disease status, uncovering demographic trends.

- **Distribution of Heart Disease (Pie Chart):** A pie chart showing the proportion of patients with and without heart disease for dataset balance representation.

- **Chest Pain Type Distribution (Donut Chart):** A donut chart highlighting the prevalence of different chest pain types among patients.

- **Average Cholesterol Levels by Age Group:** A line plot revealing variations in average cholesterol levels across different age groups.

- **Count of Patients by Chest Pain Type:** A countplot showing patient distribution across different chest pain types for commonness understanding.

- **Count of Patients by Fasting Blood Sugar Status:** This visualization details the count of patients above or below fasting blood sugar thresholds for health risk insights.





## Model Comparison and Evaluation

- A comparison of model accuracies was generated using a DataFrame, showcasing the performance of various algorithms.
- The accuracies of the models were as follows: Logistic Regression (79.51%), Decision Tree (98.54%), Random Forest (100.00%), and Support Vector Machine (88.29%).
- The Random Forest model emerged as the best performer, achieving a perfect accuracy of 100%.
- Based on the best model identified, a detailed classification report was generated for the Random Forest model.
- The classification report provided metrics such as precision, recall, and F1-score for both classes (0 and 1).
- The results indicated that both classes were predicted with perfect precision and recall, demonstrating the model's robustness.
- The macro and weighted averages for precision, recall, and F1-score were all 1.00, further confirming the model's outstanding performance.
- These metrics highlight the effectiveness of the Random Forest algorithm in accurately predicting heart disease outcomes.
- The comprehensive evaluation of model performance aids in understanding the predictive capabilities of different machine learning approaches.
- The results emphasize the importance of model selection in achieving high accuracy in healthcare predictive modeling.

