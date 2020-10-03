# ORIE4741_Project

ORIE 4741 Project Proposal: How does covid-19 affect stock index?
Jinyi Jiang(jj756), Qianqian Wu(qw273), Yujie Cao(yc2628)



Problem Statement：
Background:
In 2020, the sudden worldwide outbreak of Coronavirus has caused a tremendous impact on our economic life, social life, and spiritual life. Currently, we are facing enormous uncertainty, which is the last thing businessmen and investors like to see. 

Question:
How does COVID-19 affect the stock market? 
What are the impacts of new confirmed cases, cumulative cases, new deaths, and cumulative deaths on the stock indexes in the US and China and across sectors?

Significance:
The impact of COVID-19 on the economy, and on stock markets in particular still remains unclear. With our project insights, investors can better allocate their investment portfolios by investigating the relationship between confirmed/death cases and stock price variations in the US and China.

Dataset Description:
Daily new diagnoses, cumulative cases, new deaths, and cumulative deaths caused by COVID-19:
For daily new diagnoses, cumulative cases, new deaths, and cumulative deaths of coronavirus data, we used data from the World Health Organization (https://covid19.who.int/table). We got new cases, cumulative cases, new deaths, and cumulative deaths of different countries in the table downloaded from the WHO website. We defined the dataset X for prediction of China as XC8n, and X for prediction of America as XA8n. Here the dimension of X is 8n because we wanted X to contain n days of historical data. And for each day, the 8n dimension data was comprised of the daily new diagnoses, cumulative cases, new death, and cumulative deaths in the world and in either China or America for country-specific analysis. Then we will use algorithms to choose the best n for our model.

Stock index of various sectors in China:
For prediction in China, we will use CSI 300 Index (overall industry index), Chinese Financials Index, Chinese Food & Beverage Index, Chinese Media Index, Chinese Real Estate Index, Chinese Pharmaceuticals & Biotechnology Index, Chinese Industrial Transportation Index, and Chinese Software & Computer Services Index. All of these index data could be downloaded from the Wind Terminal, which is a financial terminal with the most financial data in the Chinese market(https://www.wind.com.cn/en/wft.html). 
For all the indices, we will use their daily logarithmic return as y. (yt= ln(Index_t) – ln(Index_t-1))

Stock index of various sectors in the US:
For prediction in America, we will use the S&P 500 Index (overall industry index), Dow Jones U.S. Financials Index, Dow Jones U.S. Food & Beverage Index, Dow Jones U.S. Media Index, Dow Jones U.S. Real Estate Index, Dow Jones U.S. Pharmaceuticals & Biotechnology Index, Dow Jones U.S. Industrial Transportation Index and Dow Jones U.S. Software & Computer Services Index. All of these index data could be downloaded from Yahoo Finance (https://finance.yahoo.com/).  
For all indices, we will use their daily logarithmic return as y. (yt= ln(Index_t) – ln(Index_t-1))
