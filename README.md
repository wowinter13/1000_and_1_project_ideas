# One Thousand and One...Project Ideas

## Bio/Med-tech

### 1. First aid kit & Medication Tracker (Mobile)

|               |          |
| ------------- |----------|
| Geography     | *RU*     |
| Tags          | *mobile* |


**Functionality:**
1. List all items in a kit
2. Notifications on expiration date
3. Pill reminder

**Additional monetization:**
1. (*) Search&Compare drug prices
2. No limit on notifications


### 2. Medical lootboxes

|               |          |
| ------------- |----------|
| Geography     | *EU, RU* |

Why not to start with some vitamine combos from https://iherb.com?
Or check out: https://transcend.me/products/your-personalized-packets-11

## Invest-tech/Fin-tech

### 1. Quasi-broker

|               |             |
| ------------- |-------------|
| Geography     | *EU, RU*    |
|               |             |


### 2. Financial news/ideas/analytics aggregator

|               |             |
| ------------- |-------------|
| Geography     | *World, RU* |
| Tags          | *telegram*  |
|               |             |

**Twitter data sources:**

1. (*RU*) @ArtCapitalTrade, @prime1, @onfleek419, @divalerts, @trader_book_news, @russianmacro, @Trade_The_News

2. (*International*) @barton_options, @DiMartinoBooth, @pat_hennessy, @biancoresearch, @CitronResearch, @profgalloway, @Fxhedgers, @old_but_works, @nntaleb, @muddywatersre, @govttrader, @jessefelder, @ThinkTankCharts

**MVP:**
At this stage, a Telegram/Twitter bot would be enough. For some inspiration, you could check these links: https://t.me/headlines_for_traders, https://t.me/fin_twitt, https://t.me/StockNews100
The only problem – possible news duplications, can be solved using algos such as `Word2vec` or `Doc2vec`.

**Functionality:**
1. A real-time news feed for traders
2. Filters on companies (*tickers*)
3. Filters on data types (*analytics, news, div calendar, etc.*)


### 3. Scouting for business jets

|               |             |
| ------------- |-------------|
| Geography     | *World, US* |
| Tags          | *alternative data*, *API*  |

Guys from Quandl did this trick.
1. They started tracking for Buffett's jets and watching all flights.
2. After that, they found companies' offices (*from the above cities*), where Berkshire Hathaway had some interest.
3. *Magic.* Sort all given data by flight  quantity and frequency.
4. PROFIT: **Anadarko Petroleum**. Buffett had visited \$OXY a couple of times right before the $10 billion deal was publicly announced.


### 4. ML-darkpools

|               |             |
| ------------- |-------------|
| Geography     | *World, US* |
| Tags          | *alternative data*, *trade matching*  |


**Description**
*(A dark pool is a privately organized financial forum or exchange for trading securities. Dark pools allow institutional investors to trade without exposure until after the trade has been executed and reported. Dark pools are a type of alternative trading system (ATS) that give certain investors the opportunity to place large orders and make trades without publicly revealing their intentions during the search for a buyer or seller. @Investopedia)*

When a trader places an order to buy stocks, the stock exchange matches it with a counter one to sell. ML middleware could split this order into smaller composite parts.
So we reduce the impact of the trade on the market price; optimizing the process of trading for big and complex positions.


**Why now?**
Here we have a strong interest from small/medium-sized funds, which can't use darkpools from such guys as Morgan Stanley or other big banks, but still don't want to move some penny stock prices (or emerging market stocks) simply because of portfolio rebalancing.

### 5. Advanced Backtesting

|               |             |
| ------------- |-------------|
| Geography     | *World, RU* |
| Tags          | *API*, *alternative data*  |


**Description**

Relatively speaking, that is a strategies' backtesting using data on crises and unexpected stock market crashes.

A platform that rafts your strategy through plenty of simulated crises, industry risk cases and can define some historical risk index for the total portfolio.
Also, we have some space to dream up ideas based on the intersection of value investing and stocks scoring. So we will be able to find out the best companies which can transcend any market difficulties.

**MVP:**

Let's be fair - it is just a simple pseudo stock exchange, that has the functionality to process (ETL) and reply data. Also, it could be a set of pseudo stock exchanges to train arbitrage strategies.
And the funny thing is – that you could find all these *Black Swan Events* or *alternative data* in countless different public sources.


**Why now?**

<img width="372" height="243" src="https://user-images.githubusercontent.com/12775766/104593839-57e00080-5681-11eb-8919-cda105b15162.jpg">

Let's have a look at this chart by Bloomberg. It's a little outdated, but it still looks actual. Every year the hedge-funds and biggest investment banks increase their spendings on technology and **quant strategies development** while cutting spendings on direct trading and front-offices.

In the world of algos and robots, it is getting harder and harder to trade discretionarily.


## Common

### 1. Vinyl lootboxes (or subscription)

|               |             |
| ------------- |-------------|
| Geography     | *World, RU* |
| Design     | https://dribbble.com/shots/6255851-SQUARE-Interaction-Vol-3 |

**Why now?**

*In 2016, vinyl sales hit a 28-year high – and there’s no slowing it down! Maybe it’s time to restart the business model.*

(Source: https://fortune.com/2016/04/16/vinyl-sales-record-store-day/)
