# Stock-Trading Backtesting and Data Analysis

### Develop profitable asset allocation portforlio better than traditional All-weather-portfolio

In this project, we developed the asset allocation portforlio in order to secure stable funds after retirement. This project based on Data Mining and Economic statistics.

#### Data Sources : [Investing.com](https://www.investing.com/)

    Index: SP_Index, Interm_Index, Longterm_Index, Commodity_Index, Gold_Index
    feature : weekly data
    period: 1996.07.01 ~ 2020.06.29(25 years)

team: 이태헌, 김희주

## Backtesting
* As the purpose of this project is for study, we didn't consider allocation, dividend tax, rebalancing and just focused on the indices close data in traditional all-weather-portfolio.

### 1. Understanding of 5 Indices close data
- Analyzed weekly return and cumulative return by asset types(stock, long-term, mid-term, commodity, gold)

### 2. Traditional Asset Allocation Portfolio
   - Visualized and Compared traditional asset allocation portfolio.
        - portfolio_1 : stock 100%
        - portfolio_2 : stock 60% + long-term bond 40%
        - portfolio_3 : All_Weather : stock 30% + long-term bond 40% + mid-term bond 15% + commodity 7.5% + gold 7.5%
        
            <img src="https://user-images.githubusercontent.com/68367134/97185929-06dc1100-17e4-11eb-95c9-7f75cdcb5d45.png" width="750">

### 3. Trend Analysis about Rate of Cumulative Return by the Portfolios
   - All_weather portfolio doesn't seem to be the best portfolio in terms of investment, since the rate of cumulative return is 170% over the last 25 years even though it's safer than any others. 
   - Therefore, we assumed that it would be valuable to build a new portfolio that is able to make more returns as maintaining the safeness of All_Weather portfolio.
    
### 4. Compose New Portfolio
   - Composed New Portfolios based on traditional all-weather portfolio increasing the weight of the assets which are more correlated with SP_500(stock) 
        - all_weather2 :  stock 30% + long-term bond 40% + mid-term bond 5% + commodity 5% + gold 20%
        - all_weather3 :  stock 40% + long-term bond 30% + mid-term bond 5% + commodity 5% + gold 20%
        - all_weather4 :  stock 50% + long-term bond 20% + mid-term bond 5% + commodity 5% + gold 20%
        - all_weather5 :  stock 50% + long-term bond 20% + mid-term bond 10% + commodity 5% + gold 15%
        
![Screen Shot 2020-10-26 at 23 44 19](https://user-images.githubusercontent.com/68367134/97187167-89190500-17e5-11eb-88e9-afc4ef46af18.png)

### 5. Trend Analysis about Rate of Cumulative Return by New Portfolios

## Conclusion
   - According to our assumption, it is found that All-weather portfolio 4 is the best 'assest allocation portfolio' to increase returns with the limited risk of loosing investment. 
   


