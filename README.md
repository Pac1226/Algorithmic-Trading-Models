# Algorithmic Trading Bots | Machine Learning Models

This is the beta version of an algorthmic trading model. The program connects to the YFinance API and pulls price data for any ticker symbol. It utilizes a linear regression parallel channel to create buy/sell signals and applies a series of machine learning algorithms to optimize returns.

* Logistic Regression
* Random Forest Classification
* Support Vector Machine (SVM)

---

## Technologies

```python
The program uses Pandas, NumPy, Scikit-learn, Pathlib, FinancialAnalysis libraries. 
```

---

## Results

The algorithmic trading model was backtested with 25 stocks and outperformed a buy/hold strategy by 141%. The algorithm bought a stock when its price dropped below the long-term trendline and sold it when the price rose above it. The buy/sell signals can be changed to optimize returns.

The algorithm yielded an average return of 41% across the 25 stocks over a one year period. A buy/hold strategy would've returned -12%. A major caveat is that the algorithm has the benefit of hindsight. It makes buy/sell recommendations knowing the long-term trend ahead of time. 

Returns were optimized by applying the Logistic Regression, Random Forest Classification, and Support Vector Machine algorithms. They all failed to outpeform the human-designed trading bot, but often outperformed the buy/hold strategy. Testing new data inputs need to be done.

The following results are from 05/01/21 to 05/16/22.

![Stock Performance](images/stock_performance.png)

![Sector Performance](images/sector_performance.png)
