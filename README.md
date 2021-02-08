# ML_DiabetesPrediction
Prediksi diabetes menggunakan Machine Learning

Diabetes prediction using machine learning

Dataset: https://www.kaggle.com/uciml/pima-indians-diabetes-database

## I. Requirements:
- Python 3.8
- Scikit-learn
- Pandas
- Matplotlib
- Numpy

## II. Methods:
- Data Preparation: Load data, review data, inspect, clean data, molding
- Choose Algorithm: Naive Bayes
- Model training: Data splitting, Preprocessing, Feature selection, model training
- Accuracy testing: Evaluate the model, performance enhancing (Random Forest Classifier, Logistic Regression)
- Cross Validation

## III. Results:
### 3.1. Naive bayes:
Accuracy test (naive bayes): 0.7359

Confusion Matrix

[[118  33]<br>
 [ 28  52]]

Classification Report
              precision    recall  f1-score   support

           0       0.81      0.78      0.79       151
           1       0.61      0.65      0.63        80

    accuracy                           0.74       231
   macro avg       0.71      0.72      0.71       231
weighted avg       0.74      0.74      0.74       231

### 3.2. Random Forest Classifier
Accuracy test (random forest): 0.7100

Confusion Matrix

[[121  30] <br>
 [ 37  43]]

Classification Report
              precision    recall  f1-score   support

           0       0.77      0.80      0.78       151
           1       0.59      0.54      0.56        80

    accuracy                           0.71       231
   macro avg       0.68      0.67      0.67       231
weighted avg       0.70      0.71      0.71       231

### 3.3. Logistic Regression:
Accuracy test (logistic regression): 0.7143

Confusion Matrix:

[[105  46]<br>
 [ 20  60]]

Classification Report
              precision    recall  f1-score   support

           0       0.84      0.70      0.76       151
           1       0.57      0.75      0.65        80

    accuracy                           0.71       231
   macro avg       0.70      0.72      0.70       231
weighted avg       0.75      0.71      0.72       231

### 3.4. Logistic Regression CV:
Accuracy test (logistic regression CV): 0.7013

Confusion Matrix:

[[109  42]<br>
 [ 27  53]]

Classification Report
              precision    recall  f1-score   support

           0       0.80      0.72      0.76       151
           1       0.56      0.66      0.61        80

    accuracy                           0.70       231
   macro avg       0.68      0.69      0.68       231
weighted avg       0.72      0.70      0.71       231
