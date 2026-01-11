# ZOMATO-PROJECT
The objective of this project is to analyze Zomato restaurant metadata and customer review data to extract meaningful insights using data science and machine learning techniques. The project aims to understand customer sentiment based on ratings and review text, evaluate restaurant performance identify patterns that influence customer satisfaction.
# Objective 
The primary objective of this project is to analyze customer sentiment from restaurant reviews and derive insights that benefit both customers and businesses. Specifically, the project aims to:
Analyze customer sentiments from textual reviews using NLP techniques.
Segment restaurants based on ratings, sentiment consistency, cost, and popularity.
Help customers identify the best restaurants based on data-driven metrics.
Identify cost vs benefit inefficiencies for restaurants.
Detect influential reviewers (critics) who significantly impact public perception.
Build and evaluate machine learning models to classify sentiment accurately.
Ensure the solution is deployment-ready and reproducible.
# Machine Learning Models Implemented
** Logistic Regression
Baseline model
Good interpretability
Moderate performance on minority classes
** Support Vector Machine (Final Model)
Best performance across accuracy, precision, recall, and F1-score
Handled high-dimensional TF–IDF features effectively
Balanced class predictions after SMOTE
Chosen as the final model
** Multinomial Naive Bayes
Extremely fast and CPU-efficient
Competitive performance after RandomizedSearchCV tuning
Used as a lightweight alternative model

# BEST MODEL - LOGISTIC REGRESSION

# Conclusion
This project successfully implemented an end-to-end machine learning pipeline for restaurant sentiment analysis using Zomato customer review data, with a clear focus on extracting actionable insights for both customers and businesses. Through detailed exploratory data analysis, the project identified key behavioral patterns such as the dominance of positive customer reviews, the measurable impact of customer engagement (pictures uploaded and review depth) on sentiment, and the strong relationship between rating consistency and overall customer satisfaction. These findings validated the project’s objective of helping customers identify the best-performing restaurants while enabling companies to recognize operational gaps.
Comprehensive data preprocessing and feature engineering were performed to ensure analytical robustness. This included missing value imputation, IQR-based outlier treatment, categorical encoding, and an extensive NLP pipeline involving text normalization, tokenization, lemmatization, and TF–IDF vectorization. The TF–IDF feature space, combined with dimensionality reduction and feature selection, effectively captured sentiment-bearing terms while maintaining computational efficiency. Class imbalance was successfully addressed using SMOTE, ensuring that negative and neutral sentiments were learned fairly alongside the dominant positive class.
Multiple machine learning models—Logistic Regression, Support Vector Machine, and Multinomial Naive Bayes—were trained and evaluated using accuracy and F1-score as primary metrics. Logistic Regression emerged as the best-performing model, achieving an accuracy of approximately 0.89 and an F1-score close to 0.89, outperforming SVM and Naive Bayes in both stability and class-wise balance. Its superior performance, combined with high interpretability, made it the most suitable model for this sentiment classification task. Coefficient-based explainability further enabled identification of key positive and negative sentiment-driving terms, translating model predictions into meaningful business insights.
Advanced analytical extensions such as cost–benefit analysis, restaurant segmentation, and critic identification provided additional value. The analysis revealed that higher cost does not necessarily guarantee higher satisfaction, emphasizing the importance of service quality and consistency. Influential reviewers were identified using engagement metadata, offering the platform an opportunity to monitor sentiment leaders and improve trust-based ranking mechanisms.
Finally, the Logistic Regression model was saved, reloaded, and validated on unseen data, confirming deployment readiness and reproducibility. Overall, this project successfully met all defined objectives, delivering a production-ready, interpretable, and business-relevant sentiment analysis system. The insights generated can support better restaurant recommendations, pricing strategies, customer experience optimization, and informed decision-making, demonstrating a professionally executed and academically sound machine learning capstone project.

# ZOMATO PROJECT REPORT - https://docs.google.com/document/d/1qYO2lxqCf0Dkeb8m1vi5vkOSIwFvaXzeAC1jCJ3sHWU/edit?usp=sharing

