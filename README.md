## Wine-Quality-Prediction ##
![71W+3bONurL _AC_UF894,1000_QL80_](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/58245e81-7a90-46cf-ac0f-04454b38efe8)


## Introduction
The objective of this project is to build a model that predicts the quality of wine based on various features such as acidity, pH, alcohol content, etc. The dataset used for this project is the "winequality-red.csv" file.
## Data Exploration
The dataset is loaded into a pandas DataFrame. The first five rows of the dataset are displayed to get a quick overview of the data. The dataset contains 1599 rows and 12 columns.
## Data Description
A statistical summary of the dataset is generated using the **'describe()'** function. This summary provides information such as count, mean, standard deviation, minimum, 25th percentile, median, 75th percentile, and maximum values for each numerical column.
![image](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/a4aeb12f-5399-41a7-b500-3cd3912c08cb)
## Data Analysis
Various visualizations are created to analyze the distribution of different features in the dataset. Histograms, KDE plots, box plots, and pair plots are used to gain insights into the data and identify any potential patterns or correlations.
![image](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/56e94342-d86f-4354-807e-30e204185926)
![image](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/77d74b26-51af-4537-b0b5-ecbfa7355da6)
![image](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/7576dc5c-3844-4f7b-b23a-45596949afc9)
![image](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/b1f88c43-0059-4a00-9abc-ab808b9ed117)
![image](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/1e32222b-ae96-43f8-b540-4ff60dd09874)
![image](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/dcbd3341-7440-45fa-a139-8a9bf7b81867)
![image](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/a81f313b-bb74-42e3-9ae9-83d9ee479da6)
![image](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/c2faa574-7c88-4597-a3ad-fa4a5412ace6)

## Feature Selection
In order to perform wine quality prediction, the target variable "quality" is converted into a binary classification variable "goodquality" where wines with a quality score of 7 or higher are labeled as 1 (good) and the rest as 0 (not good). The feature variables (X) and the target variable (Y) are separated.
## Model Training and Evaluation
Several machine learning models are used to predict wine quality based on the selected features. The models used include Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Classifier (SVC), Decision Tree, Gaussian Naive Bayes, Random Forest, and XGBoost. Each model is trained on the training set and evaluated on the test set using accuracy score as the evaluation metric.
## Results
The accuracy scores of different models are recorded and summarized in a table. The Random Forest model achieved the highest accuracy of 0.893, closely followed by XGBoost with an accuracy of 0.879.
## Conclusion
In conclusion, the Random Forest and XGBoost models are effective for predicting wine quality based on the selected features. Further fine-tuning and optimization of hyperparameters could potentially improve the performance of these models. This project demonstrates the application of machine learning techniques for wine quality prediction, which can be valuable for winemakers and wine enthusiasts in assessing the quality of wines based on measurable characteristics.






https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/5f76d5d4-a1fd-490f-b1a6-738cee270241

## CHEERS!

![fragrance_champagne](https://github.com/Ankitthakur2025/Wine-Quality-Prediction/assets/111188389/2a5f9d06-3f17-443c-9dd5-68efdca7b80b)



