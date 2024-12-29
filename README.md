# Iris Flower Classification

This project follows a systematic machine learning workflow to classify Iris flower species efficiently and accurately. Below is an overview of the steps involved:

## Project Process

### 1. Data Preparation
- **Loading the Dataset**: The Iris dataset was loaded and explored to understand its structure.
- **Data Cleaning**: Checked for missing values and duplicates; removed one duplicate to maintain data integrity.
- **Outlier Handling**: Used the Interquartile Range (IQR) method to detect and remove outliers for better model performance.

### 2. Exploratory Data Analysis (EDA)
- Visualized the distribution of target classes and various features.
- Used boxplots and histograms to analyze feature characteristics.
- Created pair plots and a correlation matrix to understand relationships between features.

### 3. Data Splitting
- Divided the data into features (X) and target labels (y).
- Split the dataset into training and testing sets with an 80-20 ratio to ensure a fair evaluation.

### 4. Model Selection and Evaluation
- Identified four classification algorithms: Random Forest, Support Vector Machine, Logistic Regression, and Gradient Boosting Classifier.
- Trained and evaluated each model to compare accuracy and performance.
- Used cross-validation to determine the most robust model, selecting the Random Forest Classifier for its consistent accuracy.

### 5. Feature Scaling and Model Optimization
- Scaled features using StandardScaler for improved performance.
- Performed hyperparameter tuning with GridSearchCV to find the best settings for the Random Forest model.

### 6. Model Deployment
- Saved the trained model using `joblib` for future predictions.
- Demonstrated predictions using new input data.

---

Feel free to explore and use the code to understand and build similar projects.


