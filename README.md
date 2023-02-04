# Heartstroke-Prediction-using-R
This project focuses on predicting the age in which people get health issues and whether a person has had a stroke or not in R.

<h1>OVERVIEW</h1>

In this project i worked on a dataset which contains the information of the patients such as their age, gender, health issues etc. The overall goal of this project was to create predictive models for variables age and stroke by using Multiple Linear Regression and Logistic Linear Regression methods. 
•	Goal1: To predict whether a person has had a heart stroke or not.
•	Goal2: To predict the age in which people get health issues.
Perfomed data cleaning followed by performing EDA, feature selection and fitting/predicting the models in R. 

- Descriptive Statistics of Heartstroke data
![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/hs1_DescriptiveStatisticsofData.png)

-Exploratory Data Analysis 
![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/hs2_EDA.png)
![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/hs3_EDA.png)
![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/hs4_EDA.png)
![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/hs5_EDA.png)
![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/hs6_EDA.png)

-Correlation Matrix of continuous variables

![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/hs7_Correlation.png)

- Multiple Regression Model

![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/Model1_ML.png)

-Logistic Regression Model

![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/hs_model2.png)

- Model Output using stepwise feature selection criteria

![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/hs_Model_Output.png)

-Confusion Matrix

![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/hs_ConfusionMatrix.png)

-The ROC (Receiver Operating Characteristic Curve):

![image](https://github.com/priyankac15/Heartstroke-Prediction-using-R/blob/main/AUC_Curve.png)

<h2> CONCLUSION </h2>
Goal-1: To predict the Age in which people get health issues.
To predict Age, I have cleaned the data followed by doing Exploratory data analysis. Visualized the relationship between our target (Age) and other variables including numerical & categorical. Next, by plotting a scatterplot matrix, checked the numerical variables which are correlated with the target variable. Also, performed the feature selection methods to choose the variable which can improve our model. Built the Multiple Linear Regression model with all the selected predictors with R Squared 0.66 and RSE is 13.14.
Goal-2: To predict whether a person has had a heart Stroke or not
For the above Goal2, the dataset has been cleaned and from the dataset the missing values of the variable BMI have been removed, after conducting Exploratory Data Analysis, the variables have been checked for correlation with the stroke variable. The Logistic Regression model has been built using all the predictor variables which gave an AIC value of 965.45. Further, stepwise feature selection criteria have been used to eliminate insignificant variables and a model has been constructed with all the significant predictor variables which has a lower AIC of 944.33 and the accuracy of the model is 72.2%. Finally, ROC (Receiver Operating Characteristics Curve) has been plotted and the area under the curve is 84.37%.


