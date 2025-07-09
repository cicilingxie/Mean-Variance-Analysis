# Portfolio Frontier Engine

**Portfolio Frontier Engine** is a Python-based analytical tool that models and visualizes the efficient frontier of a two-asset portfolio using historical price data. This prototype focuses on Amazon (AMZN) and Goldman Sachs (GS), offering a framework for evaluating the tradeoff between risk and return across varying portfolio allocations.

## Overview

The project implements a simple form of modern portfolio theory to calculate and visualize how portfolio performance changes based on asset weighting. By computing historical returns and simulating combinations of the two assets, the model produces a minimum-variance frontier—useful for exploring basic principles of portfolio optimization.

## Key Features

- Loads and processes historical monthly price data
- Computes percentage returns for individual assets
- Simulates portfolio returns across a range of weights
- Calculates mean return and standard deviation (risk) for each combination
- Visualizes the efficient frontier
- Saves key figures as static images for external use

## Technical Details

- Language: Python 3
- Libraries: `pandas`, `numpy`, `matplotlib`
- Input: Parquet file containing historical stock data in long format
- Output: Plots showing individual asset prices and the minimum-variance frontier

## Directory Structure


## Future Development

This prototype can be extended to:

- Include more assets and a full covariance matrix
- Introduce constraints or investor preferences
- Visualize the Capital Market Line (CML) or Sharpe ratios
- Convert into an interactive dashboard using Streamlit or Dash

## Author

CiCi Ling-Xie  
Contact: [LinkedIn](https://www.linkedin.com/in/cici-ling-xie) | GitHub: [github.com](https://github.com/)

