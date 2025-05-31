# Elevate_Labs_Task4
1. Binary Classification Dataset
Used Breast Cancer dataset from sklearn.datasets.

Target variable: 0 = Malignant, 1 = Benign.

2. Train-Test Split & Standardization
Split data into training/testing sets with stratified sampling.

Scaled features using StandardScaler for better model performance.

3. Fit Logistic Regression Model
Trained LogisticRegression from scikit-learn.

Handled multivariate binary classification.

4. Evaluate with Metrics
Calculated Confusion Matrix, Precision, Recall, ROC-AUC.

Plotted the ROC curve to visualize trade-offs.

5. Tune Threshold & Explain Sigmoid
Adjusted decision threshold (e.g. from 0.5 to 0.3) to improve recall.

Explained sigmoid function: maps linear output to probability using 1 / (1 + exp(−z)).

