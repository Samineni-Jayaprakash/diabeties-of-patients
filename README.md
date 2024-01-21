# diabeties-of-patients


# Objective:
The primary goal of this project is to analyze a dataset containing information about diabetes patients and build a predictive model to identify whether a person is likely to have diabetes or not. The dataset includes various health-related features such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age.

# Data Exploration:

# Data Importing:
The project starts with importing necessary libraries such as pandas, numpy, matplotlib, and seaborn. The dataset is loaded into a pandas DataFrame for further analysis.

# Data Exploration and Cleaning:
The dataset is explored using methods like info(), describe(), and checks for duplicates and missing values. Fortunately, the dataset contains no missing values or duplicates, making it suitable for analysis.

# Exploratory Data Analysis (EDA):
EDA involves visualizing relationships between different features using pair plots, correlation matrices, and various statistical analyses. Key observations include correlations between certain features and the target variable (Outcome), providing insights into potential predictive features.

# Data Visualization:

Pair Plot: A pair plot is created to visualize the relationships between different features, with distinct markers for diabetic and non-diabetic outcomes.

Correlation Matrix: A heatmap of the correlation matrix is generated to highlight the strength and direction of relationships between features.

Count Plot and Pie Chart: Visual representations of the distribution of diabetic and non-diabetic outcomes are presented using count plots and a pie chart, providing a clear overview of the dataset's class distribution.

Histograms and Distribution Plots: Histograms and distribution plots are used to analyze the distribution of each feature, providing a deeper understanding of their characteristics.

# Model Building:

Random Forest Classifier: A machine learning model, specifically a Random Forest Classifier, is implemented to predict the likelihood of diabetes based on the input features.

Training and Testing: The dataset is split into training and testing sets to evaluate the model's performance.

# Model Evaluation:
Model performance is evaluated using mean squared error (MSE), root mean squared error (RMSE), and accuracy scores.

# Results:
The Random Forest Classifier achieves an accuracy of approximately 72.7% on the test set, indicating its capability to predict diabetes outcomes.

# Conclusion:
In conclusion, this project demonstrates the application of data analysis and machine learning techniques to understand and predict diabetes outcomes based on patient information. The insights gained from this analysis can potentially contribute to early identification and management of diabetes, facilitating better healthcare outcomes.
