# Stock Price, Volatility, and Sentiment Prediction Using Machine Learning

This project is part of the **CISC 5800: Machine Learning** course under Prof. Juntao Chen.  
It aims to predict stock price direction and volatility using both historical market data and sentiment derived from financial news.

---

## 🧠 Objectives
- Predict next-day stock price direction (Up/Down) using Logistic Regression, SVM, and Neural Networks.
- Forecast rolling 20-day volatility using regression models.
- Compare feature contributions between technical indicators and sentiment metrics.

---

## 📊 Data Sources
- [Yahoo Finance](https://finance.yahoo.com) – Stock data (AAPL, TSLA, MSFT).
- [Kaggle: Stock Market News Sentiment](https://www.kaggle.com/datasets/yusufali9/stock-market-news-sentiments).
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/).

---

## ⚙️ Technologies Used
- **Python 3.10+**
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `nltk`, `yfinance`, `plotly`

---

## 🧩 Project Workflow
1. Data collection via `yfinance` and Kaggle datasets.
2. Feature engineering: RSI, EMA, MACD, Bollinger Bands, and sentiment features.
3. PCA for dimensionality reduction.
4. Model training and comparison (LogReg, SVM, NN).
5. Visualization of results and feature importance.

---

## 📅 Timeline
| Phase | Dates | Deliverable |
|-------|-------|-------------|
| Data + EDA | Nov 3–9 | Cleaned datasets, trend plots |
| Modeling | Nov 10–23 | Trained models, evaluation metrics |
| Reporting | Nov 24–Dec 8 | Final report + visuals |
| Submission | Dec 15 | Presentation & GitHub repo |

---

## 📈 Visuals
Include:
- Correlation heatmaps  
- PCA scatter plots  
- ROC curves and confusion matrices  
- Predicted vs actual price trend lines

---

## 👨‍💻 Author
**Aryan Varmora**  
