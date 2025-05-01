# Optimizing Portfolio Risk of Cryptocurrencies Using Data-Driven Risk Measures

For successful investments, risk management is crucial. Common risk measures in portfolio optimization include the standard deviation of portfolio returns, expected shortfall, and mean absolute deviation. 
Traditional approaches assume that data are normally distributed, leading to an underestimation of risk when incorporating volatile assets such as cryptocurrencies.
In this work, data-driven kurtosis-based risk measures and their superiority over traditional methods are demonstrated using portfolios with high-frequency stocks and cryptocurrency price data.

The PDF copy of the paper can be downloaded from here: [Download Paper](https://www.mdpi.com/1911-8074/15/10/427)

### Methodology

The assumption of normality in returns often leads to the underestimation of risk, and most financial return distributions exhibit excess kurtosis and skewness.
In order to address these limitations, a data-driven risk measure incorporating larger skewness and kurtosis is used to obtain optimal portfolio weights.

Following the class of unbiased estimating functions (EFs) in the form $g = g_1 + Cg_2$ and considering estimating functions $R_P - \mu_p$ and $\text{sign} (R_P - \mu_p)$, 
where $R_p$ is portfolio simple returns and $\mu_p$ is portfolio expected return, the estimated portfolio risk using sign correlation, denoted by VES (volatility estimate using sign correlation), is given by
$$
\text{VES}_{P} = \hat{\sigma}_{P}\sqrt{1 - \hat{\rho}_{P, sign}^2},
$$
where $\hat{\rho}_{P, sign} = \text{Corr} (R_P - \bar{R}_P,\, \text{sign} (R_P - \bar{R}_P))$, $\bar{R}_P$ is estimate of portfolio expected return, and $\hat{\sigma}_{P}$ is the estimate of portfolio volatility (standard deviation of portfolio returns).

### Findings

A kurtosis-dependent risk measure is developed using combined estimating function theory, allowing direct calculation of portfolio risk without requiring inversion of the covariance matrix. The novel risk measure is applied to portfolios constructed from high-frequency cryptocurrency data. 
Results demonstrate that the data-driven portfolio optimization method outperforms (larger Sharpe ratios) minimum variance and tangency portfolios.

