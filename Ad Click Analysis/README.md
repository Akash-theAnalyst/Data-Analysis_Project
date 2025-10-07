Online Ad Click Analysis

Overview
This project presents an end-to-end analysis of online advertisement engagement, combining data exploration, feature engineering, and predictive modeling to generate actionable insights for marketing campaigns. The analysis demonstrates technical expertise in Python, machine learning, and data visualization while providing business-relevant recommendations.

Project Highlights
	•	Objective: Understand the factors influencing online ad clicks and predict user engagement.
	•	Dataset: 10,000 records of online ads with user demographics, behavior, and ad attributes (Kaggle CTR dataset).
	•	Key Questions:
	◦	Which user features most influence ad clicks?
	◦	How do temporal factors (hour, day-of-week) impact engagement?
	◦	Which ad topics perform best?

Technical Stack
	•	Libraries: pandas, NumPy, seaborn, matplotlib, scikit-learn, imblearn
	•	Data Cleaning & EDA: Handling missing values, encoding categorical variables, visualizing distributions and correlations
	•	Feature Engineering: Age groups, temporal features (hour, day-of-week), top-feature selection
	•	Modeling: Random Forest classifier, hyperparameter tuning with GridSearchCV, feature importance analysis
	•	Evaluation Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

Key Insights
	•	Age Matters: Users aged 25–35 are more likely to click ads.
	•	Engagement Metrics Are Important: Daily Internet usage and time spent on site strongly predict clicks.
	•	Timing Optimization: Hour of day and day-of-week affect click-through rates; schedule campaigns during peak engagement.
	•	Regional Campaigns: Area income shows modest influence; consider geographic targeting.
	•	Ad Content Impact: While creative messaging matters, targeting and timing are more critical.

Modeling & Results
	•	Random Forest Classifier used for prediction.
	•	Hyper-parameter tuning found best n_estimators = 300 for top features model.
	•	Performance on Test Set:
	◦	Accuracy: 0.76
	◦	Precision: 0.76
	◦	Recall: 0.74
	◦	F1-score: 0.75
	•	Most Important Features:
	◦	Age
	◦	Daily Internet Usage
	◦	AgeGroup
	◦	Daily Time Spent on Site
	◦	Area Income

Conclusion
This project demonstrates full-cycle data analysis and predictive modeling for online ad clicks. It combines technical rigor with business relevance and provides actionable recommendations to optimize marketing campaigns, user engagement, and email growth initiatives.
