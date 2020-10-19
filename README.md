# SmarterTrading ![](https://github.com/allsouza/SmarterTrading/blob/master/src/images/atom.svg)

[SmarterTrading](https://allsouza.github.io/SmarterTrading/) is an app that watches the stock market trends and variations and tells the user the best time to buy or sell stock based on historic data fetched from an API.

# Background and Overview

While some might view the stock market as a casino where only luck plays a factor into wether or not you make profit or lose money. A real investor knows that analysing the data and being able to identify patterns will improve the chances of profit greatly.  The aim of SmarterTrading is to analise previous stock market data and assist the user in making a more educated decison on what the best time to sell or buy a stock is.

By using historical data fetched from an external API SmarterTrading will run an analysis and make a suggestion on what action the user should take reguarding the specific stock.

# Functionality and MVPs

SmarterTrading will allow the user to search for a specific stock, and display information regarding said stock.
![](https://github.com/allsouza/SmarterTrading/blob/master/read_me/search.gif)

The app will connect with Finnhub API and fetch historical data about the searched stock.
![](https://github.com/allsouza/SmarterTrading/blob/master/read_me/request.png)

The app will display graphs on historical data about the stock.
![](https://github.com/allsouza/SmarterTrading/blob/master/read_me/graph.gif)

The app will analyse past trends and make a suggestion about the stock.
![](https://github.com/allsouza/SmarterTrading/blob/master/read_me/Screenshot%20from%202020-10-19%2012-02-15.png)
![](https://github.com/allsouza/SmarterTrading/blob/master/read_me/hold.png)
![](https://github.com/allsouza/SmarterTrading/blob/master/read_me/sell.png)

# Architecture and Technologies

* Javascript
* D3 graphing
* Finnhub API
