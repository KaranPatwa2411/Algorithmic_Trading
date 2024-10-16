
# Algorithmic Trading Machine Learning Quant Strategies

This repository contains three algorithmic trading strategies developed using machine learning techniques. Each project implements a different approach to trading based on historical market data, social media sentiment, and statistical modeling. The goal is to showcase quantitative trading strategies and provide a starting point for further development.

## Project Overview

### Project 1 - Unsupervised Learning Trading Strategy
This project leverages unsupervised learning techniques such as clustering to identify patterns in financial market data. By grouping similar days or market conditions together, the strategy aims to discover hidden trading opportunities without relying on labeled data.

### Project 2 - Twitter Sentiment Trading Strategy
In this project, Twitter sentiment analysis is employed to gauge public opinion on certain stocks or the broader market. Using sentiment scores derived from Twitter data, the trading strategy aims to predict market movements and make informed buy or sell decisions.

### Project 3 - Intraday GARCH Trading Strategy
This project focuses on intraday trading using the Generalized Autoregressive Conditional Heteroskedasticity (GARCH) model. The GARCH model helps in forecasting market volatility, which is crucial for adjusting trading positions dynamically to minimize risk and optimize returns.

## Repository Structure

- `Algorithmic_Trading_Machine_Learning_Quant_Strategies.ipynb`: Main Jupyter notebook containing the code and analysis for all three projects.
- `README.md`: This file, providing an overview of the projects and instructions for setup.
- `sentiment_data.csv`: This file is for first project.
- `simulated_5min_data.csv`: This file is for second project.
- `simulated_daily_data`: This file is for third project.

## Getting Started

### Prerequisites

Make sure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `scikit-learn`
- `statsmodels`
- `matplotlib`
- `seaborn`
- `nltk` (for sentiment analysis)



### Running the Projects

Open the Jupyter notebook file (`Algorithmic_Trading_Machine_Learning_Quant_Strategies.ipynb`) and follow the instructions in each section to execute the code for each project. Make sure to load the appropriate data files in the `data/` directory.

## Results

- **Project 1**: The clusters identified from historical data can be used to understand market regimes and predict future movements.
- **Project 2**: Sentiment scores derived from Twitter data show correlations with market trends, providing a potential edge in trading.
- **Project 3**: The GARCH model effectively forecasts market volatility, allowing for adaptive trading strategies.

---

Let me know if you need more specific details or any adjustments based on the actual content of the notebook.
