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
# Conclusion
This project successfully demonstrated an end-to-end machine learning pipeline for restaurant sentiment analysis using Zomato data, encompassing data understanding, preprocessing, feature engineering, visualization, hypothesis testing, and model development. Extensive exploratory data analysis revealed meaningful patterns in customer behavior, such as the dominance of positive reviews, the influence of engagement indicators on sentiment, and the relationship between rating consistency and customer satisfaction. These insights helped frame both business-relevant hypotheses and informed modeling decisions.
Robust data preprocessing techniques were applied, including missing value handling, outlier treatment, categorical encoding, and comprehensive text preprocessing steps such as normalization, tokenization, and vectorization. TF–IDF proved effective in capturing important textual features, while dimensionality reduction and feature selection helped manage high-dimensional data and improve computational efficiency. Special care was taken to handle class imbalance using SMOTE, ensuring fair learning across sentiment categories and preventing model bias toward the majority class.
Multiple machine learning models were implemented and evaluated, including Logistic Regression, Support Vector Machine, and Multinomial Naive Bayes. Among these, the Support Vector Machine emerged as the most reliable and balanced model, achieving strong performance across accuracy, precision, recall, and F1-score metrics. Hyperparameter tuning further enhanced model performance, demonstrating the importance of optimization techniques in improving generalization. Model explainability through coefficient-based analysis provided valuable insights into key sentiment-driving terms, enabling interpretability and actionable business understanding.
Finally, the selected model was saved, reloaded, and tested on unseen data to validate deployment readiness, confirming the robustness and reproducibility of the solution. Overall, this project not only achieved its technical objectives but also delivered meaningful business insights that can support restaurant performance monitoring, customer experience improvement, and data-driven decision-making. The workflow, results, and conclusions together reflect a production-ready, academically sound, and professionally executed machine learning capstone 

# ZOMATO PROJECT REPORT - https://docs.google.com/document/d/1qYO2lxqCf0Dkeb8m1vi5vkOSIwFvaXzeAC1jCJ3sHWU/edit?usp=sharing

