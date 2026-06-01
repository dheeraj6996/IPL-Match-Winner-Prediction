IPL Match Winner Prediction
Overview
This project predicts IPL match winners using historical IPL match data and Machine Learning algorithms.The project includes complete data cleaning, exploratory data analysis (EDA), feature engineering, preprocessing, model training, and prediction workflows.

Features
* IPL historical match analysis
* Match winner prediction system
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Machine Learning model comparison
* Random Forest based prediction system

Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

Project Workflow
1. Data Collection
* Collected IPL historical match dataset from Kaggle.
2. Data Cleaning
* Removed unnecessary columns
* Handled missing values
* Filtered relevant IPL teams
* Removed invalid rows
3. Exploratory Data Analysis
* Team performance analysis
* Toss impact analysis
* Venue analysis
* Match trend visualization
4. Feature Engineering
* Selected important features
* Applied One-Hot Encoding
* Prepared ML-ready dataset
5. Machine Learning Models
Models used:
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
6. Model Evaluation
* Compared model accuracies
* Improved performance using better preprocessing and feature selection

Machine Learning Models Accuracy
Model	Accuracy
Logistic Regression	22.36 %
Decision Tree	36.64 %
Random Forest	57.89 %
Important Features Used
* team1
* team2
* toss_winner
 tossdecision
 venue
 city
 playerofmatch
 targetruns
 target_overs
Graphs & Visualizations
The project includes:
* Team win analysis
* Toss decision analysis
* Venue distribution graphs
* Match trend visualizations
* Correlation analysis

Prediction System
A reusable prediction function was created where users can input:
* Team names
* Toss winner
* Toss decision
* Venue
* City
* Target score
The model predicts the probable match winner.

Future Improvements
* Add live IPL API integration
* Add player statistics
* Add win probability prediction
* Build Streamlit web application
* Use advanced ML models like XGBoost

Conclusion
This project demonstrates an end-to-end Machine Learning workflow using IPL cricket data.�It covers data preprocessing, visualization, feature engineering, model building, evaluation, and prediction system development.

Author
Dheeraj Reddy
