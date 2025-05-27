# EPS Surprise Enhanced Momentum Strategy

## Project Overview
This project stems from our participation in the **McGill-FIAM Asset Management Hackathon**, where our team, **"Montreal McGilleans"**, achieved **4th place** out of more than 70 teams. 
The hackathon brought together experts in **Finance** and **Data Science** to bridge the gap between these disciplines and create cutting-edge asset management strategies.

Our project, the **All-Weather Fundamental Surprise Enhanced Momentum Strategy**, leverages a combination of **Hidden Markov Model (HMM)** regime detection and **Random Forest** 
for portfolio construction. By incorporating **Artificial Intelligence (AI)**, we significantly boosted predictive performance, resulting in a strategy that stands out for its innovation, 
effective risk management, and scalability for institutional use.

This repository details the methodology, implementation, and evaluation of our strategy, highlighting its potential as a scalable solution for real-world asset management.

---

## Features of the Project
- **Enhanced Momentum**: Combines traditional momentum factors with **EPS surprises** to improve stock selection.
- **Economic Regime Detection**: Utilizes HMM to classify Bull and Bear markets, tailoring strategies accordingly.
- **Comprehensive Evaluation**: Includes metrics such as Sharpe ratio, alpha, drawdowns, and turnover for robust performance analysis.
- **Benchmark Comparison**: Evaluates strategy performance against the S&P 500 index and a momentum-only portfolio.
- **Scalability**: Designed to be adaptable for institutional-level portfolio management.

---

## Dataset Description
1. **Primary Data**: 
   - Historical stock returns, financial metrics (e.g., EPS surprises, momentum indicators, risk-free rates), and S&P 500 index data.
2. **Key Variables**:
   - `ret_12_1`: 12-month momentum factor.
   - `stock_exret`: Stock excess return.
   - `rf`: Risk-free rate.
   - `diff`: EPS surprise normalized by stock price.
   - `ni_be`: Net income to book equity ratio.
3. **Time Period**:
   - Data spans from January 2010 to December 2023.

---

## Methodology
1. **Regime Detection**:
   - Applied **Hidden Markov Models (HMM)** to classify market conditions into Bull and Bear regimes.
2. **Portfolio Construction**:
   - Combined traditional momentum signals with **EPS surprises** for stock selection.
   - Adapted stock weighting based on market regimes.
3. **AI Integration**:
   - Implemented **Random Forest** for enhanced predictive performance using Lighting AI to hypertune parameters.
4. **Risk Management**:
   - Incorporated tracking error and position limits to manage risks effectively.
5. **Evaluation**:
   - Benchmarked against traditional momentum-only strategies and the S&P 500.

---

## Modeling
1. **Hidden Markov Models**:
   - Used for dynamic regime detection, guiding portfolio strategy during Bull and Bear markets.
2. **Random Forest**:
   - Enhanced stock selection through EPS-based predictions.
3. **Key Metrics**:
   - Sharpe ratio, alpha, beta, information ratio, drawdowns, and turnover.
4. **Visualization**:
   - Comparative plots of cumulative returns across strategies and benchmarks.

---

## Key Results
- **Hackathon Achievement**:
   - **4th place out of 70+ teams** at the **McGill-FIAM Asset Management Hackathon**.
- **Innovative Strategy**:
   - Recognized for the innovative use of **AI and ML** to improve predictive accuracy and adaptability.
   - Factor based strategy to determine portafolio positions instead of traditional price predictions. 
- **Superior Risk-Adjusted Returns**:
   - Achieved a higher Sharpe ratio compared to the momentum-only strategy and S&P 500.
- **Alpha Generation**:
   - Significant annualized alpha, demonstrating the strategy's ability to generate excess returns.
- **Scalability**:
   - Strategy evaluated as scalable for institutional-level asset management.

---

## Future Improvements
1. **Factor Expansion**:
   - Incorporate additional factors such as volatility, liquidity, and sector-specific metrics.
2. **Advanced Regime Modeling**:
   - Explore probabilistic regime transitions for smoother adjustments using AI models.
3. **Real-World Testing**:
   - Integrate transaction costs, slippage, and real-world constraints into the backtesting framework.
4. **Dynamic Factor Weighting**:
   - Develop adaptive weighting based on macroeconomic indicators and market sentiment.
5. **Broader Applicability**:
   - Test scalability across different asset classes (e.g., bonds, ETFs).

---

## Acknowledgments
Special thanks to our incredible team:
- **Florentin Belfio**
- **Heng Tang**
- **Rick Yabuki-Soh**
- **Yash Sethi**

---

## Getting Started
1. **Dependencies**:
   - Python 3.8+
   - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `yfinance`.

2. **Usage**:
   - Clone the repository:
     ```bash
     git clone https://github.com/your-username/eps-surprise-momentum-strategy.git
     ```
   - Run the Jupyter Notebook for data processing, modeling, and visualization.

---

## Contact
For questions or collaboration opportunities, please reach out to:
- **Name**: Arturo Medina
- **LinkedIn**: [linkedin.com/in/arturo-medina/]
