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



# Heart Disease Prediction Data Visualization

Data visualization plays a crucial role in understanding the dataset, identifying patterns, and presenting insights clearly. Below are explanations of the various visualizations used in the analysis of heart disease prediction data.

## 1. Correlation Matrix
**Heatmap**: A correlation matrix visualizes the relationship between features. The heatmap displays correlation coefficients, helping identify which features are strongly correlated with each other and with the target variable (heart disease presence). The color intensity indicates the strength of the correlation.

## 2. Target Variable Distribution
**Countplot**: This plot shows the distribution of the target variable, indicating the balance between patients with heart disease and those without. Understanding this distribution helps assess class imbalance, which can influence model training.

## 3. Gender Distribution
**Countplot**: Visualizing gender distribution provides insights into the demographic makeup of the dataset, allowing exploration of potential gender disparities in heart disease.

## 4. Chest Pain Type vs. Target
**Countplot**: This visualization examines the relationship between chest pain type and the presence of heart disease, helping to understand if certain types of chest pain correlate with higher risks.

## 5. Fasting Blood Sugar vs. Target
**Countplot**: This plot shows how fasting blood sugar levels relate to heart disease outcomes, helping identify potential risk factors associated with high blood sugar levels.

## 6. Resting ECG Results vs. Target
**Countplot**: Similar to previous plots, this one explores the relationship between resting ECG results and heart disease, providing valuable diagnostic insights.

## 7. Exercise-induced Angina vs. Target
**Countplot**: This visualization assesses the impact of exercise-induced angina on heart disease outcomes, revealing possible associations.

## 8. Age Distribution by Target
**Boxplot**: This plot shows the distribution of patient ages based on their heart disease status, highlighting age-related patterns and the central tendency within each group.

## 9. Resting Blood Pressure by Target
**Boxplot**: This visualization presents resting blood pressure distributions, helping to identify any significant differences between patients with and without heart disease.

## 10. ST Depression by Target
**Boxplot**: This plot highlights differences in ST depression levels, which can be a key indicator in diagnosing heart disease.

## 11. Feature Correlations with Target
**Heatmap**: Another heatmap focused solely on the correlation of features with the target variable. It aids in identifying the most significant predictors of heart disease.

## 12. Age Distribution by Target (Histogram)
**Histogram**: This plot provides a detailed view of age distribution, with density estimates (KDE) for both classes (with and without heart disease).

## 13. Max Heart Rate Achieved Distribution by Target (Histogram)
**Histogram**: Similar to the age histogram, this visualization focuses on max heart rate achievements, offering insights into how it correlates with heart disease.

## 14. Average Age of Patients with and without Heart Disease (Line Plot)
**Line Plot**: This plot tracks the average age for each heart disease category, indicating trends in age among affected and unaffected individuals.

## 15. Gender Distribution by Heart Disease (Stacked Bar Plot)
**Stacked Bar Plot**: This visualization illustrates how gender and heart disease status are related, helping to uncover potential demographic trends.

## 16. Distribution of Heart Disease (Pie Chart)
**Pie Chart**: This chart provides a quick view of the proportion of patients with and without heart disease, offering a clear representation of the dataset's balance.

## 17. Chest Pain Type Distribution (Donut Chart)
**Donut Chart**: Similar to the pie chart, this visualization highlights the prevalence of different chest pain types among patients.

## 18. Average Cholesterol Levels by Age Group
**Line Plot**: This plot reveals how average cholesterol levels vary across different age groups, which can be essential for identifying risk factors related to age.

## 19. Count of Patients by Chest Pain Type
**Countplot**: This plot shows the distribution of patients across different chest pain types, aiding in understanding the commonness of each type.

## 20. Count of Patients by Fasting Blood Sugar Status
**Countplot**: This visualization details how many patients have fasting blood sugar levels above or below the threshold, giving insights into potential health risks.


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

