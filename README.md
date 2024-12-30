# Loan-Repayment-Prediction--Random-Forest

**Project Purpose:**

To develop a predictive model that assists PeerLoanKart in evaluating the likelihood of borrowers repaying their loans, thereby enhancing investor confidence and ensuring better risk management.

**Business Case:**

PeerLoanKart, a peer-to-peer lending NBFC, connects borrowers with investors. Investors require reliable insights into borrower profiles to make informed decisions. Predicting repayment probabilities will improve investor satisfaction, reduce default risks, and drive growth for the platform.

**Goal:**

Build a machine learning model to accurately predict whether a borrower is likely to repay their loan based on their profile and historical data.

**Deliverable:**

A fully functional predictive model with detailed performance metrics, ready for deployment, to classify borrowers based on repayment likelihood.


# Results and Model Evaluation

From a business perspective, accurately predicting borrowers likely to repay their loans (True Positives) is crucial to reducing default risks and maintaining investor confidence. Therefore, both Precision and Recall are important measures for this model to ensure reliable predictions and minimize errors. Since the model shows consistent performance across metrics and classes, it demonstrates robustness and suitability for deployment without overfitting or sacrificing predictive power.

**Precision:** Precision on the testing data is 87%, indicating the model effectively minimizes False Positives. This ensures that most predicted borrowers are genuinely good repayment candidates.

**Accuracy:** Accuracy on the testing data is 86%, meaning the model correctly predicts borrower repayment likelihood for about 6 out of every 7 cases.

**Recall:** Recall on the testing data is 83%, showing the model successfully identifies the majority of borrowers likely to repay.

**F1 Score:** The F1 score on the testing data is 85%, reflecting the balance between precision and recall for repayment predictions.


# Business Impact

The model enhances risk management by reducing defaults and boosting investor confidence through accurate repayment predictions. Automation streamlines loan approvals, enabling faster processing and improved operational efficiency.
