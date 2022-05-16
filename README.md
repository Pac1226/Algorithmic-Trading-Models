# Algorithmic Trading Bots | Machine Learning Models

This is a machine learning template that can be adapted to build unique algorithmic trading bots. 

It aggregates data from any three sources and prepares the data using "Train, Test, Split", "RandomOversampler", and "StandardScaler." 

Finally it runs the cleaned data through three (3) machine learning models:

* Logistic Regression
* Random Forest Classification
* Support Vector Machine (SVM)


---

## Technologies

```python
The program uses Pandas, NumPy, Scikit-learn, pathlib 
```

---

## Usage

The current template uses cumulative returns data pulled from the Alpaca API for SPY, QQQ, and ARKK. This data is used as a placeholder. Users are meant to feed desired data through the model to build a customized trading bot for crypto, equities, or commodities.
