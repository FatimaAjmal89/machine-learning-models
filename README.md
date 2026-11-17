# Machine Learning Models

A collection of hands-on machine learning projects using Python and Scikit-learn.

## Projects

### 1. Linear Regression
- Understanding Linear Regression
- Data preprocessing and preparation
- Model training and prediction
- Model evaluation

### 2. Logistic Regression

**Employee Turnover Prediction**
- Working with an employee turnover dataset
- Training a Logistic Regression model
- Evaluating model performance

**Heart Disease Prediction**
- Exploring the heart disease dataset
- Preparing data for classification
- Setting up a Logistic Regression model

### 3. Naive Bayes
- Understanding Naive Bayes Classification
- Text classification / Spam detection / Categorical data classification
- Model training and evaluation

### 4. K-Nearest Neighbors (KNN)
- **Data Preprocessing Fix:** Applied `StandardScaler` for feature scaling to improve model accuracy.
- **Hyperparameter Tuning:** Evaluated model performance across multiple k values (k = 3, 5, 7).
- **Performance Evaluation:** Optimized recall and precision metrics on the heart disease prediction dataset.

### 5. Decision Trees & Pruning
- **Model Training:** Building fully grown decision tree classifiers.
- **Pre-Pruning:** Hyperparameter tuning using `max_depth` and `min_samples_split` to prevent overfitting.
- **Post-Pruning (Cost-Complexity Pruning):** Calculating optimal `ccp_alphas` via `cost_complexity_pruning_path` and evaluating on test sets to select the best pruned tree.
- **Visualization:** Plotting decision trees using `plot_tree` with customized feature and class names.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Repository Structure

```text
machine-learning-models/
├── Linear_Regression/
├── Logistic_Regression/
├── Naive_Bayes/
├── KNN/
├── Decision_Trees/
└── README.md
