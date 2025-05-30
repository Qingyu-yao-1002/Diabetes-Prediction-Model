#Diabetes prediction model project

##Project Overview
This project aims to develop a diabetes prediction model based on machine learning, and use the patient's clinical data (such as blood sugar value, BMI index, blood pressure, etc.) to predict whether the patient has diabetes. This model can serve as a medical aid tool to assist doctors in early screening and intervention.

##Problem statement
Diabetes is a common chronic disease, which has a serious impact on the health and quality of life of patients. Early diagnosis and intervention can effectively control the progression of the disease and reduce the risk of complications. Therefore, it is of great clinical significance to develop an accurate and reliable diabetes prediction model.

##Data source
This project uses the Pima Indians Diabetes Dataset, which contains 768 samples, and each sample contains 8 characteristics and 1 target variable (whether or not suffering from diabetes). Features include:
-Pregnancy frequency
-Blood sugar level
-Blood pressure
-Skin thickness
-Insulin levels
-BMI index
-Diabetes genetic function
-Age

##Key findings
1. Blood glucose value, BMI index and diabetes genetic function are the most important factors to predict diabetes.
The accuracy of the model on the test set reached about 80%, indicating that the model has good predictive ability.
3. From the confusion matrix, the model still has room for improvement in identifying diabetes patients (positive).

##Model performance
We compared two machine learning models: logistic regression and support vector machine (SVM). In the end, the support vector machine model performed slightly better than the logistic regression model, with an accuracy of about 80%.

|                       Model                    |           Accuracy         |         AUC Value        |
|----------------------------------|----------------------|----------------------|
|          Logistic Regression           | Approximately 78% | Approximately 0.84|
|Support Vector Machine (SVM) | Approximately 80% | Approximately 0.86|

##Output result
1. Data information and warnings: During the data loading phase, the basic information, row count, and column count of the dataset will be output, and corresponding warning or exception information will be given based on the data size.
2. Missing value statistics: During the data preprocessing stage, missing value statistics for each column will be output.
3. Feature correlation: in the data visualization and analysis phase, the correlation between features and diabetes will be printed.
4. Model evaluation metrics: During the model training and evaluation phase, the optimal parameters, accuracy, confusion matrix, and classification report of each model will be output.
5. Visual Charts: Generate multiple visual charts, including feature correlation heatmap (correlation_ceatmap. png), feature distribution and boxplot (feature-distribution. png), target variable distribution (target-distribution. png), ROC curve (roc_curve. png), precision recall curve (precision_decall_curve. png), and feature importance map (feature_iImportance. png).
6. Feature importance analysis: For logistic regression models, the feature importance analysis results will be output and a feature importance map will be drawn.
7. Model Explanation and Business Suggestions: In the final stage, the name and accuracy of the best model will be output, and the model explanation and business suggestions will be saved to the insights_and_decommendations. txt file.

##Potential improvement
1. Collect more sample data, especially data of diabetes patients, to improve model performance.
2. Consider using ensemble learning methods (such as random forests, gradient boosting trees) or deep learning to further improve prediction accuracy.
3. Develop a simple application so that doctors can input patient data and obtain diabetes risk prediction.

##Conclusion
The diabetes prediction model developed in this project has good prediction performance and can be used as a medical auxiliary tool to help doctors conduct early screening. By further optimizing the model and collecting more data, the performance of the model is expected to be further improved.
    