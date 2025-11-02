# Programming Assignment 3

Author: Eli Freedman<br>
Course: MSDS 451: Financial Engineering<br>
Date: November 2, 2025

## Overview

This assignment investigates employing a mean-reversion and momentum-based trading strategy for the term project's asset portfolio. The portfolio used for the term project is a consumer staples ETF called $SGCS, consisting of five blue-chip equities in the consumer staples market. Additionally, these trading strategies will be back-tested and benchmarked against the S&P 500.

## Structure

`README.md`: Contains all information required to understand and run this assignment<br>
`requirements.txt`: All Python modules used in this assignment<br>
`programming_assignment_3.ipynb`: Code used to develop the predictive model<br>
`programming_assignment_3.html`: HTML version of the notebook (better viewing)<br>
`programming_assignment_3.pdf`: Research report<br>
`COST.csv`: Historical data of Costco from 2000-2024<br>
`KO.csv`: Historical data of Coca-Cola from 2000-2024<br>
`PEP.csv`: Historical data of PepsiCo from 2000-2024<br>
`PG.csv`: Historical data of Procter & Gamble from 2000-2024<br>
`SPY.csv`: Historical data of the S&P 500 from 2000-2024<br>
`WMT.csv`: Historical data of Walmart from 2000-2024<br>
`test_top5_vs_spy_equity.csv`: Returns of top 5 tuned strategies against S&P 500 in test time frame<br>
`test_top5_vs_spy_summary.csv`: Summary of top 5 tuned strategies against S&P 500 in test time frame<br>
`train_top5_params.csv`: Parameters for top 5 strategies<br>
`train_tuning_results.csv`: All tuning parameters results<br>
`best_strategy_test_cumulative.png`: Graph of top 5 strategies against S&P 500<br>
`best_strategy_test_normalized.png`: Graph of top 5 strategies against S&P 500 normalized<br>
`best_strategy_train_test.png`: Graph of best training and testing strategy returns

## Set Up

1. Ensure you are running Python 3.12 or later. This project was developed using 3.12, so it may not be compatible with previous versions.
2. Create a virtual environment by executing `python -m venv .venv`
3. Enter the virtual environment
4. Download the requirements by executing `pip -r requirements.txt`
5. Run all cells in the `programming_assignment_3.ipynb` notebook

## AI Usage

AI was utilized to assist in the development of several helper functions and bug fixing throughout the `programming_assignment_3.ipynb` notebook.
