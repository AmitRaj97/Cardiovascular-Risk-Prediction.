# Cardiovascular-Risk-Prediction.

✴ Project Summary
The Cardiovascular Risk Prediction dataset provides valuable information on 3,390 individuals, including demographic, behavioral, and medical risk factors, to predict the 10-year risk of developing coronary heart disease (CHD). In this project, we were tasked with building a machine learning model to accurately predict the risk of CHD development.

Our project started with understanding the data and getting familiar with the predictor and target variables. After that, we gathered and cleaned the data, handled the null values, and typecasted the necessary features to visualize them properly. We performed in-depth exploratory data analysis (EDA) and plotted different types of graphs, separating them into univariate, bivariate, and multivariate categories. As a result, we gained some meaningful insights that helped us make future decisions in the machine learning model pipeline.

To improve the accuracy of the model, we used feature engineering and data preprocessing techniques, extracting new features like pulse_pressure and removed multicollinearity within the independent variables We also applied various transformation such as log transformation techniques to get normally distributed data and scaled the data using the sklearn library StandardScaler. We also employed some techniques to analyze the important features

However, the dataset had an imbalance in the distribution of the target variable, with only 15% of individuals classified as having a high risk of developing CHD. To address this, we used the Synthetic Minority Oversampling Technique (SMOTE) to create a balanced dataset.

We split the data into stratified samples of both classes in train and test sets and implemented several classification models, including Logistic Regression, Random Forest, XGBoost, Naive Bayes, KNN, and SVM. We compared various metrics obtained from classification reports such as Precision, Recall, F1 Score, Accuracy, and AUC-ROC. We also analyzed the number of patients that were correctly or incorrectly classified by our model with the help of the confusion matrix.

Among all the models, Optiaml_XGBoost provided the highest precision, Recall, F1 score, accuracy, and AUC-ROC score, achieving 0.88, 085, 086 and 0.93 respectively, by hyperparameter tuning with the learning rate of 0.1, maximum tree depth of 5, and the total number of 350 trees in the forest. After careful analysis and comparison, we selected Optimal_XGBoost as our final optimal model among all 7 models for deployment.

Overall, this project was challenging, but with the right approach and knowledge, we created a machine learning model that can accurately predict the risk of CHD development in patients. By using a combination of data processing, machine learning techniques, and model evaluation skills, we achieved our goal and created a valuable tool for healthcare professionals to identify high-risk patients and take preventive measures.
