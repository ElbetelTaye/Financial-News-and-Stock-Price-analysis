# Financial-News-and-Stock-Price-analysis
## Overview

This project explores the relationship between financial news sentiment and stock market movements. By analyzing a large dataset of financial news articles and stock prices, we aim to uncover how sentiment from news headlines correlates with stock price changes. This project is divided into three main tasks:

- Descriptive analysis of financial news data - Analyzing headline lengths, publication trends, and sentiment distributions.
- Stock data analysis - Performing technical analysis on stock data.
- Correlation analysis between news sentiment and stock prices - Aligning news and stock price data by dates and analyzing sentiment's impact on stock returns.

### Datasets

The project uses two primary datasets:

Financial News Dataset: Contains headlines, URLs, publishers, publication dates, and stock ticker symbols.
Stock Market Dataset: Contains daily stock prices, including Open, High, Low, Close, Volume, Dividends, and Stock Splits data for seven companies.

### Tools and Libraries
- Python: Main programming language used for analysis.
- Pandas: For data manipulation and preparation.
- Matplotlib & Seaborn: For data visualization.
- TA-Lib: For performing technical analysis on stock data.
- VADER Sentiment Analysis: For analyzing the sentiment of news headlines.
- LDA (Latent Dirichlet Allocation): For topic modeling of news headlines.
- yfinance: For fetching historical stock price data.

## Project Structure

The repository is structured as follows:

```
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       └── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
│   └── __init__.py
├── notebooks/
│   ├── __init__.py
│   ├── Task1.ipynb
│   ├── Task2.ipynb
│   ├── Task3.ipynb
│   └── README.md
├── tests/
│   └── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md
```

## Setup and Installation

To run the notebooks locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ElbetelTaye/Financial-News-and-Stock-Price-analysis.git
   ```

2. **Navigate to the repository**:
   ```bash
   cd your-repository-name
   ```

3. **Set up the Python environment**:
   - It is recommended to use a virtual environment for the project. Run the following commands to set up and activate it:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`
     ```

4. **Install the required packages**:
   - Install the necessary packages listed in the `requirements.txt` file (if available):
     ```bash
     pip install -r requirements.txt
     ```

5. **Launch Jupyter Notebook**:
   - Start Jupyter Notebook to access and run the notebooks:
     ```bash
     jupyter notebook
     ```

6. **Open the Notebook**:
   - Once Jupyter Notebook is launched, open the Task1 notebook to run it interactively.

### Usage

The project is divided into several Jupyter notebooks and scripts for different tasks:

#### Task 1: News Dataset Analysis:

- Explore the distribution of headline lengths, analyze trends in publication dates, perform sentiment analysis, and extract topics from the news dataset.
- Open and run notebooks/Task1_Analysis.ipynb.

#### Task 2: Stock Data Analysis:

- Perform technical analysis on stock prices, including calculating moving averages, RSI, MACD, and volatility.
- Open and run notebooks/Task2_Analysis.ipynb.

#### Task 3: Sentiment and Stock Price Correlation Analysis:

- Align the news and stock price datasets, analyze the correlation between sentiment and stock returns, and visualize the results.
- Open and run notebooks/Task3_Analysis.ipynb.

### Results

- Sentiment Distribution: The majority of news articles tend to have neutral sentiment, with fewer articles expressing extreme positive or negative sentiment.
- Stock Technical Analysis: Technical indicators like moving averages, RSI, and MACD were computed to assess stock trends and potential trading signals.
- Correlation Analysis: A weak positive correlation was observed between news sentiment and stock closing prices, indicating that while sentiment may have an effect, it is not the primary driver of stock price movements.

### Conclusion

The analysis showed that there is a weak positive relationship between financial news sentiment and stock prices. While sentiment does have some effect, the correlation is not strong, suggesting that other factors also play significant roles in stock price movements.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
