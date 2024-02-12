# Marketing Campaign Analysis and Prediction
### Project for course - B565 Data Mining

### Abstract
Prediction plays a crucial role in business, especially in marketing campaigns. This project aims to enhance the impact of marketing campaigns by using predictive modeling techniques to assess the probability of a new user becoming a customer. By leveraging exploratory data analysis (EDA) and training a binary classification model, the project aims to provide valuable insights and predictions for the success of the next marketing campaign.

### 1. Introduction

On average, companies invest a significant percentage of their revenue in marketing campaigns. Targeted marketing is employed to identify potential future customers and optimize returns on this investment. This project focuses on analyzing historical marketing campaign data through data analysis and training a binary classification model. The goal is to predict whether a new customer will respond positively or negatively to the next product based on responses gathered from previous marketing campaigns.

### 2. Problem Statement

The primary objective is to classify whether a new customer will respond positively or negatively to the next product based on their responses in previous marketing campaigns. The analysis involves exploring both data visualization techniques and classification models using various attributes such as demographics, contact history, and campaign results.

### 3. Methodology

The project follows a comprehensive methodology that includes data validation, exploratory data analysis (EDA), more data analysis, data pre-processing, and modeling. The classification models used encompass logistic regression, random forest, AdaBoost, and decision tree. Various pre-processing steps, including normalization, encoding, and oversampling, are applied to enhance model performance.

### 4. Data Validation

The data validation phase involves checking for missing values, handling null values, and classifying attributes into numeric or categorical. The dataset contains attributes such as target, duration, age, gender, job, marital status, education, and credit failure.

### 5. Univariate Analysis

Univariate analysis explores the distributions of attributes, and outliers are removed using the Inter Quantile Range (IQR) method. Insights gained include the distribution of age, account balance, and contact frequency, among others.

### 6. Bivariate Analysis

Bivariate analysis delves into the relationships between two variables, offering insights into age groups, success rates during specific months, and the correlation between different attributes and the target variable.

### 7. Correlation Analysis

Correlation analysis reveals the relationships between attributes, with duration having the highest positive correlation with the target variable. Chi-squared tests are employed for correlation between categorical variables and the target.

### 8. Modeling - Classification

Classification models, including Logistic Regression, Random Forest, AdaBoost, and Decision Tree, are trained on various combinations of datasets (balanced, imbalanced, with and without outliers). Performance metrics such as accuracy, F1-score, and ROC-AUC scores are compared across different models and datasets.

### 9. Conclusion and Future Scope

The project concludes with the identification of effective classification models for predicting customer responses in marketing campaigns. Future scope includes the need for more diverse and relevant data sources to build a more generalized model that can be applied across different product categories.

Feel free to explore the detailed analysis and findings in the [project report](https://github.com/rushanksheta/Marketing-Campaign-Analysis-and-Prediction/blob/main/Final%20Report.docx.pdf) and code files.
