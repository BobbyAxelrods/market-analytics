# Introduction & Objective 

The objective of this project is to identify which asset class have the best performance for Trader A. In order to analyze Trader A performance, we have to perform below task step by step where :- 
1. Scrape table data performance in 
    - https://inthemoneystocks.com/verified-investing-stock-trade-alerts-gareth-soloway/ (STOCKS PERFORMANCE TABLE) 
    - https://verifiedinvestingcrypto.com/ (CRYPTO PERFORMANCE TABLE) 

2. Run the scraping method in files "1.0 Scraping" to begin scraping data from HTML table format. The table data then converted into csv format to make it easier to be analyzed in next stage. 
    - CSV name for crypto = 'g.csv'
    - CSV name for stocks = 'stocks.csv'
    
3. Once data has been extracted from and to csv format, run script '2. analytics' to produce graph of Sum of Total Percents Profit against Agregated Monthly 


# Findings 


Based on Stocks Perfomance, 
1. the trend is downtrend with a slight rebound during April to June
2. The trend continue bearish until December
3. Highest profit sum is 400% & the lowest profit is 10%
https://s3.us-west-2.amazonaws.com/secure.notion-static.com/577c102a-3736-4e3a-b2f8-d0cf49dc8e48/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220718%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220718T143740Z&X-Amz-Expires=86400&X-Amz-Signature=bb8f2abfce4d863550dc247fa26685dfe4fe71f79a8237cd5143c2afa3d88b11&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject

![Untitled.png](attachment:Untitled.png)

Based on Stocks Perfomance, 
1. the trend is downtrend with a slight rebound during April to June
2. The trend continue bearish until December
3. Highest profit sum is 140% & the lowest profit is -20%
https://s3.us-west-2.amazonaws.com/secure.notion-static.com/8a1bcd9a-af2b-43e4-b1fc-8ea005cb023b/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220718%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220718T143709Z&X-Amz-Expires=86400&X-Amz-Signature=90d0c511e94577f38e6c3fb3d0b73d8c6f40fffde35b69aeaff063bf6ea3c773&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject

# Conclusion 

Selection made to proceed with crypto since the peformance trend is better and more months in profit higher than 20% compared to stocks.

By selecting crypto market, we can expect the minimum return is 20% and the highest 140% throughout the year. 

