# CodeAlpha_task_1
Heart Disease Prediction
Task 1:
The Heart Disease Prediction model utilizes a Random Forest Classifier to predict the presence of heart disease based on various medical and demographic features. The process involves:

1. Data Preprocessing: The dataset is split into training and testing sets. Numerical features are standardized using `StandardScaler` to ensure they are on the same scale.

2. Feature Selection: `SelectKBest` with the `f_classif` function is employed to identify the most significant features contributing to heart disease prediction.

3. Model Training: A Random Forest Classifier is trained on the selected features. Hyperparameters are optimized using `GridSearchCV` to enhance model accuracy.

4. Evaluation: The model's performance is assessed using accuracy, a confusion matrix, and a classification report. These metrics help evaluate the model's ability to correctly classify individuals as having or not having heart disease.

5. Visualization: The results, including feature importance and confusion matrix, are visualized using Matplotlib to gain insights into the model's decision-making process.

This model helps in predicting the likelihood of heart disease, aiding in early diagnosis and potential intervention strategies.


