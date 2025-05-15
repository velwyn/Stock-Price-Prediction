 Stock Price Prediction using Linear Regression

This project aims to predict the **closing price** of Apple Inc. (AAPL) stock using historical stock market data and a **Linear Regression model**. It's a basic machine learning regression task built with Python and Jupyter Notebook.



 Project Structure

- `Stock_Price_Prediction_Project.ipynb`: Main notebook with all code and analysis
- `README.md`: Project documentation (you’re reading it)
- Optional: Project report in `.docx` or presentation in `.pptx`



 Problem Statement

Stock prices change daily and are influenced by multiple factors. Investors need reliable tools to help **predict future prices**. This project demonstrates how historical data can be used to forecast stock prices using **supervised learning (regression)**.



The solution involves:
- Fetching real-time stock data using the `yfinance` API
- Cleaning and analyzing the data
- Creating a correlation heatmap
- Training a **Linear Regression** model
- Evaluating the model using **MSE** and **R² Score**
- Plotting **actual vs predicted prices**

 Technologies & Libraries

- Python
- Jupyter Notebook / Google Colab
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `yfinance` (for downloading stock data)

 Data Used

- Source: Yahoo Finance
- Stock: Apple Inc. (AAPL)
- Date Range: January 2020 – December 2024
- Features: `Open`, `High`, `Low`, `Volume`
- Target: `Close`

 How to Run

 Option 1: Google Colab
1. Open the notebook in [Google Colab](https://colab.research.google.com)
2. Run each cell step-by-step
3. View predictions and plots

Option 2: Local Jupyter Notebook
```bash
pip install yfinance pandas numpy matplotlib seaborn scikit-learn

Results

Mean Squared Error (MSE): 1.1321429168327077
R² Score: 0.9993541074730083

The scatter plot clearly shows a good match between actual and predicted values.

 Conclusion
This project shows how simple linear regression can help predict financial data trends. It’s a great start for understanding how machine learning is used in finance.

 Future Scope
Adding technical indicators like Moving Average or RSI
Try advanced models: Random Forest, XGBoost, LSTM
Deploy on Streamlit for real-time use

 References

Yahoo Finance API
scikit-learn Documentation
Pandas Library
Google Colab



