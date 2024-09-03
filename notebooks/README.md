# Financial-News-and-Stock-Price-analysis
## Overview

The project involves analyzing a large corpus of financial news data to discover correlations between news sentiment and stock market movements. The goal is to understand how news sentiment affects stock prices and to identify significant trends and events. The analysis involves a rigorous sentimental and correlation analysis of the financial news dataset.

### Notebooks:
1. **Task1: Descriptive Statics, Text analysis (Sentiment analysis & Topic Modeling), Time Series Analysis, Publisher Analysis**
2. **Task2: Quantitative analysis using pynance and TaLib**
3. **Task3: Correlation analysis**

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


## Notebooks

This notebook covers:
### Task1
1. **Descriptive Statistics:**
   - Obtain basic statistics for textual lengths (like headline length).
   - Count the number of articles per publisher to identify the most active publishers.
   - Analyze the publication dates to identify trends over time, such as increased news frequency on particular days or during specific events.

2. **Text Analysis (Sentiment Analysis & Topic Modeling):**
   - Perform sentiment analysis on headlines to gauge the sentiment (positive, negative, neutral) associated with the news.
   - Use natural language processing (NLP) to identify common keywords or phrases, potentially extracting topics or significant events (like "FDA approval," "price target," etc.).

3. **Time Series Analysis:**
   - Analyze publication frequency over time.
   - Check for spikes in article publications related to specific market events.
   - Examine the alignment of news data with stock price data by normalizing timestamps.

4. **Publisher Analysis:**
   - Identify which publishers contribute most to the news feed and examine the differences in the type of news they report.
   - Identify unique domains to see if certain organizations contribute more frequently.

### Task2

This notebook covers:

- **Quantitative Analysis Using TA-Lib:**
   - Calculation of financial metrics such as EMA (Exponential Moving Average), SMA (Simple Moving Average), MA (Moving Average), MACD (Moving Average Convergence Divergence), volatility, and RSI (Relative Strength Index).
   - Visualization of these indicators to better understand their impact on stock prices.

### Task3

This notebook covers:

- **Correlation Analysis:**
   - Establishing statistical correlations between the sentiment derived from news articles and the corresponding stock price movements.
   - Tracking stock price changes around the publication date of news articles and analyzing the impact of news sentiment on stock performance.
   - Performing lagged correlation analysis to assess the impact of news sentiment over multiple days.
   - Visual representation of correlation results to highlight key relationships.

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
   - Once Jupyter Notebook is launched, open the respective file (eg. Task1) notebook to run it interactively.

## Results

The analysis results include:

- **Descriptive Statistics:** Overview of headline lengths, article counts per publisher, and publication trends.
- **Text Analysis:** Sentiment analysis results and key topics or phrases extracted from headlines.
- **Time Series Analysis:** Insights into publication frequency trends and alignment with stock price data.
- **Publisher Analysis:** Contributions of different publishers and their focus areas.
- **Quantitative Analysis:** Technical indicators calculated using TA-Lib and their impact on stock prices.
- **Correlation Analysis:** Statistical correlations between news sentiment and stock price movements, including lagged effects.


## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
