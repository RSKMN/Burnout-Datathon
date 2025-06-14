# 🏁 Burnout Datathon 2025 - MotoGP Lap Time Prediction

## 📌 Problem Statement

This project was developed for **Round 1 of the Burnout Datathon 2025**, hosted on Kaggle by IEEE-CS MUJ. The goal is to predict **MotoGP lap times (`Lap_Time_Seconds`)** based on various rider statistics, track conditions, bike specs, and environmental features.

---

## 📂 Files Included

| File Name           | Description                                                  |
|---------------------|--------------------------------------------------------------|
| `notebook.ipynb`    | Main notebook for data preprocessing, modeling, and prediction |
| `submission.csv`    | Final submission file in required Kaggle format              |
| `train.csv`         | Training data (provided by competition)                      |
| `test.csv`          | Test data (provided by competition)                          |
| `README.md`         | This documentation                                           |
| `requirements.txt`  | (Optional) Required Python packages                          |

---

## 📊 Dataset Overview

- **Total Rows in Training Data:** ~1.9 million
- **Target Variable:** `Lap_Time_Seconds`
- **Features:** Rider stats, track features, weather, session info, etc.
- **No external datasets were used** (as per competition rules)

---

## 🧠 Approach

- Model Used: **LightGBM Regressor**
- Reason: Fast training on large tabular data, handles missing values, and robust performance
- Steps:
  - Basic preprocessing, feature selection
  - Train/validation split using `train_test_split`
  - Model evaluation using RMSE
  - Final predictions saved in `submission.csv`

---

## 🧪 Evaluation

- The competition is evaluated using **RMSE (Root Mean Squared Error)**.
- Submissions are scored using a **50/50 combination of public and private leaderboard**.

---

## 📎 Kaggle Notebook (Public)

📌 View the notebook on Kaggle [here]([https://www.kaggle.com/code/your-kaggle-username/burnout-laptime-lightgbm](https://www.kaggle.com/code/rsrikrishnamurthy/rskmn-motogp))  
> _Replace the above link with your actual Kaggle notebook URL_

---
