# 💬 Twitter Sentiment Analysis

A simple machine learning project that predicts whether a tweet is **positive** or **negative**, using a custom logistic regression model built from scratch with **NumPy**.

---

## 🧠 How It Works

- Preprocesses and cleans tweets (lowercase, remove links, etc.)
- Converts text into Bag-of-Words vectors
- Trains a logistic regression model manually
- Wraps model using Python class and saves as `model.pkl`
- User can enter a tweet and get a predicted sentiment

---

## 📁 Project Structure

Twitter_Sentiment_Analysis/
├── app.py # App logic for prediction (Streamlit UI)
├── model.pkl # Saved model (weights + vocab)
├── requirements.txt # Python dependencies
└── README.md # This file

