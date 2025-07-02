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

## 📦 requirements.txt

streamlit
numpy

---

## 🔧 Run Locally

```bash
git clone https://github.com/mohann1234/Twitter_Sentiment_Analysis.git
cd Twitter_Sentiment_Analysis
pip install -r requirements.txt
streamlit run app.py

📊 Example Prediction
Input Tweet:
I love this phone! Great battery life.

Output:
😊 Positive (Confidence: 0.93)

Input Tweet:
The product stopped working after one day.

Output:
😞 Negative (Confidence: 0.88)

🚀 Future Enhancements
Add neutral sentiment category

Use TF-IDF or Word2Vec instead of BOW

Improve UI with charts or word clouds

Support batch tweet predictions

Add model training from UI

🛠 Tech Stack
Python

NumPy

Streamlit

Pickle

