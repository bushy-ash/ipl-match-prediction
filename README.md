# 🏏 IPL Match Win Predictor

This project is a **machine learning-based web app** that predicts the winning probability of an IPL team during the second innings based on live match data.

Built using **Random Forest Classifier** and deployed with **Streamlit**, the app uses historical IPL data to determine the likely outcome of the match.

🔗 **Live App**: [Click here to try the app](https://harshjain41-ipl-match-win-predictor-app-gceipf.streamlit.app/)

---

## 📊 How It Works

- Takes the **first innings data** as input (total runs scored, etc.)
- Collects current **second innings data** (runs, wickets, overs, etc.)
- Computes live **match metrics** (like run rate, remaining balls, required run rate)
- Predicts the **winning probability** of either team using a trained ML model

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- scikit-learn (Random Forest Classifier)
- Streamlit (for interactive web interface)
- Matplotlib & Seaborn (for visualization)
- Jupyter Notebook (model development)

---

## 📁 Files Included

- `IPL Win Probability Predictor.ipynb`: Jupyter notebook for model training and EDA
- `app.py`: Streamlit code for the web app
- `pipe.pkl`: Pickled trained model
- `deliveries.csv` & `matches.csv`: IPL datasets used for training
- `requirements.txt`: Python dependencies

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/bushy-ash/ipl-match-prediction.git
cd ipl-match-prediction
pip install -r requirements.txt
streamlit run app.py

