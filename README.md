# Applied-Roots
Applied Roots Projects

**Donors Choose.Org Application Screening**<br><br>
**Data Source:** Kaggle<br><br>
**Objective:** To predict whether a DonorsChoose.Org project proposal
submitted by a teacher will be approved or not.<br><br>
**Models:** Multinomial Naïve Bayes, Decision Trees, Gradient Boosted
Decision Trees.<br><br>
**Featurization:**<br><br>
**Text Features:** BOW, TFIDF, W2V, Sentiment Analysis.<br>
**Categorical Features:** One hot encoding, Response Coding.<br>
**Numerical Features:** Normalization, Standardization.<br><br>
**Hyperparameter Tuning:** Random searchCV, Grid searchCV.<br><br>
**Results:**<br><br>
**Naive Base:** Achieved 0.7406 and 0.7024 as train and test AUC with BOW
Vectorization. 0.7505 and 0.5880 as train and test AUC with Tfidf
Vectorization.<br>
**Decision Tree:** Train and Test AUC is 0.663 and 0.636 for TFIDF Vectorizer and
for TFIDF W2V Vectorizer, test AUC is 628. Train and Test AUC for
TFIDF nonzero feature is 0.698 and 0.635.<br>
**XGBoost:** obtained 0.826 and 0.751 as Train and Test AUC with TFIDF
and TFIDF W2V 0.804 and 0.731 as train and test AUC.<br>

**Implemented SGD algorithm with log loss from scratch in python**<br>
**Data source:** Custom<br>
**Objective:** Compare custom implementation and SGD classifiers
weights and intercept, making sure that they are as close as possible.
That is, difference should be in terms of 10^-3.<br>
Created custom dataset, split data in to train and test, standardize the
data, implemented logistic regression with L2 regularization using SGD
with no sklearn. Plotted epoch number vs train, test loss.
