# Stock-Trading Backtesting and Data Analysis

### Develop profitable asset allocation portforlio better than traditional All-weather-portfolio

In this project, we developed the asset allocation portforlio in order to secure stable funds after retirement. This project based on Data Mining and Economic statistics.

team: 이태헌, 김희주

## Backtesting
* We downloaded stock trading data and extract close data. Then we analyzed correlation between 5 indexes and profitability & volatility.
* As the purpose of this project is for study, we didn't consider allocation, dividend tax, rebalancing and just focused on the indices close data in traditional all-weather-portfolio.

### 1. Backtest component
1. Standard Deviation
- calcualtion of standard deviation to see the possibility if the portfolio can achieve expected rate of return

2. Sharpe Ratio
- ('return of portfolio' - 'risk-free rate') / (standard deviation of the portfolio’s excess return)
- assumed 'risk-free rate' as 1% interest of Kakao bank saving

### 2. Steps for backtesting 
* Preprocessing & Backtesting using historical data
* Compose new portfolio
* Result Analysis


### Data Sources : [Investing.com](https://www.investing.com/)
   Index 

    Index: SP_Index, Interm_Index, Longterm_Index, Commodity_Index, Gold_Index
    feature : weekly data
    period: 1996.07.01 ~ 2020.06.29(25 years)
    

## Data Analysis

* comparison about rate of cumulative return by asset types

### 1. Traditional Asset Allocation Portfolio
- portfolio_1 : stock 100%
- portfolio_2 : stock 60% + long-term bond 40%
- portfolio_3 : All_Weather : stock 30% + long-term bond 40% + mid-term bond 15% + commidity 7.5% + gold 7.5%

### 2. Trend Analysis about Rate of Cumulative Return by the Portfolios
* Backtest Result for the Traditional All-weather
   - All_weather portfolio doesn't seem to be the best portfolio in terms of investment, since the rate of cumulative return is 170% over the last 25 years even though it's safer than any others. 
   - Therefore, we assumed that it would be valuable to build a new portfolio that is able to make more returns as maintaining the safeness of All_Weather portfolio.
    
### 3. Compose New Portfolio
   - Compose New Portfolios(4 portfolios) based on traditional all-weather portfolio increasing the weight of the assets which are more correlated with SP_500(stock) 

### 4. Trend Analysis about Rate of Cumulative Return by New Portfolios
   - Backtest Result for All-weather portfolio 4

## Conclusion
   - It is found that All-weather portfolio 4 is the best 'assest allocation portfolio' to increase returns with the limited risk of loosing investment. 
