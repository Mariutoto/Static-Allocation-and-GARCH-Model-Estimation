# Empirical Methods in Finance - Project 2 (Group 11)

## Project Overview
This project focuses on applying empirical finance methods to real-world financial datasets. The main topics covered include:

1. **Static Allocation**: Maximizing portfolio allocation based on different levels of risk aversion.
2. **GARCH Model Estimation**: Modeling the volatility of financial assets and analyzing excess returns.
3. **Dynamic Allocation**: Exploring time-varying portfolio weights and cumulative returns.
4. **Value at Risk (VaR) Calculation**: Computing the Value at Risk using various models, including GARCH and Generalized Extreme Value (GEV) models.

## Files
- `Project2-EMF-Group11.ipynb`: The main Jupyter notebook containing code and analysis.
- `Project2-EMF-Group11.xlsx`: Excel file with financial data used for analysis.
- `Project2-EMF-Group11.pdf`: The project report documenting the methods, results, and conclusions.

## Main Topics Covered
1. **Static Allocation**:
   - Portfolio allocation with different levels of risk aversion.
   
2. **GARCH Model Estimation**:
   - Estimation of volatility using the GARCH(1,1) model.
   - Analysis of the autoregressive behavior of financial returns.

3. **Dynamic Portfolio Allocation**:
   - Time-varying portfolio weights based on mean-variance optimization.

4. **Value at Risk (VaR)**:
   - Calculation of unconditional VaR.
   - Implementation of AR1-GARCH(1,1) and GEV models for conditional VaR estimation.

## How to Run the Project
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/Project2-EMF-Group11.git
    ```
2. Open the Jupyter notebook `Project2-EMF-Group11.ipynb` to explore the code and results.
3. Ensure you have all necessary Python libraries installed. You can install the dependencies using:
    ```bash
    pip install -r requirements.txt
    ```

## Key Insights
- **Portfolio Optimization**: The optimal weights shift depending on risk aversion levels, demonstrating how different levels of risk tolerance affect investment strategies.
- **GARCH Models**: Volatility clustering is evident, with past shocks influencing current volatility.
- **Dynamic Allocation**: Dynamic portfolios significantly outperform static ones, though they involve higher risk.
- **VaR Models**: The GEV model provides a more accurate measure of risk by focusing on extreme values.

