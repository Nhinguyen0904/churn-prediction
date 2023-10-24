# churn-prediction
## Objective
The purpose of this code and analysis is to identify and predict customer churn for a telecom company. Churn refers to customers discontinuing their services with a company. Understanding and predicting customer churn is vital for businesses as it can help them take proactive measures to retain customers and reduce revenue loss. In this analysis, we will import the necessary libraries, perform data checking, exploratory data analysis, and build and evaluate machine learning models to predict churn.

## Methodologies
### 2. Descriptive Analysis and Exploratory Data Analysis
- Conduct descriptive analysis to understand the basic statistics of the dataset, including mean, standard deviation, minimum, and maximum values.
- Explore the distribution of categorical and continuous variables.
- Visualize the distribution of each variable using histograms and correlation heatmaps.
- Examine relationships between churn and other variables, such as contract renewal, data plan, customer service calls, data usage, monthly charge, and overage fees.
### 3. Train-Test Split data
Split the dataset into training and testing sets to train and evaluate machine learning models.
Standardize feature values using StandardScaler to ensure that features are on the same scale.
### 4. Building and Evaluating Models
- Support Vector Machine (SVM) Model
Build an SVM model on the imbalanced dataset.
Build SVM models using SMOTE and ADASYN to balance the training data.
Evaluate the models' performance using metrics like accuracy, recall, and precision.
- Decision Tree Model
Build a decision tree model on the imbalanced dataset.
Build decision tree models using SMOTE and ADASYN to balance the training data.
Visualize decision trees for both imbalanced and balanced data.
- Logistic Regression Model
Build a logistic regression model on the imbalanced dataset.
Build logistic regression models using SMOTE and ADASYN to balance the training data.
Evaluate the models' performance using metrics like accuracy, recall, and precision.
### 5. Model Evaluation
Evaluate the models by comparing confusion matrices, ROC curves, and AUC scores and focus on recall as it measures the ability to predict true positives (churn cases).
### 6. Hyperparameter Optimization for the best performing model, Logistic Regression (SMOTE)
- Implement hyperparameter tuning for the chosen Logistic Regression model with SMOTE using grid search with cross-validation to find the hyperparameter combination that maximizes the recall score.
The analysis concludes with a Logistic Regression model (SMOTE) that has been fine-tuned with optimized hyperparameters, leading to improved performance in predicting churners.
