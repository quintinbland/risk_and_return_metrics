# Risk and Return of Large Fund Portfolios

This program provides quantatative and visual analysis on large fund portfolios with the S&P 500. Analysis covers: performance, volatility, risk, risk-return profile and porfolio diversification. The analysis will be used to determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For DataFrame construction and data sorting.

* [%matplotlib](https://github.com/matplotlib/matplotlib) - For data vizualization.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install pandas
  pip install %matplotlib
```

---

## Analysis

* Performance Analysis:
    - Based on the cumulative return data and the visualization, do any of the four fund portfolios outperform the S&P 500 Index?
        - None of the fund portfolios outperform the S&P 500 Index during this time period.
* Volatility Analysis:
     - Based on the box plot visualization of just the four fund portfolios, which fund was the most volatile (with the greatest spread) and which was the least volatile (with the smallest spread)?
        - According to the box plot, the most volatile fund is Berkshire Hathway, conversely, Pauslon & CO. INC was the least volatile over the time period.
* Risk Analysis:
    * Based on the annualized standard deviation, which portfolios pose more risk than the S&P 500?
        - Based on annualized standard deviation, none of the portfolios are more risky than the S&P 500.

    * Based on the rolling metrics, does the risk of each portfolio increase at the same time that the risk of the S&P 500 increases?
        - In this given time period, the risk of each portfolio generally increases when the risk is increasing for the S&P 500 as well.

    * Based on the rolling standard deviations of only the four fund portfolios, which portfolio poses the most risk? Does this change over time?
        - At the begining of 2015, Soros Fund Management was the most risky portfolio. Towards the end of 2015, Tiger Global was briefly the most risky of the 4 portfolios. Ultimately, Berkshire Hathaway emerges as the most risk fund during this time period.

* Analyze the Risk-Return Profile:
    * Which of the four portfolios offers the best risk-return profile? Which offers the worst?
        - Berkshire Hathaway offers the highest Sharpe Ratio and therefore the best risk-return profile. SOROS Fund Management offers the worst risk-return profile. 
        
* Diversify the Portfolio
    * Which of the two portfolios seem more sensitive to movements in the S&P 500?
        -  Berkshire has a higher average beta indicating it is more sensitive to movements in the S&P.

    * Which of the two portfolios do you recommend for inclusion in your firm’s suite of fund offerings? 
        - I recommend Berkshire for inclusoin because it presents the highest and most attractive risk to return(Sharpe) ratio. 
---

## Contributors


*  **Quintin Bland** <span>&nbsp;&nbsp;</span> |
<span>&nbsp;&nbsp;</span> *email:* quintinbland2@gmail.com <span>&nbsp;&nbsp;</span>|
<span>&nbsp;&nbsp;</span> <a href="https://www.linkedin.com/in/quintin-bland-a2b94310b/"><img src="https://img.shields.io/badge/-Quintin_Bland-0077B5?style=flat-square&logo=Linkedin&logoColor=white"/></a> 

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
