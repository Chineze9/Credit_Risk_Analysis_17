# Credit_Risk_Analysis_17

SOLVING CREDIT CARD RISK
Overview of the Analysis
I am expected to apply machine learning to solve a real-world challenge: credit card risk, using different
techniques to train and evaluate models with unbalanced classes. In the process, I used imbalanced-
learn and scikit-learn libraries to build and evaluate models using resampling. In the process, I applied
the credit card dataset from lending services and oversampled the data while using Randomoversampler
and smote algorithms, as well as undersampling the data with ClusterCenroids algorithm. Then a
combinatorial approach of over and undersampling with the use of smoteenn algorithm. At the end, the
two new machine learning models were compared to reduce bias, to predit credit risk. The
performance of these two models were evaluated in their performances.
Results
An accuracy score for the model is calculated. A confusion matrix has been generated, and an
imbalanced classification report was generated. Please see Results below:


COMPARISON
1. CREDIT RISK ENSEMBLE – BALANCED
CLASSIFICATION REPORT

After loading the Loan Data and splitting the Data
into training and Testing, I discovered
y.value_counts had low risk of 68470 and high risk
of 347. (image 1)
The calculated balanced accuracy score was 78%
(image 2)
Whereas the Confusion Matrix had actual values
of
Array [ 57, 30]
[ 1368, 15750] (image 3)
Yielding the average total predictions at 0.99%
Precision and 0.92% Recall (image 4)

2. CREDIT RISK RESAMPLING – BALANCED CLASSIFICATION REPORT

Images for Credit Risk Resampling

After loading the Loan Data and splitting the Data into training and
Testing I discovered the y.value_counts had a low_risk of 68470
with high risk of 347 target values. (image1)
The calculated balanced accuracy score was 65%. (image 2)
Whereas the Confusion Matrix had actual values of
Array [ 79, 8]
[979, 16139] (image 3)
Yielding the average total predictions at 0.99% Precision and 0.94%
Recall (image 4)

3. CREDIT RISK ENSEMBLE – OVERSAMPLING CLASSIFICATION
REPORT
After loading the Loan Data and splitting the Data into training and
Testing I discovered the y.value_counts had a low_risk of 51352
with high risk of 51352 target values. (image1)
The calculated balanced accuracy score was 64%. (image 2)
Whereas the Confusion Matrix had actual values of
Array [ 55, 32]
[5697, 11421] (image 3)

Yielding the average total predictions at 0.99% Precision and 0.67%
Recall (image 4)

Summary
You can see from the report of my evaluation that both precision and recall are crucial for information
retrieval, where positive class mattered the most as compared to negative. I recommend that the Credit
risk Ensemble – Oversampling Classification Report will be the most efficient model to use, with 0.99%
Precision and 0.67% Recall as opposed to 0.94% Recall in Credit risk Resampling because in the real
machine world, 0.11111% is huge and could take a company months to achieve.
