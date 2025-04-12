# Mental-health-Prediction-and-Chatbot-System
A comparison of three machine learning models, Gradient Boosting, Random Forest, and Logistic Regression, revealed significant performance features. Gradient Boosting was the best-performing model, with an accuracy of 78.61%, precision of 76.25%, and recall of 83.83%, resulting in an F1-score of 79.86% and ROC AUC of 0.871 following hyperparameter optimization. The fine-tuned model employed the optimum parameters (learning_rate=0.1, max_depth=5, n_estimators=150), indicating its capacity to deal with complicated, non-linear interactions in mental health survey data.
The confusion matrix demonstrated the model's balanced performance.
- Correct predictions are 24,479 (treatment) and 21,171 (no treatment).
- Misclassifications include 7,724 false positives and 4,784 false negatives.

This shows a minor bias toward advocating therapy, which is consistent with clinical aims to reduce missed instances. 

Mental-Health assessment tool will ask a series of questions to predict if treatment is needed by individual. It also lets the user know that this is not a professional diagnosis, but rather an assessment based on machine learning analysis of similar cases.

