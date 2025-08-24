🏏 IPL Score Predictor – Machine Learning Project
🌟 Project Overview

The IPL Score Predictor is a Machine Learning project designed to predict the final score of an IPL team in the first innings based on the match situation such as runs, wickets, overs, current run rate, and venue.

👉 Think of it as a virtual commentator 🎤 that can estimate “This team might score around 185 today!” even before the innings ends.

🧠 Problem Statement

In cricket, especially in the Indian Premier League (IPL), predicting the final score of a batting team is very difficult because:

🏃‍♂️ Run rates change rapidly across overs.

🧱 Fall of wickets disrupts momentum.

🌍 Venue and pitch conditions matter.

⚡ Big hitters accelerate in the death overs.

This project addresses these challenges using machine learning regression algorithms.

⚙️ Key Features

Accepts input such as batting team, bowling team, runs, wickets, overs, venue, and current run rate.

Predicts the final score range (e.g., 170–185).

Provides insights into match progression and helps understand scoring trends.

Can be extended into a web app for live usage.

🏗️ System Architecture

Flow:
User Input ➝ Data Preprocessing ➝ ML Model ➝ Predicted Score

Frontend (optional): Streamlit or Flask Web App.

Backend: Python with ML model exposed through REST API.

ML Models: Linear Regression, Ridge Regression, Random Forest, XGBoost.

Dataset: Kaggle IPL dataset containing ball-by-ball and match details.

📊 Dataset

The dataset includes:

Batting and Bowling teams.

Venue information.

Current runs, overs, and wickets.

Current run rate (CRR) and last 5 overs run rate.

The data is cleaned, categorical values (teams, venues) are encoded, and features are scaled before training ML models.

🔮 Machine Learning Approach

Exploratory Data Analysis (EDA): Understanding run rate patterns, wicket impacts, and venue scoring behaviour.

Algorithms Applied:

Linear Regression.

Ridge Regression.

Random Forest Regressor 🌳.

XGBoost Regressor ⚡.

Model Evaluation Metrics: R² Score and Mean Absolute Error (MAE).

Best Model: XGBoost Regressor achieved the highest accuracy and gave the most reliable predictions.

🎨 Example Prediction

Example Input: Batting Team: MI, Bowling Team: CSK, Overs: 10.2, Score: 82/2, Venue: Wankhede Stadium.
Example Output: Predicted Final Score: 170–185.

📈 Results

Achieved around 92% prediction accuracy on test data.

Random Forest and XGBoost models gave the best results.

Predictions closely matched real IPL match outcomes.

🌐 Tech Stack

Programming Language: Python 🐍.

Libraries: Pandas, NumPy, Matplotlib, Scikit-learn, XGBoost.

Frameworks: Flask or Streamlit for deployment.

Version Control: Git & GitHub.

🏆 Future Enhancements

Use Deep Learning models (LSTM) for sequential prediction.

Connect with live match APIs for real-time predictions.

Deploy as a full-scale web application on AWS/Heroku.

Add visual dashboards for cricket analysts and fans.

👨‍💻 Contributors

👑 Team PathMatrix

Nikita Mehra

(Add teammates if group project)

❤️ Acknowledgments

Dataset Source: Kaggle IPL Dataset.

Tools: Scikit-Learn, XGBoost, Pandas, Streamlit.

Inspiration: Passion for IPL Cricket 🏏 and Data Science 💻.

✨ This project blends Cricket + Data Science to make IPL even more exciting with intelligent predictions!
