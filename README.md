# eXpender

## Goal
- Auto-categorize bank/transaction CSVs (e.g., Food, Transport, Groceries).
- Show insights: monthly trends, category breakdowns, anomalies, budgets.
- Hybrid approach: rules + ML (TF-IDF + Logistic Regression/MultinomialNB).
- Deployed as a Streamlit web app.

## Tech Stack
- **Python**: pandas, scikit-learn, numpy, joblib
- **NLP**: nltk (light text cleaning)
- **App**: Streamlit + Plotly
- **(Optional)**: imbalanced-learn, scipy

## High-Level Plan (30 Days)
- W1: Data loading, rules baseline
- W2: TF-IDF classifier + eval
- W3: Insights dashboard, anomalies, feedback
- W4: Retraining, deploy, docs
