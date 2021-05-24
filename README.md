# Crypto Portfolio with Excel
 A live-updated Cryptocurrency Portfolio tracker with Microsoft Excel.\
 Data are provided from the [CoinMarketCap API](https://coinmarketcap.com/api/)

 ### Features

🌎 Aggregate Market Information\
💰 Overview of Holdings\
📊 Profit and Loss per Asset Chart\
⭕️ Asset Allocation Chart\
📅 Trade History\
📈 Net Worth Calculator\
☁️ Automatic Live Updates, Minimal User Input\
⚡ <100KB - Fast & Lightweight

 ### Screenshots

 * Market information and Overview of Holdings

<img src="https://github.com/gskoupras/crypto_portfolio_excel/blob/ac71541b528a9a81478de186e18dba4443d5e83b/screenshots/dashboard.png"  width="100%"> 

* Profit and Loss per Asset Chart

<img src="https://github.com/gskoupras/crypto_portfolio_excel/blob/ac71541b528a9a81478de186e18dba4443d5e83b/screenshots/pnl_chart.png"  width="100%"> 

* Asset Allocation Chart

<img src="https://github.com/gskoupras/crypto_portfolio_excel/blob/ac71541b528a9a81478de186e18dba4443d5e83b/screenshots/allocation_chart.png"  width="100%"> 

* Trade History

<img src="https://github.com/gskoupras/crypto_portfolio_excel/blob/61311c897a204c1d744efa8c55de63c3c4f137ed/screenshots/trade_history.png"  width="100%"> 

* Net Worth Calculator

<img src="https://github.com/gskoupras/crypto_portfolio_excel/blob/4438e230d72a0295af05e001f438a5a57a141b5b/screenshots/net_worth.png"  width="100%"> 


 ### How to use

To use this portfolio, you need to create your own API key with [CoinMarketCap.](https://coinmarketcap.com/api/) The API is free of charge for a certain number of calls per month (should be enough for the majority of users). You can find this info [here](https://coinmarketcap.com/api/pricing/) and upgrade your plan if you need. 

Once you have your API key, you only need to input it on the three queries of the spreadsheet, by accessing the advanced editor. To access the editor and make all the required changes:
* Open the "My Crypto Portfolio.xlsm" and ignore potential errors (currently, no API key is connected to the queries). 
* Click the tab "Data" (step 1), and then click on "Show Queries" (step 2), under the "Get & Transform" set of tools. 
* You will be transferred on the "Queries" sheet and the "Workbook Queries" panel will appear on the far right of the window. Right-click on one of the three queries (step 3) and then click on "Edit" (step 4).
* A "Power Query Editor" window will appear, where you have to click "Advanced Editor" (step 5), under the "Query" tools.
* The "Advanced Editor" window will appear, where you have to scroll right until you find the "<ENTER_YOUR_API_KEY_HERE>" entry, which you will have to replace with your api key (step 6). 
* For the "ALL DATA" workbook query only, you also need to update the list of cryptos, by updating the list of IDs (step 7) with the IDs of the cryptos in your portfolio, in the exact same format as the one on the editor. You can find a full list of the crypto IDs by CoinMarketCap with this link: "https://pro-api.coinmarketcap.com/v1/cryptocurrency/map?CMC_PRO_API_KEY=<ENTER_YOUR_API_KEY_HERE>" where you also have to replace the "<ENTER_YOUR_API_KEY_HERE>" entry with your api key. The other two queries "GLOBAL 1" and "GLOBAL 2" do not need a list of IDs.
* You need to repeat the process for all three power workbook queries: "GLOBAL 1", "GLOBAL 2" and "ALL DATA". That means updating your api key in all three of them.
* If everything is done correctly, the only thing that remains is for you to input your trading history in the relevant sheet, and your portfolio is ready to use. The portfolio only supports buying on the trading history. Thus, it is advised to be used for your long term holdings.

The 7 basic steps of this guide are also illustrated here:

<img src="https://github.com/gskoupras/crypto_portfolio_excel/blob/61311c897a204c1d744efa8c55de63c3c4f137ed/screenshots/access_queries.png"  width="100%"> 


**Disclaimer:** The cryptocurrencies and exchanges presented on the default portfolio file are completely chosen at random and by no means represent investment advice or insights on my own cryptocurrency potfolio. 