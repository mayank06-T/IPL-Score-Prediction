# 🏏 IPL Score Prediction – AI/ML Project

This project is an AI-powered IPL score prediction system that leverages machine learning models trained on historical IPL data (`ipl.csv`) to forecast the final score of an innings based on real-time match inputs.

## 📌 Project Description

Using key match parameters like batsman, bowler, number of overs completed, current score, venue, and both teams' names, this model accurately predicts the expected final score of an IPL inning. The system is ideal for use in cricket analytics, fantasy sports platforms, or live match prediction tools.

---

## 📊 Features

- ⚡ Real-time input of match parameters
- 🧠 Trained ML model on IPL data (`ipl.csv`)
- 📈 Predicts final score of an ongoing match
- 📍 Takes into account venue impact and team performance
- 🔍 Lightweight and beginner-friendly codebase

---

## 🧠 Input Parameters

The model takes the following inputs from the user:

| Parameter           | Description                                 |
|---------------------|---------------------------------------------|
| 🏏 Batsman          | Current batsman name                        |
| 🎯 Bowler           | Current bowler name                         |
| ⏱️ Overs            | Number of overs completed                   |
| 🧮 Current Runs     | Runs scored so far                          |
| 🟢 Batting Team     | Name of the batting team                    |
| 🔴 Bowling Team     | Name of the bowling team                    |
| 🏟️ Venue           | Location of the match                       |

---

## 🧪 How It Works

1. Loads and preprocesses IPL match data (`ipl.csv`).
2. Uses `LabelEncoder` to handle categorical data like team names, venues, and players.
3. Trains a regression model (e.g., Random Forest or Linear Regression).
4. Takes live match input from the user.
5. Predicts the most probable final score using the trained model.

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn (optional for visualization)
- Jupyter Notebook / Streamlit (for UI)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mayank06-T/IPL-Score-Prediction
   cd ipl-score-predictor

2. Install dependencies:
   
 pip install -r requirements.txt

3. Run the script or notebook:
 python predict.py

Or open:
jupyter notebook IPL_Score_Prediction.ipynb

🧠 Sample Output

 🏏 Batsman: Virat Kohli  
 🎯 Bowler: Jasprit Bumrah  
 ⏱️ Overs: 14  
 🧮 Current Runs: 125  
 🟢 Batting Team: RCB  
 🔴 Bowling Team: MI  
 🏟️ Venue: M. Chinnaswamy Stadium

📊 Predicted Final Score: 185


📁 File Structure

 📂 ipl-score-prediction/
├── ipl.csv                   # Historical IPL dataset
├── predict.py                # Main prediction script
├── IPL_Score_Prediction.ipynb# Jupyter Notebook version
├── requirements.txt          # Required Python packages
└── README.md                 # You're here!

🙋‍♂️ Author
Mayank Tiwari

 

