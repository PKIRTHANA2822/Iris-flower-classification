# Project Title
- Iris Flower Classification using Logistic Regression
![1_4OKY4weOaes0N0zAlmBOrg](https://github.com/user-attachments/assets/273d1bef-351e-4898-8ad3-b0e7082b35cb)
# Objective
- The objective of this project is to classify iris flowers into one of three species (Setosa, Versicolor, Virginica) based on their sepal and petal dimensions. The model should learn patterns in the data and accurately predict the species of a flower given its measurements.
# Why We Use This Project
- The Iris dataset is a classic dataset for beginners in machine learning — small, clean, and well-balanced.
- It helps in understanding multi-class classification problems.
- It demonstrates the use of Logistic Regression for classification in a simple yet effective way.
- It allows practice with data preprocessing, feature scaling, and evaluation metrics like accuracy, classification report, and confusion matrix.
# Step-by-Step Approach
### Data Collection
- Used Seaborn’s built-in iris dataset containing 150 rows and 5 columns:
- Features: sepal_length, sepal_width, petal_length, petal_width
- Target: species (categorical — 3 classes)
# Exploratory Data Analysis (EDA)
- Shape check: (150, 5)
- Class distribution: Equal distribution among three species (50 samples each).
- Scatter plots:
- Sepal length vs sepal width
- Petal length vs petal width
- Boxplots: Checked for outliers in each feature.
- Null values: No missing data.
# Feature Selection
- All four features were kept:
- sepal_length
- sepal_width
- petal_length
- petal_width
# Feature Engineering
- Label Encoding: Converted categorical species names to numeric labels:
- Setosa → 0
- Versicolor → 1
- Virginica → 2
- Standardization: Applied StandardScaler to scale all features for better model performance.
# Model Training
- Algorithm: Logistic Regression (multi-class).
- Train-Test Split: 75% training, 25% testing.
- Random State: 42 for reproducibility.
# Model Testing & Evaluation
- Predictions: Generated predictions for the test set.
- Evaluation Metrics:
- Accuracy Score: High accuracy (~97–100%).
- Classification Report: Precision, Recall, F1-score for each class.
- Confusion Matrix: Heatmap visualization to show prediction correctness.
# Output
<img width="230" height="787" alt="Screenshot 2025-08-15 204838" src="https://github.com/user-attachments/assets/da7e1999-2533-4108-953a-a47b50be42a5" />
<img width="244" height="506" alt="Screenshot 2025-08-15 204852" src="https://github.com/user-attachments/assets/9aa99939-b43a-4751-8e99-f84faa2a3941" />
