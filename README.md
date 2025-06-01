# Task-4-Classification-with-Logistic-Regression.
🔍 Binary Classification with Logistic Regression
This project demonstrates how to build and evaluate a logistic regression model on a binary classification dataset using Python and scikit-learn. It includes data preprocessing, model training, evaluation, threshold tuning, and visualization of the sigmoid function.

📁 Dataset
Assumes data.csv contains:

Features: One or more numeric or categorical predictor variables.

Target: A binary column (e.g., 0 or 1, yes/no, etc.) indicating class membership. The last column is treated as the target.

✅ Steps Performed
1. Upload and Load Dataset
Load the data.csv file using pandas.

2. Preprocess the Data
Train-test split (80/20)

Standardize features using StandardScaler

3. Train Logistic Regression
Train a LogisticRegression model from sklearn.linear_model

4. Model Evaluation
Confusion Matrix

Precision, Recall, F1-Score

ROC Curve and AUC Score

5. Threshold Tuning
Custom threshold (e.g., 0.3) applied to predicted probabilities

Recalculate confusion matrix at new threshold

6. Sigmoid Function Visualization
Plot the sigmoid curve:

𝜎
(
𝑧
)
=
1
1
+
𝑒
−
𝑧
σ(z)= 
1+e 
−z
 
1
​
 
Helps explain how logistic regression maps linear outputs to probabilities.

📊 Example Output
lua
Copy
Edit
Confusion Matrix:
[[43  7]
 [ 5 45]]

Classification Report:
              precision    recall  f1-score   support
           0       0.90      0.86      0.88        50
           1       0.87      0.90      0.89        50

ROC-AUC Score: 0.95
![ROC Curve Screenshot]
![Sigmoid Curve Screenshot]

📦 Libraries Used
pandas

numpy

sklearn

matplotlib

▶️ How to Run in Google Colab
Open Google Colab

Upload your data.csv file

Paste the script (see main.ipynb) into a notebook

Run each cell to see the full analysis
