# Stock-Trading Backtesting and Data Analysis

### Develop profitable asset allocation portforlio better than traditional All-weather portfolio

In this project, we developed the asset allocation portforlio in order to secure stable funds after retirement. This project based on Data Mining and Economic statistics.

team: 이태헌, 김희주

### Backtesting
* We downloaded stock trading data and extract close data. Then we analyzed correlation between 5 indexes and profitability & volatility.

#### Steps for backtesting 
* Define strategy
* Back Test using historical data
* Result Analysis
* Develop portfolio based on analysis
* Compare profitability,volatility prediction


### Data Sources : [Investing.com](https://www.investing.com/)
Index 

    Index: SP_Index, Interm_Index, Longterm_Index, Commodity_Index, Gold_Index
    feature : weekly data
    period: 1996.07.01 ~ 2020.06.29(25 years)
    
ETF    

    ETF: SPY, IEF, TLT, DBC, GLD
    feature: weakly data
    period: 2006.06.26 ~ 2020.06.29(15 years)
    
### Define a Problem
* High Relative Poverty Rate for the Elderly in Korea
![1](https://user-images.githubusercontent.com/68367134/97185204-20308d80-17e3-11eb-80ba-af56ae278924.png)


## Data Processing

* comparison about rate of cumulative return by asset types
![Screen Shot 2020-10-26 at 23 34 28](https://user-images.githubusercontent.com/68367134/97185701-bbc1fe00-17e3-11eb-9d31-46d8ad0e3895.png)


### Portfolio
- portfolio_1 : stock 100%
- portfolio_2 : stock 60% + long-term bond 40%
- portfolio_3 : All_Weather : stock 30% + long-term bond 40% + mid-term bond 15% + commidity 7.5% + gold 7.5%
![Screen Shot 2020-10-26 at 23 36 33](https://user-images.githubusercontent.com/68367134/97185929-06dc1100-17e4-11eb-95c9-7f75cdcb5d45.png)



#### Trend Analysis about Rate of Cumulative Return by the Portfolios
![Screen Shot 2020-10-26 at 23 38 41](https://user-images.githubusercontent.com/68367134/97186200-57536e80-17e4-11eb-955e-f9ee4a33291c.png)
![Screen Shot 2020-10-26 at 23 38 47](https://user-images.githubusercontent.com/68367134/97186205-58849b80-17e4-11eb-9c49-d2c82c3f3c60.png)
    
    * Backtest Result
    - All_weather portfolio doesn't seem to be the best portfolio in terms of investment, since the rate of cumulative return is 170% over the last 25 years even though it's safer than any others. 
    - Therefore, we think that it would be valuable to build a new portfolio that is able to make more returns as maintaining the safeness of All_Weather portfolio.

### New Portfolio
- increasing the weight of the assets which are more correlated with SP_500(stock) 

* correlation matrix 

