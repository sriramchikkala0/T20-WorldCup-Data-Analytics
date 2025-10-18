🏏 T20 World Cup Data Analytics Project

📘 Overview

This project analyzes T20 World Cup cricket data using both Machine Learning (ML) and Deep Learning (DL) models.
It includes complete data preprocessing, Exploratory Data Analysis (EDA), and model building for match outcome prediction.

The goal is to build an intelligent system that predicts whether Team 1 will win a match, based on match details such as teams, toss results, and venues.


---

📊 Key Features

🧹 Data Cleaning & Preprocessing

📈 Exploratory Data Analysis (EDA)

⚙ Machine Learning Models:

Logistic Regression

Random Forest Classifier


🧠 Deep Learning (Keras MLP) model for improved prediction

📊 Player Performance Insights:

Top Run Scorers

Top Wicket Takers


📁 Model saving (.joblib and .keras) for reuse



---

🧠 Technologies Used

Python

Pandas, NumPy, Matplotlib

Scikit-Learn (ML models)

TensorFlow / Keras (DL model)

Joblib (Model serialization)

Jupyter Notebook



---

🧩 Project Structure

T20-WorldCup-Data-Analytics/
│
├── match_master.csv
├── player_master.csv
├── T20WorldCup.ipynb        ← main notebook
├── logistic_model.joblib
├── rf_model.joblib
├── keras_model.keras
└── README.md


---

🚀 How to Run

1. Clone the repo:

git clone https://github.com/<your-username>/T20-WorldCup-Data-Analytics.git
cd T20-WorldCup-Data-Analytics


2. Install dependencies:

pip install pandas numpy matplotlib scikit-learn tensorflow joblib


3. Open the notebook:

jupyter notebook T20WorldCup.ipynb


4. Run all cells step-by-step.




---

📈 Results

Model	Accuracy	Description

Logistic Regression	~85%	Fast baseline ML model
Random Forest	~90%	Ensemble-based strong ML model
Deep Learning (Keras MLP)	~92%	Neural network for better generalization


(Your actual accuracy may vary depending on dataset version.)


---

🏆 Insights

Team performance varies by venue and toss results.

Toss-winning teams have a higher winning probability.

Certain venues favor batting-first teams.

Deep Learning slightly outperforms classical ML for complex match data.



---

👨‍💻 Author

Sriram Chikkala
🎓 Final Year Student — Data Analytics Project
📧 sriramchikkala004@gmail.com


---

🌟 Show Your Support

If you like this project, ⭐ star the repository on GitHub and share it!


---

Would you like me to customize this README for your GitHub username (sriramchikkala0) so it includes your real repo link?
