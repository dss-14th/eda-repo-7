# Stock-Trading Backtesting and Data Analysis

### Develop profitable asset allocation portforlio better than traditional All-weather-portfolio
#### Is All-weather-portfolio the only and the best ? 

In this project, we developed the asset allocation portforlio in order to secure stable funds after retirement. This project based on Data Mining and Economic statistics.

team: 이태헌, 김희주

### Backtesting
* We downloaded stock trading data and extract close data. Then we analyzed correlation between 5 indexes and profitability & volatility.
* As the purpose of this project is for study, we didn't consider allocation, dividend tax, rebalancing and just focused on the indices close data in traditional all-weather-portfolio.

### Backtest component
1. Standard Deviation
- calcualtion of standard deviation to see the possibility if the portfolio can achieve expected rate of return

2. Sharpe Ratio
- ('return of portfolio' - 'risk-free rate') / (standard deviation of the portfolio’s excess return)
- assumed 'risk-free rate' as 1% interest of Kakao bank saving

### Steps for backtesting 
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
![Screen Shot 2020-10-26 at 23 34 28](https://user-images.githubusercontent.com/68367134/97185701-bbc1fe00-17e3-11eb-9d31-46d8ad0e3895.png)


### Traditional Asset Allocation Portfolio
- portfolio_1 : stock 100%
- portfolio_2 : stock 60% + long-term bond 40%
- portfolio_3 : All_Weather : stock 30% + long-term bond 40% + mid-term bond 15% + commidity 7.5% + gold 7.5%
![Screen Shot 2020-10-26 at 23 36 33](https://user-images.githubusercontent.com/68367134/97185929-06dc1100-17e4-11eb-95c9-7f75cdcb5d45.png)


### Trend Analysis about Rate of Cumulative Return by the Portfolios
* Backtest Result for the Traditional All-weather
- All_weather portfolio doesn't seem to be the best portfolio in terms of investment, since the rate of cumulative return is 170% over the last 25 years even though it's safer than any others. 
- Therefore, we assumed that it would be valuable to build a new portfolio that is able to make more returns as maintaining the safeness of All_Weather portfolio.
![Screen Shot 2020-10-26 at 23 38 41](https://user-images.githubusercontent.com/68367134/97186200-57536e80-17e4-11eb-955e-f9ee4a33291c.png)
    
### New Portfolio
- increasing the weight of the assets which are more correlated with SP_500(stock) 

* New Portfolio's Composition
![Screen Shot 2020-10-26 at 23 44 19](https://user-images.githubusercontent.com/68367134/97187167-89190500-17e5-11eb-88e9-afc4ef46af18.png)

### Trend Analysis about Rate of Cumulative Return by New Portfolios
* Backtest Result for All-weather portfolio 4
- All-weather portfolio 4(stock 50%, long_bond 20%, mid_bond 5%, commodity 5%, gold 20%) records the highest cumulative returns with decreased numbers of negative returns
![Screen Shot 2020-10-26 at 23 44 32](https://user-images.githubusercontent.com/68367134/97187181-8cac8c00-17e5-11eb-9a67-ab45fe01427e.png)


## Conclusion
- It is found that All-weather portfolio 4 is the best 'assest allocation portfolio' to increase returns with the limited risk of loosing investment. 
