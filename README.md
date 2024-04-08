### Project Title: Predictive Modeling of Diabetes using Machine Learning Techniques
- Group Members and their course
Po Yu Lai: STAT-627
Ting Yi Chuang: STAT-627
Bright Amenyo:  STAT-627
Ryo Tanaka: STAT-627

Topic: We want to analyze which independent variables lead to the development of diabetes
Questions of Interest: How accurately can we predict blood glucose levels using machine learning techniques based on patient demographics and clinical parameters?
Classification: How effectively can we classify individuals into diabetic and non-diabetic categories using machine learning techniques, leveraging patient data and medical attributes?
Planned Approach: This includes framing the problem, the data, the methods, and the Intended Outcome.
Literature Review: We had a look at Machine Learning Techniques for Diabetes Prediction: A Review by G. Singh et al. (2019), in order to gain a better understanding of techniques employed in diabetes prediction, risk assessment, and management. During the literature review, we found that there is still some room for improvement in terms of development of machine learning models to assist in the early diagnosis of diabetes or prediabetes based on clinical data, biomarkers, and patient characteristics.
Additionally, if there's more sufficient data, we want to utilize machine learning to predict the risk of diabetic complications such as retinopathy, neuropathy, nephropathy, and cardiovascular diseases based on patient data, including demographics, clinical history, and biomarkers.

Data Assessment: 
Diabetes Dataset: Rashid, Ahlam (2020), “Diabetes Dataset”, Mendeley Data, V1, doi: 10.17632/wj9rwkp9c2.1
Number of observations: 1000
Expected number and type of variables: 14; categorical variables:2, numeric variables: 12 
Variables in the datasets: No. of Patient, Sugar Level Blood, Age, Gender, Creatinine ratio(Cr), Body Mass Index (BMI), Urea, Cholesterol (Chol), Fasting lipid profile, including total, LDL, VLDL, Triglycerides(TG) and HDL Cholesterol , HBA1C, Class (the patient's diabetes disease class may be Diabetic, Non-Diabetic, or Predict-Diabetic)
Planned Methods: this includes

- Decision Tree Regression: Decision tree regression recursively splits the data into subsets based on the most significant attribute at each node and predicts the average target value of the instances in each subset. 
- Random Forest Regression:Random forest regression is an ensemble learning technique that combines multiple decision trees to improve prediction accuracy. It can handle complex relationships between features and the target variable and is robust to overfitting.
- Logistic Regression:Logistic regression is a linear classification model that estimates the probability that an instance belongs to a particular class. It's commonly used for binary classification tasks but can be extended to handle multi-class classification as well. We’re using this method to obtain Mean Squared Error.
- KNN Classification: You can use KNN for classification tasks where the class label of a new instance is determined by the majority class among its k nearest neighbors in the feature space. It's a non-parametric method and doesn't make strong assumptions about the underlying data distribution.
- KNN Regression: Alternatively, you can use KNN for regression tasks by averaging the target values of the k nearest neighbors to predict the target value of a new instance.
- Stepwise Regression: Stepwise regression is a variable selection technique that sequentially adds or removes predictors based on their statistical significance or contribution to the model's performance. It can help identify the subset of features that best explain the variation in the target variable.
- Bootstrap Resampling: Bootstrap resampling is a statistical technique for estimating the variability of a statistic by repeatedly sampling data with replacement from the original dataset. It can be used to assess the stability and uncertainty of regression coefficients, prediction errors, or other model parameters.
- Linear Discriminant Analysis (LDA): LDA is a classification technique that models the distribution of the predictor variables separately for each class and then uses Bayes' theorem to calculate the probability of class membership for a new instance. It assumes that the predictor variables are normally distributed and have a common covariance matrix within each class.
- Leave-One-Out Cross-Validation (LOOCV): Jackknife resampling can be implemented using leave-one-out cross-validation (LOOCV), where you train the model on the diabetes data
- Correlation Matrix and Heatmap: Calculate the correlation coefficients between pairs of numerical features in your dataset. Visualize the correlation matrix using a heatmap to identify highly correlated features, which may indicate multicollinearity.
- Variance Inflation Factor (VIF): Compute the VIF for each predictor variable in your regression models. VIF measures the degree of multicollinearity by assessing how much the variance of an estimated regression coefficient is inflated due to collinearity with other predictors. A VIF value greater than 5 or 10 suggests multicollinearity.
- Principal Component Analysis (PCA): Perform PCA to reduce the dimensionality of the dataset and identify linear combinations of features that explain most of the variance. Assess the proportion of variance explained by each principal component and examine loadings to understand which variables contribute to each component.
- Bias and Fairness: We want to be mindful of potential biases in the dataset that could result in unfair or discriminatory outcomes. Take steps to mitigate bias in data collection, preprocessing, and model development to ensure fairness and equity in the predictions and recommendations generated by the machine learning models.
- Transparency and Interpretability: We strive for transparency and interpretability in the machine learning models used in the project. Provide explanations for how the models make predictions or recommendations to facilitate understanding and trust among users, healthcare providers, and patients.
- Risk Assessment and mitigation: Regularly review and update the risk assessment as the project progresses; establish mechanisms for stakeholders to report and address emerging risks or concerns; conduct periodic audits or reviews of project activities to ensure compliance with risk mitigation strategies.
By conducting a thorough risk assessment and implementing effective mitigation strategies, you can minimize potential risks and ensure the successful and responsible execution of your diabetes machine learning project.
