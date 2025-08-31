1) The code in first cell will generate buy and sell signals for 16 tickers. These signals are based on signal strength. Factors considered are Z score, Kurtosis, Skew, Adf and Volume. Weightages are assigned for each tickers, to calculate the signal strength. It generates ticker_specific_signals_LLM.csv file
2) The code in 2nd cell will backtest these signals and generated a portfolio summary sheet i.e strict_position_trades
3) RAG approach is applied to analyze the portfolio summary file. The RAG report is saved in a json file i.e backtest_rag_analysis
