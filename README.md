# AspireNex
#Task 1: 
This task involves building a machine learning model to detect spam messages from SMS data. The notebook follows these key steps:

Data Loading and Preparation:

The dataset is loaded from a CSV file.
Unnecessary columns are dropped, and the remaining columns are renamed for clarity.
A new feature, message length, is added to the dataset for exploratory data analysis.
Exploratory Data Analysis:

Descriptive statistics and visualizations are used to understand the distribution of message lengths for spam and non-spam messages.
The dataset is summarized and visualized using histograms.
Data Preprocessing:

The target labels are encoded into numerical format.
The data is split into training and testing sets.
Feature Extraction:

Text data is converted into numerical features using CountVectorizer.
Model Training and Evaluation:

Several classifiers are defined and trained, including:
Support Vector Machine (SVM)
Multinomial Naive Bayes
Gaussian Naive Bayes
Logistic Regression
Random Forest
AdaBoost
Functions are provided for training models and making predictions.
Each classifier is evaluated using the accuracy score on the test set.

#Task2:
This task involves building a machine learning model to detect fraudulent credit card transactions. The notebook follows these key steps:

Data Loading and Preparation:

The dataset is loaded from a CSV file.
Basic data exploration is performed, including checking for null values and summarizing the dataset.
The dataset is divided into fraud and non-fraud cases for comparative analysis.
Exploratory Data Analysis (EDA):

Histograms of various features are plotted to understand their distributions.
Scatter plots are used to visualize the relationship between transaction time and amount for both fraud and genuine transactions.
A correlation heatmap is generated to identify the relationships between different features.
Model Training and Evaluation:

Random Forest Classifier:
The dataset is split into training and testing sets.
A Random Forest model is trained on the training data and evaluated on the test data.
The accuracy of the model is calculated.
Logistic Regression:
Similarly, a Logistic Regression model is trained and evaluated, with accuracy reported.
Decision Tree Model:
A Decision Tree model is also trained, though specific results are not displayed in the preview.



