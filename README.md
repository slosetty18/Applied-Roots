# Applied-Roots
Applied Roots Projects

**DonorsChoose Proposal Approval Prediction (Kaggle Dataset)**<br>
- Built an end-to-end ML pipeline to predict project approval using structured and text data, including preprocessing, feature engineering, and       model evaluation.<br>
- Engineered features using TF-IDF, Word2Vec, sentiment analysis, and categorical encoding techniques (one-hot, response coding).<br>
- Trained and compared multiple models including Naive Bayes, Decision Trees, and XGBoost with hyperparameter tuning (GridSearchCV, RandomSearchCV).<br>
- Achieved best performance with XGBoost (Test AUC: 0.75), outperforming baseline models and demonstrating strong generalization.<br>
- Analyzed model performance across feature representations, identifying trade-offs between model complexity and overfitting.<br>

**Custom Logistic Regression with SGD Optimization**<br>

- Implemented a custom SGD-based logistic regression model with L2 regularization, reproducing behavior of SGDClassifier with parameter differences within 10^-3.<br>
- Designed end-to-end training workflow including data preprocessing, optimization, and convergence analysis.<br>
- Evaluated model stability and generalization through epoch-wise loss tracking on train and test datasets.<br>
