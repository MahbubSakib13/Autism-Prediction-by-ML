# Autism-Prediction-by-ML
# Classification Result

🔹 Classification Report for Random Forest:

              precision    recall  f1-score   support

           0       0.98      1.00      0.99       854
           1       0.99      0.95      0.97       361

    accuracy                           0.98      1215
   macro avg       0.99      0.97      0.98      1215
weighted avg       0.98      0.98      0.98      1215


🔹 Classification Report for LightGBM:

              precision    recall  f1-score   support

           0       1.00      1.00      1.00       854
           1       0.99      1.00      0.99       361

    accuracy                           1.00      1215
   macro avg       1.00      1.00      1.00      1215
weighted avg       1.00      1.00      1.00      1215


🔹 Classification Report for Logistic Regression:

              precision    recall  f1-score   support

           0       0.93      0.92      0.93       854
           1       0.82      0.84      0.83       361

    accuracy                           0.90      1215
   macro avg       0.88      0.88      0.88      1215
weighted avg       0.90      0.90      0.90      1215


🔹 Classification Report for Decision Tree:

              precision    recall  f1-score   support

           0       0.98      0.96      0.97       854
           1       0.91      0.95      0.93       361

    accuracy                           0.96      1215
   macro avg       0.94      0.95      0.95      1215
weighted avg       0.96      0.96      0.96      1215


🔹 Classification Report for SVM:

              precision    recall  f1-score   support

           0       0.97      0.97      0.97       854
           1       0.93      0.94      0.93       361

    accuracy                           0.96      1215
   macro avg       0.95      0.95      0.95      1215
weighted avg       0.96      0.96      0.96      1215


🔹 Classification Report for KNN:

              precision    recall  f1-score   support

           0       0.96      0.94      0.95       854
           1       0.86      0.90      0.88       361

    accuracy                           0.93      1215
   macro avg       0.91      0.92      0.91      1215
weighted avg       0.93      0.93      0.93      1215


🔹 Classification Report for Naive Bayes:

              precision    recall  f1-score   support

           0       0.94      0.91      0.92       854
           1       0.80      0.86      0.83       361

    accuracy                           0.89      1215
   macro avg       0.87      0.88      0.88      1215
weighted avg       0.90      0.89      0.89      1215


 Summary: Model Evaluation Results:
                     Accuracy  Precision    Recall  F1 Score   AUC-ROC
LightGBM             0.996708   0.991736  0.997230  0.994475  0.999906
Random Forest        0.983539   0.991354  0.952909  0.971751  0.999168
SVM                  0.959671   0.926230  0.939058  0.932600  0.992173
Decision Tree        0.957202   0.912000  0.947368  0.929348  0.954363
KNN                  0.926749   0.857895  0.903047  0.879892  0.974665
Logistic Regression  0.897119   0.818919  0.839335  0.829001  0.957541
Naive Bayes          0.893827   0.798969  0.858726  0.827770  0.946746
