Machine Learning Model Development Report

1. Data Upload
Description: Uploaded the dataset into a DataFrame.
Shape: The dataset contains 1000 rows and 21 columns.

2. Data Exploration
Null Values: Checked for missing values in the dataset.
Summary Statistics: Generated descriptive statistics for the dataset to understand distributions.
Boxplot Analysis: Created boxplots for Credit amount, Duration in months, and Age to visualize the spread and detect outliers.

3. Outlier Detection and Removal
Outlier Detection: Detected outliers using the Interquartile Range (IQR) method.
Outlier Removal: Removed outliers from the dataset to improve model performance.

4. Data Preprocessing
Correlation Matrix: Generated a correlation matrix to understand relationships between features.
Column Cleaning: Removed leading and trailing spaces from column names using strip() method to ensure consistency.
Feature Scaling: Applied StandardScaler to normalize the feature values.

5. Data Transformation and Splitting
One-Hot Encoding: Encoded categorical variables using OneHotEncoder.
Column Transformation: Applied ColumnTransformer to handle both numerical and categorical features.
Train-Test Split: Divided the dataset into training and testing sets using train_test_split.

6. Model Training and Evaluation
Random Forest Classifier: Trained a Random Forest model on the preprocessed data.
Logistic Regression: Trained a Logistic Regression model and evaluated performance.
Model Evaluation Metrics:
Accuracy Score: Evaluated the accuracy of the model.
Confusion Matrix: Generated a confusion matrix to understand classification performance.
Classification Report: Provided precision, recall, F1-score, and support for each class.
Recall, F1-Score, Precision: Evaluated these metrics individually.
ROC-AUC Score: Calculated the Area Under the Receiver Operating Characteristic Curve (ROC-AUC).
ROC Curve: Plotted ROC Curve to visualize the true positive rate vs. false positive rate.

7. Additional Algorithms
K-Nearest Neighbors (KNN): Trained and evaluated a KNN model.
Further Evaluation: Compared performance of different models to identify the best-performing one.
