# credit-risk-classification
**Report on Machine Learning Model Performance**

In this report, we will provide a summary and analysis of the performance of machine learning models used in a classification task, particularly focusing on logistic regression. Two variants of logistic regression models were trained and evaluated: one using the original data and the other using oversampled data to address class imbalance.

**Logistic Regression with Original Data:**
- Precision for "0" (healthy loans) label: 1.00
- Recall for "0" (healthy loans) label: 1.00
- F1-score for "0" (healthy loans) label: 1.00
- Precision for "1" (high-risk loans) label: 0.86
- Recall for "1" (high-risk loans) label: 0.91
- F1-score for "1" (high-risk loans) label: 0.88
- Overall accuracy: 0.99

**Analysis:**
The logistic regression model trained with the original data performed exceptionally well. It accurately predicted both healthy and high-risk loans with high precision and recall. The model achieved an outstanding accuracy of 0.99, indicating its success in the classification task with the imbalanced dataset. The high precision and recall values demonstrate its ability to differentiate between the two classes effectively.

**Logistic Regression with Oversampled Data:**
- Precision for "0" (healthy loans) label: 1.00
- Recall for "0" (healthy loans) label: 0.99
- F1-score for "0" (healthy loans) label: 1.00
- Precision for "1" (high-risk loans) label: 0.85
- Recall for "1" (high-risk loans) label: 0.99
- F1-score for "1" (high-risk loans) label: 0.92
- Overall accuracy: 0.99

**Analysis:**
The logistic regression model trained with oversampled data also exhibited outstanding performance. It accurately predicted both healthy and high-risk loans with high precision and recall, similar to the original data model. The oversampling technique successfully addressed the class imbalance, resulting in a balanced model with high accuracy.

**Conclusion:**
Both logistic regression models performed remarkably well, achieving high precision, recall, and F1-scores for both classes. The oversampled data model effectively addressed class imbalance while maintaining exceptional predictive capabilities. The models' high accuracy demonstrates their suitability for the classification task, making them valuable tools for assessing loan health and risk.

These models can be valuable assets in the financial industry for automating loan risk assessment and decision-making, ultimately leading to more efficient and informed lending practices.
