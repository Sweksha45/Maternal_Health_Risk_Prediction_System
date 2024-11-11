# Maternal_Health_Risk_Prediction_System

This project aims to develop a robust machine learning model to predict the health risk level of pregnant women based on vital health parameters. By leveraging the power of Random Forest, a versatile ensemble learning algorithm, I aim to accurately classify women into different risk categories.
<br>
<br>

Data and Preprocessing
<br>
<br>
The dataset used for this project contains vital health parameters of pregnant women, including:<br>
Age: Age of the patient<br>
SystolicBP: Systolic blood pressure<br>
DiastolicBP: Diastolic blood pressure<br>
BloodSugar: Blood sugar level<br>
BodyTemp: Body temperature<br>
HeartRate: Heart rate<br>
RiskLevel: The target variable indicating the risk level (Low, Medium, High)<br>
Before training the model, the data undergoes rigorous preprocessing to handle missing values, outliers, and feature scaling.
<br>
<br>

Model Selection and Training
<br>
<br>
After exploring various machine learning algorithms, Random Forest was chosen due to its superior performance in terms of accuracy, precision, recall, and F1-score. The model is trained on the preprocessed dataset to learn the complex patterns and relationships between the features and the target variable.
<br>
<br>

Evaluation and Results
<br>
<br>
The trained Random Forest model is evaluated using a combination of metrics:<br>
Accuracy: 0.8374384236453202<br>
Precision: 0.844974898171829<br>
Recall: 0.8398282941396044<br>
F1-score: 0.8407320311062838<br>
The model achieves impressive results, demonstrating its ability to accurately predict maternal health risk levels.
<br>
<br>

GitHub Repository
<br>
<br>
This GitHub repository contains the following:<br>
Colab Notebook: Jupyter Notebook showcasing the data preprocessing, model training, evaluation, and visualization steps.<br>
Dataset: CSV file containing the maternal health dataset obtained from the UCI Machine Learning Repository.<br>
By open-sourcing this project, I aim to contribute to the advancement of maternal healthcare and encourage further research and development in this area.
