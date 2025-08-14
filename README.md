# 🏏 IPL Match Prediction Model

## 📌 Overview
This project uses **Machine Learning** to predict the winning team of an **Indian Premier League (IPL)** cricket match based on historical match data.  
It applies **data preprocessing**, **feature encoding**, and a **classification model** to estimate the probability of victory for each team.

---

## 📊 Dataset
- **Source**: Historical IPL match data (CSV file)
- **Features**:
  - `batting_team` - Team currently batting
  - `bowling_team` - Team currently bowling
  - `venue` - Stadium name
  - `toss_winner` - Toss-winning team
  - `toss_decision` - Bat/Field decision
  - `target_runs` - Target score
  - `current_score` - Score so far
  - `overs_completed` - Overs played
  - `wickets_left` - Remaining wickets
- **Target**:
  - `result` - Winning team

---

## ⚙️ Features of the Project
- Data Cleaning & Preprocessing
- Categorical Feature Encoding (`OneHotEncoder`, `LabelEncoder`)
- Train/Test Split
- Model Training (e.g., Logistic Regression / Random Forest)
- Model Evaluation (Accuracy, Confusion Matrix)
- Win Probability Prediction for given match conditions

---

## 🛠️ Tech Stack
- **Language**: Python 3
- **Libraries**:
  - `pandas`, `numpy`
  - `scikit-learn`
  - `matplotlib`, `seaborn`

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/ipl-match-prediction.git
cd ipl-match-prediction
