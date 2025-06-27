# AI-ML-TASK-4
#Logistic Regression – Breast Cancer Classification

Here I used data.csv dataset which is mention in task 4 pdf to download .
First I Loaded the Breast Cancer Dataset (data CSV).
Preprocessed the dataset and  Removed id column ,Converted diagnosis labels: M → 0, B → 1 and filled missing values with column mean.
Split data into training and test sets and standardized the feature values trained a Logistic Regression model.
#Evaluated the model using:
Confusion matrix
Precision, Recall, F1-score
ROC curve and ROC-AUC score
Plotted the ROC curve to visualize performance the model performed with high accuracy and ROC-AUC score was close to 1, indicating excellent performance.
#Tune Threshold and explain sigmoid function
Logistic regression uses the sigmoid function to convert model output into a probability between 0 and 1.
A threshold (default = 0.5) decides the final class:
If probability ≥ 0.5 → class 1 (Benign)
If probability < 0.5 → class 0 (Malignant)
You can tune this threshold (e.g., change it to 0.3 or 0.7) to make the model:
More sensitive (catch more positives)
Or more precise (reduce false alarms)

