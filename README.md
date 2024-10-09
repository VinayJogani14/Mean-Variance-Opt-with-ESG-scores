# Mean-Variance-Optimization-with-ESG-scores

The project implements a **Mean-Variance Optimization** model to construct an **ESG-optimized portfolio**, while considering both financial returns and ESG (Environmental, Social, Governance) scores as constraints. The primary projection centers around identifying an optimal portfolio that balances traditional return metrics with sustainability performance.

The projection methodology used can be broken down into a few components:

1. **Portfolio Construction and ESG Constraints**:
   - The objective is to optimize the portfolio using the classic mean-variance approach, but with an added layer of ESG screening. Each stock is assessed based on its ESG score, and the portfolio is constrained to include only those securities that meet predefined sustainability criteria. This projection method aims to select assets that do not just maximize returns but also have an above-average contribution to sustainability.

2. **Optimization Process**:
   - By employing **constrained quadratic programming** through Python’s `SciPy` optimization library, the model determines the optimal weights for each asset. The objective function maximizes the Sharpe Ratio, balancing return against risk while staying within the risk tolerance and ESG boundary conditions. This projection simulates the portfolio's efficiency frontier in both the ESG and financial performance dimensions.

3. **Backtesting and Benchmark Projection**:
   - The projection also includes a backtesting phase that assesses the historical performance of the optimized ESG portfolio against a well-known benchmark—**the S&P 500**. This involves projecting the ESG-optimized portfolio’s performance over a specific period and comparing it with the benchmark's returns and risk metrics, thereby offering insights into the relative viability and competitiveness of the ESG strategy.

4. **Visualization**:
   - To effectively communicate results, the backtested projections are visualized using Matplotlib. The resulting plots showcase the relative performance between the ESG portfolio and the benchmark, including metrics such as portfolio value growth, volatility, and cumulative returns. These projections are crucial for analyzing the risk-adjusted return and understanding whether prioritizing ESG scores results in a significant divergence from traditional financial benchmarks.

