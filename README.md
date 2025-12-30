🏏 IPL Win Probability Predictor
📌 Project Overview

The IPL Win Probability Predictor is a machine learning–based web application that predicts the real-time winning probability of an IPL team during a match. The prediction is based on match situation parameters such as batting team, bowling team, venue, current score, overs, wickets, and target.

This project demonstrates end-to-end ML skills, including feature engineering, model training, and deployment using Streamlit.

🎯 Problem Statement

Cricket fans and analysts often want to understand how match conditions influence the chances of winning. This project aims to:

Predict win probabilities dynamically as match conditions change

Provide data-driven insights instead of intuition-based predictions

🧠 Machine Learning Approach

Converted match data into a supervised learning format

Performed extensive feature engineering (run rate, required run rate, balls left, wickets remaining)

Trained classification models to estimate win probability

Selected the best-performing model based on accuracy and probability calibration

🛠️ Tech Stack

Language: Python

Libraries:

pandas

numpy

scikit-learn

matplotlib

streamlit

Model: Logistic Regression / Random Forest (as applicable)

📂 Project Structure
├── app.py                  # Streamlit application
├── model.pkl               # Trained ML model
├── encoder.pkl             # One-hot encoder
├── requirements.txt        # Dependencies
├── IPL_Win_Predictor.ipynb # Model training notebook
├── README.md               # Project documentation

📊 Key Features

Real-time win probability prediction

Interactive and user-friendly Streamlit UI

Handles multiple teams and venues

Probability-based output (not just win/lose)

▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/saurabh99902/IPL-Win-Probability-Predictor.git
cd IPL-Win-Probability-Predictor

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
streamlit run app.py

🧪 Sample Input Parameters

Batting Team

Bowling Team

Host City

Target Score

Current Score

Overs Completed

Wickets Fallen

📈 Output

Winning probability of the batting team

Winning probability of the bowling team
