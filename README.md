# Maternal_Health_Risk_Prediction_System

This project aims to develop a robust machine learning model to predict the health risk level of pregnant women based on vital health parameters. By leveraging the power of Random Forest, a versatile ensemble learning algorithm, I aim to accurately classify women into different risk categories.

Data and Preprocessing

The dataset used for this project contains vital health parameters of pregnant women, including:
Age: Age of the patient
SystolicBP: Systolic blood pressure
DiastolicBP: Diastolic blood pressure
BloodSugar: Blood sugar level
BodyTemp: Body temperature
HeartRate: Heart rate
RiskLevel: The target variable indicating the risk level (Low, Medium, High)
Before training the model, the data undergoes rigorous preprocessing to handle missing values, outliers, and feature scaling.

Model Selection and Training

After exploring various machine learning algorithms, Random Forest was chosen due to its superior performance in terms of accuracy, precision, recall, and F1-score. The model is trained on the preprocessed dataset to learn the complex patterns and relationships between the features and the target variable.

Evaluation and Results

The trained Random Forest model is evaluated using a combination of metrics:
Accuracy: 0.8374384236453202
Precision: 0.844974898171829
Recall: 0.8398282941396044
F1-score: 0.8407320311062838
The model achieves impressive results, demonstrating its ability to accurately predict maternal health risk levels.

GitHub Repository

This GitHub repository contains the following:
Colab Notebook: Jupyter Notebook showcasing the data preprocessing, model training, evaluation, and visualization steps.
Dataset: CSV file containing the maternal health dataset obtained fron UCI Machine Learning Repository.
By open-sourcing this project, I aim to contribute to the advancement of maternal healthcare and encourage further research and development in this area.
