# NASDAQ Merger Analysis Tool

The NASDAQ Merger Analysis Tool evaluates potential mergers between NASDAQ-listed companies by analyzing market capitalization and stock trends. It leverages live financial data, performs trend analysis, and provides clear merger decisions with visualized stock performance.

## Key Features

- **Market Cap Analysis**: Automatically fetches and compares the market capitalizations of two companies.
- **Stock Price Trend Analysis**: Uses historical stock prices to analyze trends using linear regression.
- **Decision Support**: Provides a clear recommendation on whether the merger is favorable based on financial data.
- **Visualization**: Plots historical stock prices for visual comparison.
- **Ease of Use**: Simple input prompts for users to analyze any two NASDAQ-listed companies.

## Use Cases

- **Corporate M&A Teams**: Evaluate potential mergers and acquisitions.
- **Investors and Analysts**: Gain insights into the financial compatibility of two companies.
- **Business Strategists**: Understand market trends and data-driven merger opportunities.

---

## Overview

The NASDAQ Merger Analysis Tool is a Python script designed to evaluate the financial impact of a potential merger between two NASDAQ-listed companies. It provides a detailed analysis of market capitalization, stock price trends, and offers a clear merger decision based on the data.

This tool leverages Yahoo Finance for live data, performs time-series analysis using linear regression, and plots historical stock price trends for better visualization and decision-making.

## Features

- **Market Cap Evaluation**: Compares the market capitalizations of two companies to assess their relative sizes.
- **Stock Price Analysis**: Analyzes stock price trends over the past year using linear regression to identify positive or negative growth trends.
- **Merger Decision Support**: Provides a clear recommendation on the favorability of the merger based on market cap contributions and stock trends.
- **Data Visualization**: Plots historical stock prices to show trends and correlations visually.

## Requirements

- Python 3.7+
- Libraries:
  - `yfinance`
  - `pandas`
  - `matplotlib`
  - `scipy`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nasdaq-merger-analysis-tool.git
   cd nasdaq-merger-analysis-tool
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the script:
   ```bash
   python nasdaq_merger_analysis.py
   ```
2. Enter the tickers of two NASDAQ-listed companies when prompted (e.g., `AAPL` and `MSFT`).
3. View the detailed analysis of market cap, stock trends, and merger decision in the console.
4. Visualize the stock price trends in the plotted chart.

## Example

Input:

```
Enter the ticker of the first company (e.g., AAPL): AAPL
Enter the ticker of the second company (e.g., MSFT): MSFT
```

Output:

```
Market Cap of AAPL: $2,800,000,000,000.00
Market Cap of MSFT: $2,400,000,000,000.00
Combined Market Cap (Post-Merger): $5,200,000,000,000.00

Stock Price Trend Analysis:
AAPL: Slope = 1.20, R² = 0.85
MSFT: Slope = 1.50, R² = 0.90

Merger Decision:
Both companies show positive stock trends. Merger may be favorable.
```

## Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or suggestions, please contact [rishavsofer](mailto\:rishavlincoln@gmail.com) or open an issue on GitHub.

