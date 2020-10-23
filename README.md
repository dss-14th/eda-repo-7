## Stock-Trading Backtest
In this project, we developed investment portfolio in order to secure stable funds after retirement. The purpose of this project is to improve profitable investment portforlio than Traditional All-weather portforlio.This project based on Data Mining and Economic statistics.

#### team: 이태헌, 김희주

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

