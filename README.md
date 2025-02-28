# Car-Insurance-Claim-Prediction

# Project Overview
This project focuses on predicting car insurance claims using machine learning algorithms implemented in SAS and visualized using Tableau. The goal is to analyze customer profiles and identify key factors that influence the likelihood of an insurance claim being filed. The project involves data exploration, preprocessing, predictive modeling, and visualization to derive insights and build accurate predictive models.

# Project Structure
The project is structured as follows:

Introduction: Provides an overview of the project, including the problem statement, aim, and objectives.

Data Source: Links to the dataset used for the project.

Dataset Description: Details the variables and data types in the dataset.

Data Visualization: Visualizes key features and patterns in the data using Tableau.

Data Exploration and Preprocessing: Explains the steps taken to clean and preprocess the data.

Predictive Modeling: Describes the machine learning models used (Logistic Regression, Decision Tree, Gradient Boosting) and their implementation in SAS.

Interpretation of Findings and Recommendations: Summarizes the key findings from the analysis and provides recommendations for improving the model.

Summary and Lessons Learned: Reflects on the lessons learned during the project.

Future Extensions: Suggests potential future work to improve the model.

References: Lists the references used in the project.

# Dataset
The dataset used in this project is available on Kaggle:

Dataset Link: Insurance Claim Dataset

The dataset contains 44 variables, including both numerical and categorical features, with the target variable being is_claim (a Boolean indicating whether a claim was filed).

# Key Features
Data Visualization: Tableau was used to visualize key patterns in the data, such as the relationship between car age and claim settlement, fuel type, and policy tenure.

Predictive Modeling: SAS E Miner was used to implement machine learning models, including Logistic Regression, Decision Tree, and Gradient Boosting.

Data Preprocessing: Python and PyCharm were used for data validation and cleansing, including handling missing values and inconsistent data.

# Key Findings
Important Variables: The most important variables influencing the likelihood of a claim were found to be Policy_Tenure, Age_of_car, Area_cluster, and Age_of_policyholder.

Model Performance: Logistic Regression performed the best among the models tested, although the dataset's imbalance (94% no claims vs. 6% claims) posed challenges for model accuracy.

Gradient Boosting: Gradient Boosting improved the model by incorporating additional variables like engine_type.

# Recommendations
Data Correction: The dataset needs to be more balanced to improve model performance.

Advanced Techniques: Future work could explore more advanced techniques like neural networks or other boosting algorithms to enhance model accuracy.

# Lessons Learned
Data Understanding: Understanding the data and the features that influence the outcome is crucial for building accurate predictive models.

Model Evaluation: It is important to evaluate multiple machine learning algorithms to determine the best-performing model.

Data Visualization: Tableau was instrumental in identifying patterns and insights in the data.

# Future Extensions
Improved Data: Future work should focus on obtaining a more balanced dataset to improve model performance.

Advanced Models: Exploring advanced techniques like neural networks or ensemble methods could further enhance the model's accuracy.

Additional Visualizations: Adding more visualizations could help in better understanding the data and identifying new patterns.

# References
McGuire, G., Taylor, G., and Miller, H. (2018). Self-Assembling Insurance Claim Models Using Regularized Regression and Machine Learning. SSRN Electronic Journal. doi:10.2139/ssrn.3241906.

"Sensitivity vs Specificity". Analysis & Separations from Technology Networks. Retrieved 10 December 2021.

Quinlan, R. (1983). Learning efficient classification procedures. Machine Learning: an artificial intelligence approach, Michalski, Carbonell & Mitchell (eds.), Morgan Kaufmann, p. 463--482. doi:10.1007/978-3-662-12405-5_15.

# How to Run the Project
Data Preparation: Download the dataset from the provided Kaggle link and preprocess it using Python or SAS.

Data Visualization: Use Tableau to visualize the data and identify key patterns.

Model Building: Implement the predictive models using SAS E Miner.

Model Evaluation: Evaluate the models based on misclassification rate and average square error.

Interpretation: Interpret the findings and provide recommendations for improving the model.

# Contributors
Revanth Addagalla

Bhanusree Chavvakula

Shruti Patricia Tatapudi

Naveen Kumar Uppara
